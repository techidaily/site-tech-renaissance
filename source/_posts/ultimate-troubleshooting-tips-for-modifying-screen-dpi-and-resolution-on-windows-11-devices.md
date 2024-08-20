---
title: Ultimate Troubleshooting Tips for Modifying Screen DPI & Resolution on Windows 11 Devices
date: 2024-08-18T22:51:55.037Z
updated: 2024-08-19T22:51:55.037Z
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
<li><a href="https://tech-renaissance.techidaily.com/engagement-techniques-hashtags-trends-and-retweets-to-increase-visibility/"><u>[Engagement Techniques: Hashtags, Trends, & Retweets to Increase Visibility]</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-windows-videography-embrace-hdr-magic/"><u>[New] 2024 Approved  Windows Videography  Embrace HDR Magic</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-youtube-communication-incorporating-fun-with-emojis/"><u>[New] 2024 Approved  YouTube Communication  Incorporating Fun with Emojis</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-harnessing-the-power-of-film-in-educational-practice/"><u>[New] Harnessing the Power of Film in Educational Practice</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-pinpointing-your-unique-tiktok-tagline/"><u>[New] In 2024, Pinpointing Your Unique TikTok Tagline</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-the-ultimate-exploration-of-apeaksofts-screen-recorder/"><u>[Updated] 2024 Approved  The Ultimate Exploration of Apeaksoft's Screen Recorder</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-essential-tips-for-maximizing-harvests-in-valheims-agriculture-for-2024/"><u>[Updated] Essential Tips for Maximizing Harvests in Valheim's Agriculture for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-mastering-androids-screen-recorder-functions/"><u>[Updated] In 2024, Mastering Android's Screen Recorder Functions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-unleash-photos-on-instagram-with-ease-follow-this-guide/"><u>[Updated] In 2024, Unleash Photos on Instagram with Ease – Follow This Guide</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-maximizing-monetization-unlocking-partnerships-without-limits-for-2024/"><u>[Updated] Maximizing Monetization  Unlocking Partnerships Without Limits for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-professional-insights-top-10-capture-cards-for-youtube-enthusiasts/"><u>[Updated] Professional Insights  Top 10 Capture Cards for YouTube Enthusiasts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/1715860024349-updated-the-ultimate-cut-for-quality-offline-ipad-gaming/"><u>[Updated] The Ultimate Cut for Quality Offline iPad Gaming!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/13-ways-to-fix-spotify-not-working-on-android-auto/"><u>13 Ways to Fix Spotify Not Working on Android Auto</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/56-divided-by-3-is-18-with-a-remainder-of-2/"><u>56 Divided by 3 Is 18 with a Remainder of 2.</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-about-macos-15-sequoia-when-to-expect-its-debut-remarkable-functionality-and-recent-developments-explained/"><u>All About MacOS 15 'Sequoia': When to Expect Its Debut, Remarkable Functionality & Recent Developments Explained</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/boost-your-profiles-find-love-strategies-to-avoid-no-matches-on-bumble/"><u>Boost Your Profiles, Find Love: Strategies to Avoid No Matches on Bumble</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/can-you-successfully-operate-multiple-channels-on-youtube/"><u>Can You Successfully Operate Multiple Channels On YouTube?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comparative-insights-what-sets-the-roku-express-apart-from-the-roku-stick/"><u>Comparative Insights: What Sets the Roku Express Apart From the Roku Stick?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/connect-fubotv-to-fire-tv-stick-a-comprehensive-walkthrough/"><u>Connect FuboTV to Fire TV Stick - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/deciphering-the-practice-of-tagging-an-in-depth-explanation/"><u>Deciphering the Practice of Tagging - An In-Depth Explanation</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-system-velocity-finding-the-ideal-processing-pace-for-your-pc/"><u>Decoding System Velocity: Finding the Ideal Processing Pace for Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-most-affordable-apple-watch-prices-of-month/"><u>Discover the Most Affordable Apple Watch Prices of [Month]!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-ways-to-introduce-bot-functionality-into-your-discord-space/"><u>Easy Ways to Introduce Bot Functionality Into Your Discord Space</u></a></li>
<li><a href="https://some-techniques.techidaily.com/funnybox-simple-setup-for-content-creators-for-2024/"><u>FunnyBox  Simple Setup for Content Creators for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722886637634-hottest-apple-watch-savings-dont-miss-out/"><u>Hottest Apple Watch Savings: Don't Miss Out</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-resolve-the-missing-helperdll-problem-in-windows/"><u>How to Resolve the Missing Helper.dll Problem in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-xs-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone XS Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-nokia-g310-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/ipad-recovery-troubleshooting-how-to-reset-and-restore-your-device/"><u>IPad Recovery Troubleshooting: How to Reset and Restore Your Device</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-technology-inside-look-at-toms-hardware-discoveries/"><u>Mastering Technology: Inside Look at Tom's Hardware Discoveries</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722882140453-mastering-the-cmd-interface-across-windows-versions-a-step-by-step-guide/"><u>Mastering the CMD Interface Across Windows Versions – A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-new-ios-16-a-step-by-step-guide-to-using-photo-cutout-on-your-iphone/"><u>Mastering the New iOS 16: A Step-by-Step Guide to Using Photo Cutout on Your iPhone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/methods-to-stop-your-macbook-from-going-to-sleep-when-you-close-the-cover/"><u>Methods to Stop Your MacBook From Going to Sleep when You Close the Cover</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/migrating-apple-chat-a-step-by-step-tutorial-for-using-imessage-on-android-phones/"><u>Migrating Apple Chat: A Step-by-Step Tutorial for Using iMessage on Android Phones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/multiple-bluetooth-sound-systems-connect-and-control-from-just-one-device/"><u>Multiple Bluetooth Sound Systems: Connect and Control From Just One Device</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/must-have-samsung-smart-tv-software-recommendations/"><u>Must-Have Samsung Smart TV Software Recommendations</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigate-through-nightmares-comprehensive-fixes-for-phase0exception-stop-error/"><u>Navigate Through Nightmares: Comprehensive Fixes for Phase0Exception STOP Error</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-best-free-video-editing-software-imovie-alternatives/"><u>New Best Free Video Editing Software IMovie Alternatives</u></a></li>
<li><a href="https://buynow-info.techidaily.com/reviewing-cyberpunk-2077-bold-vision-hindered-by-flaws-and-unfinished-areas/"><u>Reviewing Cyberpunk 2077: Bold Vision Hindered by Flaws and Unfinished Areas</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/revisiting-youtubes-archive-two-proven-watch-strategies-for-2024/"><u>Revisiting Youtube's Archive  Two Proven Watch Strategies for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/snapchat-support-queries-answered-how-to-reach-out-successfully/"><u>Snapchat Support Queries Answered: How to Reach Out Successfully</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-enabling-two-factor-security-in-your-gmail-account/"><u>Step-by-Step Guide: Enabling Two-Factor Security in Your Gmail Account</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-retrieving-deleted-texts-across-all-smartphones/"><u>Step-by-Step Guide: Retrieving Deleted Texts Across All Smartphones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-wiping-out-your-tiktok-user-profile-once-and-for-all/"><u>Step-by-Step Instructions: Wiping Out Your TikTok User Profile Once and For All</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tips-to-find-an-email-without-compromising-privacy/"><u>Step-by-Step Tips to Find an Email Without Compromising Privacy</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/stream-your-favorites-in-stunning-detail-hitachis-4k-ultra-hd-televisions-with-inbuilt-roku/"><u>Stream Your Favorites in Stunning Detail: Hitachi's 4K Ultra HD Televisions with Inbuilt Roku</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/teslas-self-driving-taxi-venture-expected-cost-release-timeline-specs-whats-the-buzz/"><u>Tesla's Self-Driving Taxi Venture: Expected Cost, Release Timeline, Specs - What's the Buzz?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-list-5-exceptional-sleep-monitoring-apps-on-your-apple-watch/"><u>The Ultimate List: 5 Exceptional Sleep Monitoring Apps on Your Apple Watch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-walkthrough-to-switching-your-discord-profile-pic/"><u>The Ultimate Walkthrough to Switching Your Discord Profile Pic</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/tips-for-ethically-finding-an-individuals-email-in-the-digital-age/"><u>Tips for Ethically Finding an Individual’s Email in the Digital Age</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-tech-bargains-during-amazon-prime-day/"><u>Top Tech Bargains During Amazon Prime Day</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-errors-how-to-fix-failed-attempts-at-opening-word-files/"><u>Troubleshooting Errors: How to Fix Failed Attempts at Opening Word Files</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-outlook-steps-to-rectify-a-malfunctioning-spell-checker/"><u>Troubleshooting Outlook: Steps to Rectify a Malfunctioning Spell Checker</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-tips-for-the-elusive-rpcrt4dll-file-mismatch/"><u>Troubleshooting Tips for the Elusive Rpcrt4.dll File Mismatch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-tips-solutions-when-you-cant-access-youtube/"><u>Troubleshooting Tips: Solutions When You Can’t Access YouTube</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlocking-the-potential-of-artificial-intelligence-with-instagrams-metadata-strategies/"><u>Unlocking the Potential of Artificial Intelligence with Instagram's Metadata Strategies</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-upgrades-julys-choice-for-best-complimentary-driver-updater-programs-top-8/"><u>Unlocking Upgrades: July's Choice for Best Complimentary Driver Updater Programs (Top 8)</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-nvidia-rtx-3080-ti-graphics-card-drivers-for-windows-users-win10-8-7/"><u>Updated NVIDIA RTX 3080 Ti Graphics Card Drivers for Windows Users (Win10, 8, 7)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/video-capture-pro-for-windows-10-ultimate-quality-for-2024/"><u>Video Capture Pro for Windows 10 - Ultimate Quality for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-fusion-reinstating-usb-port-functions/"><u>Windows Fusion: Reinstating USB Port Functions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/your-definitive-list-for-the-most-efficient-key-trackers-available/"><u>Your Definitive List for the Most Efficient Key Trackers Available</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->