---
title: Comprehensive Guide To Reviving Non-Working USB Ports On Laptops
date: 2025-01-27T16:30:43.023Z
updated: 2025-01-30T16:51:53.166Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Comprehensive Guide To Reviving Non-Working USB Ports On Laptops
excerpt: This Article Describes Comprehensive Guide To Reviving Non-Working USB Ports On Laptops
thumbnail: https://thmb.techidaily.com/6bdcba73a44ac207e8fdf00ab1c5febff71a5d180b14959fd7d55488ff318cda.jpg
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
<li><a href="https://youtube-blog.techidaily.com/irectly-infuse-youtube-music-into-any-imovie-project/"><u>[New] Directly Infuse YouTube Music Into Any iMovie Project</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-complete-evaluation-the-dji-inspire-1-unveiled/"><u>[New] In 2024, Complete Evaluation The DJI Inspire 1 Unveiled</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-projector-vs-tv-showdown-which-prevails-in-4k-clarity/"><u>[New] Projector vs TV Showdown Which Prevails in 4K Clarity?</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-ghostly-movies-innovation-in-recorders/"><u>[Updated] In 2024, Ghostly Movies Innovation in Recorders</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/apples-revolutionary-move-new-camera-enabled-airpods-on-the-horizon-for-2eighty-six-according-to-zdnet-coverage/"><u>Apple's Revolutionary Move? New Camera-Enabled AirPods on the Horizon for 2Eighty-Six, According to ZDNET Coverage</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-a78-5g-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on A78 5G.</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/elevate-your-wristwear-game-in-depth-review-and-faceoff-between-new-google-pixel-watch-and-apple-watch-series-9/"><u>Elevate Your Wristwear Game: In-Depth Review and Faceoff Between New Google Pixel Watch and Apple Watch Series 9</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/immersive-4k-visuals-and-seamless-roku-integration-in-hitachi-television-models/"><u>Immersive 4K Visuals and Seamless Roku Integration in Hitachi Television Models</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-8-solutions-to-fix-find-my-friends-location-not-available-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>In 2024, 8 Solutions to Fix Find My Friends Location Not Available On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/inside-the-world-of-toms-hardware-components-and-systems/"><u>Inside the World of Tom's Hardware Components & Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/no-more-error-code-31-woes-proven-techniques-to-restore-your-windows-stability/"><u>No More Error Code 31 Woes: Proven Techniques to Restore Your Windows Stability</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-inexpensive-apple-watch-series-se-gets-a-fresh-look-discover-the-latest-enhancements-digitaltrends/"><u>The Inexpensive Apple Watch Series SE Gets a Fresh Look - Discover the Latest Enhancements | DigitalTrends</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-linking-a-single-telephone-number-across-multiple-platforms/"><u>The Ultimate Guide to Linking a Single Telephone Number Across Multiple Platforms</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-pick-windows-notebook-beats-macbook-air-in-price-and-features-now-at-a-steal-exclusive-review/"><u>Top-Pick Windows Notebook: Beats MacBook Air in Price & Features, Now at a Steal – Exclusive Review</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-resolving-audio-problems-in-windows-7/"><u>Troubleshooting Guide: Resolving Audio Problems in Windows 7</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/turn-off-autoplay-in-your-itunes-library-quick-tips-and-tricks/"><u>Turn Off AutoPlay in Your iTunes Library: Quick Tips & Tricks</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiled-top-4-new-ipados-16-innovations-from-apples-worldwide-developers-conference-2024-compatible-devices-revealed/"><u>Unveiled: Top 4 New iPadOS 16 Innovations From Apple's Worldwide Developers Conference 2024 - Compatible Devices Revealed!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

