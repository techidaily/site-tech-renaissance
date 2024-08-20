---
title: Desktop Icons Missing in Windows 10 [Solved]
date: 2024-08-18T22:55:43.652Z
updated: 2024-08-19T22:55:43.652Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Desktop Icons Missing in Windows 10 [Solved]
excerpt: This Article Describes Desktop Icons Missing in Windows 10 [Solved]
thumbnail: https://thmb.techidaily.com/60fe1a74657905b47d054d52197782d9df31df8374f9444c7a6b8dc97d98722a.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-dissecting-video-platform-features-youtube-vs-dailymention/"><u>[New] 2024 Approved  Dissecting Video Platform Features  YouTube Vs. DailyMention</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-top-10-effortless-steps-to-viral-tiktok-success/"><u>[New] 2024 Approved  Top 10 Effortless Steps to Viral TikTok Success</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-explore-leading-websites-for-text-embellishments/"><u>[New] Explore Leading Websites for Text Embellishments</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/pread-the-rhythm-sharing-playlists-in-minutes/"><u>[New] Spread the Rhythm  Sharing Playlists in Minutes</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/nlock-youtube-monetization-with-500-subscribers/"><u>[New] Unlock YouTube Monetization with 500 Subscribers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-how-to-enhance-audibility-with-adjusted-obs-settings-for-2024/"><u>[Updated] How to Enhance Audibility with Adjusted OBS Settings for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-omega-series-high-definition-full-touch-workstations/"><u>[Updated] Omega Series  High Definition Full Touch Workstations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-film-producers-essential-guide-to-color-grading-with-standardized-luts/"><u>2024 Approved  A Film Producer's Essential Guide to Color Grading with Standardized LUTs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-masterclass-top-10-recorder-options-on-spotify/"><u>2024 Approved  Masterclass Top 10 Recorder Options on Spotify</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-youtube-live-thumbnails-essentials/"><u>2024 Approved  Mastering YouTube Live Thumbnails Essentials</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-comprehensive-guide-solving-the-mystery-of-d3dx934dll-errors-on-your-pc/"><u>A Comprehensive Guide: Solving The Mystery of d3dx9_34.dll Errors on Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/android-users-beware-how-to-opt-out-of-intrusive-amber-alerts/"><u>Android Users Beware! How to Opt Out of Intrusive Amber Alerts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/best-offline-car-racer-games-of-2024-top-picks-you-can-play-anytime-anywhere/"><u>Best Offline Car Racer Games of 2024 - Top Picks You Can Play Anytime, Anywhere</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/connect-your-disneyplus-subscription-to-a-chromecast-a-comprehensive-guide/"><u>Connect Your Disney+ Subscription to a Chromecast – A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/craft-perfect-videos-with-these-top-5-editing-programs-we-love/"><u>Craft Perfect Videos with These Top 5 Editing Programs We Love</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-the-perks-of-hulu-and-hulu-plus-which-one-to-choose/"><u>Decoding the Perks of Hulu & Hulu Plus – Which One to Choose?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-everything-you-need-to-know-about-the-newly-released-samsung-galaxy-watch-7/"><u>Discover Everything You Need to Know About the Newly Released Samsung Galaxy Watch 7!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-exceptional-websites-with-complimentary-digital-literature/"><u>Discover Exceptional Websites with Complimentary Digital Literature</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-list-of-no-cost-voip-services-for-2n24/"><u>Discover the Ultimate List of No-Cost VoIP Services for 2N24</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-list-the-11-most-uplifting-movies-ever-made/"><u>Discover the Ultimate List: The 11 Most Uplifting Movies Ever Made</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/dont-miss-a-buzzer-beater-comprehensive-mens-ncaa-march-madness-and-final-four-radio-highlights/"><u>Don’t Miss a Buzzer-Beater: Comprehensive Men's NCAA March Madness and Final Four Radio Highlights!</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-tutorial-on-getting-rid-of-the-ai-assistant-microsoft-copilot-in-windows-11/"><u>Easy Tutorial on Getting Rid of the AI Assistant, Microsoft Copilot, in Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enhance-your-ipads-life-with-easy-battery-replacement-instructions/"><u>Enhance Your iPad's Life with Easy Battery Replacement Instructions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/experience-limitless-roaming-on-the-go-with-metro-by-t-mobiles-wireless-plans/"><u>Experience Limitless Roaming on the Go with Metro by T-Mobile's Wireless Plans</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/explore-windows-11-best-new-gaming-titles-for-2024/"><u>Explore Windows 11  Best New Gaming Titles for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-the-elusive-error-code-0xc000185-techniques-and-solutions-for-smooth-operations/"><u>Fixing the Elusive Error Code 0Xc000#185: Techniques and Solutions for Smooth Operations</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/from-g-to-i-transfer-tactics-how-to-migrate-google-photos-to-icloud-effortlessly/"><u>From G-to-I Transfer Tactics: How To Migrate Google Photos to iCloud Effortlessly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/from-plugging-in-to-power-up-a-comprehensive-overview-of-at-home-ev-charging/"><u>From Plugging In to Power Up: A Comprehensive Overview of At-Home EV Charging</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-to-deleting-programs-on-your-samsung-intelligent-tv/"><u>Guide to Deleting Programs on Your Samsung Intelligent TV</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-to-fixing-the-missing-cygwin1dll-error-on-your-computer/"><u>Guide to Fixing the Missing cygwin1.dll Error on Your Computer</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/head-to-head-review-the-new-era-of-smartphones-s24-vs-s23-ultra/"><u>Head-to-Head Review: The New Era of Smartphones - S24 Vs. S23 Ultra</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-enable-and-disable-iphone-recovery-mode-easily/"><u>How to Enable and Disable iPhone Recovery Mode Easily</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-iphone-12-pro-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your iPhone 12 Pro</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-11-passcode-not-working-drfone-by-drfone-ios/"><u>In 2024, How to Fix Apple iPhone 11 Passcode not Working? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-nord-3-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Nord 3 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-icloud-unlocker-download-unlock-icloud-lock-for-your-apple-iphone-xs-max-by-drfone-ios/"><u>In 2024, iCloud Unlocker Download Unlock iCloud Lock for your Apple iPhone XS Max</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-secrets-revealed-how-to-convert-facebooks-hd-videos-to-mp4-for-free/"><u>In 2024, Secrets Revealed  How to Convert Facebook's HD Videos to MP4 for Free</u></a></li>
<li><a href="https://article-posts.techidaily.com/max-360-and-hero-11-gopro-comparison-which-reigns-supreme-for-2024/"><u>Max 360 and Hero 11 GoPro Comparison - Which Reigns Supreme for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-the-waters-of-education-savings-a-step-by-step-to-snagging-a-tidal-academic-discount/"><u>Navigating the Waters of Education Savings: A Step-by-Step to Snagging a Tidal Academic Discount</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722889084485-ps5-faceoff-examining-differences-between-ps5-slim-and-original-model/"><u>PS5 Faceoff: Examining Differences Between PS5 Slim & Original Model</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resetting-mac-dns-records-the-ultimate-walkthrough/"><u>Resetting Mac DNS Records: The Ultimate Walkthrough</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/rpcrt4dll-not-found-heres-how-you-can-repair-the-issue-easily/"><u>RPCRT4.DLL Not Found? Here's How You Can Repair the Issue Easily</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/seamless-viewing-how-to-cast-content-from-an-android-smartphone-to-a-firestick/"><u>Seamless Viewing: How to Cast Content From an Android Smartphone to a Firestick</u></a></li>
<li><a href="https://extra-hints.techidaily.com/sharpen-your-footage-with-videoleaps-zoom/"><u>Sharpen Your Footage with Videoleap's ZOOM</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-how-to-access-and-enjoy-3d-movie-night-with-fandango-from-the-comfort-of-home/"><u>Step by Step: How to Access and Enjoy 3D Movie Night with Fandango From the Comfort of Home</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-solutions-to-eliminate-bsod-issues-in-windows/"><u>Step-by-Step Solutions to Eliminate BSOD Issues in Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/steps-for-fixing-an-absent-d3dx939dll-error-on-your-pc/"><u>Steps for Fixing an Absent d3dx9_39.dll Error on Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/streamline-your-familys-time-with-these-7-essential-calendar-apps/"><u>Streamline Your Family's Time With These 7 Essential Calendar Apps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-next-big-thing-from-tesla-investigate-the-rumored-machines-forecasted-price-point-release-date-and-technical-insights/"><u>The Next Big Thing From Tesla? Investigate the Rumored Machine's Forecasted Price Point, Release Date, and Technical Insights</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-fixes-for-nonfunctioning-chromecast-sound-issues/"><u>The Ultimate Fixes for Nonfunctioning Chromecast Sound Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-list-8-most-popular-reading-apps-to-download/"><u>The Ultimate List: 8 Most Popular Reading Apps to Download</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-value-of-playstation-5-4-compelling-reasons-to-make-the-leap/"><u>The Value of PlayStation 5: 4 Compelling Reasons to Make the Leap</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-17-graphic-design-programs-the-ultimate-selection-guide/"><u>Top 17 Graphic Design Programs: The Ultimate Selection Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-tecno-spark-go-2023-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Tecno Spark Go (2023) Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-6-troubleshooting-steps-for-apple-watch-pairing-issues/"><u>Top 6 Troubleshooting Steps for Apple Watch Pairing Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-to-zooming-in-and-out-on-your-apple-tablet-or-smartphone/"><u>Ultimate Guide to Zooming in and Out on Your Apple Tablet or Smartphone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unbeatable-offers-score-the-latest-gadgets-this-amazon-prime-weekend/"><u>Unbeatable Offers: Score the Latest Gadgets This Amazon Prime Weekend</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unbelievable-deals-on-premium-technology-triumphs/"><u>Unbelievable Deals on Premium Technology Triumphs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-the-windows-10-battery-status-screen-a-comprehensive-guide/"><u>Understanding the Windows 10 Battery Status Screen - A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-the-windows-11-battery-status-feature-a-comprehensive-guide/"><u>Understanding the Windows 11 Battery Status Feature: A Comprehensive Guide</u></a></li>
<li><a href="https://article-posts.techidaily.com/unlock-the-potential-of-close-up-videos-using-videoleap/"><u>Unlock the Potential of Close-Up Videos Using Videoleap</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlock-the-world-of-communication-with-these-16-free-sign-language-learning-aids/"><u>Unlock the World of Communication with These 16 Free Sign Language Learning Aids</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unraveling-the-mystery-of-your-ps4s-colorful-led-meanings-behind-blue-white-red-orange-alerts/"><u>Unraveling the Mystery of Your PS4's Colorful LED: Meanings Behind Blue, White, Red, Orange Alerts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/watch-anywhere-with-these-12-free-mobile-movies-apps/"><u>Watch Anywhere with These 12 Free Mobile Movies Apps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Motorola Moto G23 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->