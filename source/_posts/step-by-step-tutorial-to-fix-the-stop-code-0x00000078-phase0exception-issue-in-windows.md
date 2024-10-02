---
title: Step-by-Step Tutorial to Fix the STOP Code 0X00000078 (PHASE0_EXCEPTION) Issue in Windows
date: 2024-09-26T19:55:07.492Z
updated: 2024-10-02T08:30:05.505Z
categories:
  - BestProducts
description: This Article Describes Step-by-Step Tutorial to Fix the STOP Code 0X00000078 (PHASE0_EXCEPTION) Issue in Windows
excerpt: This Article Describes Step-by-Step Tutorial to Fix the STOP Code 0X00000078 (PHASE0_EXCEPTION) Issue in Windows
thumbnail: https://www.lifewire.com/thmb/isn0ko2HLlTK7WUnMbUXQcunVqg=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/blue-screen-of-death-bsod-windows-56a6faab3df78cf772913ee6.png
---

## Error Code 0X80004005 Resolved? Step-by-Step Strategies to Fix It
 Error 0x80004005 is a type of unspecified Windows error code that usually appears as "Error Code 0x80004005\. Unspecified error." Error 0x80004005 may show up on its own or alongside other error messages. Sometimes, additional text may help you narrow down the source of the problem.

 Instructions in this article apply to[Windows 11](https://www.lifewire.com/windows-11-5188930) ,[Windows 10](https://www.lifewire.com/windows-10-2626217) ,[Windows 8](https://www.lifewire.com/windows-8-2626235) ,[Windows 7](https://www.lifewire.com/windows-7-2626265) ,[Windows Vista](https://www.lifewire.com/windows-vista-2626311) , and[Windows XP](https://www.lifewire.com/windows-xp-2626354) .

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes Error Code 0x80004005?

 Error code 0x80004005 typically happens when you access shared folders or drives, use specific programs, or have a problem installing Windows updates. Here are the most common causes of error code 0x80004005:

* Problems with[Windows Update](https://www.lifewire.com/what-is-windows-update-2624597) .
* Moving or renaming files and folders.
* Windows notification issues.
* Problems opening or extracting[compressed files](https://www.lifewire.com/what-is-a-compressed-file-2625829) and folders.

 If you notice the error occurs when you use a specific program, the problem is likely[software](https://www.lifewire.com/what-is-software-4153107) related.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
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
![A screenshot of Windows Registry with the Numerical Value and OK button highlighted](https://www.lifewire.com/thmb/OqNevLWWV50Z3qSb36MeYz61-8Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001-how-to-fix-error-code-0x80004005-4689559-7b5e14fd0ef942718355465faefbcb77.jpg)  
 Don't delete or change anything in the Windows registry unless you know what you're doing.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-discover-top-affordable-video-editors-of-2023-today/"><u>[New] 2024 Approved Discover Top Affordable Video Editors of 2023 Today</u></a></li>
<li><a href="https://location-fake.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-best-7-driving-traffic-apps-on-the-market/"><u>Discover the Best 7 Driving Traffic Apps on the Market</u></a></li>
<li><a href="https://some-approaches.techidaily.com/diy-manycam-magic-learn-how-to-design-unique-overlays-and-transitions-for-your-streams/"><u>DIY ManyCam Magic: Learn How to Design Unique Overlays & Transitions for Your Streams</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exceptional-ipad-deals-you-cant-miss-this-season/"><u>Exceptional iPad Deals You Can't Miss This Season</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-fix-a-mac-application-thats-not-opening/"><u>How to Fix a Mac Application That's Not Opening</u></a></li>
<li><a href="https://some-approaches.techidaily.com/luminous-videos-an-android-lighting-guide-for-2024/"><u>Luminous Videos An Android Lighting Guide for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/speedy-image-viewer-powered-by-windows-11/"><u>Speedy Image Viewer Powered by Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-integrate-old-games-with-win11-mypictures/"><u>Steps to Integrate Old Games with Win11 MyPictures</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-differences-between-basic-and-advanced-ev-charging-levels-explored/"><u>The Differences Between Basic and Advanced EV Charging - Levels Explored</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-essential-framework-for-adding-media-to-youtube-compilations/"><u>The Essential Framework for Adding Media to YouTube Compilations</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-list-of-32-no-cost-backup-utilities-rated-for-security-and-convenience/"><u>The Ultimate List of 32 No-Cost Backup Utilities, Rated for Security & Convenience</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-list-2024s-best-learning-applications-according-to-us/"><u>The Ultimate List: 2024'S Best Learning Applications, According to Us</u></a></li>
<li><a href="https://driver-error.techidaily.com/total-disk-utilization-fix-for-win11-and-10/"><u>Total Disk Utilization Fix for Win11 & 10</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/whats-inside-the-next-foldable-iphone-rumors-about-pricing-release-dates-and-tech-specs-unveiled/"><u>What's Inside the Next Foldable iPhone? Rumors About Pricing, Release Dates and Tech Specs Unveiled</u></a></li>
</ul></div>

