---
title: Diagnose and Fix Intensive CPU Consumption During Windows Modules Install on W10
date: 2025-02-06T00:09:13.720Z
updated: 2025-02-12T00:39:46.944Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Diagnose and Fix Intensive CPU Consumption During Windows Modules Install on W10
excerpt: This Article Describes Diagnose and Fix Intensive CPU Consumption During Windows Modules Install on W10
thumbnail: https://thmb.techidaily.com/0b81880445efb7746c34685a24a5e53155bfff0ac907d2d7a06d83968e5eaef1.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-speedy-solution-8-best-slow-mo-video-enhancers/"><u>[New] In 2024, Speedy Solution 8 Best Slow-Mo Video Enhancers</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-top-pick-automated-video-to-text-tools/"><u>[Updated] 2024 Approved Top Pick Automated Video to Text Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unlocking-smooth-streams-facebooks-buffering-breakthrough-for-2024/"><u>[Updated] Unlocking Smooth Streams - Facebook's Buffering Breakthrough for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-10-best-funny-videos-on-twitter/"><u>2024 Approved 10 Best Funny Videos on Twitter</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-deleting-youtube-content-a-step-by-step-guide/"><u>2024 Approved Deleting YouTube Content A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-leading-alternative-to-apple-and-tile-expert-evaluation-of-the-best-wallet-airtags-zdnet-insights/"><u>Discover the Leading Alternative to Apple and Tile: Expert Evaluation of the Best Wallet AirTags | ZDNET Insights</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-honor-play-8t-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Honor Play 8T Through Google Earth?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/macbook-showdown-pro-vs-air-decoding-features-to-find-your-perfect-match-for-work-and-play-zdnet/"><u>MacBook Showdown: Pro Vs. Air - Decoding Features to Find Your Perfect Match for Work and Play | ZDNET</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/maximize-your-iphone-storage-with-easy-de-cluttering-tips-techtut/"><u>Maximize Your iPhone Storage with Easy De-Cluttering Tips | TechTut</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-36-prime-day-tablet-bargains-of-2024-exclusive-offers-you-dont-want-to-miss/"><u>Top 36 Prime Day Tablet Bargains of 2024: Exclusive Offers You Don't Want to Miss!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-and-fixes-for-when-d3d9dll-is-absent-or-unreachable/"><u>Troubleshooting and Fixes for When d3d9.dll Is Absent or Unreachable</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveiling-advanced-features-of-vlc-for-mac-users/"><u>Unveiling Advanced Features of VLC for Mac Users</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

