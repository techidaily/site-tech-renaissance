---
title: "Personalizing the MacOS Sonoma Menu Bar: A Step-by-Step Guide to Customization & Organization"
date: 2024-09-25T07:50:23.039Z
updated: 2024-10-02T07:23:58.581Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a6017269d4c04c5e1e1b5dd34c08e1f92a0a41c1ec409bdbe7a0807e99cdc6f4.jpg
---

## Mastering Cross-Platform Use: A Step-by-Step Guide to Running Linux on Xcode with an Ingenious Hack  Exclusive

![xcode-download](https://www.zdnet.com/a/img/resize/72daf9c10a8cbb72018f54fd48d893e5c1fdc697/2024/02/20/72eff26e-8b49-4c53-8f95-e123371d2227/xcode-download.jpg?auto=webp&width=1280)

Screenshot by David Gewirtz/ZDNET

So, you want to install Linux on a Mac? Well, there's more than one way to get that done. Compared to what I'm going to show you below, there's a somewhat easier set of steps that my colleague [Adrian Kingsley-Hughes ran through](https://www.zdnet.com/article/how-to-install-kali-linux-on-apple-silicon-macs/) using an installer on the App Store and Kali Linux.

**Also: [How to install Ubuntu Linux (It's easy!)](https://www.zdnet.com/article/how-to-install-ubuntu-linux/)**

But I'm going full geek. Together, we're going to use Xcode and build our own sample app, which we'll then use to install the full distribution of the [latest Ubuntu release](https://www.zdnet.com/article/ubuntu-desktop-23-10-arrives-a-glimpse-into-ubuntu-linuxs-future/), Noble Numbat.

Once you've done this, you will have considerable bragging rights. There's a lot to cover, so let's dig in. 

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

##  Download these first

You'll need to download these items before you get started setting up Linux: 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

**Xcode:** You will need to download and install Xcode from the Mac App Store. Xcode is the primary development environment Apple wants developers to use to build Mac applications and mobile apps. It's free. Just open the App Store app and type "xcode" into the search field.

**The latest build of Ubuntu, for 64-bit Arm:** The Arm installer ISO isn't located on the main Ubuntu download site. Instead, point your browser to the [daily build page](https://cdimage.ubuntu.com/daily-live/current/) and scroll down until you see the desktop image for 64-bit ARM (standard download).

Screenshot by David Gewirtz/ZDNET

**GUILinuxVirtualMachineSampleApp:** [This is a sample app](https://developer.apple.com/documentation/virtualization/running%5Fgui%5Flinux%5Fin%5Fa%5Fvirtual%5Fmachine%5Fon%5Fa%5Fmac) that runs the virtual machine inside of Xcode. You'll need to download it and unzip it. 

Screenshot by David Gewirtz/ZDNET

Before you move on to the next step, be sure that Xcode is fully installed, that you have the Ubuntu .iso file, and that you have downloaded and unzipped the sample app. 

**Also: [Ubuntu Desktop 23.10 arrives: A glimpse into Ubuntu Linux's future](https://www.zdnet.com/article/ubuntu-desktop-23-10-arrives-a-glimpse-into-ubuntu-linuxs-future/)**

Once all of that is done, we can move on. 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Configure the VM hosting app in Xcode

Go ahead and open Xcode. You'll see a starter screen. Tell it to open up an existing project. 

Screenshot by David Gewirtz/ZDNET

From here, navigate inside the folder you created when you extracted the sample application, and look for a file ending in .xcodeproj. Click open. 

Screenshot by David Gewirtz/ZDNET

This will open the sample application. Well, actually, it will warn you that you're opening a project downloaded from the Internet. But since the project comes right off the Apple developer site, I think you're good. 

Screenshot by David Gewirtz/ZDNET

Now, you'll have the project open. You need to do a bit of housekeeping, and then you'll be good. 

In the left-most pane, click the top-level sample app (shown at 1). Then, click the Signing & Capabilities tab (shown at 2), and finally, click the Add Account button at the Team prompt (shown at 3). 

Screenshot by David Gewirtz/ZDNET

This will take you to your Accounts tab, where you'll just set yourself up as a team. 

Screenshot by David Gewirtz/ZDNET

Once you've done this, close the window, and you'll be ready to move on. Here, you can see my app is going to be signed by my personal account. This just tells MacOS that it's my app and I want to allow it to run.

Screenshot by David Gewirtz/ZDNET

You're ready to start running the VM. Hit the little arrow to build and run. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Installing Ubuntu

Your Xcode app will open a blank black window and a file chooser. The file chooser (although it doesn't tell you this) is looking for the Ubuntu install .iso file. So navigate to that .iso, click it, and click Open. 

Screenshot by David Gewirtz/ZDNET

Next, GRUB (Grand Unified Bootloader) will show up in that black window. Select Try or Install Ubuntu and hit Enter. 

Screenshot by David Gewirtz/ZDNET

And let the magic commence! Ubuntu is getting settled into your Xcode app: 

Screenshot by David Gewirtz/ZDNET

And here you go. Start configuring your Ubuntu install. 

Screenshot by David Gewirtz/ZDNET

Go ahead and select Install Ubuntu since you're already installing into a VM and not directly onto your computer anyway. 

Screenshot by David Gewirtz/ZDNET

I did the full installation: 

Screenshot by David Gewirtz/ZDNET

**Also: [Fedora Linux now runs on all M-powered Macs - except one](https://www.zdnet.com/article/fedora-linux-now-runs-on-all-m-powered-macs-except-one/)**

Use the default, which is to allow the installer to erase the virtual disk and set up your virtual filesystem: 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Run Ubuntu

Ubuntu is ready to run. Just click Restart Now and go to town. 

Screenshot by David Gewirtz/ZDNET

Once you restart, you'll be in a standard environment, with a nice little virtual machine you can play with. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105866/7443" target="_top" id="2105866">
  <img src="//a.impactradius-go.com/display-ad/7443-2105866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Final thoughts

During the installation phase, the Virtualization framework generates a GUI Linux VM.bundle package within your home folder. This grows fairly quickly, so if you're space-constrained, you may want to delete it when you're done Ubuntuing. Mine is 68.72GB after only a few hours of tinkering. 

**Also: [Ubuntu 23.10 seems like the usual boring update - until you dig into it](https://www.zdnet.com/article/ubuntu-23-10-seems-like-the-usual-boring-update-until-you-dig-in/)**

While the example application is limited to operating a single VM concurrently, the MacOS virtualization framework itself is capable of handling several VMs at the same time. This is not controlled by the application we built, but developers can use this framework to build more powerful virtualization management consoles. 

What do you think? Did you go ahead and install Ubuntu inside Xcode? Are you going to tattoo "Ubuntu/Xcode Forever" on your shoulder? Are you going to sing glorious songs of your Xcode prowess to all who will listen? I mean, you could. If you're not going to belt out songs of Macs and Linux, perhaps you could leave us a few comments below. 

---

_You can follow my day-to-day project updates on social media. Be sure to subscribe to my weekly update newsletter [on Substack](https://advancedgeekery.substack.com/), and follow me on Twitter at [@DavidGewirtz](https://twitter.com/davidgewirtz), on Facebook at [Facebook.com/DavidGewirtz](https://www.facebook.com/davidgewirtz), on Instagram at [Instagram.com/DavidGewirtz](https://www.instagram.com/DavidGewirtz/), and on YouTube at [YouTube.com/DavidGewirtzTV](https://www.youtube.com/user/DavidGewirtzTV)._

#### Linux

[The best Linux laptops for consumers and developers](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops for consumers and developers")

[Want to save your aging computer? Try these 5 Linux distributions](https://www.zdnet.com/article/want-to-save-your-old-computer-try-these-5-linux-distributions/ "Want to save your aging computer? Try these 5 Linux distributions")

[The best distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best distros for beginners")

[How to enable Linux on your Chromebook (and why you should)](https://www.zdnet.com/article/how-to-enable-linux-on-your-chromebook-and-why-you-should/ "How to enable Linux on your Chromebook (and why you should)")

* [The best Linux laptops for consumers and developers](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops for consumers and developers")
* [Want to save your aging computer? Try these 5 Linux distributions](https://www.zdnet.com/article/want-to-save-your-old-computer-try-these-5-linux-distributions/ "Want to save your aging computer? Try these 5 Linux distributions")
* [The best distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best distros for beginners")
* [How to enable Linux on your Chromebook (and why you should)](https://www.zdnet.com/article/how-to-enable-linux-on-your-chromebook-and-why-you-should/ "How to enable Linux on your Chromebook (and why you should)")

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
<li><a href="https://fox-cloud.techidaily.com/new-dive-into-quality-tips-for-shooting-crystal-clear-gopro-video-below-the-surface/"><u>[New] Dive Into Quality Tips for Shooting Crystal Clear GoPro Video Below the Surface</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-flv-to-youtubes-master-the-art-of-video-transformation-with-these-top-tools-for-2024/"><u>[Updated] Flv to Youtubes Master the Art of Video Transformation with These Top Tools for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-exclusive-guide-to-affordable-premium-video-editors/"><u>[Updated] In 2024, Exclusive Guide to Affordable, Premium Video Editors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/mp4-72024/"><u>【無料ガイド】MP4 ファイルを超えた圧縮方法の達人7選【2024年新春特大版】</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-editing-magic-transformative-strategies-for-youtube-creators/"><u>2024 Approved Editing Magic Transformative Strategies for YouTube Creators</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-choices-for-action-camera-gear-in-202-groovy-year-expert-insights-from-zdnet/"><u>Discover the Ultimate Choices for Action Camera Gear in 202 Groovy Year – Expert Insights From ZDNET</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-selection-of-zero-emission-fire-pits-for-2ebutry-your-outdoor-space/"><u>Discover the Ultimate Selection of Zero Emission Fire Pits for 2Ebutry Your Outdoor Space</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-ultimate-solar-charger-rankings-on-zdnet-the-top-picks/"><u>Discover the Ultimate Solar Charger Rankings on ZDNET: The Top Picks</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-guide-crafting-your-own-camera-obscura-for-safe-solar-eclipse-viewing-tips-and-tricks/"><u>DIY Guide: Crafting Your Own Camera Obscura for Safe Solar Eclipse Viewing – Tips & Tricks</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/durability-and-water-resistance/"><u>Durability & Water Resistance</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/eufycam-2c-pro-security-camera-bundle-substantial-discounts-of-38-off-available-now/"><u>EufyCam 2C Pro Security Camera Bundle - Substantial Discounts of $38 Off Available Now!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exclusive-ge-cync-offer-save-up-to-61-on-innovative-lighting-and-controls-smart-devices-galore/"><u>Exclusive GE Cync Offer: Save Up to 61% on Innovative Lighting & Controls - Smart Devices Galore!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/experience-the-spectacular-april-2024-solar-eclipse-comprehensive-guide-on-how-to-watch-safely-and-what-equipment-youll-require-digitalobserver/"><u>Experience the Spectacular April 2024 Solar Eclipse - Comprehensive Guide on How to Watch Safely and What Equipment You'll Require | DigitalObserver</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-the-ultimate-selection-the-5-highest-quality-no-smoke-fire-pits-of-20212022-according-to-zdnet/"><u>Explore the Ultimate Selection: The 5 Highest Quality No-Smoke Fire Pits of 2021/2022 According to ZDNET</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-crafting-characters-and-settings/"><u>In 2024, Crafting Characters and Settings</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-secret-sauce-for-a-viral-tiktok-unboxer-masterpiece/"><u>In 2024, The Secret Sauce for a Viral TikTok Unboxer Masterpiece</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-overcoming-persistent-crashes-of-fuser-in-windows-environment/"><u>Troubleshooting: Overcoming Persistent Crashes of Fuser in Windows Environment</u></a></li>
<li><a href="https://win-help.techidaily.com/what-you-need-to-know-microsoft-announces-paid-pricing-plan-for-windows-11-updates-cost-breakdown/"><u>What You Need To Know: Microsoft Announces Paid Pricing Plan For Windows 11 Updates - Cost Breakdown</u></a></li>
</ul></div>

