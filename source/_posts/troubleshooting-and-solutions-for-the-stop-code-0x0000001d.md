---
title: Troubleshooting and Solutions for the STOP Code 0X0000001D
date: 2024-09-04T01:12:56.130Z
updated: 2024-09-05T01:12:56.130Z
categories:
  - BestProducts
description: This Article Describes Troubleshooting and Solutions for the STOP Code 0X0000001D
excerpt: This Article Describes Troubleshooting and Solutions for the STOP Code 0X0000001D
thumbnail: https://www.lifewire.com/thmb/isn0ko2HLlTK7WUnMbUXQcunVqg=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/blue-screen-of-death-bsod-windows-56a6faab3df78cf772913ee6.png
---

## Error Code 0X80004005 Explained: Tips and Solutions to Fix It Now
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-leading-tech-for-remote-team-engagement/"><u>[New] 2024 Approved  Leading Tech for Remote Team Engagement</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-artistic-horizons-scouting-the-finest-8-drawing-apps-for-iphones/"><u>[New] In 2024, Artistic Horizons  Scouting the Finest 8 Drawing Apps for iPhones</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-picture-perfect-zero-cost-photo-enhancement-app/"><u>[New] In 2024, Picture Perfect  Zero Cost Photo Enhancement App</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instagram-tips-how-to-perfectly-flip-videos-on-devices-for-2024/"><u>[New] Instagram Tips  How to Perfectly Flip Videos on Devices for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-navigating-virtual-meetings-setting-up-video-calls-via-whatsapp-browser-on-pcs-for-2024/"><u>[New] Navigating Virtual Meetings  Setting up Video Calls via WhatsApp Browser on PCs for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-shoot-the-worlds-hustle-and-bustle-iphone-tips-for-shutter-speed-blurs/"><u>[New] Shoot the World's Hustle and Bustle  IPhone Tips for Shutter Speed Blurs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-win11s-ultimate-app-selection-for-quality-recording-for-2024/"><u>[New] Win11's Ultimate App Selection for Quality Recording for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-composing-captivating-cutting-edge-synopses-for-2024/"><u>[Updated] Composing Captivating Cutting-Edge Synopses for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-leveraging-streamlabs-obs-for-engaging-live-streams-for-2024/"><u>[Updated] Leveraging Streamlabs OBS for Engaging Live Streams for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-stop-youtube-shorts-forever-a-step-by-step-guide/"><u>[Updated] Stop YouTube Shorts Forever  A Step-by-Step Guide</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-gopros-versatility-up-against-nikons-km-170/"><u>2024 Approved  GoPro's Versatility Up Against Nikon's KM-170</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-unlock-apple-iphone-6-without-passcode-or-face-id-by-drfone-ios/"><u>3 Ways to Unlock Apple iPhone 6 without Passcode or Face ID</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/6-essential-strategies-to-create-your-ideal-images-with-midjourney/"><u>6 Essential Strategies to Create Your Ideal Images with MidJourney</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-comprehensive-review-of-nebulas-mars-3-air-excellence-or-disappointment-for-on-the-go-cinematic-experience/"><u>A Comprehensive Review of Nebula's Mars 3 Air: Excellence or Disappointment for On-The-Go Cinematic Experience?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/accessing-midjourney-with-ease-a-guide-to-utilizing-the-new-web-interface/"><u>Accessing Midjourney with Ease: A Guide to Utilizing the New Web Interface</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/best-long-range-evs-discover-the-5-most-impressive-models-available-now/"><u>Best Long-Range EVs: Discover the 5 Most Impressive Models Available Now</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-dying-light-co-op-gameplay-guide-unleash-your-inner-survivor-with-dynamic-parkour/"><u>Comprehensive Dying Light Co-Op Gameplay Guide - Unleash Your Inner Survivor with Dynamic Parkour</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/cost-breakdown-of-replacing-your-evs-power-source/"><u>Cost Breakdown of Replacing Your EV's Power Source</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-premier-drones-dominating-the-skies/"><u>Discover the Premier Drones Dominating the Skies</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/effortless-dvd-to-video-conversion-on-mac-with-macx-dvd-video-converter-pro-software/"><u>Effortless DVD-to-Video Conversion on Mac with MacX DVD Video Converter Pro Software</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/enhancing-collaboration-slack-melded-with-filmoras-video-capabilities/"><u>Enhancing Collaboration  Slack Melded With Filmora’s Video Capabilities</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/evaluating-the-usability-of-humanes-artificial-intelligence-pin-functionality-potential-challenges/"><u>Evaluating the Usability of Humane's Artificial Intelligence Pin Functionality - Potential Challenges</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/everyday-essentials-showdown-choosing-between-the-claude-and-chatgpt-applications-for-optimal-performance/"><u>Everyday Essentials Showdown: Choosing Between the Claude and ChatGPT Applications for Optimal Performance</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-hidden-functions-maximizing-your-experience-with-the-oculus-quest-vr-gears-best-kept-secrets/"><u>Explore Hidden Functions: Maximizing Your Experience with the Oculus Quest VR Gear's Best-Kept Secrets</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-inexpensive-options-for-artificial-intelligence-powered-visual-content-beyond-chatgpt/"><u>Explore Inexpensive Options for Artificial Intelligence-Powered Visual Content Beyond ChatGPT.</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-the-upgraded-chatgpt-plus-with-cutting-edge-pdf-insight-and-dynamic-modality-controls/"><u>Explore the Upgraded ChatGPT Plus with Cutting-Edge PDF Insight and Dynamic Modality Controls</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-changes-a-comprehensive-midjourney-v52-vs-v6-alpha-showdown/"><u>Exploring Changes: A Comprehensive MidJourney v5.2 Vs. V6 Alpha Showdown</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-next-generation-of-storage-beyond-nvme-and-the-evolution-of-ssds/"><u>Exploring the Next Generation of Storage: Beyond NVMe and the Evolution of SSDs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/from-driving-to-forecasting-the-evolution-of-waymos-intelligent-vehicles-as-mobile-meteorology-experts/"><u>From Driving to Forecasting: The Evolution of Waymo's Intelligent Vehicles as Mobile Meteorology Experts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-frequently-are-electrical-vehicles-prone-to-fires/"><u>How Frequently Are Electrical Vehicles Prone to Fires?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-i-mastered-writing-a-weeks-communications-using-google-gemini-insights-and-experience/"><u>How I Mastered Writing a Week's Communications Using Google Gemini – Insights & Experience</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-nvidias-latest-innovation-an-ai-chatbot-operating-locally-outperforms-traditional-cloud-based-alternatives/"><u>How Nvidia's Latest Innovation: An AI Chatbot Operating Locally Outperforms Traditional Cloud-Based Alternatives</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mental-wellness-through-virtual-environments/"><u>In 2024, Mental Wellness Through Virtual Environments</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-your-yearly-list-prime-free-video-editing-software/"><u>In 2024, Your Yearly List  Prime Free Video Editing Software</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/innovative-3d-printing-technology-powered-by-saltwater-instead-of-light-and-heat/"><u>Innovative 3D Printing Technology Powered by Saltwater Instead of Light and Heat</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722970910415-instant-access-to-essential-asus-monitor-drivers-effortless-download-awaits/"><u>Instant Access to Essential ASUS Monitor Drivers - Effortless Download Awaits</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/iphone-users-rejoice-new-enhancements-now-available-in-the-latest-chatgpt-update/"><u>IPhone Users Rejoice: New Enhancements Now Available in the Latest ChatGPT Update</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/join-microsoft-designer-today-say-goodbye-to-the-previous-hold-lists/"><u>Join Microsoft Designer Today - Say Goodbye to the Previous Hold Lists!</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-smooth-playthroughs-of-psychonauts-2-on-pc-how-to-avoid-the-crash-bug/"><u>Mastering Smooth Playthroughs of Psychonauts 2 on PC – How to Avoid the Crash Bug</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-art-of-creating-winning-resumes-with-chatgpt-a-comprehensive-guide/"><u>Mastering the Art of Creating Winning Resumes with ChatGPT: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-twitter-the-ultimate-guide-to-earning-cryptocurrency-advice/"><u>Mastering Twitter: The Ultimate Guide to Earning Cryptocurrency Advice</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/orion-spacecraft-returns-from-lunar-mission-a-closer-look-at-nasas-historic-journey/"><u>Orion Spacecraft Returns From Lunar Mission: A Closer Look at NASA’s Historic Journey</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/pioneering-ai-imaging-with-adobes-new-venture-into-firefly-artificial-intelligence-systems/"><u>Pioneering AI Imaging with Adobe's New Venture Into Firefly Artificial Intelligence Systems</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premium-platforms-converting-vids-for-the-bird-for-2024/"><u>Premium Platforms  Converting Vids for the Bird for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/preparing-your-residence-for-electric-vehicle-ev-charger-installation-a-step-by-step-guide/"><u>Preparing Your Residence for Electric Vehicle (EV) Charger Installation: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/recent-updates-may-impact-tax-credits-for-popular-choices-in-the-electric-vehicle-market/"><u>Recent Updates May Impact Tax Credits for Popular Choices in the Electric Vehicle Market</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/self-driving-claims-halted-by-tesla-in-certain-american-states-due-to-regulatory-compliance/"><u>Self-Driving Claims Halted by Tesla in Certain American States Due to Regulatory Compliance</u></a></li>
<li><a href="https://windows11.techidaily.com/shrouding-outage-with-code-0xc00d36b4-in-windows/"><u>Shrouding Outage with Code 0XC00D36B4 in Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-installing-third-party-software-directly-on-oculus-quest/"><u>Step-by-Step Guide: Installing Third-Party Software Directly on Oculus Quest</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/taking-gardening-to-new-heights-a-comprehensive-guide-using-perplexity-tools/"><u>Taking Gardening to New Heights: A Comprehensive Guide Using Perplexity Tools</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-decline-of-user-satisfaction-in-apples-recent-self-service-repair-scheme/"><u>The Decline of User Satisfaction in Apple's Recent Self-Service Repair Scheme</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-downfall-of-gms-pioneering-electric-vehicle-a-comprehensive-analysis/"><u>The Downfall of GM's Pioneering Electric Vehicle: A Comprehensive Analysis</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-true-value-of-purchasing-nft-art-beyond-simply-downloading-the-work/"><u>The True Value of Purchasing NFT Art - Beyond Simply Downloading the Work</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-foldable-computers-is-it-time-for-you-to-make-the-switch/"><u>The Ultimate Guide to Foldable Computers - Is It Time for You to Make the Switch?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-5-strategies-for-maximizing-output-with-dall-e-2/"><u>Top 5 Strategies for Maximizing Output with DALL-E 2</u></a></li>
<li><a href="https://discover-community.techidaily.com/winx-dvd-copy-pro-easy-steps-para-clonar-dvds-y-crear-backups-en-formato-iso/"><u>WinX DVD Copy Pro: Easy Steps Para Clonar DVDs Y Crear Backups en Formato ISO</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->