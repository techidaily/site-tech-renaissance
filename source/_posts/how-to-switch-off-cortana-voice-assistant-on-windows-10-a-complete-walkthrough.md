---
title: How to Switch Off Cortana Voice Assistant on Windows 10 - A Complete Walkthrough
date: 2024-08-18T22:53:58.884Z
updated: 2024-08-19T22:53:58.884Z
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
<li><a href="https://vimeo-videos.techidaily.com/new-deciding-on-ideal-vimeo-subscription-plan-for-2024/"><u>[New] Deciding on Ideal Vimeo Subscription Plan for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-excellent-applications-reshaping-the-art-of-virtual-broadcasting/"><u>[New] In 2024, Excellent Applications Reshaping the Art of Virtual Broadcasting</u></a></li>
<li><a href="https://youtube-web.techidaily.com/tarting-strong-with-these-trendy-15-video-intros-for-2024/"><u>[New] Starting Strong with These Trendy 15 Video Intros for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-for-streamlining-iphone-video-content/"><u>[Updated] The Ultimate Guide for Streamlining iPhone Video Content</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-ultimate-list-best-no-cost-lut-downloads/"><u>[Updated] Ultimate List  Best No-Cost LUT Downloads</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-professional-gear-tips-gopro-edition/"><u>2024 Approved  Professional Gear Tips  GoPro Edition</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-comprehensive-guide-to-choosing-between-cat5-or-cat6-cables-for-your-home-office/"><u>A Comprehensive Guide to Choosing Between Cat5 or Cat6 Cables for Your Home Office</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/bring-the-best-of-both-worlds-operating-android-apps-on-windows-11-systems/"><u>Bring the Best of Both Worlds: Operating Android Apps on Windows 11 Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capturing-perfect-sounds-our-top-6-recommendations-for-livestreamers-for-2024/"><u>Capturing Perfect Sounds  Our Top 6 Recommendations for Livestreamers for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-7-traffic-control-software/"><u>Discover the Ultimate 7 Traffic Control Software</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-list-of-complimentary-cross-border-chat-tools/"><u>Discover the Ultimate List of Complimentary Cross-Border Chat Tools</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-immersive-worlds-identifying-key-variations-among-ar-vr-mr-and-xr/"><u>Exploring Immersive Worlds: Identifying Key Variations Among AR, VR, MR & XR</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/from-play-to-post-how-to-snap-and-share-game-images-from-your-nintendo-switch/"><u>From Play to Post: How to Snap and Share Game Images From Your Nintendo Switch</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-xs-max-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone XS Max Data Permanently | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-crafting-unique-360-degree-videos-on-an-iphone/"><u>In 2024, Crafting Unique 360-Degree Videos on an iPhone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/list-of-ipad-devices-with-integrated-gps-technology/"><u>List of iPad Devices with Integrated GPS Technology</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-key-retrieval-top-acoustic-locator-2e-devices-of-the-year-2024-unveiled/"><u>Mastering Key Retrieval: Top Acoustic Locator '2E' Devices of the Year 2024 Unveiled</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-parsing-avoid-these-common-errors-with-our-top-grooks-and-fixes-in-android-development/"><u>Mastering Parsing: Avoid These Common Errors with Our Top Grooks and Fixes in Android Development</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723010692599-phoenix-point-crash-dilemma-heres-how-you-can-get-back-on-track/"><u>Phoenix Point Crash Dilemma? Here's How You Can Get Back on Track!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/regain-entry-to-your-ipad-a-guide-on-password-or-passcode-restoration/"><u>Regain Entry to Your iPad: A Guide on Password or Passcode Restoration</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/silence-is-golden-a-step-by-step-guide-to-noise-reduction-in-fcpx/"><u>Silence Is Golden A Step-by-Step Guide to Noise Reduction in FCPX</u></a></li>
<li><a href="https://facebook.techidaily.com/step-by-step-guide-facebook-group-assembly-blueprints/"><u>Step-by-Step Guide: Facebook Group Assembly Blueprints</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-remedies-for-your-magic-mouses-tracking-problems/"><u>Step-by-Step Remedies for Your Magic Mouse's Tracking Problems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tutorial-linking-disneyplus-with-your-google-chromecast-for-hassle-free-viewing/"><u>Step-by-Step Tutorial: Linking Disney+ with Your Google Chromecast for Hassle-Free Viewing</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ins-and-outs-of-ray-tracing-what-you-need-to-know/"><u>The Ins and Outs of Ray Tracing: What You Need to Know</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-combining-your-favorite-songs-into-one-spotify-list/"><u>The Ultimate Guide to Combining Your Favorite Songs Into One Spotify List</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/trouble-with-msidll-heres-how-to-fix-the-file-not-detected-error/"><u>Trouble with msi.dll? Here’s How to Fix the File Not Detected Error</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-steps-for-resolving-vpn-connection-issue-code-80n/"><u>Troubleshooting Steps for Resolving VPN Connection Issue: Code 80N</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-steps-resolving-issues-with-windows-11-not-shutting-down/"><u>Troubleshooting Steps: Resolving Issues with Windows 11 Not Shutting Down</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-to-victorious-battles-against-links-enemies-defeat-a-breath-of-the-wild-lynel/"><u>Ultimate Guide to Victorious Battles Against Link's Enemies: Defeat a Breath of the Wild Lynel</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-404-errors-strategies-for-resolution-and-prevention/"><u>Understanding 404 Errors: Strategies for Resolution & Prevention</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unleash-your-creativity-using-the-latest-photo-cutout-tool-on-iphones-ios-16/"><u>Unleash Your Creativity Using the Latest Photo Cutout Tool on iPhones (iOS 16)</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-download-4k-videos-in-mp4-the-best-conversion-methods-explained/"><u>Updated 2024 Approved Download 4K Videos in MP4 The Best Conversion Methods Explained</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722883354527-vizio-televisions-and-wi-fi-woes-heres-how-you-can-fix-it/"><u>Vizio Televisions and Wi-Fi Woes? Here's How You Can Fix It</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Realme C67 5G | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->