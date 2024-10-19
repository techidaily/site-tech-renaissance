---
title: Effective Strategies for Crafting Personalized Do Not Disturb Settings on macOS Monterey
date: 2024-10-16T12:27:36.765Z
updated: 2024-10-19T12:56:13.025Z
tags:
  - apple
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/efe0186bb4efbb8b153d97138dfec7129db0c940/2022/01/26/b1e03c55-97b4-4a27-8fb3-7424ca187964/shutterstock-1799864374.jpg?width=278&height=156&fit=crop&auto=webp
---

## Two Effective Methods for Updating Applications on macOS Explained

![fullscreen-1-4-24-7-23pm](https://www.zdnet.com/a/img/resize/4d0754ca50eca284946b9049b2a02512354bb4c1/2024/01/05/f413ba01-74e1-4edb-8d1e-41b8aa539d45/fullscreen-1-4-24-7-23pm.jpg?auto=webp&width=1280)

Screen Sharing on MacOS Sonoma

Jason Perlow/ZDNET

Any time I see updates available for my MacOS machines, I immediately apply them. Why? Because those updates often contain security patches that keep my computers safe. Those updates might also contain new features for apps or performance and reliability improvements. Either way, I find these updates to be an essential part of [maintaining the security of my devices](https://www.zdnet.com/article/how-to-update-every-apple-device/) and keeping my mind at ease.

**Also: [How I purged over 175GB of files from my Mac in under a minute (and you can too)](https://www.zdnet.com/article/how-i-purged-over-175gb-of-files-from-my-mac-in-under-a-minute/)**

When I go to update a MacOS device, I know there's more than one way to approach the task -- from the App Store (via the MacOS GUI) or from the command line. Because I've spent decades [working with Linux](https://www.zdnet.com/article/thinking-about-switching-to-linux-things-you-need-to-know/), I'm 100% comfortable using the command line, so I will sometimes open the terminal app, check for upgrades, and then run them when they're available. Or, if I'm feeling a bit lazy, I'll just go the App Store route.

Let me show you both approaches.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to update MacOS apps from the App Store

**What you'll need:** The only things you'll need are an Apple device (a MacBook or iMac) and a valid user account on the machine. That's it. Let's get to the updates.

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open the App Store

The fastest way to check and see if there are any updates available is by clicking the Apple button in the upper-left corner, where you might see something like _2 updates_ listed (indicating you have two apps that have updates available). Click that entry to open the App Store.

I have two available updates on my MacBook Pro.

Screenshot by Jack Wallen/ZDNET

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080342/19272" target="_top" id="2080342">
  <img src="//a.impactradius-go.com/display-ad/19272-2080342" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080342/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Update your apps

When the App Store opens, you can either update the apps individually (by clicking the Update button associated with the app in question) or update them all at once (by clicking Update All). During the update process, you might be prompted to close an app (or even a related app) if it's blocking the update from continuing. Should that be the case, close the app in question, return to the App Store, and click Continue from the pop-up warning.

These two apps on my MacBook Pro have pending updates.

Screenshot by Jack Wallen/ZDNET

Once the update is completed, close the App Store and you're done.

## How to update MacOS apps from the command line

This is a bit more complicated, for two reasons: first, you have to find out what apps are available for updating, and, second -- as with Linux -- the app names are case-sensitive.

## 1\. Open the Terminal app

To run commands, you must first open the terminal app, which can be done from the Launchpad. Click the Launchpad icon in your Dock and then type _terminal_. Click the launcher to open the Terminal app.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Check for available updates

Next, you need to run the command to check for updates. The command in question is _softwareupdate_ and is used for both checking and running the updates. To check for available updates, issue the command:

sudo softwareupdate -l

You will be prompted for your sudo password (which is your MacOS user password). 

**Also: [How to update every Apple device (iPhone, iPad, Apple Watch, Mac, more)](https://www.zdnet.com/article/how-to-update-every-apple-device/)**

The -l option stands for _list_. This will print out any available app updates and, if required, it will inform you if a restart is needed to complete any recent OS updates. If you see such a warning, make sure to do the reboot to complete the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Update the apps

Let's say the command lists that Apple Mail has an update available, which should be listed as _Mail_ (remember, case sensitivity). Before you update the app, make sure to close it first. Once closed, update the app with a command like this:

sudo softwareupdate -i Mail

After successfully typing your sudo password, the update will proceed. When the update completes, you may or may not have to restart the machine. (You will be informed if a reboot is necessary.) You can then re-open the app you just updated and enjoy whatever fresh features or security patches the update applied.

**Also: [The Apple products you shouldn't buy this month](https://www.zdnet.com/article/the-apple-products-you-shouldnt-buy-this-month/)** 

This is about as simple a method as you'll find to help keep your MacOS machines running smoothly and securely. Never leave an app update lingering because it often contains security patches, which are required for the health and well-being of your operating system.

#### Apple

[iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")

[My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")

[We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")

[6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

* [iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")
* [My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")
* [We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")
* [6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

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
<li><a href="https://fox-boxes.techidaily.com/new-prime-landscapes-for-streaming-success/"><u>[New] Prime Landscapes for Streaming Success</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-revamp-your-tone-7-premier-vocal-modification-tools/"><u>[Updated] Revamp Your Tone 7 Premier Vocal Modification Tools</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-spectrum-savvy-the-filmmakers-guide-to-color-for-2024/"><u>[Updated] Spectrum Savvy The Filmmaker's Guide to Color for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/15-best-gopro-alternatives-for-all-your-needs/"><u>15 Best GoPro Alternatives for All Your Needs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/a-step-by-step-approach-to-strengthen-digital-television-signal-in-your-living-room/"><u>A Step-by-Step Approach to Strengthen Digital Television Signal in Your Living Room</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/code-43-bug-fixes-advanced-techniques-for-developers/"><u>Code 43 Bug Fixes: Advanced Techniques for Developers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decode-and-repair-expert-strategies-to-tackle-code-28-failures/"><u>Decode and Repair: Expert Strategies to Tackle Code 28 Failures</u></a></li>
<li><a href="https://some-techniques.techidaily.com/easy-steps-to-rename-your-files-with-windows-powershell-tools/"><u>Easy Steps to Rename Your Files with Windows PowerShell Tools</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-to-follow-techniques-and-strategies-for-beginners-in-pokemon-go/"><u>Easy-to-Follow Techniques and Strategies for Beginners in 'Pokémon Go'</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/effortless-image-retrieval-from-facebook-expert-seo-strategies-for-flawless-results/"><u>Effortless Image Retrieval From Facebook – Expert SEO Strategies for Flawless Results</u></a></li>
<li><a href="https://tech-revival.techidaily.com/elite-athletes-prompts-for-ai-engagement/"><u>Elite Athletes' Prompts for AI Engagement</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/handling-the-disappearing-act-of-openalamo32dll-on-your-pc/"><u>Handling the Disappearing Act of openalamo32.dll on Your PC</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-realme-c33-2023-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Realme C33 2023 Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-retrieve-lost-instagram-reels-the-ultimate-walkthrough/"><u>How To Retrieve Lost Instagram Reels – The Ultimate Walkthrough</u></a></li>
<li><a href="https://win-forum.techidaily.com/optimize-window-11-launch-times-with-these-expert-system-tweaks/"><u>Optimize Window 11 Launch Times with These Expert System Tweaks</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-compatibility-problems-with-input-devices-and-screens/"><u>Overcoming Compatibility Problems with Input Devices and Screens</u></a></li>
<li><a href="https://extra-information.techidaily.com/simple-guide-turning-favorite-tiktok-beats-into-cellphone-signals/"><u>Simple Guide Turning Favorite TikTok Beats Into Cellphone Signals</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-complete-tutorial-for-mac-managing-and-opening-rar-compressed-files/"><u>The Complete Tutorial for Mac: Managing & Opening RAR Compressed Files</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-5-must-try-video-editing-tools-for-stunning-visual-creations/"><u>Top 5 Must-Try Video Editing Tools for Stunning Visual Creations</u></a></li>
</ul></div>

