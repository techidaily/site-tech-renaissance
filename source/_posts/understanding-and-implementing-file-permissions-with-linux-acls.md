---
title: Understanding and Implementing File Permissions with Linux ACLs
date: 2024-12-09T22:41:54.300Z
updated: 2024-12-17T11:05:57.477Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/52971071867_d12b5cc0f7_o.jpg
---

## Understanding and Implementing File Permissions with Linux ACLs

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* To view all ACL entries for a file, use the command 'getfacl filename' but replace 'filename' with the name of your file.
* To set a new ACL entry for a file, use the command 'setfacl -m u:username:rwx filename'
* To set a Default ACL entry on a directory, use the command 'setfacl -d -m u:username:rwx dirname'

 Are you in charge of a shared file server between multiple groups of people, who all need varying access? In this tutorial we'll go over the basics of ACLs and employ them in a fictional office scenario.

##  What Are ACLs?

 Access Control Lists (ACLs) supplement the [standard file system permissions model on Linux and Unix](https://os-tips.techidaily.com/how-to-reset-waze-location-memory-on-ios-devices-a-step-by-step-guide/). In a nutshell, they allow you to go beyond the "user/group/other" concept to create additional sets of permissions for files and directories. They also do neat things like automatically applying permissions to new files and directories. But first, let's cover some basic Linux file system permissions concepts in which ACLs work alongside.

###  Standard File System Permissions

 To understand file system permissions under Linux, first you need to know that Linux is a "multi-user operating system". This means there exist multiple [user accounts](https://fox-links.techidaily.com/updated-gif-magic-transformations-without-extra-files-downloaded-for-2024/) which essentially allow more than one person to log into the system, each having their own freedoms and restrictions.

 Some user accounts are "system" accounts; not ones that are used by a person, but rather by a piece of software, for instance. Processes run under these special accounts to allow and restrict them to various parts of the OS, just as a normal user account would.

 Now that we understand users, I can introduce you to "groups." Groups are pretty easy to understand—they're simply collections of existing users. To assign permission for a resource to lots of users at the same time, you can create a new group and grant specific users membership to that group. You then assign permission for the resource to the group, instead of each individual user. This makes administration easier and more streamlined.

 OK, let's talk about files and directories. These are the resources we care about granting and protecting access to.

 Most Linux file systems (EXT4, XFS and ZFS for example) allow you to apply 3 primary permissions to files and directories. These permissions are:

* **Read:** Allow a file to be read (or list contents inside a directory)
* **Write:** Allow a file to be written to or modified (or create files and subdirectories _inside_ a directory)
* **Execute:** Allow to run a program or script (or enter into a directory, for example with the [cd command](https://audio-shaping.techidaily.com/updated-decoding-vimeos-video-dimensions-a-complete-perspective-on-aspect-ratios-for-2024/))

 All files and directories on a file system have standard permission assigned to 3 distinct entities: the user who owns it, the group owner and all other users. Each entity may have a combination of read, write and execute (r/w/x) permissions assigned. You can [use the ls command](https://extra-tips.techidaily.com/in-2024-capturecraft-hd-top-10-freepaid-filters-list/) to look at all of this info:

ls -l mysupersecretfile.txt

![A terminal window showing standard file permissions of a sample file on Linux.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-1.png) 

1. \[U\]ser (owner) permissions
2. \[G\]roup permissions
3. All \[O\]ther users' permissions
4. Owning username
5. Owning group name

 By default, each newly created user is also assigned to a new primary group of the same name. In the example above, #4 is the username "user" and #5 is the group name "user". Keep that in mind when looking at output such as this as it may be confusing at first.

 The files and directories that users are allowed to modify depend on a couple of things, including whether the user "owns" it or if they otherwise have the appropriate permissions to via a group membership. Note that the [root user](https://digital-screen-recording.techidaily.com/updated-2024-approved-entrance-video-analysis-review/) can modify any file on the system, regardless of ownership.

 This approach to file system permissions works well for most at-home and standalone setups. Of course, when you're working with systems where multiple users are accessing the same file hierarchy, and you must give certain people access to some areas (and restrict them from others), you'll start to understand the standard "1 owner, 1 group" methodology falls a bit short.

###  How ACLs Enhance the Standard Permissions Model

 Access Control Lists add the ability to apply permission entries to multiple users and groups for files and directories. One example where ACLs are a good option is when you want to assign a certain user permission to a file that already has specific owner and group owner permissions assigned.

 ACLs for directories follow the standard permissions **r**/**w**/**x** model in that they give you the ability to (**r**)ead (list contents, but not enter) the directory, (**w**)rite (create) new files and directories _inside_ the directory, and e(**x**)ecute (enter) the directory.

 How about an example? Let's say you have a file, report.pdf, owned by a user, peter, with read+write permissions. You've additionally granted group ownership of this file to the accounting group. Now you've received a request to grant read access to the user named lumberg.

 Let's assume you're using the standard permissions model. Here are a few (futile) ideas for completing this request:

* You can't grant lumberg membership to the accounting group (that would give him access to all sorts of other files he shouldn't be looking at).
* You also don't want to, as a matter of proper administrative practice, create a whole new group with users from the accounting group plus lumberg, just for this file.
* You _especially_ don't want to open up permissions to all other users, for obvious security reasons.

ls -l report.pdf

![A terminal window showing file listing output on Debian.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 What to do? Well, you _could_ just take an early lunch break. However, let's instead employ ACLs!

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Checking for ACL Support on Your System

 Most modern Linux distributions support ACLs out-of-the-box. Most common file systems support them, their default mount options include ACL support and default installations should include the proper packages.

 To verify on ext2/3/4 file systems, use tune2fs. For example, if you want to check /dev/sda1 (which contains an ext4 file system):

sudo tune2fs -l /dev/sda1 | grep "Default mount options"

![A terminal window showing output of tune2fs command, and acl default mount option circled.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-1.png) 

 For reference, here's a [list of different file system support for ACLs, grouped by platform, written by IBM](https://www.ibm.com/docs/en/storage-protect/8.1.21?topic=linux-file-system-acl-support).

##  The getfacl Command

 The getfacl command displays (gets) file access control lists for files and directories. If you run getfacl on our report file from above, you'll see:

getfacl report.pdf

![A terminal window showing getfacl command and its output on a file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Right now the output shows the _minimum ACL_ of the file. The minimum ACL comprises the standard permissions for the owner, owning group and all other users.

 If there were an _extended ACL_ entry for another user, let's call them michael, we'd see this:

getfacl report.pdf

![A terminal window showing getfacl command and its output.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8.png) 

 In addition to the minimum ACLs, we now have an extended ACL entry for user michael (read+write permissions). If you list the file again with extended ACLs, you'll notice a plus (+) sign to the right of the "other users" permissions, indicating that extended ACL entries exist:

ls -l report.pdf

![A terminal window showing ls command output with ACL entry flag.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9.png) 

##  The setfacl Command

 The setfacl command is what actually _sets_ ACLs for files and directories. It adds and removes user and group entries, modifies permissions and other tasks like setting default ACLs on directories and working with masks. We'll use it to complete the request above by granting the lumberg user read access to report.pdf.

 To add the new user ACL entry, you'll use setfacl with this syntax (which I'll break down below):

sudo setfacl -m u:lumberg:r report.pdf

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## ![A terminal window showing the setfacl command modifying a file's ACL entry.](https://static0.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

* **\-m** means we're modifying an ACL entry for the file
* **u:** means it's a user we're adding, followed by a colon (:) separator (a **g:** adds a group and **o:** adds all other users' permissions)
* **lumberg:** is the username we're adding, followed by another colon separator
* **r** means we're adding read permissions (only) to the entry
* **report.pdf** is the name of the file we're adding the ACL entry to

 Now that this is set we can take a look, using getfacl, once again:

getfacl report.pdf

![A terminal window showing output of getfacl command on our sample file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10.png) 

 Do you spot our new entry?

##  Default ACLs

 Default ACLs only apply to directories (folders). When you set a default ACL on a directory, the entry you specify will automatically be applied to _every_ new file and directory within it, regardless of who creates them. It's sort of a catch-all, recursive approach which makes it pretty useful when you're planning your file system hierarchy.

 Let's make sure Lumberg will be able to read new files and enter new directories that are created under Accounting. We'll use the -d option for adding a _default ACL_:

sudo setfacl -d -m u:lumberg:rX Accounting

![A terminal window showing setfacl command to set permissions, then getfacl to show them.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/12.png) 

 An upper-case **X** applies the execute permission only against new subdirectories; not files.

 Access control lists are great for when you want to take your file system permissions to the next level. You can get away with a lot with standard user/group/other permissions, but there will likely be a point in your journeys where using ACLs makes much more sense.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-unraveling-zdsofts-screen-monitor-magic/"><u>[Updated] 2024 Approved Unraveling ZDSoft's Screen Monitor Magic</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-streamlining-revenue-adsense-tips-for-youtubers-for-2024/"><u>[Updated] Streamlining Revenue AdSense Tips for YouTubers for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/desktop-adventures-await-with-pokemon-unite-get-started-here/"><u>Desktop Adventures Await with Pokémon Unite - Get Started Here</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-how-to-edit-your-discord-user-image-easily/"><u>DIY: How to Edit Your Discord User Image Easily</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-school-apps-the-best-10-picks-for-high-school-students/"><u>Essential School Apps: The Best 10 Picks for High School Students</u></a></li>
<li><a href="https://some-guidance.techidaily.com/free-and-easy-winx-dvd-creator-professional-video-and-data-dvd-burning-software-for-windows-1011/"><u>Free and Easy WinX DVD Creator: Professional Video & Data DVD Burning Software for Windows 10/11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722968274863-get-the-newest-amd-radeon-pro-w5700-driver-for-win11107-systems-today/"><u>Get the Newest AMD Radeon Pro W5700 Driver for Win11/10/7 Systems Today</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-sanitize-your-television-remote-best-cleaning-practices-unveiled/"><u>How To Sanitize Your Television Remote – Best Cleaning Practices Unveiled</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-oppo-find-x6-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Oppo Find X6 Phone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/insight-chatgpts-default-tools-explained/"><u>Insight: ChatGPT's Default Tools Explained</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-unlock-4k-the-ultimate-list-of-free-video-converters/"><u>New 2024 Approved Unlock 4K The Ultimate List of Free Video Converters</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/online-privacy-hacks-how-to-locate-an-individuals-mobile-number-legally-and-ethically/"><u>Online Privacy Hacks: How to Locate an Individual’s Mobile Number Legally and Ethically</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/protect-your-live-streams-the-periscope-video-howto-for-2024/"><u>Protect Your Live Streams The Periscope Video HowTo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solving-microphone-troubles-when-chatting-in-valorant-games/"><u>Solving Microphone Troubles When Chatting in Valorant Games</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-future-unfolds-with-samsung-galaxy-z-fold-6-a-look-at-its-specs-release-date-and-market-price/"><u>The Future Unfolds with Samsung Galaxy Z Fold 6: A Look at Its Specs, Release Date & Market Price</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-12-no-cost-defragmentation-utilities-july-2024-edition/"><u>Top 12 No-Cost Defragmentation Utilities: July 2024 Edition</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-tips-for-wirelessly-connecting-airpods-to-a-laptop-from-hp/"><u>Ultimate Tips for Wirelessly Connecting AirPods to a Laptop From HP</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-the-potential-of-ai-mastering-prompts-with-claude-3-from-anthropic/"><u>Unlocking the Potential of AI: Mastering Prompts with Claude 3 From Anthropic</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/use-roku-hotel-and-dorm-connect-while-traveling-or-at-school/"><u>Use Roku Hotel & Dorm Connect While Traveling or at School</u></a></li>
</ul></div>

