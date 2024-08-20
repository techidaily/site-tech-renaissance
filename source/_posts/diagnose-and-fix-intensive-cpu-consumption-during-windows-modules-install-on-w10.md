---
title: Diagnose and Fix Intensive CPU Consumption During Windows Modules Install on W10
date: 2024-08-18T22:58:29.265Z
updated: 2024-08-19T22:58:29.265Z
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-cutting-edge-tech-to-record-your-remote-gatherings/"><u>[New] 2024 Approved  Cutting-Edge Tech to Record Your Remote Gatherings</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-ultimate-playbook-navigating-youtube-etiquette/"><u>[New] 2024 Approved  Ultimate Playbook  Navigating YouTube Etiquette</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-video-exporting-youtube-content-directed-to-facebook-stream/"><u>[New] 2024 Approved  Video Exporting  YouTube Content Directed to Facebook Stream</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-captured-discourse-inspection/"><u>[New] Captured Discourse Inspection</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-soundtrack-to-life-fbs-music-offerings/"><u>[New] In 2024, Soundtrack to Life  FB's Music Offerings</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-5-simplified-steps-for-sequential-youtube-video-viewing-free/"><u>[Updated] 2024 Approved  5 Simplified Steps for Sequential YouTube Video Viewing (Free)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-a-step-by-step-guide-to-updating-photos-and-videos-on-instagram-for-2024/"><u>[Updated] A Step-by-Step Guide to Updating Photos and Videos on Instagram for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-quieting-unwanted-sounds-obs-audio-issue-fixed/"><u>[Updated] In 2024, Quieting Unwanted Sounds  OBS Audio Issue Fixed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-comprehensive-tutorial-to-access-password-archives-on-a-mac-computer/"><u>A Comprehensive Tutorial to Access Password Archives on a Mac Computer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-comprehensive-tutorial-restoring-or-replacing-rockaldlldll-when-its-unavailable-or-deleted/"><u>A Comprehensive Tutorial: Restoring or Replacing rockaldll.dll When It's Unavailable or Deleted</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-you-need-to-know-about-macos-15-sequoia-upcoming-release-schedule-and-expert-breakdown-of-key-enhancements/"><u>All You Need to Know About MacOS 15 Sequoia: Upcoming Release Schedule & Expert Breakdown of Key Enhancements</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/anticipating-the-google-pixel-10-latest-leaks-on-price-release-date-and-specs/"><u>Anticipating the Google Pixel 10 - Latest Leaks on Price, Release Date & Specs!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/arranging-your-matrix-film-experience-from-origins-to-revolutions/"><u>Arranging Your Matrix Film Experience: From Origins to Revolutions</u></a></li>
<li><a href="https://win11.techidaily.com/clear-and-concise-views-mastering-compact-explorer-layout/"><u>Clear and Concise Views: Mastering Compact Explorer Layout</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/connect-airpods-to-hp-pc-effortlessly-the-ultimate-how-to-tutorial/"><u>Connect AirPods to HP PC Effortlessly - The Ultimate How-To Tutorial</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-our-picks-the-best-second-mobile-numbers-applications/"><u>Discover Our Picks: The Best Second Mobile Numbers Applications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-best-free-backup-programs-for-secure-data-management-the-definitive-guide-and-comparison/"><u>Discover the Best Free Backup Programs for Secure Data Management - The Definitive Guide & Comparison</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-signs-is-my-text-being-read/"><u>Discover the Signs: Is My Text Being Read?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-top-10-fitness-journalling-apps-revolutionizing-workouts/"><u>Discover the Top 10 Fitness Journalling Apps Revolutionizing Workouts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/elevate-your-diary-habits-with-our-selection-of-the-best-journaling-apps/"><u>Elevate Your Diary Habits with Our Selection of the Best ✍️ Journaling Apps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-strategies-to-correct-kernel-memory-issues-on-your-pc/"><u>Expert Strategies to Correct Kernel Memory Issues on Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-the-easiest-and-cheapest-4-online-planners-out-there/"><u>Explore the Easiest and Cheapest 4 Online Planners Out There</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-zoom-camera-problems-a-step-by-step-guide/"><u>Fixing Zoom Camera Problems: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-correctly-address-pdhdll-absent-or-undetectable-errors/"><u>How to Correctly Address pdh.dll Absent or Undetectable Errors</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-realme-narzo-60-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-resolve-the-problem-of-a-non-functioning-google-meet-webcam/"><u>How To Resolve the Problem of a Non-Functioning Google Meet Webcam?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-vivo-x-fold-2-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Vivo X Fold 2 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-streamlined-mp4-creation-must-have-tools-on-mac/"><u>In 2024, Streamlined MP4 Creation  Must-Have Tools on Mac</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/is-it-worth-constructing-or-purchasing-your-own-desktop-system/"><u>Is It Worth Constructing or Purchasing Your Own Desktop System?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/latest-comprehensive-guide-linksys-default-passwords-as-of-july-2024/"><u>Latest Comprehensive Guide: Linksys Default Passwords as of July 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/netflix-picture-in-picture-how-to-use-the-netflix-floating-window-feature/"><u>Netflix Picture-in-Picture - How to Use the Netflix Floating Window Feature</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quality-control-vll-approach-to-apps-for-2024/"><u>Quality Control  VLL Approach to Apps for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722880582237-roku-tv-wont-start-heres-how-you-can-turn-the-situation-around/"><u>Roku TV Won't Start? Here's How You Can Turn the Situation Around</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simple-solutions-for-starting-up-your-macbook-pro-again/"><u>Simple Solutions for Starting Up Your MacBook Pro Again</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-ac1st16dll-file-not-detected-step-by-step-troubleshooting-guide/"><u>Solving the ac1st16.dll File Not Detected: Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-your-silent-iphone-a-guide-to-restoring-ringtones/"><u>Solving Your Silent iPhone: A Guide to Restoring Ringtones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-handling-errors-for-non-existent-d3dx924dll-files/"><u>Step-by-Step Guide: Handling Errors for Non-Existent d3dx9_24.dll Files</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streamline-your-youtube-watch-with-no-black-or-white-edges-for-2024/"><u>Streamline Your YouTube Watch with No Black or White Edges for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-signs-that-indicate-someone-has-read-your-text-unveiled/"><u>The Signs That Indicate Someone Has Read Your Text - Unveiled</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-9-tech-tools-that-are-indispensable-for-your-education-journey/"><u>Top 9 Tech Tools That Are Indispensable for Your Education Journey</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-tips-for-enhancing-your-photos-with-professional-selfie-light-sets/"><u>Top Tips for Enhancing Your Photos with Professional Selfie Light Sets</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722892577666-top-rated-ceiling-sound-systems-a-comprehensive-guide/"><u>Top-Rated Ceiling Sound Systems - A Comprehensive Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/trimmed-techniques-quick-quality-recording-for-dell-for-2024/"><u>Trimmed Techniques  Quick, Quality Recording for Dell for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-tips-restoring-normal-functionality-from-a-black-screen-on-android/"><u>Troubleshooting Tips: Restoring Normal Functionality From a Black Screen on Android</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-boosting-viewership-and-engagement-on-apple-tv/"><u>Ultimate Guide: Boosting Viewership & Engagement on Apple TV</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-the-cognitive-features-of-android-systems/"><u>Understanding the Cognitive Features of Android Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-ultimate-list-of-disney-plus-gems-perfect-for-kids-june-to-july-2024/"><u>Unveiling the Ultimate List of Disney Plus Gems Perfect for Kids - June to July 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/x-men-movie-marathon-watch-them-all-in-ideal-order/"><u>X-Men Movie Marathon: Watch Them All in Ideal Order!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/xbox-game-pass-ultimate-unveiled-your-complete-guide-to-cloud-based-gaming/"><u>Xbox Game Pass Ultimate Unveiled: Your Complete Guide to Cloud-Based Gaming</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->