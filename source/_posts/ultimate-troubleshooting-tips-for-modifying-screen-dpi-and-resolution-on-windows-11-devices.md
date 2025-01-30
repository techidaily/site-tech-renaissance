---
title: Ultimate Troubleshooting Tips for Modifying Screen DPI & Resolution on Windows 11 Devices
date: 2025-01-27T18:01:17.009Z
updated: 2025-01-30T16:40:26.026Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Ultimate Troubleshooting Tips for Modifying Screen DPI & Resolution on Windows 11 Devices
excerpt: This Article Describes Ultimate Troubleshooting Tips for Modifying Screen DPI & Resolution on Windows 11 Devices
thumbnail: https://thmb.techidaily.com/bc4e71fa64ffb5cacb645afa1410abd3ad84d4a51ac3139b9a6d52813f47097e.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-capture-perfection-reviewing-the-best-5-hd-webcams-with-audio/"><u>[New] In 2024, Capture Perfection Reviewing The Best 5 HD Webcams with Audio</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-boost-connectivity-discover-the-best-5-chrome-tools-for-facebook-videos-for-2024/"><u>[Updated] Boost Connectivity Discover the Best 5 Chrome Tools for Facebook Videos for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-quick-clicks-big-smiles-crafting-memes-easily/"><u>2024 Approved Quick Clicks, Big Smiles Crafting Memes Easily</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/4-ways-to-unlock-apple-iphone-xs-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>4 Ways to Unlock Apple iPhone XS to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/5-ingenieuze-methoden-om-een-gekeus-standpunt-te-creeren-in-windows-1110-startleerlingen-vergemakkelijkt/"><u>5 Ingenieuze Methoden Om Een Gekeus Standpunt Te Creëren in Windows 11/10: Startleerlingen Vergemakkelijkt!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/android-efficiency-techniques-to-curb-covert-running-of-apps-behind-the-scenes/"><u>Android Efficiency: Techniques to Curb Covert Running of Apps Behind the Scenes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensively-understanding-wm6-setup/"><u>Comprehensively Understanding WM6 Setup</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-our-curated-list-of-favorite-free-movie-picks-on-youtube-july-edition/"><u>Discover Our Curated List of Favorite Free Movie Picks on YouTube - July Edition</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/enhancing-your-tiktok-intro-with-mac-techniques/"><u>Enhancing Your TikTok Intro with Mac Techniques</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722888197043-essentials-unveiled-a-buyers-guide-to-picking-the-perfect-smartwatch-top-5-tips/"><u>Essentials Unveiled: A Buyer's Guide to Picking the Perfect Smartwatch - Top 5 Tips!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/iphone-tips-how-to-prevent-silent-intruders-by-blocking-private-numbers-and-no-caller-id/"><u>IPhone Tips: How To Prevent Silent Intruders by Blocking Private Numbers & No Caller ID</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/les-plus-performants-solutions-de-backup-pour-outlook-options-libres-et-securisees/"><u>Les Plus Performants Solutions De Backup Pour Outlook: Options Libres Et Sécurisées</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/professionals-choice-5-outstanding-video-editing-solutions-to-boost-your-production-quality/"><u>Professionals' Choice: 5 Outstanding Video Editing Solutions to Boost Your Production Quality</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-integrating-code-snippets-into-your-word-document/"><u>Step-by-Step Guide: Integrating Code Snippets Into Your Word Document</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-essential-how-to-promoting-key-imconversations-in-your-instagram-feed/"><u>The Essential How-To: Promoting Key IMConversations in Your Instagram Feed</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/allocation-mastery-work-and-youtube-synergy/"><u>Time Allocation Mastery Work & YouTube Synergy</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-tutorial-on-launching-command-prompt-across-various-windows-versions/"><u>Ultimate Tutorial on Launching Command Prompt Across Various Windows Versions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

