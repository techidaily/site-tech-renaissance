---
title: "Effortless Setup: How to Link and Use Your New Logitech Mouse Easily"
date: 2024-09-23T04:01:12.891Z
updated: 2024-09-27T06:03:47.103Z
categories:
  - BestProducts
description: "This Article Describes Effortless Setup: How to Link and Use Your New Logitech Mouse Easily"
excerpt: "This Article Describes Effortless Setup: How to Link and Use Your New Logitech Mouse Easily"
thumbnail: https://thmb.techidaily.com/7f58c54be3fb446b417c67b3b88e71900b79dad1ab69f246e6dc4f6374786b65.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482">
  <img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902289/19272" target="_top" id="1902289">
  <img src="//a.impactradius-go.com/display-ad/19272-1902289" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902289/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Flush DNS on Mac OS X

 The Mac OS X flush DNS command is different than the one used in modern versions of the operating system. Open Terminal and then enter the command that corresponds with your version:

* **El Capitan** : sudo killall -HUP mDNSResponder
* **Yosemite** : sudo discoveryutil udnsflushcaches
* **Lion, Mountain Lion, and Mavericks** : sudo killall -HUP mDNSResponder
* **Snow Leopard** : sudo dscacheutil -flushcache
* **Leopard** : sudo lookupd -flushcache
* **Tiger** : lookupd -flushcache

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925565/19272" target="_top" id="1925565">
  <img src="//a.impactradius-go.com/display-ad/19272-1925565" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925565/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-increase-video-playback-speed-on-instagram-for-2024/"><u>[New] Increase Video Playback Speed on Instagram for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-premier-12-video-capture-goes-on-forever-in-2024/"><u>[Updated] Premier 12 Video Capture - Goes On Forever, In 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-premier-hd-picks-for-impeccable-video-recorders-for-2024/"><u>[Updated] Premier HD Picks for Impeccable Video Recorders for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-key-strategies-to-craft-persuasive-testimonials-that-resonate/"><u>2024 Approved Key Strategies to Craft Persuasive Testimonials That Resonate</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1723808167177-best-torrenting-platforms-for-gaming-enthusiasts-ranked-and-reviewed/"><u>Best Torrenting Platforms for Gaming Enthusiasts: Ranked and Reviewed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1723808243727-change-your-gmail-password-quickly-and-easily/"><u>Change Your Gmail Password. Quickly & Easily!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/connect-and-use-any-printer-with-easy-tips-for-windows-11-users/"><u>Connect and Use Any Printer with Easy Tips for Windows 11 Users</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/direct-ps3-controller-connection-for-gaming-on-pc-no-need-for-motioninjoy/"><u>Direct PS3 Controller Connection for Gaming on PC: No Need for MotionINJoy</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1723808113704-dont-miss-out-grab-your-20-off-driver-easy-offer-with-the-official-coupon/"><u>Don't Miss Out: Grab Your 20% Off Driver Easy Offer with the Official Coupon !</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-visual-splendor-of-blade-cameras-in-full-hd/"><u>In 2024, The Visual Splendor of Blade Cameras in Full HD</u></a></li>
<li><a href="https://win-blog.techidaily.com/masterclass-overcoming-connection-loss-problems-in-escape-from-tarkov/"><u>Masterclass: Overcoming Connection Loss Problems in Escape From Tarkov</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1723808256375-navigate-with-confidence-and-cut-costs-take-advantage-of-our-official-2n04-driver-easy-promo-offer-save-20-today/"><u>Navigate with Confidence & Cut Costs: Take Advantage of Our Official 2N04 Driver Easy Promo Offer - Save 20% Today!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/quick-guide-splitting-your-youtube-footage-with-expert-precision-techniques/"><u>Quick Guide: Splitting Your YouTube Footage with Expert Precision Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-realm-of-melodies-where-to-get-hearing-heroes-ringtones-for-2024/"><u>The Realm of Melodies Where to Get Hearing Heroes' Ringtones for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-function-key-issues-on-your-asus-laptop/"><u>Troubleshooting Non-Functional Function Key Issues on Your ASUS Laptop</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/windows-11-troubleshooting-effective-solutions-for-defrosting-frozen-systems/"><u>Windows 11 Troubleshooting: Effective Solutions for Defrosting Frozen Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/wiring-basics-how-to-link-an-external-monitor-with-your-notebook/"><u>Wiring Basics: How to Link an External Monitor with Your Notebook</u></a></li>
</ul></div>

