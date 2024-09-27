---
title: "Powerful Yet Portable: Best Options for Serious Gamers' Mini PCs"
date: 2024-09-20T23:49:03.352Z
updated: 2024-09-27T07:51:05.836Z
categories:
  - BestProducts
description: "This Article Describes Powerful Yet Portable: Best Options for Serious Gamers' Mini PCs"
excerpt: "This Article Describes Powerful Yet Portable: Best Options for Serious Gamers' Mini PCs"
thumbnail: https://thmb.techidaily.com/5c4901379d06e76779eeda32a494315f2bc02d2e9ce3c41076b40598a264c895.jpg
---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

## What Does Flushing DNS Do?

 Each time you access a website in your web browser, the URL you enter is sent to a[DNS server](https://www.lifewire.com/what-is-a-dns-server-2625854) for translation into an[IP address](https://www.lifewire.com/what-is-an-ip-address-2625920) . This information is stored in a cache on your Mac for easy retrieval in the future, hence the term_DNS cache_ .

 When you try to access a website you’ve been to recently, your Mac uses its DNS cache instead of checking with an actual DNS server. The web browser doesn’t have to go through the extra step of communicating with a remote DNS server, which results in less time between entering a website address and the website loading.

 If the local DNS cache is corrupt or outdated, it’s kind of like trying to use an old phone book that's been vandalized. Your web browser checks the cache to find an IP address for the website you’re trying to visit, and it finds either the wrong address or an unusable one. This can slow the process down or prevent websites or specific web page elements, like videos, from loading.

 When you flush your DNS cache, you instruct your Mac to delete its local DNS records. This in turn forces your web browser to check with a DNS server for fresh information. You should always flush your DNS cache after[changing the DNS servers on your Mac](https://www.lifewire.com/network-preference-pane-change-macs-dns-settings-2260394) . It can also be helpful if you’re having connectivity problems.  

 FAQ

* How do I check the DNS cache on a Mac?  
 Open the built-in Console log-viewer app on your Mac and type**any:mdnsresponder** into the search bar. Then, launch Terminal, type in**sudo killall –INFO mDNSResponder** , and press**Enter** or**Return** . Back in the Console app, you can view a list of cached DNS records.
* How do I clear the DNS cache on Windows 10?  
 To[clear the DNS cache on Windows 10](https://www.lifewire.com/flush-and-clear-windows-dns-cache-5095298) , open the Run dialog box, type in**ipconfig /flushdns** , and click**OK** . You can also use the same command in the Windows command prompt if you want more information on the process.
* What is DNS cache poisoning?  
 DNS cache poisoning, also known as DNS spoofing, is when someone deliberately enters false or incorrect information into a DNS cache. After the false information is input, future DNS queries will return incorrect responses and direct users to the wrong websites.

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
<li><a href="https://extra-hints.techidaily.com/new-conquering-peaks-and-valleys-comparing-the-mightiest-gopros-b-and-sessions/"><u>[New] Conquering Peaks and Valleys Comparing the Mightiest GoPros, B & Sessions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-installing-snapchat-a-mac-owners-handbook-for-2024/"><u>[Updated] Installing Snapchat A Mac Owner's Handbook for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-hues-harmony-an-editors-guide-to-perfect-grading/"><u>2024 Approved Hues Harmony An Editor's Guide to Perfect Grading</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/amd-radeon-graphics-card-firmware-update-v2410/"><u>AMD Radeon Graphics Card Firmware Update V24.10</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-motorola-moto-g13-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Motorola Moto G13? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/data-handling-done-right-fastest-5-ways-to-move-files-onto-your-computer/"><u>Data Handling Done Right Fastest 5 Ways To Move Files Onto Your Computer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-fixes-for-when-you-encounter-a-missing-bootmgr-error/"><u>Easy Fixes for When You Encounter a Missing BOOTMGR Error</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-steps-for-downloading-the-latest-xp-pen-driver-updates/"><u>Easy Steps for Downloading the Latest XP-PEN Driver Updates</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-on-correcting-wmvcoredll-not-found-problems/"><u>Expert Advice on Correcting 'Wmvcore.dll Not Found' Problems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-secrets-of-duckduckgo-how-safe-is-it-really-for-internet-searching/"><u>Exploring the Secrets of DuckDuckGo - How Safe Is It Really for Internet Searching?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/innovative-fixes-for-dealing-with-the-persistent-hulu-rununk13-error-on-streaming-services/"><u>Innovative Fixes for Dealing with the Persistent Hulu Rununk13 Error on Streaming Services</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-permission-controls-altering-trustedinstaller-accessibility-in-windows-11-systems/"><u>Mastering Permission Controls: Altering TrustedInstaller Accessibility in Windows 11 Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-the-intersection-of-modern-gadgets-and-timeless-tales-phones-computers-and-bibliophile-delights/"><u>Navigating the Intersection of Modern Gadgets and Timeless Tales: Phones, Computers, and Bibliophile Delights</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/oxford-3000-mondly-style-for-quick-learning/"><u>Oxford 3000, Mondly Style for Quick Learning</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unmasking-your-macs-secret-files-with-easy-terminal-commands/"><u>Unmasking Your Mac's Secret Files with Easy Terminal Commands</u></a></li>
<li><a href="https://video-capture.techidaily.com/your-free-guide-to-android-device-screenshots-for-2024/"><u>Your FREE Guide to Android Device Screenshots for 2024</u></a></li>
</ul></div>

