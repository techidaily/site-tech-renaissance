---
title: Winning Over TrustedInstaller - A User's Manual for Windows 10 Permission Requests
date: 2024-08-19T00:15:15.641Z
updated: 2024-08-20T00:15:15.641Z
categories:
  - BestProducts
description: This Article Describes Winning Over TrustedInstaller - A User's Manual for Windows 10 Permission Requests
excerpt: This Article Describes Winning Over TrustedInstaller - A User's Manual for Windows 10 Permission Requests
thumbnail: https://www.lifewire.com/thmb/bN_F8h8TKTX1N0seGbQ341fq0Y0=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/GettyImages-179036384-b081a08d421b4b6da954cac5b8461946.jpg
---

## Winning Over TrustedInstaller - A User's Manual for Windows 10 Permission Requests
### What to Know

* Use the**TAKEOWN** and**icacls** Command Prompt commands to take ownership of the file or folder.
* Or, right-click the item and go to**Properties** \>**Security** \>**Advanced** to add yourself to the list.
* TrustedInstaller is a built-in user account that owns lots of important system files.

 This article describes two ways to deal with the message in Windows 10 about needing permission from TrustedInstaller to make changes to a file or folder.

## How to Fix the TrustedInstaller Error Using Command Prompt

 There are two really simple[Command Prompt commands](https://www.lifewire.com/list-of-command-prompt-commands-4092302) you can use to bypass the TrustedInstaller permissions prompt. Follow these steps to fix the TrustedInstaller "error" by granting your user account permission to make changes to the file or folder:

1. [Open an elevated Command Prompt](https://www.lifewire.com/how-to-open-an-elevated-command-prompt-2618088) . The quickest way there is to search for it from the Start menu, right-click the result, and choose**Run as administrator** .  
![The Run As Administrator option for the Windows 10 Command Prompt](https://www.lifewire.com/thmb/qK50_I4SdSJ98eEbO9R6yPSN1Vk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/command-prompt-admin-windows-10-45f7ecab69a442f489eaf6a499a353d4.png)
2. Enter**TAKEOWN /F** and then type the file or folder name. Here's an example:  
 `TAKEOWN /F C:\Windows\System32\fr-FR\fms.dll.mui`
3. Press**Enter** to take control of the file. You'll see a success message if the command executed correctly.  
![The TAKEOWN /F command in Windows 10 Command Prompt](https://www.lifewire.com/thmb/nOnoS4n34cd8C2EJEDT2_rLzdhw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/takeown-command-trustsedinstaller-windows-10-267bfffb4f974a29940a0af233ef4a84.png)
4. Enter the following command (replacing our example file with your own) to immediately give your user account permission to delete or change the file or folder:  
 `icacls C:\Windows\System32\fr-FR\fms.dll.mui /grant Administrators:F /T`  
![icacls command executed in Windows 10 Command Prompt](https://www.lifewire.com/thmb/clN3CT0-H0V3QdOSRZWprDCigZ4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/icacls-command-windows-10-7f562cffaf424cd281b4e58c68b19e25.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
## Edit the File's Security Options to Fix the TrustedInstaller Error

 If you don't feel comfortable using Command Prompt to take ownership of the folder or file, there is another way. Here's how to use File Explorer to edit the security settings for the data, which will let you delete or modify it as needed.

Make sure you are logged in as an administrator.

1. Locate the item you need permission to change and then right-click it and choose**Properties** .  
![The context menu for a Windows 10 folder ](https://www.lifewire.com/thmb/CSwAkry59uiW_sJ5GzqkO0QrOuk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/context-menu-folder-windows-10-0447423a01764cecad790f8dc6303c59.png)
2. Go to**Security** \>**Advanced** , then select**Change** next to**Owner: TrustedInstaller** .  
![The Properties and Advanced Security Settings options for a Windows 10 folder](https://www.lifewire.com/thmb/823H3LgLGW5GbhyNSwSn1HNUZlk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/advanced-security-settings-windows-10-folder-4eb4fed4cb134eb1ba00993a705f7175.png)
3. Type your username into the text box and then choose**Check Names** \>**OK** .  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows 10 Check Names box with a user account listed](https://www.lifewire.com/thmb/ESMv2bIcNtWxpryKYLlwZFwmyCA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-10-select-user-or-group-880cbe35a52348f19d11206db4d7a0b6.png)
4. Check the box next to**Replace owner on subcontainers and objects** .  
![The replace owner on subcontainers and objects checkbox in Windows 10](https://www.lifewire.com/thmb/n8OW45wPPq3HiSTrW4eQIT_Y0EU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-owner-windows-10-folder-885ef894881e4e21a60b1b09568ea020.png)
5. Select**OK** at the bottom and then**OK** on the Properties window you opened in Step 1.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Open**Properties** \>**Security** \>**Advanced** once more. This time, select**Add** .  
![The Advanced Security Settings for a Windows 10 folder](https://www.lifewire.com/thmb/fEVYPGbUtSiGdO8kZg1RZd6gtIE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/add-button-advanced-security-settings-3ffcde5bc8b942278219bbd9b4663921.png)
7. Choose**Select a principal** and then type your username in the box.
8. Press**Check Names** \>**OK** .  
![A user account listed in the Select User or Group box for a Windows 10 folder](https://www.lifewire.com/thmb/a8Ie_eyPviEwOjytgb9HHofaQgc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/select-user-group-windows-10-security-b2ffe7d116f2424e845a612090d4e932.png)
9. Check the box next to**Full control** , then select**OK** .  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Full Control permission selected for a folder in Windows 10](https://www.lifewire.com/thmb/cLa_4Jv8moyuFMZaNvHFNWAcllw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/full-control-folder-permissions-b0f31e6f8d7d418e91990e6c32476c30.png)
10. Check the box next to **Replace all child object permission entries with inheritable permission entries from this object** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
![The checkbox called Replace all child object permission entries in Windows 10](https://www.lifewire.com/thmb/6T2vTKuuRj3ONEWEpCefVrYtszQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/replace-all-child-object-permission-entries-windows-10-fc09040d1d8b4357b5866ced25b79262.png)
11. Select**OK** on the Advanced Security Settings window and then**Yes** on the confirmation prompts. You should now have full permission to make changes to the file or folder, and you can close any other windows you opened to make these changes.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## Why Do I Need Permission From TrustedInstaller?

 Provided you're the primary user of your home computer, you might be surprised to find out you need anyone’s permission to deal with files on your own PC.

 All Windows 10 PCs have an in-built Microsoft account known as the TrustedInstaller. This account exists to prevent accidental damage to important system files, so it's given ownership over many important operating system files. For you to be able to take control of these files, you need to make yourself the owner as described above.  

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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-swift-strategies-to-beat-instagrams-video-blues/"><u>[New] In 2024, Swift Strategies to Beat Instagram's Video Blues</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-picsart-in-detail-the-ultimate-guide-to-2024-updates/"><u>[New] PicsArt in Detail  The Ultimate Guide to 2024 Updates</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-the-ultimate-compendium-ios-gif-apps-reviewed-for-2024/"><u>[New] The Ultimate Compendium  IOS GIF Apps Reviewed for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-magixs-acid-pro-reviewed-comparing-similar-software/"><u>[Updated] 2024 Approved  Magix's ACID Pro Reviewed  Comparing Similar Software</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/android-tips-how-to-go-incognito-and-hide-your-number-from-calls/"><u>Android Tips: How To Go Incognito and Hide Your Number From Calls</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/anticipated-google-symposium-breaking-news-and-fresh-reveals/"><u>Anticipated Google Symposium: Breaking News & Fresh Reveals</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/boost-productivity-in-microsoft-teams-tips-for-effective-copilot-integration/"><u>Boost Productivity in Microsoft Teams: Tips for Effective Copilot Integration</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/breaking-down-the-latest-on-tesla-robotaxi-forecasted-pricing-info-launch-timeline-and-rumored-technical-aspects/"><u>Breaking Down the Latest on Tesla Robotaxi: Forecasted Pricing Info, Launch Timeline & Rumored Technical Aspects</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/current-hot-deals-for-your-new-apple-smartwatch/"><u>Current Hot Deals for Your New Apple Smartwatch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/dealing-with-wi-fi-adapter-errors-here-are-10-effective-strategies/"><u>Dealing With Wi-Fi Adapter Errors? Here Are 10 Effective Strategies</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-required-drivers-for-your-samsung-850-evo-ssd-now/"><u>Download Required Drivers for Your Samsung 850 EVO SSD Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-diagnosing-and-repairing-errors-related-to-the-nt-loader-ntldr/"><u>Expert Advice: Diagnosing & Repairing Errors Related to the NT Loader (NTLDR)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-on-removing-grime-and-ensuring-hygiene-of-your-personal-loudspeakers-at-home/"><u>Expert Tips on Removing Grime and Ensuring Hygiene of Your Personal Loudspeakers at Home</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-nvidia-geforce-rtx-2060-super-drivers-compatible-with-win10-and-win11/"><u>Get the Latest NVIDIA GeForce RTX 2060 Super Drivers - Compatible with Win10 & Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-clean-a-tv-remote/"><u>How to Clean a TV Remote</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-leverage-twitter-with-these-easy-to-use-hashtag-monitoring-tools-successguide/"><u>How to Leverage Twitter with These Easy-to-Use Hashtag Monitoring Tools (#SuccessGuide)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-setting-up-your-apple-homepod-as-a-component-of-your-tv-audio-experience/"><u>How To: Setting up Your Apple HomePod as a Component of Your TV Audio Experience</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Vivo Y78 5G? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-monetary-worth-of-podcasting/"><u>In 2024, The Monetary Worth of Podcasting</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/in-depth-instructions-on-upgrading-an-ailing-ipads-charge-unit/"><u>In-Depth Instructions on Upgrading an Ailing iPad's Charge Unit</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/in-depth-instructions-how-to-seamlessly-add-a-subwoofer-to-your-samsung-soundbar-setup/"><u>In-Depth Instructions: How to Seamlessly Add a Subwoofer to Your Samsung Soundbar Setup</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/insights-on-playstation-5-slim-latest-updates-pricing-info-and-launch-timeline/"><u>Insights on PlayStation 5 Slim - Latest Updates, Pricing Info & Launch Timeline</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mac-and-pc-differences-what-are-they-really/"><u>Mac and PC Differences: What Are They Really?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-your-fitness-goals-a-guide-to-using-the-measure-app-on-android/"><u>Mastering Your Fitness Goals: A Guide to Using the Measure App on Android</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-wlanapidll-file-absence-issues-a-step-by-step-guide/"><u>Resolving 'WLANAPI.DLL' File Absence Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/restoring-access-how-to-bring-back-a-closed-snapchat-profile/"><u>Restoring Access: How to Bring Back a Closed Snapchat Profile</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/samsung-soundbar-woes-heres-how-you-can-get-it-working-again/"><u>Samsung Soundbar Woes? Here's How You Can Get It Working Again!</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/send-smiles-wide-step-by-step-for-sharing-gifs-on-snapchat/"><u>Send Smiles Wide  Step-by-Step for Sharing Gifs on Snapchat</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solutions-to-resolve-missing-d3dx939dll-files/"><u>Solutions to Resolve Missing d3dx9_39.dll Files</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722873844369-step-by-step-guide-repairing-dvd-blu-ray-and-cd-drives-stuck-in-closed-position/"><u>Step-by-Step Guide: Repairing DVD, Blu-Ray, and CD Drives Stuck in Closed Position</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-tips-resolving-issues-when-your-mac-app-wont-launch/"><u>Troubleshooting Tips: Resolving Issues When Your Mac App Won't Launch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-what-to-do-when-you-encounter-a-missing-python24dll/"><u>Troubleshooting: What to Do When You Encounter a Missing Python24.dll</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-cross-platform-functionality-run-your-favorite-android-apps-in-windows-10/"><u>Unlocking Cross-Platform Functionality: Run Your Favorite Android Apps in Windows 10</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-solutions-for-windows-11-black-screen-troubleshooting-tips/"><u>Unveiling Solutions for Windows 11 Black Screen Troubleshooting Tips</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-xiaomi-redmi-note-12-proplus-5g-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Xiaomi Redmi Note 12 Pro+ 5G Phone Network-Ready</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtubes-top-tools-studio-vs-latest-beta-features-for-2024/"><u>YouTube's Top Tools  Studio Vs. Latest Beta Features for 2024</u></a></li>
</ul></div>
