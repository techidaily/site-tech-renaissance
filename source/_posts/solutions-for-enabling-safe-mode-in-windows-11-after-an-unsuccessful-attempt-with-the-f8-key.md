---
title: Solutions for Enabling Safe Mode in Windows 11 After an Unsuccessful Attempt with the F8 Key
date: 2024-08-18T22:56:11.633Z
updated: 2024-08-19T22:56:11.633Z
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-discover-the-top-7-free-youtube-tag-extractor-vendors/"><u>[New] 2024 Approved  Discover the Top 7 Free YouTube Tag Extractor Vendors</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-the-art-of-selecting-peak-pace-for-slow-video-capture/"><u>[New] Mastering the Art of Selecting Peak Pace for Slow Video Capture</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-rendering-reawakening-amds-radeon/"><u>[Updated] 2024 Approved  Rendering Reawakening  AMD's Radeon</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-infinix-note-30-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Infinix Note 30 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ace-your-productivity-learn-the-top-18-ios-shortcut-app-tricks-to-streamline-tasks/"><u>Ace Your Productivity: Learn the Top 18 iOS Shortcut App Tricks to Streamline Tasks</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/affordable-alternatives-the-best-10-free-streaming-platforms-like-netflix/"><u>Affordable Alternatives: The Best 10 Free Streaming Platforms Like Netflix</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/bridge-platforms-steps-to-access-icloud-images-anywhere/"><u>Bridge Platforms: Steps to Access iCloud Images Anywhere</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/co-listening-is-it-possible-for-two-people-to-stream-on-spotify-at-once/"><u>Co-Listening: Is It Possible for Two People to Stream on Spotify at Once?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diving-deeper-into-dac-technology-is-it-worth-adding-to-your-audio-setup/"><u>Diving Deeper Into DAC Technology: Is It Worth Adding To Your Audio Setup?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-battery-swap-techniques-for-revitalizing-your-ipad/"><u>DIY Battery Swap Techniques for Revitalizing Your iPad</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effective-ways-to-reach-out-to-snapchat-support/"><u>Effective Ways to Reach Out to Snapchat Support</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/efficient-methods-to-restore-default-settings-on-your-dell-laptop-device/"><u>Efficient Methods to Restore Default Settings on Your Dell Laptop Device</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exclusive-look-at-the-rumored-tesla-mobile-device-anticipated-release-schedule-price-estimates-and-teasers-on-advanced-features/"><u>Exclusive Look at the Rumored Tesla Mobile Device - Anticipated Release Schedule, Price Estimates & Teasers on Advanced Features</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-our-expert-picks-the-ultimate-guide-to-iphone-gps-applications/"><u>Explore Our Expert Picks: The Ultimate Guide to iPhone GPS Applications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-dll-not-found-issues-with-comctl32dll-on-windows-computers/"><u>Fixing 'DLL Not Found' Issues with Comctl32.dll on Windows Computers</u></a></li>
<li><a href="https://activate-lock.techidaily.com/full-guide-to-apple-iphone-15-plus-icloud-bypass-by-drfone-ios/"><u>Full guide to Apple iPhone 15 Plus iCloud Bypass</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/going-off-the-grid-your-complete-guide-to-wireless-internet-solutions/"><u>Going Off the Grid? Your Complete Guide to Wireless Internet Solutions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-effortlessly-take-screenshots-on-your-playstation/"><u>How to Effortlessly Take Screenshots on Your PlayStation 지킬</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-earn-extra-bucks-maximizing-youtubes-mobile-revenue-opportunities/"><u>In 2024, Earn Extra Bucks  Maximizing YouTube's Mobile Revenue Opportunities</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unveiling-the-finest-zero-cost-digital-darkroom-tools/"><u>In 2024, Unveiling the Finest Zero-Cost Digital Darkroom Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-realme-narzo-60-pro-5g-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Realme Narzo 60 Pro 5G Phones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/inside-the-next-gen-vr-experience-sonys-psvr-2-info-pricing-details-release-schedule-and-hardware-specs-revealed/"><u>Inside the Next-Gen VR Experience - Sony's PSVR 2 Info: Pricing Details, Release Schedule, and Hardware Specs Revealed!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/latest-d-link-factory-passwords-index-for-july-2024-released/"><u>Latest D-Link Factory Passwords Index for July 2024 Released</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mozilla-thunderbird-wont-start-heres-what-you-need-to-do-to-get-it-running-smoothly-again/"><u>Mozilla Thunderbird Won't Start? Here's What You Need to Do to Get It Running Smoothly Again</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-deleted-iphone-whatsapp-attachments-on-mac-and-windows-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Recover Deleted iPhone WhatsApp Attachments on Mac and Windows | Stellar</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-the-user32dll-missing-file-issue-a-step-by-step-guide/"><u>Resolving the 'User32.dll' Missing File Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/seamlessly-link-several-bluetooth-speakers-to-your-smartphone-or-tablet/"><u>Seamlessly Link Several Bluetooth Speakers to Your Smartphone or Tablet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solution-guide-what-to-do-when-your-roku-tv-refuses-to-boot-up/"><u>Solution Guide: What to Do When Your Roku TV Refuses to Boot Up</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solve-your-windows-11-search-problems-with-these-effective-solutions/"><u>Solve Your Windows 11 Search Problems with These Effective Solutions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-issues-with-unopenable-microsoft-word-documents/"><u>Solving Issues with Unopenable Microsoft Word Documents</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-non-functional-issues-with-your-macbook-pro-keyboard-a-step-by-step-guide/"><u>Solving Non-Functional Issues with Your MacBook Pro Keyboard: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-photoshop-scratch-disks-at-capacity-effective-solutions/"><u>Solving Photoshop Scratch Disks at Capacity: Effective Solutions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-entering-and-exiting-iphones-safe-mode/"><u>Step-by-Step Guide: Entering and Exiting iPhone's Safe Mode</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/steps-to-reactivate-a-disabled-instagram-profile-a-comprehensive-guide/"><u>Steps to Reactivate a Disabled Instagram Profile: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/stream-on-the-big-screen-how-to-hook-up-a-laptop-to-tv-via-hdmi/"><u>Stream on the Big Screen: How to Hook Up a Laptop to TV via HDMI</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/tap-into-easy-payments-the-ultimate-guide-to-setting-up-and-using-apple-pay-on-an-apple-watch/"><u>Tap Into Easy Payments: The Ultimate Guide to Setting Up and Using Apple Pay on an Apple Watch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-steps-for-when-d3dx940dll-cannot-be-located/"><u>Troubleshooting Steps for When d3dx9_40.dll Cannot Be Located</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-removing-applications-from-your-mac-with-ease/"><u>Ultimate Guide: Removing Applications From Your Mac with Ease</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-steps-to-permanently-remove-your-twitch-profile/"><u>Ultimate Guide: Steps to Permanently Remove Your Twitch Profile</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlock-fast-video-trimming-in-windows-11-apps/"><u>Unlock Fast Video Trimming in Windows 11 Apps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-next-innovation-the-oneplus-nord-ce-anticipated-costs-launch-timeline-and-potential-features/"><u>Unveiling the Next Innovation: The OnePlus Nord CE - Anticipated Costs, Launch Timeline & Potential Features</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/upcoming-foldable-iphones-unveiled-pricing-launch-timeline-and-features-revealed/"><u>Upcoming Foldable iPhones Unveiled: Pricing, Launch Timeline & Features Revealed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/virtual-interview-mastery-2024s-proven-strategies-to-land-your-dream-role/"><u>Virtual Interview Mastery: 2024'S Proven Strategies to Land Your Dream Role</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/whats-the-current-macos-the-complete-macos-versions-guide/"><u>What's the Current macOS? The Complete macOS Versions Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/your-insider-source-for-samsungs-big-event-2025-date-reveals-and-anticipated-product-launches/"><u>Your Insider Source for Samsung's Big Event - 2025 Date Reveals and Anticipated Product Launches</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->