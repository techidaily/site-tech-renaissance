---
title: Effective Strategies to Resolve rpcrt4.dll Error on Your Computer
date: 2024-08-20T10:34:25.670Z
updated: 2024-08-21T10:34:25.670Z
categories:
  - BestProducts
description: This Article Describes Effective Strategies to Resolve rpcrt4.dll Error on Your Computer
excerpt: This Article Describes Effective Strategies to Resolve rpcrt4.dll Error on Your Computer
thumbnail: https://www.lifewire.com/thmb/NQAXvRvGzwNFJI9UFTVcHTrp418=/540x405/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/rpcrt4-dll-error-message-5aeb515bba61770036a3dda8.png
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

## How to Fix Error Code 0x80004005

 Follow these steps in the order presented to troubleshoot error code 0x80004005:

1. [Run the Windows Update troubleshooter](https://support.microsoft.com/help/4027322/windows-update-troubleshooter) . The error can happen when an automatic Windows Update fails, or when files downloaded by Windows Update are corrupted. On Windows 7 or later, the easiest[way to fix problems with Windows updates](https://www.lifewire.com/how-to-fix-problems-caused-by-windows-updates-2625775) is to run the built-in automatic troubleshooter.
2. Delete everything in the Windows Update download folder. If the automatic troubleshooter does not fix the problem, open Windows[File Explorer](https://www.lifewire.com/what-is-a-file-manager-4589189) and navigate to**C:\\Windows\\SoftwareDistribution** , for Windows 11 or**C:\\Windows\\SoftwareDistribution\\Download** for earlier Windows versions, then delete everything inside the folder.
3. [Run Windows Update](https://www.lifewire.com/how-to-check-for-install-windows-updates-2624596) . If the problem is related to Windows Update, you may have to finish downloading and installing updates. After running the troubleshooter and manually deleting the files in the Windows Update folder, run Windows Update again.
4. [Delete temporary files](https://www.lifewire.com/how-to-delete-temporary-files-in-windows-2624709) . In some cases, a corrupt temporary file can cause error 0x80004005\. Use the Windows Disk Cleanup tool or type**%temp%** in the Windows search bar to find the**Temp** folder and delete everything inside it.
5. [Disable Outlook mail notifications](https://www.lifewire.com/configure-outlook-email-notifications-1173647) . The error code can occur when[Microsoft Outlook](https://www.lifewire.com/microsoft-outlook-4164620) attempts to notify you of new messages. If disabling this feature fixes the problem, then try[starting Outlook in Safe Mode](https://www.lifewire.com/outlook-safe-mode-4164302) . If that works, a simple re-install might fix your problem.
6. [Disable Windows Defender](https://www.lifewire.com/turn-off-windows-defender-4165378) . In some cases,[antivirus](https://www.lifewire.com/what-is-antivirus-software-152947) software can detect a false positive in connection with the Microsoft Outlook app. If you experience error code 0x80004005 when using Microsoft Outlook, and disabling notifications did not help, turning off antivirus software may fix the problem. Also,[disable Norton Antivirus](https://www.lifewire.com/disable-norton-antivirus-4589389) and other third-party antivirus programs you use.  
 Disabling antivirus software leaves the system vulnerable to malware. Try different[free antivirus programs](https://www.lifewire.com/best-free-antivirus-software-4151895) to find one that doesn't conflict with the applications you use.
7. [Use a different unzip program](https://www.lifewire.com/free-unzip-programs-1356643) . If you see the error code when extracting or opening compressed files (like[.zip](https://www.lifewire.com/zip-file-2622675) or[.rar](https://www.lifewire.com/rar-file-2622216) files), use a different extraction tool.
8. Re-register jdscript.dll and vbscript.dll. If you still see error 0x80004005 after trying to unzip files with other extraction tools, then re-registering these two[dynamic link libraries](https://www.lifewire.com/what-is-a-dll-file-2625852) (DLLs) may help.  
[Open the Command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089) as an administrator, type**regsvr32 jscript.dll** , then press the**Enter** key. Then, type**regsvr32 vbscript.dll** and press**Enter** .
9. [Add a key to the Windows Registry](https://www.lifewire.com/how-to-add-change-delete-registry-keys-values-2625145) . If you suspect error 0x80004005 in conjunction with copying or moving files,[open the Windows Registry Editor](https://www.lifewire.com/how-to-open-registry-editor-2625150) and go to **HKLM\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** .  
   * On a[32-bit](https://www.lifewire.com/32-bit-64-bit-2624554) system, create a new**DWORD** [registry value](https://www.lifewire.com/what-is-a-registry-value-2626042) called**LocalAccountTokenFilterPolicy** .  
   * On a 64-bit system, create a**QWORD** registry value called**LocalAccountTokenFilterPolicy** .  
 In both cases, set the value to**numeric 1** (on), then select**OK** . After that,[restart the Windows PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see if the problem is fixed.  
![A screenshot of Windows Registry with the Numerical Value and OK button highlighted](https://www.lifewire.com/thmb/OqNevLWWV50Z3qSb36MeYz61-8Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-how-to-fix-error-code-0x80004005-4689559-7b5e14fd0ef942718355465faefbcb77.jpg)  
 Don't delete or change anything in the Windows registry unless you know what you're doing.
10. Contact support. If none of these fixes work, or if you don't want to make changes to the Windows Registry, contact customer support for your Windows PC. The manufacturer may have potential solutions.

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/best-desktop-pcs-4045927)

 FAQ

* How do I fix error code ws-37398-0?  
 Error code ws-37398-0 is a PS5 error code that occurs during PlayStation network server outages. Because the error stems from PlayStation, there's nothing you can do to fix it. You must wait until the network outage resolves.
* How do I fix error code 4b538e50 2k21?  
 This error occurs in the games_NBA 2K21_ and_NBA 2K22_ . It usually means your game files are outdated, and there's a pending file download or patch. To fix it, check to see if your computer or console still has game files to download, and wait for the downloading process to complete.
* How do I fix a code 10 error in Windows?  
 To[fix code 10 errors](https://www.lifewire.com/how-to-fix-code-10-errors-2623181) , which indicate that Device Manager can't start a hardware device, first try restarting your computer. If you recently installed a device, try uninstalling and reinstalling its drivers, or see if there are driver updates to install. You can also try installing the latest Windows update.

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[Subscribe](https://www.lifewire.com/#)

Tell us why!

 Other  Not enough details  Hard to understand

 Submit

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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-getting-started-with-macos-11-big-sur-upgrade/"><u>[New] 2024 Approved  Getting Started with macOS 11 Big Sur Upgrade</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-dive-into-creativity-mastering-artistic-elements-in-instagram-edits-for-2024/"><u>[New] Dive Into Creativity  Mastering Artistic Elements in Instagram Edits for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-ps-tips-for-perfecting-photo-shades-and-saturation/"><u>[New] PS Tips for Perfecting Photo Shades and Saturation</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/uick-launch-long-growth-the-10-best-youtube-business-channels/"><u>[New] Quick Launch, Long Growth  The 10 Best YouTube Business Channels</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-the-full-potential-of-iphones-hdr-capabilities/"><u>[New] Unlocking the Full Potential of iPhone's HDR Capabilities</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-understanding-snapchats-emojis-more-than-just-fun/"><u>[Updated] 2024 Approved  Understanding Snapchat's Emojis  More Than Just Fun</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-android-ios-and-pc-friendly-youtube-downloader-apps-reviewed/"><u>[Updated] In 2024, Android, iOS & PC-Friendly YouTube Downloader Apps Reviewed</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-transform-your-igtv-videos-with-top-10-video-editors/"><u>[Updated] Transform Your IGTV Videos with Top 10 Video Editors</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-ultimate-scene-seizing-exploration-for-2024/"><u>[Updated] Ultimate Scene Seizing Exploration for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-utilize-automatic-hdr-feature-a-compreran-guide-to-windows-11/"><u>2024 Approved  Utilize Automatic HDR Feature  A Compreran Guide to Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-vivo-y100-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Vivo Y100 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/best-book-reading-apps-for-avid-readers-a-comprehensive-guide/"><u>Best Book-Reading Apps for Avid Readers : A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/buying-blockbuster-virtual-reality-games-for-meta-quest-2-a-comprehensive-guide/"><u>Buying Blockbuster Virtual Reality Games for Meta Quest 2 - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-the-headache-of-error-0x887a0006-your-definitive-guide-to-a-smooth-update-process/"><u>Bypass the Headache of Error 0X887A0006 - Your Definitive Guide to a Smooth Update Process</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/charge-through-time-key-events-shaping-the-world-of-electric-transportation/"><u>Charge Through Time: Key Events Shaping the World of Electric Transportation</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/chromebook-locked-up-discover-8-fixes-to-unfreeze-your-device/"><u>ChromeBook Locked Up? Discover 8 Fixes to Unfreeze Your Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/compreeved-list-of-premium-androidiphone-slow-motion-video-tools/"><u>Compreeved List of Premium Android/iPhone Slow Motion Video Tools</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/dealing-with-delayed-or-non-syncing-gmail-step-by-step-solutions/"><u>Dealing With Delayed or Non-Syncing Gmail: Step-by-Step Solutions</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>Does Airplane Mode Turn off GPS Location On Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/downloading-and-updating-the-brother-mfc-7860dw-drivers-on-your-pc/"><u>Downloading and Updating the Brother MFC-#7860DW Drivers on Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-instructions-transferring-your-system-with-windows-10/"><u>Easy Instructions: Transferring Your System with Windows 10</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-methods-for-replacing-or-removing-a-cell-phone-screen-guard/"><u>Easy Methods for Replacing or Removing a Cell Phone Screen Guard</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effective-fixes-to-launch-problems-in-farming-simulator-22/"><u>Effective Fixes to Launch Problems in Farming Simulator 22</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effortlessly-sync-your-disneyplus-account-on-chromecast-comprehensive-steps-inside/"><u>Effortlessly Sync Your Disney+ Account on Chromecast: Comprehensive Steps Inside!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/elite-selection-of-smartglasses-dominating-2024/"><u>Elite Selection of Smartglasses Dominating 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/experiencing-the-full-potential-of-dolby-atmos-is-your-system-up-to-it/"><u>Experiencing the Full Potential of Dolby Atmos – Is Your System Up to It?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-eradicating-vertical-line-issues-in-your-samsung-flat-screen-tv/"><u>Expert Advice: Eradicating Vertical Line Issues in Your Samsung Flat Screen TV</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-for-saving-screens-with-logitech-keyboards-a-comprehensive-guide/"><u>Expert Tips for Saving Screens with Logitech Keyboards – A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-world-of-memes-a-detailed-overview/"><u>Exploring the World of Memes – A Detailed Overview</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-issues-with-usb-internet-sharing-a-step-by-step-approach/"><u>Fixing Issues with USB Internet Sharing: A Step-by-Step Approach</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/futures-finest-top-5-driverless-automobile-brands-of-2024/"><u>Future's Finest: Top 5 Driverless Automobile Brands of 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-to-removing-real-time-updates-on-your-windows-11-home-screen/"><u>Guide to Removing Real-Time Updates on Your Windows 11 Home Screen</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-mastering-remote-desktop-control-with-your-samsung-smart-tv/"><u>Guide: Mastering Remote Desktop Control with Your Samsung Smart TV</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-oneplus-nord-3-5g-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On OnePlus Nord 3 5G?</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-motorola-moto-g13-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-gmail-password-on-realme-c51-devices-by-drfone-android/"><u>How to Reset Gmail Password on Realme C51 Devices</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-do-you-unlock-your-iphone-15-learn-all-4-methods-drfone-by-drfone-ios/"><u>In 2024, How Do You Unlock your iPhone 15? Learn All 4 Methods | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-top-offline-mobile-world-choose-the-ultimate-game-for-fun/"><u>In 2024, Top Offline Mobile World - Choose the Ultimate Game for Fun</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Xiaomi Redmi Note 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/instantaneous-installation-laugh-with-ifunny-memes-easily/"><u>Instantaneous Installation  Laugh with iFunny Memes Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/key-points-to-check-prior-to-investing-in-a-secondhand-computer/"><u>Key Points to Check Prior to Investing in a Secondhand Computer</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-logitech-t630-driver-download-optimized-for-windows-operating-systems-win7-win8-win10/"><u>Latest Logitech T630 Driver Download: Optimized for Windows Operating Systems (Win7, Win8, Win10)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/managing-icloud-and-iphone-images-safe-removal-from-cloud-storage/"><u>Managing iCloud and iPhone Images: Safe Removal From Cloud Storage</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/master-the-art-of-line-insertion-in-word-with-this-simple-tutorial/"><u>Master the Art of Line Insertion in Word with This Simple Tutorial</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-stealthy-sidebar-tips-for-enabling-and-using-hidden-path-finder-tools/"><u>Mastering the Stealthy Sidebar: Tips for Enabling and Using Hidden Path Finder Tools</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-technique-of-forcing-your-windows-machine-to-boot-safely-in-recovery-mode/"><u>Mastering the Technique of Forcing Your Windows Machine to Boot Safely in Recovery Mode</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/obs-studio-guide-android-broadcast-optimization-for-2024/"><u>OBS Studio Guide  Android Broadcast Optimization for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/regain-entry-a-comprehensive-guide-for-a-forgotten-ipad-code/"><u>Regain Entry: A Comprehensive Guide for a Forgotten iPad Code</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolve-the-verified-developer-not-found-problem-in-macos-with-simple-steps/"><u>Resolve the Verified Developer Not Found Problem in macOS with Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-directory-name-not-recognized-issue-comprehensive-solutions/"><u>Resolving the 'Directory Name Not Recognized' Issue - Comprehensive Solutions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-for-seamlessly-implementing-copilot-in-microsoft-teams-workflows/"><u>Step-by-Step Instructions for Seamlessly Implementing Copilot in Microsoft Teams Workflows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-finest-free-roku-options-8-stellar-channels-of-2024/"><u>The Finest Free Roku Options – 8 Stellar Channels of 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-selection-5-expert-recommended-video-editing-applications/"><u>The Ultimate Selection: 5 Expert Recommended Video Editing Applications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-wifi-signal-boosters-in-2/"><u>Top Rated WiFi Signal Boosters in 2</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-immersive-technologies-ar-vr-mr-and-xr-key-differences-explained/"><u>Understanding Immersive Technologies: AR, VR, MR & XR - Key Differences Explained</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unfolding-secrets-of-future-technology-prospect-release-date-specs-and-pricing-for-the-revolutionary-foldable-iphone/"><u>Unfolding Secrets of Future Technology: Prospect Release Date, Specs & Pricing for the Revolutionary Foldable iPhone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-your-stuck-chromebook-a-guide-with-8-proven-techniques/"><u>Unlocking Your Stuck Chromebook: A Guide with 8 Proven Techniques</u></a></li>
<li><a href="https://fox-that.techidaily.com/unstuck-iphone-fixes-what-to-do-when-physical-buttons-fail-you/"><u>Unstuck iPhone Fixes: What To Do When Physical Buttons Fail You</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-dts-play-fi-a-guide-to-streaming-sound-systems/"><u>Unveiling DTS Play-Fi: A Guide to Streaming Sound Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-role-of-wireless-service-providers-in-connecting-calls-and-data-transfer/"><u>Unveiling the Role of Wireless Service Providers in Connecting Calls and Data Transfer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/updated-linksys-standard-login-credentials-for-july-2024-a-complete-list/"><u>Updated Linksys Standard Login Credentials for July 2024 – A Complete List</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/what-accessories-and-extras-come-with-your-nintendo-switch-console/"><u>What Accessories and Extras Come with Your Nintendo Switch Console?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/your-ultimate-checklist-for-watching-the-2024-summer-olympics-online/"><u>Your Ultimate Checklist for Watching the 2024 Summer Olympics Online</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->