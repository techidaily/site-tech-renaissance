---
title: "Ultimate Guide: Resolving the DRIVER_POWER_STATE_FAILURE Error"
date: 2025-01-27T16:47:21.677Z
updated: 2025-01-30T17:33:28.989Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Ultimate Guide: Resolving the DRIVER_POWER_STATE_FAILURE Error"
excerpt: "This Article Describes Ultimate Guide: Resolving the DRIVER_POWER_STATE_FAILURE Error"
thumbnail: https://thmb.techidaily.com/b11f60af4f1190ff0fe1470217a3e88ba5ec7f084c8dd4d5a027c3574d3f04e3.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-ignite-your-audience-top-10-igtv-trends-brands-cant-miss/"><u>[Updated] In 2024, Ignite Your Audience Top 10 IGTV Trends Brands Can't Miss</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-from-apple-iphone-xs-max-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password From Apple iPhone XS Max</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/britbox-to-netflix-top-uk-television-series-available-here-and-now/"><u>BritBox to Netflix: Top UK Television Series Available Here and Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/coming-soon-the-new-macbook-with-touchscreen-technology-insights-into-release-schedule-pricing-forecasts-and-specs-breakdown/"><u>Coming Soon: The New MacBook with Touchscreen Technology - Insights Into Release Schedule, Pricing Forecasts, and Specs Breakdown</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ethical-concerns-with-ai-derived-windows-11-codes/"><u>Ethical Concerns with AI-Derived Windows 11 Codes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-on-shutting-down-your-new-iphone-15-devices-including-the-pro-and-pro-max/"><u>Expert Advice on Shutting Down Your New iPhone 15 Devices, Including the Pro & Pro Max</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-fun-vs-security-whats-at-stake/"><u>Facebook Fun vs Security – What's at Stake?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/obtain-your-qualcomm-atheros-ar93-8x-drivers-without-cost-quick-and-safe-download/"><u>Obtain Your Qualcomm Atheros AR93 8X Drivers Without Cost – Quick & Safe Download</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-windows-11s-shutdown-dilemma-a-step-by-step-guide/"><u>Overcoming Windows 11'S Shutdown Dilemma: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/technologys-influential-but-controversial-figures/"><u>Technology's Influential but Controversial Figures</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

