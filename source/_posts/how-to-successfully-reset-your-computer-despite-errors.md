---
title: How to Successfully Reset Your Computer Despite Errors
date: 2024-08-18T23:55:14.685Z
updated: 2024-08-19T23:55:14.685Z
categories:
  - BestProducts
description: This Article Describes How to Successfully Reset Your Computer Despite Errors
excerpt: This Article Describes How to Successfully Reset Your Computer Despite Errors
thumbnail: https://www.lifewire.com/thmb/RTWozXNfuDskFcnTHBCFbtVSHlU=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/there-was-a-problem-resetting-your-pc-86e596e364114dc2bacc19e1295c4ce4.png
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
![Entering a password in Terminal on a Mac.](https://www.lifewire.com/thmb/hvFn07N8xnjZ9XJQvgMitPvCTVQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Password-902f4015f672459598066969c7900b2f.jpg)  
The password will not appear in Terminal as you type it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
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
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-the-ultimate-cloud-storage-cost-breakdown-2024-edition/"><u>[New] The Ultimate Cloud Storage Cost Breakdown, 2024 Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-best-youtube-shorts-video-editing-apps-for-ios-and-android/"><u>[Updated] 2024 Approved  Best YouTube Shorts Video Editing Apps for iOS and Android</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-gratuitous-high-quality-ideas-for-profitable-slideshows/"><u>[Updated] In 2024, Gratuitous, High-Quality Ideas for Profitable Slideshows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-the-vimeo-story-a-hub-for-exclusive-film-content/"><u>[Updated] In 2024, The Vimeo Story  A Hub for Exclusive Film Content</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-collection-of-film-scripts-by-genre/"><u>[Updated] The Ultimate Collection of Film Scripts by Genre</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-sj-cam-s6-unboxed-a-full-evaluation-in-detail/"><u>2024 Approved  SJ-CAM S6 Unboxed  A Full Evaluation in Detail</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-asus-rog-phone-7-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Asus ROG Phone 7 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-comprehensive-guide-to-activating-twitchs-2fa-feature/"><u>A Comprehensive Guide to Activating Twitch's 2FA Feature</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/an-in-depth-look-at-organic-light-emitting-diode-oled-functionality/"><u>An In-Depth Look at Organic Light Emitting Diode (OLED) Functionality</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/apple-ring-news-and-expected-price-release-date-specs-and-more-rumors/"><u>Apple Ring: News and Expected Price, Release Date, Specs; and More Rumors</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/building-a-stylish-tiktok-closing-credits-bar-for-2024/"><u>Building A Stylish TikTok Closing Credits Bar for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/cutting-edge-performance-check-a-detailed-review-of-apples-latest-4k-streaming-device/"><u>Cutting-Edge Performance Check - A Detailed Review of Apple's Latest 4K Streaming Device</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-the-function-of-cellular-service-providers-for-better-connectivity/"><u>Decoding the Function of Cellular Service Providers for Better Connectivity</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-5-premier-no-cost-sports-streaming-platforms-this-year/"><u>Discover the 5 Premier No-Cost Sports Streaming Platforms This Year</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/editing-techniques-for-enhancing-instagram-content/"><u>Editing Techniques for Enhancing Instagram Content</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/efficient-ways-to-keep-tabs-on-your-monthly-data-use-online/"><u>Efficient Ways to Keep Tabs on Your Monthly Data Use Online</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/email-marketing/"><u>Email Marketing</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enjoy-cinema-and-television-content-at-no-cost-on-crackle-platform/"><u>Enjoy Cinema & Television Content at No Cost on Crackle Platform</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-80s-cinema-the-ultimate-list-of-classic-movies-from-the-decade/"><u>Essential '80S Cinema: The Ultimate List of Classic Movies From the Decade</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-tips-what-you-need-to-know-before-acquiring-a-refurbished-ipad/"><u>Essential Tips: What You Need to Know Before Acquiring a Refurbished iPad</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/everything-you-should-know-about-samsung-tv-applications/"><u>Everything You Should Know About Samsung TV Applications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-our-curated-selection-of-7-premier-traffic-app-choices/"><u>Explore Our Curated Selection of 7 Premier Traffic App Choices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/google-pixel-tablet-news-price-release-date-specs-and-more/"><u>Google Pixel Tablet: News, Price, Release Date, Specs, and More</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-arrange-and-enjoy-all-episodes-of-dragon-ball-properly/"><u>How to Arrange and Enjoy All Episodes of Dragon Ball Properly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-buy-a-tv-for-your-home/"><u>How to Buy a TV For Your Home</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-realme-12plus-5g-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Realme 12+ 5G</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-keep-your-zoom-updated-on-both-windows-and-mac-computers/"><u>How to Keep Your Zoom Updated on Both Windows and Mac Computers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-sync-or-adjust-your-kindle-paperwhite-screen-clock-a-complete-guide/"><u>How to Sync or Adjust Your Kindle Paperwhite Screen Clock: A Complete Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-boxed-bliss-reinventing-the-art-of-first-contacts/"><u>In 2024, Boxed Bliss  Reinventing the Art of First Contacts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/lost-in-light-steps-to-retrieve-your-preferred-facebook-dark-mode-experience/"><u>Lost in Light: Steps to Retrieve Your Preferred Facebook Dark Mode Experience</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-sonys-new-horizons-announcements-innovations-and-news-recap/"><u>Navigating Sony's New Horizons : Announcements, Innovations, and News Recap</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-the-path-to-safer-communication-activate-your-kids-discord-safeguards/"><u>Navigating the Path to Safer Communication: Activate Your Kid's Discord Safeguards</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-the-pipe-worlds-a-selection-of-the-superior-six-mario-games-on-pc/"><u>Navigating the Pipe Worlds: A Selection of the Superior Six Mario Games on PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/newest-microsoft-windows-update-and-service-pack-releases-july-2024/"><u>Newest Microsoft Windows Update & Service Pack Releases - July 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/personalizing-your-gmail-experience-a-step-by-step-guide-to-creating-any-rule/"><u>Personalizing Your Gmail Experience: A Step-by-Step Guide to Creating Any Rule</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ps4-controller-glows-deciphering-the-meanings-behind-blue-white-red-and-orange-lights/"><u>PS4 Controller Glows: Deciphering the Meanings Behind Blue, White, Red, and Orange Lights</u></a></li>
<li><a href="https://os-tips.techidaily.com/revive-your-stuck-iphone-proven-strategies-to-overcome-power-issues/"><u>Revive Your Stuck iPhone: Proven Strategies to Overcome Power Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revolutionary-tech-evolutions-top-11-inventions-post-1844/"><u>Revolutionary Tech Evolutions: Top 11 Inventions Post-1844</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/secure-your-privacy-by-turning-off-no-caller-id-alerts-on-iphone/"><u>Secure Your Privacy by Turning Off 'No Caller ID' Alerts on iPhone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simple-steps-populating-your-samsung-smart-tv-with-various-applications/"><u>Simple Steps: Populating Your Samsung Smart TV with Various Applications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-booking-your-next-tech-support-session-with-apples-genius-bar/"><u>Step-by-Step Guide: Booking Your Next Tech Support Session with Apple's Genius Bar</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-solutions-to-tackle-and-prevent-windows-blue-screen-issues/"><u>Step-by-Step Solutions to Tackle and Prevent Windows Blue Screen Issues</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-guide-to-adding-time-markers-on-youtubes-for-2024/"><u>The Ultimate Guide to Adding Time Markers on YouTubes for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-5-free-online-sports-channels-for-watching-live-games/"><u>Top 5 Free Online Sports Channels for Watching Live Games</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-7-best-free-music-streaming-apps-on-iphone-and-android-devices/"><u>Top 7 Best Free Music Streaming Apps on iPhone & Android Devices</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transformative-technology-discover-6-new-avenues-with-chatgpts-code-conductor/"><u>Transformative Technology - Discover 6 New Avenues with ChatGPT's Code Conductor</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlock-the-full-potential-of-picture-in-picture-mode-on-android-devices/"><u>Unlock the Full Potential of Picture-in-Picture Mode on Android Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-free-access-a-guide-to-enjoying-netflix-at-no-charge/"><u>Unlocking Free Access: A Guide to Enjoying Netflix at No Charge</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unraveling-the-mechanics-behind-t-mobiles-wireless-regional-roaming-policy/"><u>Unraveling the Mechanics Behind T-Mobile's Wireless Regional Roaming Policy</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/watching-the-transformers-saga-from-start-to-finish-a-step-by-step-approach/"><u>Watching The Transformers Saga From Start to Finish: A Step-by-Step Approach</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/what-to-do-when-your-android-isnt-receiving-sms-fixes-and-tips/"><u>What to Do When Your Android Isn't Receiving SMS: Fixes and Tips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/why-cant-i-find-libxmllibxml2httpsenwikipediaorgwikilibxml-dll-solutions-inside/"><u>Why Can't I Find Libxml^[libxml2](https://en.wikipedia.org/wiki/LibXML) DLL? Solutions Inside</u></a></li>
</ul></div>
