---
title: "Step-by-Step Tutorial: Securely Storing Your DL in iPhone Wallet, Depending on Location | ZDNET Tech Insights"
date: 2024-11-12T17:44:11.834Z
updated: 2024-11-15T21:19:26.595Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8ad1313081653043389b0ec9ab2777fbe6983525a9b9183de9916f4cf1facd61.jpg
---

## Integrating Ubuntu Into macOS: A Step-by-Step Tutorial for Combining Linux and Xcode in One Smart Trick  Insights

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2047361/19272" target="_top" id="2047361">
  <img src="//a.impactradius-go.com/display-ad/19272-2047361" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047361/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Run Ubuntu

Ubuntu is ready to run. Just click Restart Now and go to town. 

Screenshot by David Gewirtz/ZDNET

Once you restart, you'll be in a standard environment, with a nice little virtual machine you can play with. 

Screenshot by David Gewirtz/ZDNET

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-hints.techidaily.com/updated-advanced-dynamic-typographic-options/"><u>[Updated] Advanced Dynamic Typographic Options</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-samsung-galaxy-s23-fe-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Samsung Galaxy S23 FE by Name | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/an-in-depth-review-of-verizons-implementation-and-progress-in-5g-technology/"><u>An In-Depth Review of Verizon's Implementation and Progress in 5G Technology</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Realme 11X 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-get-your-favorite-vk-songs-without-paying-three-trustworthy-free-download-options/"><u>How to Get Your Favorite VK Songs Without Paying: Three Trustworthy Free Download Options</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-google-pixel-8-pro-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Google Pixel 8 Pro without App | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-avoid-lag-and-enhance-engagement-mastering-xboxs-zooming-features/"><u>In 2024, Avoid Lag & Enhance Engagement Mastering Xbox's Zooming Features</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/performance-analysis-and-insights-on-the-evga-supernova-85nv-gaming-psu-gen-7-review/"><u>Performance Analysis and Insights on the EVGA SuperNova 85Nv Gaming PSU (Gen 7) Review</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/secure-your-apple-watch-s9-for-record-savings-before-the-special-promo-expires-shop-smart-today/"><u>Secure Your Apple Watch S9 for Record Savings Before the Special Promo Expires - Shop Smart Today!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-iphone-16-and-iphone-16-pro-protective-covers-reviewed-by-professionals/"><u>Top-Rated iPhone 16 & iPhone 16 Pro Protective Covers - Reviewed by Professionals</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-lifespan-of-your-apple-watch-battery-unexpected-insights-revealed-zdnet/"><u>Unveiling the Lifespan of Your Apple Watch Battery: Unexpected Insights Revealed | ZDNet</u></a></li>
</ul></div>

