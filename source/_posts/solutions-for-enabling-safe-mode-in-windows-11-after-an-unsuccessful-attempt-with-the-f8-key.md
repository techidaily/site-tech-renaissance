---
title: Solutions for Enabling Safe Mode in Windows 11 After an Unsuccessful Attempt with the F8 Key
date: 2025-02-08T18:13:41.199Z
updated: 2025-02-11T16:12:14.973Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Solutions for Enabling Safe Mode in Windows 11 After an Unsuccessful Attempt with the F8 Key
excerpt: This Article Describes Solutions for Enabling Safe Mode in Windows 11 After an Unsuccessful Attempt with the F8 Key
thumbnail: https://thmb.techidaily.com/3a0ddaab1602f9aac9589130fbb24dc40e59a2711040c0e283860347f1ffa1fb.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-integrating-youtube-media-into-instagram-experience/"><u>[New] Integrating YouTube Media Into Instagram Experience</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-leading-tech-the-top-10-4k-camera-phones-reviewed-for-2024/"><u>[New] Leading Tech The Top 10 4K Camera Phones Reviewed for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-vlog-to-audio-conversion-with-twitta-for-2024/"><u>[New] Vlog-to-Audio Conversion with Twitta for 2024</u></a></li>
<li><a href="https://win-special.techidaily.com/5luo5a6j5ywo5qih5byp5bya5ael77ya5aac5l2v5zyo5lin5zcm56gs5lu25lik5ywl6zqg5oiw6lplusy5y6f57o757uf/"><u>从安全模式开始：如何在不同硬件上克隆或还原系统</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/androids-roadmap-to-supremacy-key-areas-of-enhancement-against-ios-identified-by-zdnet/"><u>Android's Roadmap to Supremacy: Key Areas of Enhancement Against iOS Identified by ZDNet</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/automated-calendar-management-for-remote-teams/"><u>Automated Calendar Management for Remote Teams</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-advancements-in-apple-airpods-series-3-a-comprehensive-zdnet-review-on-optimized-audio-performance-and-features/"><u>Exploring the Advancements in Apple AirPods Series 3: A Comprehensive ZDNET Review on Optimized Audio Performance and Features</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/pixelplay-logger-analysis-for-2024/"><u>PixelPlay Logger Analysis for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/revitalizing-urban-development-challenges-how-to-get-your-skyfortress-game-running/"><u>Revitalizing Urban Development Challenges: How to Get Your SkyFortress Game Running</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/samsung-galaxy-watch-next-gen-unpacking-costs-anticipated-launch-dates-feature-breakdown-and-new-developments/"><u>Samsung Galaxy Watch Next-Gen: Unpacking Costs, Anticipated Launch Dates, Feature Breakdown & New Developments</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-solutions-getting-tiktok-up-and-running-again/"><u>Step-by-Step Solutions: Getting TikTok Up and Running Again</u></a></li>
<li><a href="https://media-tips.techidaily.com/stream-and-share-on-multiple-services-at-once-using-telepartys-unique-feature/"><u>Stream and Share on Multiple Services at Once Using Teleparty's Unique Feature!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-battle-of-silicon-titans-is-the-m2-powered-mac-mini-outshining-its-m1-equipped-mac-studio-counterpart/"><u>The Battle of Silicon Titans: Is the M2-Powered Mac Mini Outshining Its M1 Equipped Mac Studio Counterpart?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-12-best-no-cost-voip-services-in-24-a-comprehensive-guide/"><u>Top 12 Best No-Cost VoIP Services in 2^4 - A Comprehensive Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-vivo-y100i-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Vivo Y100i Location | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-wireless-charging-pads-industry-experts-reviews-pcmag/"><u>Top-Rated Wireless Charging Pads - Industry Experts' Reviews | PCMag</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-to-the-markets-best-computers-of-202n4-benchmarking-apple-vs-dell-and-others-gadgetflow/"><u>Ultimate Guide to the Market's Best Computers of 202N4: Benchmarking Apple Vs. Dell and Others - GadgetFlow</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-apples-vintage-mode-navigating-older-devices-in-the-modern-era-zdnet/"><u>Understanding Apple's 'Vintage Mode': Navigating Older Devices in the Modern Era | ZDNet</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/wood-species-and-external-drying-conditions-can-significantly-influence-the-thermal-behavior-of-wood-during-processing/"><u>Wood Species and External Drying Conditions Can Significantly Influence the Thermal Behavior of Wood During Processing.</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

