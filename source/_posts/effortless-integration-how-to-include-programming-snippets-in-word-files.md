---
title: "Effortless Integration: How to Include Programming Snippets in Word Files"
date: 2024-08-19T00:08:45.059Z
updated: 2024-08-20T00:08:45.059Z
categories:
  - BestProducts
description: "This Article Describes Effortless Integration: How to Include Programming Snippets in Word Files"
excerpt: "This Article Describes Effortless Integration: How to Include Programming Snippets in Word Files"
thumbnail: https://thmb.techidaily.com/ce2b50426ded5a960fb87586d9bc144c1e1a55defefae42789a30b646b9173fc.jpeg
---

## Effortless Typography Tweaks in Windows 11 – Learn How to Change Fonts Easily
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### What to Know

* Go to**Settings** \>**Personalization** \>**Fonts** to find the name of the font you want to use throughout Windows 11.
* Then, create a REG file using that name to replace the current system font. Open the REG file to change the font.
* Not all Windows fonts will change, but some do. It's easy to restore the default font if you change your mind.

 This article teaches you how to change the Windows 11 system font so that various areas of the OS will use the font type you prefer. It also covers how to undo these steps to restore the default font.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the System Font in Windows 11

 The quickest way to change the Windows 11 font is through a Windows Registry edit, which we'll do by creating a[REG file](https://www.lifewire.com/how-to-create-edit-and-use-reg-files-2622817) .

1. Open Settings, then select**Personalization** on the left, followed by**Fonts** on the right. Another way to get there is through the Run command:**ms-settings:fonts** .  
![The Personalization settings in Windows 11](https://www.lifewire.com/thmb/SJdYi81a1Rm29jJ6p7V24JP49ss=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/personalization-settings-windows-11-83afd8d0867d4d39a1b87dff59dd8fae.png)
2. Scroll down to**Available fonts** , and find and select the font you're interested in using.  
 If you don't see the font you want, you can take this time to download it. Lots of websites have free fonts, but you can also[buy fonts online](https://www.lifewire.com/buy-fonts-for-desktop-publishing-1077714) . Then, return to this area of Settings to see it. Our[How to Install Fonts in Windows 11](https://www.lifewire.com/install-fonts-in-windows-11-5192443) guide can help if you need it.
3. Locate the**Full name** line in the**Metadata** section, and write it down exactly as it's written. In our example, we recorded**Franklin Gothic Medium** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Yes highlighted in the Registry Editor prompt in Windows 11](https://www.lifewire.com/thmb/tViUCj2SD1eHRKNxSY2gP3-IusQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-change-the-font-in-windows-11-6827640-acbf618a85854ff58bb4ca6f3a0d7384.jpg)
12. [Reboot your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) to see the font changes. The quickest method is to right-click the Start button and go to**Shut down or sign out** \>**Restart** .

## What Does Changing the System Font Do?

 Changing the computer font in Windows 11 will switch up the way text looks throughout the operating system. Desktop icon text and the links in Control Panel are a couple of examples, but it's most obvious in other areas, such as the Run dialog box.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows 11 font type change in Run and Control Panel](https://www.lifewire.com/thmb/eN6m7hD9Mgh_sWhJB-Jl9QOeR2c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/windows-11-changed-font-type-control-panel-run-desktop-365bc4a2e315498f96aa4115713f7d59.png)

 However, not every part of Windows will change to the new font. All the text within Settings, Start menu, Clock, Quick Settings, and numerous other areas aren't affected.

[Troubleshooting Installed Fonts That Won't Work](https://www.lifewire.com/cant-use-installed-fonts-1074154)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
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
<li><a href="https://youtube-lab.techidaily.com/ssential-tips-for-making-youtube-introductory-trailers/"><u>[New] Essential Tips for Making YouTube Introductory Trailers</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-ace-message-management-on-discord-with-easy-pins/"><u>[New] In 2024, Ace Message Management on Discord with Easy Pins</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-simplify-your-workload-with-expert-use-of-ez-grabber/"><u>[New] Simplify Your Workload with Expert Use of EZ Grabber</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-expertly-lit-the-17-must-haves-for-youtubers/"><u>[Updated] 2024 Approved  Expertly Lit  The 17 Must-Haves for Youtubers</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-7-ideas-to-improve-the-unboxing-experience/"><u>[Updated] 7 Ideas to Improve the Unboxing Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-the-ultimate-manual-for-minecraft-playbacks-on-mac/"><u>[Updated] The Ultimate Manual for Minecraft Playbacks on Mac</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-route-to-rejuvenate-and-refine-your-vhs-collection-online/"><u>[Updated] The Ultimate Route to Rejuvenate and Refine Your VHS Collection Online</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-the-essential-guide-free-youtube-image-saving/"><u>2024 Approved  The Essential Guide  FREE YouTube Image Saving</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-window-communication-apps-5-1-top-8-list/"><u>2024 Approved  Window Communication Apps #5-#1  Top 8 List</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-samsung-galaxy-s23-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ace-your-streams-and-save-big-how-can-you-get-a-discounted-youtube-premium-membership/"><u>Ace Your Streams and Save Big: How Can You Get a Discounted YouTube Premium Membership?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/customize-gmail-alerts-with-unique-ringtone-settings-a-step-by-step-guide/"><u>Customize Gmail Alerts with Unique Ringtone Settings – A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-screen-innovation-what-sets-neo-qled-apart-from-oled-technology/"><u>Decoding Screen Innovation: What Sets Neo QLED Apart From OLED Technology</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-ios-18-availability-schedule-free-download-innovative-functions-and-recent-announcements/"><u>Discover iOS 18 - Availability Schedule, Free Download, Innovative Functions, & Recent Announcements</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enhance-your-movie-nights-with-these-15-must-watch-dolby-atmos-titles/"><u>Enhance Your Movie Nights with These 15 Must-Watch Dolby Atmos Titles</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-setting-up-automated-text-messages-on-your-iphone/"><u>Guide: Setting Up Automated Text Messages on Your iPhone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-x90s-phone-without-password-by-drfone-android/"><u>How To Unlock Vivo X90S Phone Without Password?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-expertise-in-making-screen-captures-on-ios-easier/"><u>In 2024, Expertise in Making Screen Captures on iOS Easier</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-poco-m6-pro-4g-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Poco M6 Pro 4G for Free? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/is-something-wrong-with-youtube-how-to-tell-and-fix-it/"><u>Is Something Wrong With YouTube? How to Tell and Fix It</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-art-of-quick-fixes-remedies-for-your-tvs-typical-snags/"><u>Mastering the Art of Quick Fixes: Remedies for Your TV's Typical Snags</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-basics-of-lg-channels-for-tech-enthusiasts/"><u>Mastering the Basics of LG Channels for Tech Enthusiasts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigate-like-a-pro-5-outstanding-gps-applications-for-iphones/"><u>Navigate Like a Pro: 5 Outstanding GPS Applications for iPhones</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/openais-gpt-on-ubuntu-command-line-connections-with-shellgpt/"><u>OpenAI's GPT on Ubuntu: Command-Line Connections with ShellGPT</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pro-level-stabilization-systems-for-streaming-content-for-2024/"><u>Pro-Level Stabilization Systems for Streaming Content for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/qled-vs-oled-tvs-explained-understanding-the-distinctive-features/"><u>QLED Vs. OLED TVs Explained: Understanding the Distinctive Features</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revamping-iphone-photography-top-tricks-when-the-lens-refuses-to-focus/"><u>Revamping iPhone Photography: Top Tricks When the Lens Refuses to Focus</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-resolving-line-artifacts-on-your-television-display/"><u>Step-by-Step Guide: Resolving Line Artifacts on Your Television Display</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-scanning-documents-from-your-printer-to-your-pc/"><u>Step-by-Step Guide: Scanning Documents From Your Printer to Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-solutions-correcting-the-missing-haldll-error-on-windows-xp/"><u>Step-by-Step Solutions: Correcting the 'Missing hal.dll' Error on Windows XP</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-best-kept-secret-11-freebie-updater-tools-to-enhance-and-streamline-your-system/"><u>The Best-Kept Secret: 11 Freebie Updater Tools to Enhance and Streamline Your System</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-casting-devices-on-your-firestick-using-chromecast/"><u>The Ultimate Guide to Casting Devices on Your Firestick Using Chromecast</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-method-for-consolidating-your-jpg-pictures-into-an-organized-pdf-file/"><u>The Ultimate Method for Consolidating Your JPG Pictures Into an Organized PDF File</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-8-email-services-to-replace-gmail/"><u>Top 8 Email Services to Replace Gmail</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-techniques-for-when-steamdll-is-missing-on-windows/"><u>Troubleshooting Techniques for When Steam.dll Is Missing on Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlock-without-a-code-removing-the-pin-from-windows-11-easily/"><u>Unlock Without a Code: Removing the PIN From Windows 11 Easily</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/windows-11-setup-made-easy-what-you-need-to-know-about-new-hard-drive-installation/"><u>Windows 11 Setup Made Easy: What You Need to Know About New Hard Drive Installation</u></a></li>
</ul></div>
