---
title: Learn How to Switch ON/OFF Network Visibility in Windows 10 for Enhanced Security
date: 2024-08-20T10:41:40.950Z
updated: 2024-08-21T10:41:40.950Z
categories:
  - BestProducts
description: This Article Describes Learn How to Switch ON/OFF Network Visibility in Windows 10 for Enhanced Security
excerpt: This Article Describes Learn How to Switch ON/OFF Network Visibility in Windows 10 for Enhanced Security
thumbnail: https://www.lifewire.com/thmb/qM1nNnmQahuj0QFb4ZrHH5hMw1k=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-turn-on-or-off-discovery-network-in-windows-10-74c70951f2ef41318b30937d76f80049.jpg
---

## Effortless Typography Tweaks in Windows 11 – Learn How to Change Fonts Easily
### What to Know

* Go to**Settings** \>**Personalization** \>**Fonts** to find the name of the font you want to use throughout Windows 11.
* Then, create a REG file using that name to replace the current system font. Open the REG file to change the font.
* Not all Windows fonts will change, but some do. It's easy to restore the default font if you change your mind.

 This article teaches you how to change the Windows 11 system font so that various areas of the OS will use the font type you prefer. It also covers how to undo these steps to restore the default font.

## How to Change the System Font in Windows 11

 The quickest way to change the Windows 11 font is through a Windows Registry edit, which we'll do by creating a[REG file](https://www.lifewire.com/how-to-create-edit-and-use-reg-files-2622817) .

1. Open Settings, then select**Personalization** on the left, followed by**Fonts** on the right. Another way to get there is through the Run command:**ms-settings:fonts** .  
![The Personalization settings in Windows 11](https://www.lifewire.com/thmb/SJdYi81a1Rm29jJ6p7V24JP49ss=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/personalization-settings-windows-11-83afd8d0867d4d39a1b87dff59dd8fae.png)
2. Scroll down to**Available fonts** , and find and select the font you're interested in using.  
 If you don't see the font you want, you can take this time to download it. Lots of websites have free fonts, but you can also[buy fonts online](https://www.lifewire.com/buy-fonts-for-desktop-publishing-1077714) . Then, return to this area of Settings to see it. Our[How to Install Fonts in Windows 11](https://www.lifewire.com/install-fonts-in-windows-11-5192443) guide can help if you need it.
3. Locate the**Full name** line in the**Metadata** section, and write it down exactly as it's written. In our example, we recorded**Franklin Gothic Medium** .  
![Full Name and Franklin Gothic Medium highlighted in Windows 11 font settings](https://www.lifewire.com/thmb/TLWCZLK0sdGg9XBIj1y4Ma1EuAA=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/001_how-to-change-the-font-in-windows-11-6827640-97099a55349a45e392459345af24caf1.jpg)
4. Open Notepad, or a[different text editor](https://www.lifewire.com/best-free-text-editors-4155819) if you prefer, and paste the following:  
 `Windows Registry Editor Version 5.00`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"=""`  
`"Segoe UI Bold (TrueType)"=""`  
`"Segoe UI Bold Italic (TrueType)"=""`  
`"Segoe UI Italic (TrueType)"=""`  
`"Segoe UI Light (TrueType)"=""`  
`"Segoe UI Semibold (TrueType)"=""`  
`"Segoe UI Symbol (TrueType)"=""`  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"="Franklin Gothic Medium"`
5. In the last line of the document, replace**Franklin Gothic Medium** with the name of the font you recorded in Step 3 (keep the quotes around the name).  
![Franklin Gothic Medium highlighted in Windows Notepad with REG file contents](https://www.lifewire.com/thmb/5UM6sKcUZ5_xlc9vkHeFpUtlwpk=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-change-the-font-in-windows-11-6827640-babf346069c14d8caa00e4c43d7992b6.jpg)
6. If you're using Notepad, go to**File** \>**Save as** , and type a name in the**File name** box.
7. Choose**All files** from the**Save as type** menu.
8. Type**.reg** at the end of the file name. Our example reads**Franklin Gothic.reg** , but yours can be called whatever you want; just make sure it ends with that file extension.
9. Choose a folder on your computer to save the file (the Desktop folder works), and then select**Save** .  
![FranklinGothic.reg and Save highlighted in a Notepad document with REG file extension](https://www.lifewire.com/thmb/4p0dmSoOCDSVSqxK6o9QnPtNX1U=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-change-the-font-in-windows-11-6827640-9563197f19ae4d848482def07b741adc.jpg)
10. Close the text editor, and then double-click or double-tap the REG file from the folder you just saved it to.
11. Press**Yes** on the User Account Control window, then**Yes** again on the Registry Editor prompt (pictured below), and finally**OK** on the success message.  
![Yes highlighted in the Registry Editor prompt in Windows 11](https://www.lifewire.com/thmb/tViUCj2SD1eHRKNxSY2gP3-IusQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-change-the-font-in-windows-11-6827640-acbf618a85854ff58bb4ca6f3a0d7384.jpg)
12. [Reboot your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see the font changes. The quickest method is to right-click the Start button and go to**Shut down or sign out** \>**Restart** .

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Does Changing the System Font Do?

 Changing the computer font in Windows 11 will switch up the way text looks throughout the operating system. Desktop icon text and the links in Control Panel are a couple of examples, but it's most obvious in other areas, such as the Run dialog box.

![Windows 11 font type change in Run and Control Panel](https://www.lifewire.com/thmb/eN6m7hD9Mgh_sWhJB-Jl9QOeR2c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-11-changed-font-type-control-panel-run-desktop-365bc4a2e315498f96aa4115713f7d59.png)

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
 However, not every part of Windows will change to the new font. All the text within Settings, Start menu, Clock, Quick Settings, and numerous other areas aren't affected.

[Troubleshooting Installed Fonts That Won't Work](https://www.lifewire.com/cant-use-installed-fonts-1074154)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## How to Restore the Default Font in Windows 11

 The best way to get the original Windows 11 font back is to reverse the registry tweak that changed it in the first place. To do that, repeat the steps from above, but replace the Notepad text with different code.

 You can do this one of two ways. This first method is easiest only if you still have the original REG file:

1. Right-click the REG file from wherever you saved it during Step 9, and select**Edit in Notepad** .
2. Highlight all the text that's in there, and replace it with this:  
 `Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts]`  
`"Segoe UI (TrueType)"="segoeui.ttf"`  
`"Segoe UI Black (TrueType)"="seguibl.ttf"`  
`"Segoe UI Black Italic (TrueType)"="seguibli.ttf"`  
`"Segoe UI Bold (TrueType)"="segoeuib.ttf"`  
`"Segoe UI Bold Italic (TrueType)"="segoeuiz.ttf"`  
`"Segoe UI Emoji (TrueType)"="seguiemj.ttf"`  
`"Segoe UI Historic (TrueType)"="seguihis.ttf"`  
`"Segoe UI Italic (TrueType)"="segoeuii.ttf"`  
`"Segoe UI Light (TrueType)"="segoeuil.ttf"`  
`"Segoe UI Light Italic (TrueType)"="seguili.ttf"`  
`"Segoe UI Semibold (TrueType)"="seguisb.ttf"`  
`"Segoe UI Semibold Italic (TrueType)"="seguisbi.ttf"`  
`"Segoe UI Semilight (TrueType)"="segoeuisl.ttf"`  
`"Segoe UI Semilight Italic (TrueType)"="seguisli.ttf"`  
`"Segoe UI Symbol (TrueType)"="seguisym.ttf"`  
`"Segoe MDL2 Assets (TrueType)"="segmdl2.ttf"`  
`"Segoe Print (TrueType)"="segoepr.ttf"`  
`"Segoe Print Bold (TrueType)"="segoeprb.ttf"`  
`"Segoe Script (TrueType)"="segoesc.ttf"`  
`"Segoe Script Bold (TrueType)"="segoescb.ttf"`  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsNT\CurrentVersion\FontSubstitutes]`  
`"Segoe UI"=-`
3. Save the file.
4. Exit Notepad, and then open the REG file. Accept all the prompts to edit the registry.
5. If the changes don't take effect immediately (they did for us), reboot your computer.

 If you don't have the original REG file readily available to edit, just repeat the steps at the top of this page. When you get to the part about pasting the code into Notepad, use the modified code from Step 2 above, and don't make any changes to it.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing Other Fonts in Windows 11

 The method outlined in this article isn't how it typically works when you want to use a new font in Windows. The directions explained above are unique for two reasons: Windows doesn't have a built-in way to change the system font, and you're changing the_system_ font, not just the font type for a single app.

 Most programs have their own font settings so you can make changes that apply to just that one program. And doing it is extremely easy because Windows 11_does_ provide a way to easily install a font that can be used by any of your software.

 For example, if you've downloaded a font you'd like to use in Microsoft Word,[install the font to your computer](https://www.lifewire.com/install-fonts-in-windows-11-5192443) , and it'll be available the next time you open Word. That's usually how it works: install the fonts to your computer to give all your programs access to them.

 You can, for instance, change the default font and size in Outlook by choosing an installed font. The same applies when you[pick a new default font for Thunderbird emails](https://www.lifewire.com/change-default-font-thunderbird-1173143) . Online apps need separate instructions since they don't typically access local fonts:[here's how to edit Gmail's default font options](https://www.lifewire.com/change-the-default-compose-font-face-and-color-in-gmail-1171898) in your browser.

 With some programs, there's a special folder in the app's installation directory that's used to load fonts for that one piece of software. This is how you[install fonts just for Photoshop](https://www.lifewire.com/installing-fonts-for-photoshop-only-1702271) .

[How to Manage Your Fonts in Windows](https://www.lifewire.com/too-many-windows-fonts-1077817)

 FAQ

* How do I change the font size on my Windows desktop icons?  
 To change the default text size in Windows 11, go to**Start** \>**Settings** \>**Accessibility** \>**Text size** . Use the slider to adjust the preview text size and select**Apply** .
* What font is used in Windows?  
 The default system font for Windows 11 is called Segoe UI. Pronounced “see-go,” this is the standard font for all Microsoft products.
* How do I change the default font in Microsoft Office?  
 You can[change the default font in Microsoft Office](https://www.lifewire.com/change-default-font-in-microsoft-office-2511891) apps by creating a template. For example, in Microsoft Word, create a new template and go to the**Home** tab, then right-click any style. Select**Modify** , then choose a font under**Formatting** . Make sure**New documents based on this template** is selected, then select**OK** .

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
<li><a href="https://facebook-videos.techidaily.com/new-tips-for-effective-screen-broadcasts-on-fb-live-for-2024/"><u>[New] Tips for Effective Screen Broadcasts on FB Live for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-overcoming-instagram-video-errors-solutions-now/"><u>[Updated] 2024 Approved  Overcoming Instagram Video Errors  Solutions Now</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-compact-guide-to-free-live-streaming-apps-on-mobile-devices/"><u>2024 Approved  Compact Guide to Free Live Streaming Apps on Mobile Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722886049547-accidentally-sent-heres-how-you-can-retrieve-your-emails-in-outlook/"><u>Accidentally Sent? Here's How You Can Retrieve Your Emails in Outlook!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-about-pixel-fold-2-projected-pricing-expected-arrival-and-tech-specs-rumor-rundown/"><u>All About Pixel Fold 2: Projected Pricing, Expected Arrival, and Tech Specs - Rumor Rundown</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/bridging-devices-and-desktops-how-to-operate-google-home-features-from-your-pc/"><u>Bridging Devices and Desktops: How to Operate Google Home Features From Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722894338376-comctl32dll-file-missing-heres-how-to-restore-it/"><u>Comctl32.dll File Missing? Here's How to Restore It</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-guide-to-the-latest-release-of-ipados-1-access-date-and-pricing-details-included-new-functions-and-industry-insights-await-you/"><u>Comprehensive Guide to the Latest Release of iPadOS 1# - Access Date & Pricing Details Included! New Functions and Industry Insights Await You</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-tips-to-address-d3dx930dll-file-unavailability-errors/"><u>Comprehensive Tips to Address d3dx9_30.dll File Unavailability Errors</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-fixes-for-when-your-vizio-tv-cant-find-a-wi-fi-signal-heres-how/"><u>DIY Fixes for When Your Vizio TV Can't Find a Wi-Fi Signal – Here’s How</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-tips-for-engaging-in-live-messages-within-mozilla-thunderbird/"><u>Easy Tips for Engaging in Live Messages Within Mozilla Thunderbird</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-not-found-or-missing-mstdfmtdll-errors-for-windows-users/"><u>Fixing Not Found or Missing mstdfmt.dll Errors for Windows Users</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-can-i-send-and-receive-imessages-on-my-android-phone/"><u>How Can I Send and Receive iMessages on My Android Phone?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-effortlessly-switch-up-your-discord-user-pic/"><u>How To Effortlessly Switch Up Your Discord User Pic</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-enjoy-netflix-shows-and-movies-on-your-nintendo-switch/"><u>How to Enjoy Netflix Shows and Movies on Your Nintendo Switch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-resolve-color-shifts-and-image-distortion-problems-with-your-monitor/"><u>How to Resolve Color Shifts and Image Distortion Problems with Your Monitor</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-motorola-edge-40-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-streamline-your-classic-gaming-with-optimal-ps2-android-emulators/"><u>In 2024, Streamline Your Classic Gaming with Optimal PS2 Android Emulators</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-htc-u23-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your HTC U23 Phone Pattern Lock</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722892516608-is-there-a-global-outage-on-microsoft-teams-heres-how-to-check/"><u>Is There a Global Outage on Microsoft Teams? Here's How to Check!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigate-the-decades-with-our-pick-of-the-best-80s-movies-to-watch-now/"><u>Navigate the Decades with Our Pick of the Best '80S Movies to Watch Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-apple-support-a-complete-walkthrough-to-schedule-a-guru-session/"><u>Navigating Apple Support: A Complete Walkthrough to Schedule a Guru Session</u></a></li>
<li><a href="https://win-able.techidaily.com/1722987245835-no-more-game-crashes-decode-and-repair-your-cod-vanguard-en-error-0x00001338-on-pc-now/"><u>No More Game Crashes – Decode and Repair Your COD Vanguard E:N (Error 0X00001338) on PC Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/optimize-and-revitalize-your-computer-overcoming-windows/"><u>Optimize and Revitalize Your Computer: Overcoming Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-android-communication-glitches-no-more-missed-texts/"><u>Overcoming Android Communication Glitches: No More Missed Texts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-missing-or-unavailable-helperdll-easy-repair-tips/"><u>Overcoming Missing or Unavailable Helper.dll – Easy Repair Tips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/quick-fixes-the-7-most-effective-techniques-to-enhance-your-computers-speed/"><u>Quick Fixes: The 7 Most Effective Techniques to Enhance Your Computer's Speed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/reconnect-with-anonymous-callers-how-to-call-a-blocked-or-private-phone-number/"><u>Reconnect with Anonymous Callers: How to Call a Blocked or Private Phone Number</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-the-network-not-registered-issue-a-step-by-step-guide-for-samsung-galaxy-users/"><u>Solving the 'Network Not Registered' Issue: A Step-by-Step Guide for Samsung Galaxy Users</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-the-issue-why-isnt-netflix-functioning-properly-on-your-roku-device/"><u>Solving the Issue: Why Isn't Netflix Functioning Properly on Your Roku Device?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-resolve-jvmdll-not-found-errors-quickly/"><u>Step-by-Step Guide: Resolve JVM.DLL Not Found Errors Quickly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/strategies-to-overcome-the-zero-match-dilemma-in-bumble-dating/"><u>Strategies to Overcome the Zero Match Dilemma in Bumble Dating</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/streaming-the-roku-channel-on-other-devices-a-comprehensive-guide/"><u>Streaming the Roku Channel on Other Devices: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/sync-up-disneyplus-with-chromecast-for-the-ultimate-media-experience-heres-how/"><u>Sync Up Disney+ with Chromecast for the Ultimate Media Experience – Here’s How!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-comprehensive-guide-to-the-newly-released-samsung-galaxy-watch-7-pricing-specs-and-release-updates/"><u>The Comprehensive Guide to the Newly Released Samsung Galaxy Watch #7 - Pricing, Specs and Release Updates</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-essential-guide-to-free-drive-diagnosis-apps-latest-picks/"><u>The Essential Guide to Free Drive Diagnosis Apps: Latest Picks</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-5-app-selections-for-easily-meeting-friends-and-enriching-your-social-life/"><u>The Ultimate 5 App Selections for Easily Meeting Friends and Enriching Your Social Life</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-elevation-requests-in-windows-fixes-for-win11-win10-and-win7-error-messages/"><u>Troubleshooting Elevation Requests in Windows: Fixes for Win11, Win10 & Win7 Error Messages</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-techniques-for-the-stop-error-0x0000005c-hal-initialization-failed/"><u>Troubleshooting Techniques for the STOP Error: 0X0000005C (Hal Initialization Failed)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/tv-essentials-unveiled-distinguishing-between-cable-and-streaming-platforms/"><u>TV Essentials Unveiled: Distinguishing Between Cable & Streaming Platforms</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/understanding-and-controlling-facebook-video-playback/"><u>Understanding and Controlling Facebook Video Playback</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-quintessential-quintet-free-malicious-software-busters/"><u>Unveiling The Quintessential Quintet: Free Malicious Software Busters</u></a></li>
</ul></div>
