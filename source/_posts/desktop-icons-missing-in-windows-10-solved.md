---
title: Desktop Icons Missing in Windows 10 [Solved]
date: 2025-01-28T18:59:56.030Z
updated: 2025-01-30T17:13:12.397Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Desktop Icons Missing in Windows 10 [Solved]
excerpt: This Article Describes Desktop Icons Missing in Windows 10 [Solved]
thumbnail: https://thmb.techidaily.com/60fe1a74657905b47d054d52197782d9df31df8374f9444c7a6b8dc97d98722a.jpg
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
<li><a href="https://article-posts.techidaily.com/new-awarded-top-12-camcorders-including-satellite-position-tracking-for-2024/"><u>[New] Awarded Top 12 Camcorders Including Satellite Position Tracking for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-visual-data-harvester/"><u>[New] In 2024, Visual Data Harvester</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-youtube-marketing-mastery-crafting-robust-backlinks-for-growth/"><u>[New] In 2024, YouTube Marketing Mastery Crafting Robust Backlinks for Growth</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-10-must-know-iphone-x-tricks-to-enhance-usage/"><u>[Updated] 2024 Approved 10 Must-Know iPhone X Tricks to Enhance Usage</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-spark-interest-everyones-free-with-our-youtube-banner-samples/"><u>2024 Approved Spark Interest - Everyone's Free With Our YouTube Banner Samples!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-realme-gt-neo-5-se-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Realme GT Neo 5 SE Without Power Button | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-delete-icloud-account-with-or-without-password-from-your-iphone-se-2020windowsmac-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account with or without Password from your iPhone SE (2020)/Windows/Mac</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-voice-command-utilization-no-cost/"><u>In 2024, Voice Command Utilization No Cost</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/iphone-16-launch-exclusive-look-at-cutting-edge-spatial-recording-and-redesigned-thin-bezels-tech-news-by-zdnet/"><u>IPhone 16 Launch: Exclusive Look at Cutting-Edge Spatial Recording and Redesigned Thin Bezels | Tech News by ZDNet</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/locked-out-of-iphone-14-pro-max-5-ways-to-get-into-a-locked-iphone-14-pro-max-drfone-by-drfone-ios/"><u>Locked Out of iPhone 14 Pro Max? 5 Ways to get into a Locked iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/prevent-your-ipad-from-crashing-with-ios-18-essential-tips-and-precautions-before-updating-techinformed/"><u>Prevent Your iPad From Crashing with IOS 18: Essential Tips & Precautions Before Updating | TechInformed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-list-of-why-you-need-an-apple-watch-an-authoritative-review-by-a-tech-guru-on-zdnet/"><u>The Ultimate List of Why You Need an Apple Watch: An Authoritative Review by a Tech Guru on ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-viewing-guide-watching-the-transformers-franchise-sequentially/"><u>The Ultimate Viewing Guide: Watching The Transformers Franchise Sequentially</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-ipad-applications-for-enhanced-efficiency-streamlining-your-task-management-insights/"><u>Top iPad Applications for Enhanced Efficiency: Streamlining Your Task Management Insights</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-apple-watch-skin-shields-of-2023-expert-reviews-and-buyers-guide/"><u>Top-Rated Apple Watch Skin Shields of 2023: Expert Reviews & Buyer's Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/uncover-the-secrets-identifying-if-someones-using-an-airtag-on-you-tips-and-tricks-revealed/"><u>Uncover the Secrets: Identifying If Someone's Using an AirTag on You - Tips & Tricks Revealed!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/uncover-the-truth-a-step-by-step-guide-on-detecting-an-airtag-following-your-movements/"><u>Uncover the Truth: A Step-by-Step Guide on Detecting an AirTag Following Your Movements</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/upgrading-your-iphone-in-the-coming-week-discover-essential-anker-charger-gadgets-that-perfectly-fit-your-needs-tips/"><u>Upgrading Your iPhone in the Coming Week? Discover Essential Anker Charger Gadgets That Perfectly Fit Your Needs - Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

