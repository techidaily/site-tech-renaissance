---
title: "Preparing Your PC: Essential Tips Before Upgrading to the Windows 11 Creator's Edition"
date: 2024-08-18T22:54:11.593Z
updated: 2024-08-19T22:54:11.593Z
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-perfecting-live-social-media-facebook-livestream-tutorials-for-tech/"><u>[New] 2024 Approved  Perfecting Live Social Media  Facebook Livestream Tutorials for Tech</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-a-step-by-step-approach-for-properly-placing-music-emojis-in-instagram/"><u>[New] A Step-by-Step Approach for Properly Placing Music Emojis in Instagram</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-building-an-impressive-instagram-network-for-2024/"><u>[Updated] Building an Impressive Instagram Network for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-crafting-a-journalistic-closing-statement-for-2024/"><u>[Updated] Crafting a Journalistic Closing Statement for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-from-struggle-to-success-a-collection-of-best-practices-for-fb-profiles/"><u>[Updated] From Struggle to Success  A Collection of Best Practices for FB Profiles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-fix-blurry-facebook-videos-on-iphoneandroidchrome/"><u>[Updated] How to Fix Blurry Facebook Videos on iPhone/Android/Chrome?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ranking-top-online-tutorial-providers-excluding-udemy/"><u>[Updated] Ranking Top Online Tutorial Providers Excluding Udemy</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-tracing-your-steps-how-to-negative-play-on-instagram-for-2024/"><u>[Updated] Tracing Your Steps  How to Negative-Play on Instagram for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-top-10-camcorders-ultimate-picks-expert-reviews/"><u>2024 Approved  Top 10 Camcorders  Ultimate Picks – Expert Reviews</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-7-plus-by-drfone-ios/"><u>7 Top Ways To Resolve Apple ID Not Active Issue For iPhone 7 Plus</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-beginners-journey-through-internet-history-with-the-wayback-machine/"><u>A Beginner's Journey Through Internet History with the Wayback Machine</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/achieve-perfect-zzzs-with-these-5-top-rated-apple-watch-sleep-applications/"><u>Achieve Perfect Zzz's with These 5 Top-Rated Apple Watch Sleep Applications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/bypassing-startup-obstacles-masterful-methods-to-address-and-repair-code-10-glitches/"><u>Bypassing Startup Obstacles: Masterful Methods to Address and Repair Code 10 Glitches</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-solutions-to-deal-with-missing-msstfmtdll-files/"><u>Comprehensive Solutions to Deal with Missing msstfmt.dll Files</u></a></li>
<li><a href="https://buynow-help.techidaily.com/decision-guide-choosing-between-ipad-pro-or-macbook-pro-for-your-needs/"><u>Decision Guide: Choosing Between iPad Pro or MacBook Pro for Your Needs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-smart-tvs-an-insight-into-internet-integration-with-your-television-set/"><u>Decoding Smart TVs: An Insight Into Internet Integration with Your Television Set</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-to-follow-tutorial-on-utilizing-the-advanced-photo-cutouts-functionality-in-ios-16-iphones/"><u>Easy-to-Follow Tutorial on Utilizing the Advanced Photo Cutouts Functionality in iOS 16 iPhones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/electric-vehicle-durability-compared-with-traditional-gasoline-cars/"><u>Electric Vehicle Durability Compared with Traditional Gasoline Cars</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-painters-companion-discovering-the-best-4-apps-for-wall-makeovers/"><u>Essential Painter's Companion: Discovering the Best 4 Apps for Wall Makeovers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-opinion-the-third-generation-apple-tv-4k-performance-and-features-breakdown/"><u>Expert Opinion: The Third Generation Apple TV 4K - Performance & Features Breakdown</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/find-your-perfect-ipad-at-record-breaking-prices-today/"><u>Find Your Perfect iPad at Record-Breaking Prices Today</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/free-streaming-platforms-that-challenge-netflixs-dominance/"><u>Free Streaming Platforms That Challenge Netflix's Dominance</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-removing-the-live-tiles-news-on-windows-11-desktop/"><u>Guide: Removing the Live Tiles News on Windows 11 Desktop</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-are-e-motorcycles-powered-unveiling-their-inner-workings/"><u>How Are E-Motorcycles Powered? Unveiling Their Inner Workings</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-does-chatgpt-code-interpretation-work-exploring-its-vital-significance/"><u>How Does ChatGPT Code Interpretation Work? Exploring Its Vital Significance</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-efficiently-access-your-windows-command-line-interface-on-any-version-of-windows-os-including-win-11-win-10-etc/"><u>How to Efficiently Access Your Windows Command Line Interface on Any Version of Windows OS (Including Win 11, Win 10, Etc.)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-separate-and-disassociate-equipment-from-google-home-platforms/"><u>How to Separate and Disassociate Equipment From Google Home Platforms</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-tecno-spark-10-4g-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Tecno Spark 10 4G online without jailbreak</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Tecno Phantom V Flip? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-prosight-review-the-next-big-step-beyond-manycam/"><u>In 2024, ProSight Review  The Next Big Step Beyond ManyCam</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/instantpause-live-image-save-tips/"><u>InstantPause  Live Image Save Tips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/is-owning-a-ps5-worth-your-money-discover-these-4-persuasive-arguments/"><u>Is Owning a PS5 Worth Your Money? Discover These 4 Persuasive Arguments</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-poco-x5-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Poco X5? | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-digital-collage-creators-for-photos-and-videos-for-2024/"><u>New Top Digital Collage Creators for Photos and Videos for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/outlook-undo-feature-the-ultimate-tutorial-for-retrieving-discarded-emails/"><u>Outlook Undo Feature: The Ultimate Tutorial for Retrieving Discarded Emails</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/pixel-10-preview-inside-scoop-on-rumored-pricing-specs-and-the-exciting-future-of-google-phones/"><u>Pixel 10 Preview - Inside Scoop on Rumored Pricing, Specs and the Exciting Future of Google Phones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-the-mfc71dll-file-not-foundmissing-issue/"><u>Resolving the mfc71.dll File Not Found/Missing Issue</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simple-steps-for-integrating-your-airpods-into-macos-systems/"><u>Simple Steps for Integrating Your AirPods Into macOS Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-the-ac1st16dll-file-missing-step-by-step-guide/"><u>Solving the 'ac1st16.dll File Missing' - Step by Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-starting-the-windows-terminal-across-all-versions/"><u>Step-by-Step Guide: Starting the Windows Terminal Across All Versions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-for-snapping-images-on-your-xbox-one-console/"><u>Step-by-Step Instructions for Snapping Images on Your Xbox One Console</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tips-for-planning-the-perfect-at-home-sing-along-bash/"><u>Step-by-Step Tips for Planning the Perfect At-Home Sing-Along Bash</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-homeowners-handbook-to-diagnosing-and-repairing-everyday-tv-issues/"><u>The Homeowner's Handbook to Diagnosing and Repairing Everyday TV Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-the-mss32dll-error-effective-solutions-to-try/"><u>Troubleshooting the 'MSS32.DLL' Error: Effective Solutions to Try</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-reviving-your-pc-or-laptop-when-it-wont-turn-on/"><u>Ultimate Guide: Reviving Your PC or Laptop When It Won't Turn On</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-step-by-step-instructions-on-how-to-perform-a-factory-reset-on-your-samsung-television/"><u>Ultimate Guide: Step-by-Step Instructions on How to Perform a Factory Reset on Your Samsung Television</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-troubleshooting-for-shaking-and-flickering-screens-on-the-surface-pro/"><u>Ultimate Troubleshooting for Shaking and Flickering Screens on the Surface Pro</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-facebook-from-humble-beginnings-to-global-phenomenon-and-what-makes-it-popular/"><u>Understanding Facebook: From Humble Beginnings to Global Phenomenon & What Makes It Popular</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/upgrade-your-desktop-with-these-15-free-windows-11-styles-and-skins/"><u>Upgrade Your Desktop with These 15 Free Windows 11 Styles and Skins</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->