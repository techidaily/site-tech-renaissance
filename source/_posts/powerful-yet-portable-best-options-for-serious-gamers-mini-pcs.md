---
title: "Powerful Yet Portable: Best Options for Serious Gamers' Mini PCs"
date: 2024-09-19T18:43:40.329Z
updated: 2024-09-20T19:08:09.947Z
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

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-resources.techidaily.com/new-best-pricing-in-the-cloud-unveil-your-options-here/"><u>[New] Best Pricing in the Cloud? Unveil Your Options Here</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-determining-best-video-frames-per-second-fps-rate/"><u>[Updated] Determining Best Video Frames Per Second (FPS) Rate</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-animate-and-make-your-own-effects/"><u>[Updated] In 2024, How to Animate and Make Your Own Effects</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-skyrocket-subscribers-mastering-youtube-traffic-boost/"><u>[Updated] Skyrocket Subscribers Mastering YouTube Traffic Boost</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-about-home-based-electric-car-power-up-techniques/"><u>All About Home-Based Electric Car Power Up Techniques</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-guide-samsungs-advanced-galaxy-z-fold-model-x-pricing-upcoming-launch-and-specifications-covered/"><u>Comprehensive Guide: Samsung's Advanced Galaxy Z Fold Model X - Pricing, Upcoming Launch & Specifications Covered</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-excellence-in-dialogue-and-plot-hub/"><u>In 2024, Excellence in Dialogue & Plot Hub</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-xiaomi-redmi-note-13-pro-5g-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Xiaomi Redmi Note 13 Pro 5G</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/major-outages-at-big-tech-firms-like-microsoft-highlight-governments-need-to-seek-alternatives/"><u>Major Outages at Big Tech Firms Like Microsoft Highlight Governments' Need to Seek Alternatives</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/master-the-fix-for-persistent-code-error-n43-expert-advice/"><u>Master the Fix for Persistent Code Error N43 - Expert Advice</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-openal32dll-cannot-be-found-strategies-and-solutions/"><u>Overcoming 'OpenAL32.dll Cannot Be Found' - Strategies and Solutions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-basics-of-output-impedance-explained-simply/"><u>The Basics of Output Impedance Explained Simply</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-prosperous-path-share-tiktok-via-twitter/"><u>The Prosperous Path Share TikTok via Twitter</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-tips-reset-procedures-for-samsung-audio-systems/"><u>Troubleshooting Tips: Reset Procedures for Samsung Audio Systems</u></a></li>
<li><a href="https://media-tips.techidaily.com/why-digital-filmstreams-cant-match-the-charm-of-in-person-dvd-lending-services/"><u>Why Digital Filmstreams Can't Match the Charm of In-Person DVD Lending Services</u></a></li>
</ul></div>

