---
title: "Quick Guide: Performing Fast Network Latency Checks Across Windows, macOS & Linux"
date: 2024-12-15T10:43:59.925Z
updated: 2024-12-16T18:05:48.505Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a876d99fc810824e790e14200a363bc8a24888dbe0f9cb4aa8918882c26356a6.jpeg
---

## Quick Guide: Performing Fast Network Latency Checks Across Windows, macOS & Linux

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Run a Speed Test on Mac via Terminal](https://instagram-videos.techidaily.com/new-capture-and-replay-screen-recording-for-instagram-stories-for-2024/)
* [Run a Speed Test on Windows via Command Prompt](https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12-proplus-5g-fixed-drfone-by-drfone-virtual-android/)
* [Run a Speed Test on Linux via Terminal](https://games-able.techidaily.com/bring-back-those-good-old-days-why-your-game-needs-pi/)

 Internet speed test websites are often bogged down with ads, slowing down your system. Fortunately, Ookla offers a lightweight Command Line Interface (CLI) version of its speed test so you can test your internet speed without the overhead of a web browser. Here's how to use it on macOS, Windows, and Linux.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Run a Speed Test on Mac via Terminal

 To accomplish this on Mac, we will be using [Homebrew](https://visual-screen-recording.techidaily.com/new-breaking-ground-video-capture-breakdown-for-2024/), a [popular macOS package manager](https://screen-activity-recording.techidaily.com/updated-in-2024-virtualvista-viewers-verdict/). If you haven't installed Homebrew yet or if you are unsure, open Terminal (you'll find it under Applications > Utilities) and enter the following command:

        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    
 This command will download and install Homebrew. Once installed, you can easily install the speed test CLI by entering:

        `brew install speedtest-cli`
    
 After the installation is complete, you can run the speed test by simply typing:

        `speedtest-cli  
`
    
![Running speedtest cli in macOS Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-macos-terminal.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-maximize-engine-power-the-best-windows-and-mac-srt-mods-countdown/"><u>[New] Maximize Engine Power The Best Windows & Mac SRT Mods Countdown</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-stay-up-to-date-with-facebooks-latest-watched-content/"><u>[New] Stay Up-to-Date with Facebook's Latest Watched Content</u></a></li>
<li><a href="https://article-files.techidaily.com/new-step-by-step-process-to-enhance-obs-with-effective-lut-filters/"><u>[New] Step-by-Step Process to Enhance OBS with Effective LUT Filters</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-navigating-devices-for-google-meet-session/"><u>[Updated] 2024 Approved Navigating Devices for Google Meet Session</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-is-it-wise-to-keep-off-facebook-activity-displayed-insights/"><u>[Updated] Is It Wise to Keep Off-Facebook Activity Displayed? Insights</u></a></li>
<li><a href="https://win-blog.techidaily.com/acknowledgment/"><u>Acknowledgment</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723005855776-battling-with-constant-pc-crashes-during-the-king-of-fighters-xv-heres-how-you-can-win/"><u>Battling with Constant PC Crashes During 'The King of Fighters XV'? Here's How You Can Win</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/clear-guide-to-overcome-d3dx924dll-errors-on-your-pc/"><u>Clear Guide to Overcome 'd3dx9_24.dll' Errors on Your PC</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discovering-the-best-youtube-mp3-transformers/"><u>Discovering the Best YouTube MP3 Transformers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exquisite-technology-on-a-budget-high-end-gadgets-for-smart-savings/"><u>Exquisite Technology on a Budget: High-End Gadgets for Smart Savings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-operation-failed-0x0000011b-error-on-windows-11-and-11/"><u>How to Fix the Operation Failed 0X0000011B Error on Windows 11 & 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-safely-discard-windows-recover-disk-space-sector/"><u>How to Safely Discard Windows Recover Disk Space Sector</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-your-fitness-goals-a-guide-to-using-the-measure-app-on-android/"><u>Mastering Your Fitness Goals: A Guide to Using the Measure App on Android</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigate-to-the-nearest-ev-charge-station-on-google-maps-what-you-need-to-know/"><u>Navigate to the Nearest EV Charge Station on Google Maps - What You Need To Know</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/pioneering-the-future-of-wireless-unveiling-verizons-5g-potential/"><u>Pioneering the Future of Wireless: Unveiling Verizon's 5G Potential</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-errors-with-outlooks-automatic-spell-correction-feature/"><u>Troubleshooting Errors with Outlook's Automatic Spell Correction Feature</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-what-to-do-when-you-encounter-a-missing-python24dll/"><u>Troubleshooting: What to Do When You Encounter a Missing Python24.dll</u></a></li>
</ul></div>

