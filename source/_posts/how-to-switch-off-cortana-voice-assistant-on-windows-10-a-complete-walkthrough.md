---
title: How to Switch Off Cortana Voice Assistant on Windows 10 - A Complete Walkthrough
date: 2025-01-24T18:35:47.982Z
updated: 2025-01-30T17:15:26.909Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How to Switch Off Cortana Voice Assistant on Windows 10 - A Complete Walkthrough
excerpt: This Article Describes How to Switch Off Cortana Voice Assistant on Windows 10 - A Complete Walkthrough
thumbnail: https://thmb.techidaily.com/01a181b2c169140bb50e16f105fae6a9a347e62628b7a3a5060d5bc396913a4e.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://fox-access.techidaily.com/new-journey-ahead-an-in-depth-look-at-panasonics-hx-a1-wearable-camera-for-2024/"><u>[New] Journey Ahead - An In-Depth Look at Panasonic’s HX-A1 Wearable Camera for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-bushido-code-continuation-top-similar-game-experiences/"><u>[Updated] In 2024, Bushido Code Continuation - Top Similar Game Experiences</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-ps4-broadcasting-made-easy-your-obs-guide/"><u>[Updated] In 2024, PS4 Broadcasting Made Easy Your OBS Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1-introducing-apples-enhanced-logic-pro-smart-ai-powered-bandmates-for-tablet-and-desktop-musicians-zdnet/"><u>1. Introducing Apple's Enhanced Logic Pro: Smart AI-Powered Bandmates for Tablet & Desktop Musicians - ZDNet</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210970067-9781088235669-entre-el-amor-y-la-guerra/"><u>Entre el Amor y la Guerra | Free Book</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-smartphone-assessment-techniques-inside-zdnets-mobile-lab/"><u>Exploring Smartphone Assessment Techniques: Inside ZDNet's Mobile Lab</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-vivo-y56-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Vivo Y56 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-chromebooks-voice-alteration-guide-the-leading-online-text-to-speech-apps/"><u>In 2024, Chromebook's Voice Alteration Guide The Leading Online Text-to-Speech Apps</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-master-iphone-cinematography-top-8-tips-for-professional-video-shooting/"><u>In 2024, Master iPhone Cinematography Top 8 Tips for Professional Video Shooting</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-7-best-action-cameras-for-snowboardingskiing/"><u>In 2024, Top 7 Best Action Cameras for Snowboarding/Skiing</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/innovative-leap-apples-upcoming-airpods-equipped-with-cameras-set-to-hit-the-market-in-2026-reports-zdnet/"><u>Innovative Leap: Apple's Upcoming AirPods Equipped with Cameras Set to Hit the Market in 2026, Reports ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-apple-pay-a-comprehensive-guide-for-seamless-shopping-both-offline-and-online-insights/"><u>Mastering Apple Pay: A Comprehensive Guide for Seamless Shopping Both Offline & Online - Insights</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-walkthrough-for-converting-your-spotify-queues-to-editable-txt-files/"><u>The Ultimate Walkthrough for Converting Your Spotify Queues to Editable TXT Files</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-accessory-picks-for-your-airpods-pro-the-ultimate-guide/"><u>Top Accessory Picks for Your AirPods Pro: The Ultimate Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-airtag-gadgets-and-accessories-2024s-ultimate-selection-techreview/"><u>Top-Rated AirTag Gadgets & Accessories - 2024'S Ultimate Selection | TechReview</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-to-small-tablet-picks-for-2eby-2024-in-depth-analysis-and-ratings/"><u>Ultimate Guide to Small Tablet Picks for 2Eby 2024 - In-Depth Analysis and Ratings</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unbeatable-offer-score-the-newest-2022-ipad-pro-at-a-whopping-700-off-for-labor-day-celebrations-techexaminer/"><u>Unbeatable Offer! Score the Newest 2022 iPad Pro at a Whopping $700 Off for Labor Day Celebrations | TechExaminer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-m3-macbook-air-by-apple-how-this-innovative-ai-device-is-changing-the-game-for-everyone-zdnet/"><u>Unveiling the M3 MacBook Air by Apple - How This Innovative AI Device Is Changing the Game for Everyone | ZDNET</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-the-technology-behind-whatsapp-voice-calls/"><u>Unveiling the Technology Behind WhatsApp Voice Calls</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

