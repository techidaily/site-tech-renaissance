---
title: Understanding and Implementing File Permissions with Linux ACLs
date: 2024-08-30T14:39:43.360Z
updated: 2024-08-31T14:39:43.360Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/52971071867_d12b5cc0f7_o.jpg
---

## Understanding and Implementing File Permissions with Linux ACLs

### Key Takeaways

* To view all ACL entries for a file, use the command 'getfacl filename' but replace 'filename' with the name of your file.
* To set a new ACL entry for a file, use the command 'setfacl -m u:username:rwx filename'
* To set a Default ACL entry on a directory, use the command 'setfacl -d -m u:username:rwx dirname'

 Are you in charge of a shared file server between multiple groups of people, who all need varying access? In this tutorial we'll go over the basics of ACLs and employ them in a fictional office scenario.

##  What Are ACLs?

 Access Control Lists (ACLs) supplement the [standard file system permissions model on Linux and Unix](https://os-tips.techidaily.com/how-to-reset-waze-location-memory-on-ios-devices-a-step-by-step-guide/). In a nutshell, they allow you to go beyond the "user/group/other" concept to create additional sets of permissions for files and directories. They also do neat things like automatically applying permissions to new files and directories. But first, let's cover some basic Linux file system permissions concepts in which ACLs work alongside.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
 What to do? Well, you _could_ just take an early lunch break. However, let's instead employ ACLs!

##  Checking for ACL Support on Your System

 Most modern Linux distributions support ACLs out-of-the-box. Most common file systems support them, their default mount options include ACL support and default installations should include the proper packages.

 To verify on ext2/3/4 file systems, use tune2fs. For example, if you want to check /dev/sda1 (which contains an ext4 file system):

sudo tune2fs -l /dev/sda1 | grep "Default mount options"

![A terminal window showing output of tune2fs command, and acl default mount option circled.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For reference, here's a [list of different file system support for ACLs, grouped by platform, written by IBM](https://www.ibm.com/docs/en/storage-protect/8.1.21?topic=linux-file-system-acl-support).

##  The getfacl Command

 The getfacl command displays (gets) file access control lists for files and directories. If you run getfacl on our report file from above, you'll see:

getfacl report.pdf

![A terminal window showing getfacl command and its output on a file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6.png) 

 Right now the output shows the _minimum ACL_ of the file. The minimum ACL comprises the standard permissions for the owner, owning group and all other users.

 If there were an _extended ACL_ entry for another user, let's call them michael, we'd see this:

getfacl report.pdf

![A terminal window showing getfacl command and its output.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8.png) 

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In addition to the minimum ACLs, we now have an extended ACL entry for user michael (read+write permissions). If you list the file again with extended ACLs, you'll notice a plus (+) sign to the right of the "other users" permissions, indicating that extended ACL entries exist:

ls -l report.pdf

![A terminal window showing ls command output with ACL entry flag.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The setfacl Command

 The setfacl command is what actually _sets_ ACLs for files and directories. It adds and removes user and group entries, modifies permissions and other tasks like setting default ACLs on directories and working with masks. We'll use it to complete the request above by granting the lumberg user read access to report.pdf.

 To add the new user ACL entry, you'll use setfacl with this syntax (which I'll break down below):

sudo setfacl -m u:lumberg:r report.pdf

## ![A terminal window showing the setfacl command modifying a file's ACL entry.](https://static0.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-1.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-quick-tips-screen-record-and-camera-integration-on-android/"><u>[New] 2024 Approved  Quick Tips  Screen Record & Camera Integration on Android</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-mastering-capturing-with-camstudio-complete-for-2024/"><u>[New] Mastering Capturing with CamStudio Complete for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-perfect-your-profile-easy-guide-for-instagram-videos-from-desktop/"><u>[Updated] 2024 Approved  Perfect Your Profile  Easy Guide for Instagram Videos From Desktop</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-comprehensive-guide-to-dts-virtualx-what-you-need-to-know-about-next-level-audio-in-cinema/"><u>A Comprehensive Guide to DTS Virtual:X - What You Need to Know About Next-Level Audio in Cinema</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/boosting-system-agility-managing-data-speed-and-wait-time-in-personal-computers/"><u>Boosting System Agility: Managing Data Speed and Wait Time in Personal Computers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/detailed-guide-to-uninstall-the-system-rescue-partition-in-windows/"><u>Detailed Guide to Uninstall the System Rescue Partition in Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-selection-8-premium-free-roku-channels-for-2amz/"><u>Discover the Ultimate Selection: 8 Premium Free Roku Channels for 2Amz</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effective-strategies-to-boost-your-twitter-following/"><u>Effective Strategies to Boost Your Twitter Following</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effective-techniques-to-remove-verticalhorizontal-lines-from-your-screen-visuals/"><u>Effective Techniques to Remove Vertical/Horizontal Lines From Your Screen Visuals</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exclusive-advantages-of-electric-vehicle-ownership-access-to-parking-and-carpool-lanes/"><u>Exclusive Advantages of Electric Vehicle Ownership: Access to Parking & Carpool Lanes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-for-fixing-disappearing-comments-on-youtube-videos/"><u>Expert Tips for Fixing Disappearing Comments on YouTube Videos</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-for-recovering-discarded-correspondence-in-outlook-without-a-trace/"><u>Expert Tips for Recovering Discarded Correspondence in Outlook Without a Trace</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-origins-who-brought-us-chatgpt/"><u>Exploring the Origins: Who Brought Us ChatGPT?</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-honor-70-lite-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-wmvcoredll-errors-for-smooth-media-playback/"><u>Fixing Wmvcore.dll Errors for Smooth Media Playback</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-host-a-virtual-movie-night-on-netflix-via-screen-sharing/"><u>How to Host a Virtual Movie Night on Netflix via Screen Sharing</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-oppo-a59-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Oppo A59 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-icloud-on-apple-iphone-se-2020-smoothly-by-drfone-ios/"><u>How To Remove iCloud On Apple iPhone SE (2020) Smoothly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-article-successfully-pairing-your-phone-or-tablet-with-an-lg-screen-mirroring-function/"><u>How-To Article: Successfully Pairing Your Phone or Tablet with an LG Screen Mirroring Function</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-tecno-spark-go-2024-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Tecno Spark Go (2024) without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-unleash-windowsmac-premium-pc-and-mac-screen-capture-tools/"><u>In 2024, Unleash Windows/Mac  Premium PC and MAC Screen Capture Tools</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ingenious-tips-on-keeping-your-cell-phone-powered-without-a-standard-adapter/"><u>Ingenious Tips on Keeping Your Cell Phone Powered Without a Standard Adapter</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-battery-life-preventing-android-apps-from-running-hiddenly/"><u>Mastering Battery Life - Preventing Android Apps From Running Hiddenly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-ios-voicemail-a-complete-guide-to-sending-audio-messages-from-your-iphone/"><u>Mastering iOS Voicemail: A Complete Guide to Sending Audio Messages From Your iPhone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-your-inbox-the-art-of-categorizing-gmail-messages-with-labels/"><u>Mastering Your Inbox: The Art of Categorizing Gmail Messages with Labels</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-d3dx930dll-errors-a-comprehensive-guide/"><u>Resolving d3dx9_30.dll Errors: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simplifying-home-entertainment-programming-a-universal-device-controller/"><u>Simplifying Home Entertainment: Programming a Universal Device Controller</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-connecting-your-ps4-controller/"><u>Step-by-Step Guide: Connecting Your PS4 Controller</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-linking-your-fire-stick-device-with-any-projector/"><u>Step-by-Step Guide: Linking Your Fire Stick Device with Any Projector</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-plan-to-organize-the-perfect-indoor-karaoke-bash/"><u>Step-by-Step Plan to Organize the Perfect Indoor Karaoke Bash</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-tracking-down-saved-insta-reels-on-the-app/"><u>The Ultimate Guide to Tracking Down Saved Insta Reels on the App</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-creating-a-professional-email-signature-on-godaddys-webmail-platform/"><u>Ultimate Guide: Creating a Professional Email Signature on GoDaddy's Webmail Platform</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-solving-the-screen-burn-in-issue-on-your-display/"><u>Ultimate Guide: Solving the Screen Burn-In Issue on Your Display</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-facebook-a-journey-through-its-history-appeal-factors-and-important-features/"><u>Understanding Facebook: A Journey Through Its History, Appeal Factors, and Important Features</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlock-the-power-of-remote-management-a-step-by-step-guide-for-samsungs-smart-tv-users/"><u>Unlock the Power of Remote Management: A Step-by-Step Guide for Samsung's Smart TV Users</u></a></li>
<li><a href="https://driver-install.techidaily.com/updating-gfx-support-the-ultimate-ddu-guide/"><u>Updating GFX Support: The Ultimate DDU Guide</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>Why does the pokemon go battle league not available On Apple iPhone 11 Pro | Dr.fone</u></a></li>
</ul></div>
