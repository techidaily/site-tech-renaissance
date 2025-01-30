---
title: "Preparing Your PC: Essential Tips Before Upgrading to the Windows 11 Creator's Edition"
date: 2025-01-26T16:06:01.830Z
updated: 2025-01-30T17:10:36.731Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Preparing Your PC: Essential Tips Before Upgrading to the Windows 11 Creator's Edition"
excerpt: "This Article Describes Preparing Your PC: Essential Tips Before Upgrading to the Windows 11 Creator's Edition"
thumbnail: https://thmb.techidaily.com/48f4aa553b20375d2e1fe666e74fcb8eb031257aa3408ce619e341568a63ddba.jpg
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
<li><a href="https://facebook-video-footage.techidaily.com/new-economical-microphones-catered-to-vloggers-for-2024/"><u>[New] Economical Microphones Catered to Vloggers for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-best-top-timelapses-quick-capture-and-edit/"><u>[Updated] 2024 Approved Best Top Timelapses Quick Capture & Edit</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-best-quality-steadicam-equipment-for-drone-filmmaking/"><u>[Updated] Best-Quality Steadicam Equipment for Drone Filmmaking</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-grids-for-greatness-photographs-next-step-up/"><u>[Updated] Grids for Greatness Photographs' Next Step Up</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/complete-instructions-to-correct-the-absence-of-d3dx933dll-file/"><u>Complete Instructions to Correct the Absence of d3dx9_33.dll File</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-the-allure-of-upgraded-tech-drives-impulse-buys-unpacking-apples-new-17-usb-c-earpods/"><u>How the Allure of Upgraded Tech Drives Impulse Buys: Unpacking Apple's New $17 USB-C EarPods</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-delete-icloud-account-with-or-without-password-from-your-iphone-11-prowindowsmac-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account with or without Password from your iPhone 11 Pro/Windows/Mac</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcoming-performance-issues-solutions-for-higher-fps-in-rainbow-six-extraction/"><u>Overcoming Performance Issues: Solutions for Higher FPS in Rainbow Six Extraction</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-6-super-mario-bros-games-for-the-pc/"><u>Top 6 Super Mario Bros Games for the PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unraveling-the-mystery-how-did-crowdstrike-spark-windows-major-security-breach-historical-insights-from-zdnet/"><u>Unraveling the Mystery: How Did CrowdStrike Spark Windows' Major Security Breach ? Historical Insights From ZDNet</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

