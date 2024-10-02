---
title: Is Someone Secretly Following Me? How to Determine if an AirTag Has Been Attached – Digital Security Guide
date: 2024-09-24T22:06:00.047Z
updated: 2024-10-01T21:08:52.806Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/apple/    https://www.zdnet.com/a/img/resize/880d71fa9a1fdd249849ed863d3c4f08d746cf76/2024/07/18/f6d75cb0-a6bc-46b6-9903-1002418bef17/airtag-moving.jpg?width=170&height=96&fit=crop&auto=webp
---

## Guide to Setting Up Various Network Configurations in MacOS for Increased Flexibility and Reliability

![MacOS Ventura](https://www.zdnet.com/a/img/resize/f9b803b11abf24ef89a80e3eab2b456c1d35293a/2022/07/11/47775a46-83d9-4a0e-a1e0-bac36bb3c798/macos-ventura-apple-hero.jpg?auto=webp&width=1280)

Apple

I connect to a lot of different networks. At home, I have three different LANs to choose from, which I use depending on my needs. For example, I have a general-purpose network and one that I use for the deployment of containers and the like. 

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Switching to a different Network Location

After you've created all of the network locations you need, MacOS makes it very easy to switch between them. All you have to do is click the Apple menu > Location > \[Location name\] (select the name of the location you want to use).

Switching between network locations is a few mouse clicks away.

Image: Jack Wallen

And that's all there is to creating and using network locations in MacOS. If you need to get specific with how your MacOS device interacts with a network, this is a great way to go. Just remember, however, if you move from the current location, you'll want to select another. For example, if you have [one location for home and one for work](https://www.zdnet.com/article/hybrid-workers-dont-want-to-return-to-the-office-but-soon-they-might-have-to/), your machine might have trouble connecting to that work LAN with the home settings.

  
Fortunately, you are now empowered to more easily make that switch.

#### Jack Wallen: Here's how to...

[How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")

[The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")

[Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")

[Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

* [How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")
* [The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")
* [Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")
* [Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-mastering-hdr-portraiture-an-ultimate-guide/"><u>[New] 2024 Approved Mastering HDR Portraiture An Ultimate Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-expertly-selected-webcams-and-recording-software-in-win-10/"><u>[New] In 2024, Expertly Selected Webcams & Recording Software in Win 10</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-harness-free-software-to-broadcast-virtual-events/"><u>[New] In 2024, Harness Free Software to Broadcast Virtual Events</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-musical-mentorship-series-top-15-youtube-wisdom-from-pros/"><u>[Updated] Musical Mentorship Series - Top 15 YouTube Wisdom From Pros</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exclusive-insight-qualcomm-joins-forces-with-samsung-and-google-on-revolutionary-mixed-reality-glasses/"><u>Exclusive Insight: Qualcomm Joins Forces With Samsung & Google on Revolutionary Mixed Reality Glasses</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/frustrated-by-the-apple-vision-pro-virtual-keys-learn-how-to-switch-back-to-an-actual-hardware-keyboard-zdnet/"><u>Frustrated by the Apple Vision Pro Virtual Keys? Learn How to Switch Back to an Actual Hardware Keyboard | ZDNET</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-y27s-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y27s Phone without Google Account?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/innovative-strategies-for-iphoneipad-screenshots-in-media-for-2024/"><u>Innovative Strategies for iPhone/iPad Screenshots in Media for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-on-sending-back-your-apple-vision-pro-insights-from-zdnet/"><u>Step-by-Step Guide on Sending Back Your Apple Vision Pro - Insights From ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-eureka-encounter-how-apples-revolutionary-vision-pro-brought-its-video-to-life-on-my-screen-an-insightful-tale-from-zdnet/"><u>The Eureka Encounter: How Apple's Revolutionary Vision Pro Brought Its Video to Life on My Screen - An Insightful Tale From ZDNET</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-oneplus-11r-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any OnePlus 11R Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-apples-vision-pro-the-game-changing-concept-prototype-that-could-revolutionize-our-future/"><u>Unveiling Apple's Vision Pro: The Game-Changing Concept Prototype That Could Revolutionize Our Future</u></a></li>
<li><a href="https://common-error.techidaily.com/vcruntime140-dll-missing-start-your-windows-11-applications-effortlessly-comprehensive-fix-guide/"><u>VCRUNTIME140 DLL Missing? Start Your Windows 11 Applications Effortlessly – Comprehensive Fix Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/zdnet-explores-the-future-of-navigation-immersive-cities-revealed-through-googles-augmented-reality-on-maps/"><u>ZDNet Explores the Future of Navigation: Immersive Cities Revealed Through Google's Augmented Reality on Maps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/zdnet-highlights-meta-quest-3-the-unanticipated-leading-tech-device-of-2023/"><u>ZDNet Highlights Meta Quest 3: The Unanticipated Leading Tech Device of 2023</u></a></li>
</ul></div>

