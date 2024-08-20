---
title: "Ultimate Guide: Resolving the DRIVER_POWER_STATE_FAILURE Error"
date: 2024-08-18T22:51:53.940Z
updated: 2024-08-19T22:51:53.940Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Ultimate Guide: Resolving the DRIVER_POWER_STATE_FAILURE Error"
excerpt: "This Article Describes Ultimate Guide: Resolving the DRIVER_POWER_STATE_FAILURE Error"
thumbnail: https://thmb.techidaily.com/b11f60af4f1190ff0fe1470217a3e88ba5ec7f084c8dd4d5a027c3574d3f04e3.jpg
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
<li><a href="https://article-files.techidaily.com/new-in-2024-the-most-popular-vr-game-experiences-on-oculus/"><u>[New] In 2024, The Most Popular VR Game Experiences on Oculus</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-most-effective-sales-strategies-unveiled-with-these-leading-15-fb-analyzers-for-2024/"><u>[New] The Most Effective Sales Strategies Unveiled with These Leading 15 FB Analyzers for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-explore-prime-cardboard-compatible-vr-adventures/"><u>[Updated] Explore  Prime Cardboard-Compatible VR Adventures</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-how-to-record-youtube-live-stream-on-any-device-for-2024/"><u>[Updated] How To Record YouTube Live Stream On Any Device for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-essential-idleness-tranquil-phone-game-recommendations/"><u>[Updated] In 2024, Essential Idleness  Tranquil Phone Game Recommendations</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-realme-11-pro-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-elevate-conversations-via-curated-creativity-in-stories-lives/"><u>2024 Approved  Elevate Conversations via Curated Creativity in Stories Lives</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/boosting-the-quality-of-photography-on-your-iphoneipad-a-comprehensive-guide/"><u>Boosting the Quality of Photography on Your iPhone/iPad: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/coming-soon-the-next-gen-touchscreen-macbook-price-estimates-launch-date-features-detailed-inside/"><u>Coming Soon? The Next-Gen Touchscreen MacBook: Price Estimates, Launch Date, Features Detailed Inside!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-list-of-july-2n24s-updates-for-microsoft-operating-systems/"><u>Comprehensive List of July 2N24's Updates for Microsoft Operating Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-latest-from-sony-game-changing-news-innovations-and-industry-trends/"><u>Discover the Latest From Sony : Game-Changing News, Innovations, and Industry Trends</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-solutions-making-your-amazon-prime-subtitles-work-again-a-comprehensive-guide/"><u>DIY Solutions: Making Your Amazon Prime Subtitles Work Again – A Comprehensive Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enabledisable-windows-11s-network-discovery-a-step-by-step-guide/"><u>Enable/Disable Windows 11'S Network Discovery: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-free-learning-apps-every-student-needs-before-going-back-to-classes/"><u>Essential FREE Learning Apps Every Student Needs Before Going Back to Classes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-insights-into-amazon-prime-day-202n4-a-comprehensive-overview/"><u>Essential Insights Into Amazon Prime Day 202N4: A Comprehensive Overview</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/evaluating-the-value-of-minecraft-realms-for-players/"><u>Evaluating the Value of Minecraft Realms for Players</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-free-alternatives-and-trials-for-microsoft-word-users/"><u>Exploring Free Alternatives and Trials for Microsoft Word Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/harness-your-windows-10-sound-power/"><u>Harness Your Windows 10 Sound Power</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-htc-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from HTC .</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-reestablish-cell-network-connection-on-an-apple-watch/"><u>How to Reestablish Cell Network Connection on an Apple Watch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-resolve-the-missing-opengl3de-rie-error-on-your-computer/"><u>How to Resolve the Missing OpenGL3ˈd͡ʒeɪ Ɛr'iə: Error on Your Computer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-reverse-a-video-in-snapchat/"><u>How to Reverse a Video in Snapchat</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-seamlessly-link-amazon-fire-stick-to-your-home-theater-projector/"><u>How To Seamlessly Link Amazon Fire Stick to Your Home Theater Projector</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Oppo Find N3? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-oppo-reno-11-pro-5g-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Oppo Reno 11 Pro 5G Phone that is Locked?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-3d-tools-optimized-for-animation-workflows/"><u>In 2024, Key 3D Tools Optimized for Animation Workflows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-trendsetters-in-virtual-reality-headsets/"><u>In 2024, Trendsetters in Virtual Reality Headsets</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unlocking-aspect-ratios-the-key-to-facebook-video-success/"><u>In 2024, Unlocking Aspect Ratios  The Key to Facebook Video Success</u></a></li>
<li><a href="https://extra-support.techidaily.com/ipads-drawing-dynasty-top-8-sketch-apps-for-2024/"><u>IPad's Drawing Dynasty  Top 8 Sketch Apps for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/july-2press-update-exploring-the-top-13-free-disk-check-software-options/"><u>July 2Press Update: Exploring the Top 13 Free Disk Check Software Options</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/mastering-the-art-of-isolating-rhythms-a-guide-to-online-beat-extraction/"><u>Mastering the Art of Isolating Rhythms A Guide to Online Beat Extraction</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-beyond-chatgpt-the-top-10-options-for-next-gen-dialogue-systems/"><u>Navigating Beyond ChatGPT: The Top 10 Options for Next-Gen Dialogue Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-through-snappydriver-installation-tool-v113-an-expert-appraisal/"><u>Navigating Through SnappyDriver Installation Tool V1.13: An Expert Appraisal</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-from-words-to-music-audio-conversion-of-textual-content-on-various-platforms/"><u>New In 2024, From Words to Music Audio Conversion of Textual Content on Various Platforms</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-make-music-without-spending-a-dime-10-free-recording-software-options/"><u>New Make Music Without Spending a Dime 10 Free Recording Software Options</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-lava-blaze-2-pro-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Lava Blaze 2 Pro to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revitalizing-your-monitors-appearance-fixes-for-pixel-damage-and-fading-hues-on-digital-displays/"><u>Revitalizing Your Monitor's Appearance: Fixes for Pixel Damage & Fading Hues on Digital Displays</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-your-powerpoints-audio-troubles-a-comprehensive-fix-guide/"><u>Solving Your PowerPoint's Audio Troubles: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-to-fixing-lame-mp3-dll-problems-in-audacity/"><u>Step-by-Step Guide to Fixing Lame MP3 DLL Problems in Audacity</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tutorial-watching-fubotv-channels-with-your-firestick/"><u>Step-by-Step Tutorial: Watching FuboTV Channels with Your Firestick</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stop-your-display-from-blinking-tips-and-tricks/"><u>Stop Your Display From Blinking: Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-talk-the-key-to-a-visible-mouse-indicator-in-windows-os/"><u>Tech Talk: The Key to a Visible Mouse Indicator in Windows OS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-comprehensive-guide-to-utilizing-androids-quick-settings-feature/"><u>The Comprehensive Guide to Utilizing Android's Quick Settings Feature</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-the-cyberpowerpc-gamer-xtreme-best-value-and-easy-upgradability/"><u>The Ultimate Guide to the CyberPowerPC Gamer Xtreme: Best Value and Easy Upgradability</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-4-fantastic-no-cost-digital-planners/"><u>Top 4 Fantastic No-Cost Digital Planners</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-stutters-and-lags-enhancing-your-fallout-76-experience/"><u>Troubleshooting Stutters & Lags: Enhancing Your Fallout 76 Experience</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-playing-various-videos-on-apple-tv-using-vlc-player/"><u>Ultimate Guide: Playing Various Videos on Apple TV Using VLC Player</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlock-peak-performance-with-these-12-free-disk-defrag-tools-july-2024/"><u>Unlock Peak Performance with These 12 Free Disk Defrag Tools (July 2024)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-mystery-teslas-upcoming-phone-with-speculative-price-points-and-rumored-specifications/"><u>Unveiling the Mystery: Tesla's Upcoming Phone with Speculative Price Points and Rumored Specifications</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Motorola Moto G24 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->