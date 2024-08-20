---
title: Expert Tips on Compelling Windows to Start Up in Safe Mode
date: 2024-08-19T00:13:39.907Z
updated: 2024-08-20T00:13:39.907Z
categories:
  - BestProducts
description: This Article Describes Expert Tips on Compelling Windows to Start Up in Safe Mode
excerpt: This Article Describes Expert Tips on Compelling Windows to Start Up in Safe Mode
thumbnail: https://www.lifewire.com/thmb/2PzECV0th8lkw2Wd2G3VSAac2Xk=/540x405/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/how-to-force-windows-to-restart-in-safe-mode-2625163-1105674bea70405ab286d0d61b498bf6.png
---

## Expert Tips on Compelling Windows to Start Up in Safe Mode
### What to Know

* To force Windows to restart in Safe Mode, access Advanced Startup Options or System Recovery Options.
* Then, use a**bcdedit** command to open Safe Mode from Command Prompt.

 This article describes how to use the bcdedit command to boot into Safe Mode when[the normal method doesn't work](https://www.lifewire.com/fix-a-computer-that-always-stops-at-startup-settings-or-abo-2624445) .  

## How to Use 'bcdedit' to Start in Safe Mode

 Forcing Windows to restart to this special mode (or making it_stop_ starting in Safe Mode) is moderately difficult and will probably take several minutes, at most. These directions will start Safe Mode from[Command Prompt](https://www.lifewire.com/command-prompt-2625840) :

1. [Open Advanced Startup Options](https://www.lifewire.com/how-to-access-advanced-startup-options-in-windows-10-or-8-2626229) if you're on Windows 11, Windows 10, or Windows 8\. Since you can't start Windows properly, use methods 4, 5, or 6 outlined in that tutorial.  
 With Windows 7 or Vista, start System Recovery Options using your installation media or a system repair disc. Unfortunately, this process doesn't work with Windows XP.  
 If you want to force or stop Safe Mode from starting, and you actually_can_ access Windows properly, you don't need to follow the procedure below. See the much easier[How to Start Windows in Safe Mode Using System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) process.
2. Open Command Prompt. If you're using Windows 7 or newer, it's located here:**Troubleshoot** \>**Advanced options** \>**Command Prompt** .  
![Advanced Startup Options for Windows 10](https://www.lifewire.com/thmb/FvRv0xdSCo8UanPmD9Vp0mBddjE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/aso-windows-10-5c5c3bde46e0fb000127c6d7.png)
3. Execute the correct bcdedit[command](https://www.lifewire.com/what-is-a-command-2625828) as shown below based on which Safe Mode option you'd like to start:  
!["bcdedit /set {default} safeboot network" command in Command Prompt](https://www.lifewire.com/thmb/tnUE5VabXIlDNfK2S4UhcOKHG9c=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/002_how-to-force-windows-to-restart-in-safe-mode-2625163-5c77678446e0fb0001d83cb3.jpg)  
 Be sure to type whatever command you choose_exactly_ as shown and then execute it using the**Enter** key. Spaces are very important! The { and } brackets are the ones above the \[ and \] keys on your keyboard. Two separate commands are required to start_Safe Mode with Command Prompt_ , so be sure to execute them both.  
 Safe Mode:  
 `bcdedit /set {default} safeboot minimal`  
 Safe Mode with Networking:  
 `bcdedit /set {default} safeboot network`  
 Safe Mode with Command Prompt:  
 `bcdedit /set {default} safeboot minimal bcdedit /set {default} safebootalternateshell yes`
4. A properly executed bcdedit command should return the message**The operation completed successfully** .  
 If you see one of these messages or something similar, check Step 3 again and make sure you executed the Safe Mode command properly:  
   * **The parameter is incorrect**  
   * **The set command specified is not valid**  
   * **...is not recognized as an internal or external command...**
5. Close the Command Prompt window.
6. In Windows 11, 10, and 8, select**Continue** .  
 In Windows 7 and Vista, select**Restart** .  
![ASO menu Windows](https://www.lifewire.com/thmb/s1Q2N-22YKjJTAP7l4M9BJzkNXE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/003_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7767ddc9e77c0001f57b8c.jpg)
7. Wait while your computer or device restarts.
8. Once Windows starts, log in as you normally do and use Safe Mode however you were planning.

 Windows will continue to start in Safe Mode every time you reboot unless you undo what you did in Step 3\. The easiest way to do that is not by executing more commands but[via System Configuration](https://www.lifewire.com/how-to-start-windows-in-safe-mode-using-system-configuration-2626115) (uncheck**Safe boot** ).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## How to Stop a Safe Mode Loop

 Try this if Windows is stuck in a sort of Safe Mode loop, preventing you from starting in normal mode again, and you've already tried the instructions in the_Important_ call-out above:

1. Start Command Prompt from_outside_ of Windows, the process outlined in Steps 1 and 2 above.
2. Execute this command once Command Prompt is open:  
 `bcdedit /deletevalue {default} safeboot`  
!["bcdedit /deletevalue {default} safeboot" command in Command Prompt on Windows](https://www.lifewire.com/thmb/iw73ubzOfXo2zuWO1YLBafnst2A=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/004_how-to-force-windows-to-restart-in-safe-mode-2625163-5c7768a5c9e77c000136a6ae.jpg)
3. Assuming it was successfully executed (see Step 4 above),[restart your computer](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Windows should start normally.
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[8 Things to Consider Before Buying a Desktop PC](https://www.lifewire.com/desktop-pc-buyers-guide-832343)

 FAQ

* How do I exit Safe Mode in Windows 10?  
 Exiting Windows 10 Safe Mode is typically just a matter of[restarting your PC](https://www.lifewire.com/how-to-reboot-a-computer-2624568) . Another method is to press the**Windows key + R** , then type in "**msconfig** " and select**OK** \>**Boot** and turn off**Safe boot** under Boot Options.
* How do I enter Safe Mode in Windows XP if F8 isn't working?  
 Normally restarting Windows XP in Safe Mode is just a matter of pressing F8 during startup. If the F8 key isn't working, check your keyboard for an F-Lock key that could have turned off your F keys. Otherwise,[open your PC's BIOS menu](https://www.lifewire.com/how-to-enter-bios-2624481) and make sure**Keyboard Support USB** is turned on.

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
<li><a href="https://vp-tips.techidaily.com/new-boosting-team-engagement-with-zoom-techniques-on-msteams/"><u>[New] Boosting Team Engagement with ZOOM Techniques on MSTEAMS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-capturing-presentations-effortlessly-a-guide-to-screen-capture-for-2024/"><u>[New] Capturing Presentations Effortlessly  A Guide to Screen Capture for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-efficient-ways-to-save-ppt-slides-for-2024/"><u>[New] Efficient Ways to Save PPT Slides for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-flashcapture-critique-plus-backup-software/"><u>[New] In 2024, FlashCapture Critique + Backup Software</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-ultimate-toolkit-for-top-notch-tiktok-cuts/"><u>[New] Ultimate Toolkit for Top-Notch TikTok Cuts</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-immersive-escapes-how-to-choose-between-rift-vive-ps-vr-in-2024/"><u>[Updated] Immersive Escapes  How to Choose Between Rift, Vive, PS VR, In 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-experts-picks-the-best-10-photography-lenses/"><u>2024 Approved  Expert's Picks  The Best 10 Photography Lenses</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-textual-dimension-mastering-adobe-illustrator/"><u>2024 Approved  The Art of Textual Dimension  Mastering Adobe Illustrator</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-about-ps-vr-2-an-in-depth-look-at-release-timing-cost-estimates-and-hardware-specs/"><u>All About PS VR 2 - An In-Depth Look at Release Timing, Cost Estimates, and Hardware Specs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/best-innovative-visual-voicemail-systems-2024-rankings/"><u>Best Innovative Visual Voicemail Systems: 2024 Rankings</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-guide-to-recovering-or-replacing-missing-winhttpdll-files-on-windows-pcs/"><u>Comprehensive Guide to Recovering or Replacing Missing Winhttp.dll Files on Windows PCs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-solution-to-correct-d3dx941dll-errors-on-your-pc/"><u>Comprehensive Solution to Correct 'd3dx9_41.dll' Errors on Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-tv-technologies-how-does-neo-qled-stack-up-against-oled/"><u>Decoding TV Technologies: How Does Neo QLED Stack Up Against OLED?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-instructions-on-how-to-get-your-iphone-running-on-updated-ios-version/"><u>Easy Instructions on How to Get Your iPhone Running on Updated iOS Version</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effortless-guide-how-to-arrange-your-personalized-experience-at-the-apple-store/"><u>Effortless Guide: How to Arrange Your Personalized Experience at the Apple Store</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effortless-workflow-enabling-and-using-split-screen-on-macbook-air/"><u>Effortless Workflow: Enabling and Using Split Screen on MacBook Air</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enhancing-your-viewing-experience-how-to-link-apple-homepod-with-your-television-set/"><u>Enhancing Your Viewing Experience: How To Link Apple HomePod with Your Television Set</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-techniques-to-maximize-your-use-of-google-gemini/"><u>Essential Techniques to Maximize Your Use of Google Gemini</u></a></li>
<li><a href="https://extra-information.techidaily.com/final-cuts-ultimate-10-plug-in-essentials-list/"><u>Final Cut's Ultimate 10 Plug-In Essentials List</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/get-informed-the-most-recent-windows-updates-and-service-packs-for-july-2024/"><u>Get Informed: The Most Recent Windows Updates and Service Packs for July 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-samsung-galaxy-xcover-6-pro-tactical-edition-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Samsung Galaxy XCover 6 Pro Tactical Edition Quickly? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-fix-jvmdll-not-found-or-missing-errors/"><u>How to Fix Jvm.dll Not Found or Missing Errors</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-tidy-up-your-samsung-tv-screen-removing-extra-applications-with-ease/"><u>How to Tidy Up Your Samsung TV Screen: Removing Extra Applications with Ease</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-7-plus-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 7 Plus to other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-verizon-apple-iphone-se-2020-by-drfone-ios/"><u>In 2024, How to Unlock Verizon Apple iPhone SE (2020)</u></a></li>
<li><a href="https://extra-information.techidaily.com/increasing-onscreen-detail-in-virtual-spaces/"><u>Increasing Onscreen Detail in Virtual Spaces</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/inside-look-at-the-new-m4-mac-mini-anticipated-costs-release-timeline-and-feature-specs-revealed/"><u>Inside Look at the New M4 Mac Mini – Anticipated Costs, Release Timeline & Feature Specs Revealed</u></a></li>
<li><a href="https://win-amazing.techidaily.com/installing-hp-officejet-pro-6968-printer-download-required-drivers/"><u>Installing HP OfficeJet Pro 6968 Printer: Download Required Drivers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ipad-showdown-analyzing-the-distinctive-traits-of-mini-and-air-versions/"><u>IPad Showdown: Analyzing the Distinctive Traits of Mini and Air Versions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/latest-wwdc-2025-insights-apples-new-releases-and-updates/"><u>Latest WWDC 2025 Insights: Apple's New Releases & Updates</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/learn-sign-language-for-free-ultimate-list-of-16-resources/"><u>Learn Sign Language For Free: Ultimate List of 16 Resources</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/master-class-on-the-fugetek-ft-568-an-outstanding-durable-selection-of-premium-selfie-support-devices/"><u>Master Class on the Fugetek FT-568: An Outstanding, Durable Selection of Premium Selfie Support Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-pokemon-unite-a-step-by-step-guide-for-pc-gaming/"><u>Mastering Pokémon Unite: A Step-by-Step Guide for PC Gaming</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-the-digital-space-with-ease-via-onestream-platform/"><u>Navigating the Digital Space with Ease via OneStream Platform</u></a></li>
<li><a href="https://android-unlock.techidaily.com/pattern-locks-are-unsafe-secure-your-samsung-galaxy-a24-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Samsung Galaxy A24 Phone Now with These Tips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/quick-fixes-the-ultimate-guide-to-accelerate-your-computer/"><u>Quick Fixes: The Ultimate Guide to Accelerate Your Computer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/restoring-functionality-how-to-replace-lost-or-damaged-keys-on-your-laptop/"><u>Restoring Functionality: How To Replace Lost or Damaged Keys On Your Laptop</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simplified-process-for-deleting-multiple-connections-in-snapchat/"><u>Simplified Process for Deleting Multiple Connections in Snapchat</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/siri-voiceover-assistance-effortlessly-navigating-textual-content-with-your-iphone-or-macbook-pro/"><u>Siri Voiceover Assistance: Effortlessly Navigating Textual Content with Your iPhone or MacBook Pro</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-properly-referencing-generative-ai-like-chatgpt-in-your-work/"><u>Step-by-Step Guide: Properly Referencing Generative AI Like ChatGPT in Your Work</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-solutions-for-the-missing-mfc42dll-error-on-your-computer/"><u>Step-by-Step Solutions for the 'Missing mfc42.dll Error' On Your Computer</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-comprehensive-guide-to-crafting-effective-reddit-posts-for-2024/"><u>The Comprehensive Guide to Crafting Effective Reddit Posts for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-elite-selection-of-10-websites-offering-free-photos/"><u>The Elite Selection of 10 Websites Offering FREE Photos</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-eliminating-user-authentication-pins-on-microsofts-latest-operating-system/"><u>The Ultimate Guide to Eliminating User Authentication Pins on Microsoft's Latest Operating System</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-10-streaming-services-like-netflix-no-cost-options/"><u>Top 10 Streaming Services Like Netflix – No Cost Options</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-steps-for-fixing-wmvcoredll-absence-errors-effectively/"><u>Troubleshooting Steps for Fixing Wmvcore.dll Absence Errors Effectively</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-comparison-of-premium-group-video-calls-solutions/"><u>Ultimate Comparison of Premium Group Video Calls Solutions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-7-must-try-free-music-services-for-android-and-ios-aficionados/"><u>Unveiling 7 Must-Try Free Music Services for Android and iOS Aficionados</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/upcoming-google-pixel-9-unveiling-rumored-features-estimated-cost-and-launch-timeline/"><u>Upcoming Google Pixel 9: Unveiling Rumored Features, Estimated Cost & Launch Timeline</u></a></li>
<li><a href="https://driver-install.techidaily.com/usb-20-to-ethernet-step-by-step-driver-instruction/"><u>USB 2.0 to Ethernet: Step by Step Driver Instruction</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-your-computer-is-low-on-memory-solved/"><u>Windows 10 Your Computer Is Low on Memory [Solved]</u></a></li>
</ul></div>
