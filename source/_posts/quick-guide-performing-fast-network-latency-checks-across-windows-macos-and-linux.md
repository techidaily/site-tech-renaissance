---
title: "Quick Guide: Performing Fast Network Latency Checks Across Windows, macOS & Linux"
date: 2024-08-30T14:39:28.757Z
updated: 2024-08-31T14:39:28.757Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a876d99fc810824e790e14200a363bc8a24888dbe0f9cb4aa8918882c26356a6.jpeg
---

## Quick Guide: Performing Fast Network Latency Checks Across Windows, macOS & Linux

### Quick Links

* [Run a Speed Test on Mac via Terminal](https://instagram-videos.techidaily.com/new-capture-and-replay-screen-recording-for-instagram-stories-for-2024/)
* [Run a Speed Test on Windows via Command Prompt](https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12-proplus-5g-fixed-drfone-by-drfone-virtual-android/)
* [Run a Speed Test on Linux via Terminal](https://games-able.techidaily.com/bring-back-those-good-old-days-why-your-game-needs-pi/)

 Internet speed test websites are often bogged down with ads, slowing down your system. Fortunately, Ookla offers a lightweight Command Line Interface (CLI) version of its speed test so you can test your internet speed without the overhead of a web browser. Here's how to use it on macOS, Windows, and Linux.

##  Run a Speed Test on Mac via Terminal

 To accomplish this on Mac, we will be using [Homebrew](https://visual-screen-recording.techidaily.com/new-breaking-ground-video-capture-breakdown-for-2024/), a [popular macOS package manager](https://screen-activity-recording.techidaily.com/updated-in-2024-virtualvista-viewers-verdict/). If you haven't installed Homebrew yet or if you are unsure, open Terminal (you'll find it under Applications > Utilities) and enter the following command:

        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    
 This command will download and install Homebrew. Once installed, you can easily install the speed test CLI by entering:

        `brew install speedtest-cli`
    
 After the installation is complete, you can run the speed test by simply typing:

        `speedtest-cli  
`
    
![Running speedtest cli in macOS Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-macos-terminal.png) 

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
##  Run a Speed Test on Linux via Terminal

 Linux users have a slightly different setup process, as the steps can vary depending on the distribution. Here, we'll cover the installation process for one of the [most widely used distributions](https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/): Debian/Ubuntu.

 First, open a Terminal window. Before installing the speed test CLI, you may need to install curl, a command-line tool for transferring data with URLs. If you're unsure whether curl is installed, you can install it by running:

        `sudo apt-get install curl`
    
 Next, add the Ookla repository to your list of package sources. This ensures that you get the latest version of the speed test CLI. Use the following command to do this:

        `curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash`
    
 Once the repository is added, you can install the speed test CLI with:

        `sudo apt-get install speedtest`
    
![Running Speedtest CLI on Ubuntu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-on-ubuntu-1.png) 

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
 After installation, you can test your internet speed by typing "speedtest" in the Terminal and pressing enter. This command will run the test and display the results directly in the window.

---

 Using Ookla's CLI speed test is an efficient way to measure your internet connection speed without the distractions and slowdowns caused by browser-based tools. No matter which OS you're using, this lightweight tool provides accurate and quick results. It's particularly useful when you want to avoid ads or need to integrate speed tests into automated systems or scripts.

 With just a few commands or a shortcut workflow, you can have a reliable tool at your disposal for monitoring and diagnosing your network performance, empowering you to run a network test at the drop of a hat or a hotkey.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-essential-guide-to-top-12-free-and-paid-gaming-introduction-creators/"><u>[New] 2024 Approved  Essential Guide to Top 12 Free and Paid Gaming Introduction Creators</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-essential-dos-and-donts-for-twilight-self-portraiture-for-2024/"><u>[New] Essential Do's and Don'ts for Twilight Self-Portraiture for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-export-ppt-as-animated-film/"><u>[New] In 2024, Export PPT as Animated Film</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-unlock-advanced-features-of-obs-studio-on-android-platforms-for-2024/"><u>[New] Unlock Advanced Features of OBS Studio on Android Platforms for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-building-on-your-content-a-guide-to-stellar-videography-closures/"><u>[Updated] 2024 Approved  Building on Your Content  A Guide to Stellar Videography Closures</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-with-polaroid-camplus-ultimate-action-footage/"><u>[Updated] Exploring with Polaroid Cam+  Ultimate Action Footage</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-step-by-step-audio-addition-for-impactful-instagram-visuals/"><u>2024 Approved  Step-by-Step Audio Addition for Impactful Instagram Visuals</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-about-at-home-electric-car-charging-what-you-should-know/"><u>All About At-Home Electric Car Charging - What You Should Know</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/android-tips-keeping-your-number-private-when-calling/"><u>Android Tips: Keeping Your Number Private When Calling</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/best-free-cad-programs-of-the-year-for-efficient-designing/"><u>Best Free CAD Programs of The Year for Efficient Designing</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-honor-magic-5-lite-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Honor Magic 5 Lite is off? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/detailed-analysis-of-snappy-driver-installer-v113/"><u>Detailed Analysis of Snappy Driver Installer V1.13</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discovering-if-theyve-seen-it-tips-on-knowing-if-your-sms-has-been-read/"><u>Discovering If They've Seen It: Tips on Knowing if Your SMS Has Been Read</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discovering-the-range-of-ipads-that-feature-internal-gps-capabilities/"><u>Discovering the Range of iPads That Feature Internal GPS Capabilities</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discovering-the-unique-identifier-of-your-macbook-effortlessly/"><u>Discovering the Unique Identifier of Your MacBook Effortlessly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/do-apple-allow-deleting-built-in-iphone-apps-and-how/"><u>Do Apple Allow Deleting Built-In iPhone Apps, and How?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-steps-for-installing-windows-10-onto-your-brand-new-hdd/"><u>Easy Steps for Installing Windows 10 Onto Your Brand-New HDD</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-steps-mirror-your-android-screen-on-the-firestick/"><u>Easy Steps: Mirror Your Android Screen on the Firestick</u></a></li>
<li><a href="https://some-approaches.techidaily.com/efficient-methods-to-clear-multiple-photos-at-once-on-an-iphone-plus/"><u>Efficient Methods to Clear Multiple Photos at Once on an iPhone (Plus)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/eliminate-your-tiktok-existence-a-detailed-deletion-walkthrough/"><u>Eliminate Your TikTok Existence: A Detailed Deletion Walkthrough</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-trends-in-tech-you-cant-afford-to-ignore-insights-for-the-wise/"><u>Essential Trends in Tech You Can't Afford to Ignore – Insights for the Wise</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-fixing-401-errors-to-restore-secure-website-access/"><u>Expert Advice: Fixing 401 Errors to Restore Secure Website Access</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-techniques-to-remove-accessories-from-your-google-home-setup/"><u>Expert Techniques to Remove Accessories From Your Google Home Setup</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-tips-for-repairing-wi-fi-connectivity-problems-in-surface-pro-devices/"><u>Expert Tips for Repairing Wi-Fi Connectivity Problems in Surface Pro Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/google-hangouts-decoded-a-comprehensive-overview-of-its-features-and-history/"><u>Google Hangouts Decoded: A Comprehensive Overview of Its Features & History</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-how-to-address-and-repair-missing-d3dx934dll-errors-on-your-pc/"><u>Guide: How To Address and Repair 'Missing d3dx9_34.dll' Errors on Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-clean-up-your-mac-by-eliminating-unnecessary-programs/"><u>How to Clean Up Your Mac by Eliminating Unnecessary Programs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-clear-all-liked-music-from-your-spotify-account-step-by-step/"><u>How To Clear All Liked Music From Your Spotify Account Step-By-Step</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/inside-the-blue-screen-unpacking-the-meaning-and-causes-of-bsod/"><u>Inside the Blue Screen: Unpacking the Meaning and Causes of BSOD</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722901741879-laptop-leaps-phone-flips-book-wonders-embracing-the-modern-day-library/"><u>Laptop Leaps, Phone Flips, Book Wonders - Embracing the Modern-Day Library</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-art-of-discovering-individual-email-identifiers-securely/"><u>Mastering the Art of Discovering Individual Email Identifiers Securely</u></a></li>
<li><a href="https://techidaily.com/remove-itel-s23plus-unlock-screen-by-drfone-android-unlock-android-unlock/"><u>Remove Itel S23+ unlock screen</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solve-no-call-dilemma-restoring-calling-functions-on-android-phones/"><u>Solve No-Call Dilemma: Restoring Calling Functions on Android Phones</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solving-the-d3dx941dll-file-not-detected-issue-a-step-by-step-guide/"><u>Solving the d3dx9_41.dll File Not Detected Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-to-overcome-issues-with-your-instagram-stories/"><u>Step-by-Step Guide to Overcome Issues With Your Instagram Stories</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-downloading-and-watching-fandango-movies-from-your-couch-with-amazon-fire-tv/"><u>Step-by-Step Guide: Downloading and Watching Fandango Movies From Your Couch with Amazon Fire TV</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-basics-of-net-neutrality-made-easy-for-everyone/"><u>The Basics of Net Neutrality Made Easy for Everyone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-tutorial-on-spotting-individuals-viewing-your-youtube-clips/"><u>The Ultimate Tutorial on Spotting Individuals Viewing Your YouTube Clips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-and-resolving-gsdll32dll-could-not-be-found-issues-on-your-pc/"><u>Troubleshooting and Resolving 'gSdll32.dll' Could Not Be Found Issues on Your PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-your-iphone-why-it-wont-ring-and-how-to-fix-it/"><u>Troubleshooting Your iPhone: Why It Won't Ring and How to Fix It</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-secrets-price-features-and-rumored-debut-date-for-the-new-samsung-galaxy-z-flip-7/"><u>Unlocking Secrets: Price, Features, and Rumored Debut Date for the New Samsung Galaxy Z Flip 7</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-the-secrets-of-viral-success-on-tiktok-a-guide-with-10-proven-steps/"><u>Unlocking the Secrets of Viral Success on TikTok: A Guide with 10 Proven Steps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-our-picks-the-six-greatest-nutrition-tracking-apps/"><u>Unveiling Our Picks: The ˈSix Greatest Nutrition Tracking Apps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722879675006-waterlogged-woes-be-gone-testing-the-waterproof-claims-for-iphone-15-pro-max/"><u>Waterlogged Woes Be Gone? Testing the Waterproof Claims for iPhone 15 Pro Max.</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/what-are-streaming-devices-and-how-do-they-work/"><u>What Are Streaming Devices and How Do They Work?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/why-are-we-switching-gears-insights-on-embracing-electric-mobility/"><u>Why Are We Switching Gears? Insights on Embracing Electric Mobility</u></a></li>
</ul></div>
