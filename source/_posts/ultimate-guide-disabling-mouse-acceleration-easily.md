---
title: "Ultimate Guide: Disabling Mouse Acceleration Easily"
date: 2025-02-04T23:40:22.798Z
updated: 2025-02-11T22:00:10.200Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Ultimate Guide: Disabling Mouse Acceleration Easily"
excerpt: "This Article Describes Ultimate Guide: Disabling Mouse Acceleration Easily"
thumbnail: https://thmb.techidaily.com/dd4233ccec15666d6d616a1b1df2dfb0cda2d2ae21f58fe6b6f759379250d50d.jpg
---

## WinSxS Folder: Clean Up and Save Space on Windows 10 Easily

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-access.techidaily.com/new-new-frontiers-in-mobile-videography-alternatives-to-periscope-for-2024/"><u>[New] New Frontiers in Mobile Videography - Alternatives to Periscope for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-ranking-the-best-no-cost-tiktok-to-mp3-conversion-services/"><u>[Updated] Ranking the Best No-Cost TikTok to MP3 Conversion Services</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-playback-in-reverse-the-ultimate-youtube-playlist-technique/"><u>2024 Approved Playback in Reverse The Ultimate YouTube Playlist Technique</u></a></li>
<li><a href="https://win-answers.techidaily.com/accelerate-your-adventure-defeating-forza-horizon-5s-persistent-load-puzzle/"><u>Accelerate Your Adventure: Defeating Forza Horizon 5'S Persistent Load Puzzle</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/deciding-on-your-ideal-tablet-in-depth-comparison-of-apples-latest-ipad-pro-models-with-m1-and-m2-processors-expert-review/"><u>Deciding on Your Ideal Tablet: In-Depth Comparison of Apple's Latest iPad Pro Models with M1 & M2 Processors | Expert Review</u></a></li>
<li><a href="https://tech-revival.techidaily.com/efficiently-revealing-private-gpt-chat-exchanges/"><u>Efficiently Revealing Private GPT-Chat Exchanges</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-much-splash-does-the-iphone-13-handle-dive-into-its-ip68-protection-details/"><u>How Much Splash Does the iPhone 13 Handle? Dive Into Its IP68 Protection Details</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-redmi-12-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi Redmi 12 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-surpass-everyday-photo-taking-with-ios-11/"><u>In 2024, Surpass Everyday Photo-Taking with iOS 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revolutionizing-productivity-and-travel-top-picks-in-xr-glasses-feature-newly-enhanced-tech/"><u>Revolutionizing Productivity & Travel: Top Picks in XR Glasses Feature Newly Enhanced Tech</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-alluring-appeal-of-apples-latest-innovation-top-4-convincing-factors-to-upgrade-to-the-new-ipad-air/"><u>The Alluring Appeal of Apple's Latest Innovation: Top 4 Convincing Factors to Upgrade to the New iPad Air</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-guide-to-mens-ncaa-ball-radio-broadcasts-from-march-mayhem-to-championship-glory/"><u>The Ultimate Guide to Men's NCAA Ball: Radio Broadcasts From March Mayhem to Championship Glory</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-4-revolutionary-capabilities-of-the-new-iphone-16-why-you-should-consider-switching-from-older-models/"><u>Top 4 Revolutionary Capabilities of the New iPhone 16: Why You Should Consider Switching From Older Models</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-pick-breakdown-the-enhanced-ring-doorbell-battery-experience-review/"><u>Top Pick Breakdown: The Enhanced Ring Doorbell Battery Experience Review</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-iphone-16-and-iphone-16-pro-protective-covers-reviewed-by-professionals/"><u>Top-Rated iPhone 16 & iPhone 16 Pro Protective Covers - Reviewed by Professionals</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/transforming-your-iphone-display-with-the-perfect-night-setting-guide/"><u>Transforming Your iPhone Display with the Perfect Night Setting Guide</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-lifespan-of-your-apple-watch-battery-unexpected-insights-revealed-zdnet/"><u>Unveiling the Lifespan of Your Apple Watch Battery: Unexpected Insights Revealed | ZDNet</u></a></li>
</ul></div>

