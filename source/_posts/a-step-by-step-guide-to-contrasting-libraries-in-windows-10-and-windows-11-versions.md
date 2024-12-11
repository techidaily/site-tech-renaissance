---
title: A Step-by-Step Guide to Contrasting Libraries in Windows 10 & Windows 11 Versions
date: 2024-12-05T17:39:01.101Z
updated: 2024-12-10T17:11:57.367Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/52846060984_17cb6c3aa6_o.jpg
---

## A Step-by-Step Guide to Contrasting Libraries in Windows 10 & Windows 11 Versions

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Compare Folders From Properties](https://tech-recovery.techidaily.com/the-ultimate-fix-for-when-youtube-comments-wont-load/)
* [Compare Folders Using Command Prompt](https://video-capture.techidaily.com/new-in-2024-exacting-speech-recognition-via-googles-precision-tools/)
* [Compare Folders With WinMerge](https://win-howtos.techidaily.com/how-to-repair-when-your-macs-trackpad-wont-respond/)

### Key Takeaways

* One way to compare folders is to right-click your folders one at a time and choose "Properties" for each. Then compare the Properties window of each folder.
* The robocopy command is a command-line tool that can be used to view the differences between folder.
* Use WinMerge to compare the contents and details of folders if you want a graphical tool.

 Do you want to compare the number of files or folders or simply visualize the difference between two folders? If so, you have two graphical and one command line method to do that. We’ll show you how to perform the folder comparison task on your Windows 11 or Windows 10 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Compare Folders From Properties

 To compare the number of files, subfolders, the size, and the creation date of two folders, use the Properties option in Windows File Explorer. This lets you quickly glance at the main attributes of a folder.

 To start, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E. Find the first folder, right-click it, and select "Properties."

!['Properties' highlighted for a folder in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-folder-properties.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Keep the first folder’s "Properties" window open. Then, find the second folder, right-click it, and select "Properties."

 You now have the "Properties" window open for both your folders. Bring these windows side-by-side by [dragging them](https://extra-resources.techidaily.com/mastering-complex-video-effects-and-transitions-in-gopro-studio/), and you can see the differences in the contents of these folders. For example, you can see how many files both folders have, what size these folders are, and so on.

!['Properties' windows for two folders in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-compare-folder-properties.jpg) 

 That gives you a general overview of the differences between your folders.

##  Compare Folders Using Command Prompt

 If you prefer command line methods over graphical ones, use the robocopy command in Command Prompt to see the differences between the two folders. This command is actually for [copying files from one folder to another](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/), but you can make it show the differences between two specified folders and not copy any files.

 To use robocopy, first open the Start Menu, search **Command Prompt**, and launch it.

![Command Prompt highlighted in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-command-prompt.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Command Prompt, type the following command. Replace "Folder1" with the path to your first folder and "Folder2" with the path to your second folder. Ensure both folder paths are enclosed in double quotes.

 To copy a folder’s full path along with double quotes around the path, hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

robocopy "Folder1" "Folder2" /L /NJH /NJS /NP /NS

![The 'robocopy' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-compare-folders-command-prompt.jpg) 

 You’ll see the differences between your folders.

 If you’re curious as to what the robocopy command does, here’s an explanation of each flag we used with the command:

* **L**: This tells the command not to copy files but show the log of the files in the specified folder.
* **NJH**: This flag excludes junctions, hard links, and reparse points from consideration. This way, the command focuses on the regular files in the specified folders.
* **NJS**: This flag excludes symbolic links from the process.
* **NP**: This flag excludes folder timestamps.
* **NS**: This flag excludes file security information.

##  Compare Folders With WinMerge

 If you want more details about the differences in your folders, Windows doesn't have a built-in tool to help you with that. However, you can use a free third-party app called WinMerge to compare multiple folders.

 To use it, launch a web browser on your PC, head to the [WinMerge](https://winmerge.org/downloads/?lang=en) site, and download and install the app. Make sure to download the app’s executable and not the ZIP version.

 Open the WinMerge app, then select File > Open in the Menu Bar or press Ctrl+O.

![File > Open highlighted in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-folder-winmerge.jpg) 

 For the "1st File or Folder" field, select "Browse" and choose the first folder to compare.

!['Browse' highlighted for the '1st File or Folder' field in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-add-first-folder-winmerge.jpg) 

 For the "2nd File or Folder" field, click the "Browse" button and choose the second folder to compare.

!['Browse' highlighted for the '2nd File or Folder' field in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-add-second-folder-winmerge.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In both fields, enable the "Read-Only" option. Click the "Folder: Filter" field and type **\*.\*** if it isn’t already there. This ensures the app compares all the files in both the specified folders. Then, at the bottom, click "Compare."

![Various comparison options highlighted in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-configure-comparison-options-winmerge.jpg) 

 On the following screen, you’ll see the comparison of the specified folders. You’ll see information like identical files in both folders, files missing from one folder, and so on.

![The comparison of two folders in WinMerge.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-folder-comparison-winmerge.jpg) 

 And that's how you know what one folder has that another doesn't. This can be really useful if you're trying to quickly compare different versions of the same folder, like you'd have when you[create a backup](https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-on-iphone-14-pro-max-if-youve-tried-everything-by-drfone-ios/).

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
<li><a href="https://youtube-blog.techidaily.com/n-2024-restoring-your-online-presence-post-strike/"><u>[New] In 2024, Restoring Your Online Presence Post-Strike</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-stepwise-route-to-discovering-elusive-youtube-footage/"><u>[New] The Stepwise Route to Discovering Elusive YouTube Footage</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-2023-how-to-share-twitter-videos-on-facebook/"><u>[Updated] 2024 Approved 2023 | How to Share Twitter Videos on Facebook?</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-unleash-your-twitter-potential-premium-video-upload-tools-for-2024/"><u>[Updated] Unleash Your Twitter Potential Premium Video Upload Tools for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-from-purchase-to-use-installing-vrecord/"><u>2024 Approved From Purchase to Use Installing VRecord</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/a-comprehensive-step-by-step-tutorial-for-downloading-and-installing-aoc-monitor-drivers-on-various-windows-versions/"><u>A Comprehensive Step-by-Step Tutorial for Downloading and Installing AOC Monitor Drivers on Various Windows Versions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/beyond-siri-how-apples-shift-towards-an-ai-centric-approach-mirrors-microsofts-use-of-bing/"><u>Beyond Siri: How Apple's Shift Towards an AI-Centric Approach Mirrors Microsoft's Use of Bing</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/future-of-tablets-unveiled-anticipate-two-advanced-oled-ipads-and-a-refreshed-129-air-by-apple-in-early-2024-as-revealed/"><u>Future of Tablets Unveiled: Anticipate Two Advanced OLED iPads & A Refreshed 12.9 Air by Apple in Early 2024, as Revealed</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-lost-files-from-realme-11x-5g-by-fonelab-android-recover-data/"><u>How to retrieve lost files from Realme 11X 5G?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-free-online-video-orientation-changer-best-options/"><u>New Free Online Video Orientation Changer Best Options</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revolutionizing-mobile-cinematography-apple-integrates-final-cut-pro-into-iphones-for-stunningly-professional-results/"><u>Revolutionizing Mobile Cinematography: Apple Integrates Final Cut Pro Into iPhones for Stunningly Professional Results</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/risks-alerted-authentic-apple-watch-chargers-vital-avoid-fakes-and-certification-doubts/"><u>Risks Alerted: Authentic Apple Watch Chargers Vital - Avoid Fakes and Certification Doubts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/tech-update-apples-projected-launch-of-budget-friendly-ar-glasses-and-vision-devices-as-revealed-by-zdnet/"><u>Tech Update: Apple's Projected Launch of Budget-Friendly AR Glasses and Vision Devices as Revealed by ZDNet</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-throwback-gadget-upgrade-an-iphone-case-that-makes-you-feel-like-the-blackberry-heyday-again/"><u>The Ultimate Throwback Gadget Upgrade: An iPhone Case That Makes You Feel Like the BlackBerry Heyday Again!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-ranked-macos-software-a-comprehensive-guide-by-zdnet/"><u>Top-Ranked macOS Software : A Comprehensive Guide by ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-ranking-2024-stylus-tablets-comprehensive-reviews-by-tech-specialists-zdnet/"><u>Top-Ranking 2024 Stylus Tablets: Comprehensive Reviews by Tech Specialists | ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-the-secrets-of-affordable-tunes-a-step-by-step-guide-to-snagging-your-apple-music-student-rate/"><u>Unlocking the Secrets of Affordable Tunes: A Step-by-Step Guide to Snagging Your Apple Music Student Rate</u></a></li>
</ul></div>

