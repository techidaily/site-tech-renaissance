---
title: "Resolving Device Manager's Code Eror: A Step-by-Step Guide"
date: 2024-08-18T23:18:02.420Z
updated: 2024-08-19T23:18:02.420Z
categories:
  - BestProducts
description: "This Article Describes Resolving Device Manager's Code Eror: A Step-by-Step Guide"
excerpt: "This Article Describes Resolving Device Manager's Code Eror: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/c2256048fdba19e150d130af22fa0ee9a49a1cc871ecb123979c39c8bac9ef09.jpg
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-crafting-captivating-tiktok-screenshots-with-ease/"><u>[New] 2024 Approved  Crafting Captivating TikTok Screenshots with Ease</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-luminous-techniques-for-engaging-vlogs/"><u>[New] In 2024, Luminous Techniques for Engaging Vlogs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-10-must-know-tips-for-nba-stream-quality/"><u>[Updated] 10 Must-Know Tips for NBA Stream Quality</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-sound-of-success-audio-recording-guide/"><u>[Updated] The Sound of Success  Audio Recording Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-splitting-screen-techniques-for-engaging-youtube-content/"><u>2024 Approved  Splitting Screen Techniques for Engaging YouTube Content</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-step-by-step-guide-setting-up-an-alternate-email-address-on-gmail/"><u>A Step-by-Step Guide: Setting Up an Alternate Email Address on Gmail</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/addressing-connectivity-errors-in-echo-products-remedies-for-echo-is-offline-messages-from-alexa/"><u>Addressing Connectivity Errors in Echo Products - Remedies for 'Echo Is Offline' Messages From Alexa</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/campus-tech-hacks-how-to-qualify-and-benefit-from-lenovo-scholarly-discounts/"><u>Campus Tech Hacks: How to Qualify and Benefit From Lenovo Scholarly Discounts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722862616590-colorful-organization-on-the-mac-learn-to-change-folder-colors-today/"><u>Colorful Organization on the Mac: Learn to Change Folder Colors Today</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/colorize-your-workspace-tutorial-for-altering-mac-folder-shades/"><u>Colorize Your Workspace: Tutorial for Altering Mac Folder Shades</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-file-retrieval-with-windows-nas/"><u>Cross-Platform File Retrieval with Windows NAS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-snapchat-a-comprehensive-cheat-sheet-on-emojis/"><u>Decoding Snapchat: A Comprehensive Cheat Sheet on Emojis</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-premier-education-apps-the-ultimate-list/"><u>Discover the Premier Education Apps - The Ultimate List</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effective-ways-to-reach-out-to-snapchat-support-get-help-now/"><u>Effective Ways to Reach Out to Snapchat Support - Get Help Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/evaluating-the-benefits-of-moving-to-ios-17-what-users-need-to-know/"><u>Evaluating the Benefits of Moving to iOS 17: What Users Need to Know</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-ussd-technology-an-insight-into-unstructured-supplementary-service-data-systems/"><u>Exploring USSD Technology: An Insight Into Unstructured Supplementary Service Data Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-corsair-mouse-ready-free-tutorial-and-downloads-available/"><u>Get Your Corsair Mouse Ready - Free Tutorial and Downloads Available!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/government-reliance-on-major-tech-firms-lessons-from-microsofts-recent-disruptions/"><u>Government Reliance on Major Tech Firms: Lessons From Microsoft's Recent Disruptions</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/grobalization-and-optimization-considering-factors-like-resource-allocation-logistics-and-environmental-impacts-in-a-comprehensive-manner/"><u>Grobalization and Optimization, Considering Factors Like Resource Allocation, Logistics, and Environmental Impacts in a Comprehensive Manner.</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-the-latest-insignia-bluetooth-adapter-drivers-and-updates-for-your-pc/"><u>How to Get the Latest Insignia Bluetooth Adapter Drivers & Updates for Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-interpret-microsofts-blue-screen-of-death-bsod-error/"><u>How to Interpret Microsoft's Blue Screen of Death (BSOD) Error</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-nubia-z50-ultra-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Nubia Z50 Ultra without App | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/in-depth-analysis-of-neo-qled-vs-oled-features-advantages-and-disadvantages/"><u>In-Depth Analysis of Neo QLED Vs. OLED: Features, Advantages, and Disadvantages</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphoneipad-cloud-woes-uncover-the-9-most-frequent-icloud-problems-and-their-fixes/"><u>IPhone/iPad Cloud Woes? Uncover the 9 Most Frequent iCloud Problems and Their Fixes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/july-24-hot-picks-amazing-family-films-to-watch-on-amazon-prime-video-today/"><u>July '24 Hot Picks: Amazing Family Films to Watch on Amazon Prime Video Today!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/mastering-the-fixes-get-your-windows-10-audio-working-again/"><u>Mastering the Fixes: Get Your Windows 10 Audio Working Again</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/msxml4dll-missing-heres-how-you-can-resolve-it/"><u>Msxml4.dll Missing? Here's How You Can Resolve It</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/passfab-apple-iphone-x-backup-unlocker-top-4-alternatives-by-drfone-ios/"><u>PassFab Apple iPhone X Backup Unlocker Top 4 Alternatives</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-missing-msvcr71dll-error-a-comprehensive-guide/"><u>Resolving 'Missing MSVCR71.DLL' Error: A Comprehensive Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-upside-down-in-windows-11-fixed/"><u>Screen Upside Down in Windows 11 [Fixed]</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/smartphone-showdown-how-to-decide-between-an-iphone-or-android-device/"><u>Smartphone Showdown: How to Decide Between an iPhone or Android Device</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-to-fix-coredll-is-missing-errors-on-your-computer/"><u>Step-by-Step Guide to Fix 'Core.dll Is Missing' Errors on Your Computer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-compatible-receiver-use-with-your-logitech-wireless-mouse/"><u>Step-by-Step Guide: Compatible Receiver Use with Your Logitech Wireless Mouse</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-initiating-a-compulsory-safe-mode-reboot-on-windows/"><u>Step-by-Step Guide: Initiating a Compulsory Safe Mode Reboot on Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-for-contacting-snapchat-assistance/"><u>The Ultimate Guide for Contacting Snapchat Assistance</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-users-handbook-effective-usage-of-the-meta-quest-microphone/"><u>The User's Handbook: Effective Usage of the Meta Quest Microphone</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-10-websites-for-easy-and-effective-apartment-hunting/"><u>Top 10 Websites for Easy and Effective Apartment Hunting</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-4-twitter-apps-for-efficient-hashtag-tracking/"><u>Top 4 Twitter Apps for Efficient Hashtag Tracking</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-9-ultimate-skype-interview-strategies-for-success/"><u>Top 9 Ultimate Skype Interview Strategies for Success</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-guide-how-to-recover-a-lost-msvcrt10dll-file/"><u>Troubleshooting Guide: How to Recover a Lost msvcrt10.dll File</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-steps-overcoming-the-black-display-problem-in-android-smartphones/"><u>Troubleshooting Steps: Overcoming the Black Display Problem in Android Smartphones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-the-nsp4r-missing-dll-message-on-your-pc/"><u>Troubleshooting the 'Nsp4r Missing DLL' Message on Your PC</u></a></li>
<li><a href="https://some-tips.techidaily.com/unleash-creativity-in-editing-leveraging-storyremix-with-windows-11-photos-for-2024/"><u>Unleash Creativity in Editing  Leveraging StoryRemix with Windows 11 Photos for 2024</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-don-t-have-infinix-note-30i-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you don't have Infinix Note 30i fingerprint</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlock-the-power-of-people-finder-top-8-platforms-unveiled/"><u>Unlock The Power Of People Finder: Top 8 Platforms Unveiled</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlock-the-secrets-finding-out-whereabouts-of-iphone-friends-safely/"><u>Unlock the Secrets: Finding Out Whereabouts of iPhone Friends Safely</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-samsung-galaxy-ring-costs-launch-details-and-latest-updates/"><u>Unveiling the Samsung Galaxy Ring: Costs, Launch Details & Latest Updates</u></a></li>
<li><a href="https://activate-lock.techidaily.com/what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-12-pro-by-drfone-ios/"><u>What You Want To Know About Two-Factor Authentication for iCloud From your Apple iPhone 12 Pro</u></a></li>
</ul></div>
