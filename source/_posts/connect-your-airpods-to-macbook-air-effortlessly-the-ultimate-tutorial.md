---
title: Connect Your AirPods to MacBook Air Effortlessly – The Ultimate Tutorial
date: 2024-08-12T03:42:48.240Z
updated: 2024-08-13T03:42:48.240Z
categories:
  - BestProducts
description: This Article Describes Connect Your AirPods to MacBook Air Effortlessly – The Ultimate Tutorial
excerpt: This Article Describes Connect Your AirPods to MacBook Air Effortlessly – The Ultimate Tutorial
thumbnail: https://www.lifewire.com/thmb/iM4HZrQoKiP6qJ_hXe5JcveVDoI=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/connect-airpods-macbook-e53c14e8ed7045db8f15117619da9bac.jpg
---

## Mac Users Rejoice: How to Reset Your DNS Records Effortlessly
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
### What to Know

* You can delete the DNS cache through Terminal. Press**Command** +**Space** to search for it.
* Enter this flush DNS command: **sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder**
* El Capitan and older Mac OS X systems use different commands to clear DNS.

 This article explains how to delete the[DNS cache](https://www.lifewire.com/what-is-a-dns-cache-817514) on a Mac.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Use the macOS Flush DNS Command

 If you’re experiencing internet connectivity issues, you may be able to fix them by resetting the[DNS](https://www.lifewire.com/what-is-dns-domain-name-system-2625855) cache with a[Terminal command](https://www.lifewire.com/mac-terminal-commands-4774997) . It should only take a few moments.  

1. [Open Terminal](https://www.lifewire.com/macos-terminal-4774149) . One quick way is to press**Command** +**Space** to launch[Spotlight](https://www.lifewire.com/use-spotlight-mac-4586951) . Then, type**Terminal** and select it from the results.  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
![Terminal highlighted in Spotlight on a Mac.](https://www.lifewire.com/thmb/QGngs7Naa2bQVtWQWVaRG0K34yc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Terminal-6e4ba7528a4c4220a28542f84f214676.jpg)  
 You can also access Terminal by navigating to**Go** \>**Utilities** \>**Terminal** .
2. Type (or[copy and paste](https://www.lifewire.com/cut-copy-paste-on-mac-4427671) ) this command into Terminal and then press**Enter** :  
 `sudo dscacheutil -flushcache; sudo killall -HUP mDNSResponder`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![Command highlighted in Terminal window](https://www.lifewire.com/thmb/S2U8vSx5U_PgZI2ZZR_uTWdGHcw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Command-e05651de1b2f44e7b99903d8f00910f5.jpg)  
 This command only works in[macOS](https://www.lifewire.com/what-is-macos-4691239) 10.12 Sierra and newer. If you have an older version, check the next section for the correct command.
3. Type your password and then press**return** . The DNS cache will be reset immediately, but there will be no message to that effect. When a new line appears, it indicates the command has been carried out.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/n-2024-youtubes-non-indexable-content-decoding-the-unlisted-phenomenon/"><u>[New] In 2024, YouTube's Non-Indexable Content  Decoding the Unlisted Phenomenon</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-mastery-in-gameye-advanced-recording-tips-for-2024/"><u>[New] Mastery in GamEye  Advanced Recording Tips for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-unveiling-the-leading-mac-speech-recorders-our-curated-list-of-5/"><u>[Updated] 2024 Approved  Unveiling The Leading Mac Speech Recorders  Our Curated List of 5</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-exploring-the-dynamics-of-canon-timelapse-imagery/"><u>2024 Approved  Exploring the Dynamics of Canon Timelapse Imagery</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-optimal-record-solution-chromebook-edition/"><u>2024 Approved  Optimal Record Solution  Chromebook Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-renewed-evaluation-sonys-s3700-video-tech-in-2-point-five-six/"><u>2024 Approved  Renewed Evaluation  Sony's S3700 Video Tech in 2 Point-Five Six</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-seamlessly-sharing-your-style-macootd-tiktoks/"><u>2024 Approved  Seamlessly Sharing Your Style  MacOOTD TikToks</u></a></li>
<li><a href="https://fox-info.techidaily.com/comprehensive-guide-to-srgb-and-rgb/"><u>Comprehensive Guide to Srgb & Rgb</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/duo-display-wizardry-easily-expand-your-workspace-with-two-screens-on-macos/"><u>Duo Display Wizardry: Easily Expand Your Workspace with Two Screens on macOS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/elevate-your-playstation-5-gaming-with-high-fidelity-graphics-at-120-fps-how-to-optimize-settings-for-ultimate-smoothness/"><u>Elevate Your PlayStation 5 Gaming with High-Fidelity Graphics at 120 FPS - How to Optimize Settings for Ultimate Smoothness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-with-these-top-6-android-apps/"><u>Elevate Your Windows 11 with These Top 6 Android Apps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-for-resetting-the-new-generation-of-iphones-the-xs/"><u>Expert Tips for Resetting the New Generation of iPhones - The XS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/get-ready-for-game-day-essential-tips-for-a-perfect-tvhome-theater-setup-during-super-bowl-festivities/"><u>Get Ready for Game Day: Essential Tips for a Perfect TV/Home Theater Setup During Super Bowl Festivities</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-successfully-integrating-automatic-chatbots-into-your-discord-community/"><u>Guide: Successfully Integrating Automatic Chatbots Into Your Discord Community</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-enjoy-apple-tv-services-using-your-amazon-firestick-a-detailed-tutorial/"><u>How to Enjoy Apple TV Services Using Your Amazon Firestick - A Detailed Tutorial</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-maintain-consistent-mouse-delta-values-and-eliminate-acceleration-on-your-mac-device/"><u>How To Maintain Consistent Mouse Delta Values and Eliminate Acceleration on Your Mac Device</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-make-your-videos-trend-on-tiktok-a-10-step-method/"><u>How to Make Your Videos Trend on TikTok: A 10-Step Method</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-6-plus-passcode-without-computer-drfone-by-drfone-ios/"><u>How to Unlock iPhone 6 Plus Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y27-4g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Vivo Y27 4G Phone with Broken Screen</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-lava-blaze-2-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Lava Blaze 2 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-romantic-gestures-how-to-make-a-stunning-valentines-day-video-for-your-partner/"><u>In 2024, Romantic Gestures How to Make a Stunning Valentines Day Video for Your Partner</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-art-of-gmail-pseudonyms-a-detailed-tutorial/"><u>Mastering the Art of Gmail Pseudonyms: A Detailed Tutorial</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/maximize-battery-life-and-speed-a-user-friendly-guide-to-clearing-your-androids-cache/"><u>Maximize Battery Life and Speed: A User-Friendly Guide to Clearing Your Android's Cache</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigate-to-nearest-ev-charge-stations-using-google-maps-key-tips-and-tricks/"><u>Navigate to Nearest EV Charge Stations Using Google Maps: Key Tips & Tricks</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/no-charger-no-problem-techniques-for-phone-battery-refresh/"><u>No Charger? No Problem! Techniques for Phone Battery Refresh</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revamp-your-music-library-a-comprehensive-guide-to-clear-likes-in-spotify/"><u>Revamp Your Music Library: A Comprehensive Guide to Clear Likes in Spotify</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-reconfiguring-your-macos-network-preferences/"><u>Step-by-Step Guide: Reconfiguring Your macOS Network Preferences</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-for-engaging-in-dialogue-via-mozilla-thunderbird/"><u>Step-by-Step Instructions for Engaging in Dialogue via Mozilla Thunderbird</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tutorial-on-active-involvement-in-x-twitter-conversations/"><u>Step-by-Step Tutorial on Active Involvement in X Twitter Conversations</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/syncing-your-mobile-number-to-all-your-electronics-for-seamless-connectivity/"><u>Syncing Your Mobile Number to All Your Electronics for Seamless Connectivity</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-impact-and-promise-of-ai-in-shaping-tomorrow/"><u>The Impact and Promise of AI in Shaping Tomorrow</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-picks-top-6-food-diary-and-tracker-apps-reviewed/"><u>The Ultimate Picks: Top 6 Food Diary and Tracker Apps Reviewed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-ipad-bargains-waiting-for-you-today/"><u>Top-Rated iPad Bargains Waiting for You Today</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-apple-watch-connectivity-solving-unresponsive-pairing-issues/"><u>Troubleshooting Apple Watch Connectivity: Solving Unresponsive Pairing Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unmatched-quality-tested-the-fugetek-ft-568-selfie-stick-review/"><u>Unmatched Quality Tested: The Fugetek FT-568 Selfie Stick Review</u></a></li>
</ul></div>
