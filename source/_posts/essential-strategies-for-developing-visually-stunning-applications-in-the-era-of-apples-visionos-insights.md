---
title: Essential Strategies for Developing Visually Stunning Applications in the Era of Apple's VisionOS - Insights
date: 2024-11-28T22:24:13.675Z
updated: 2024-12-04T16:27:57.533Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0f4e3cdd6a3a2810d9be01f02401b08a8ee0a737df3f1b1c4792de29fdd777e8.jpg
---

## Essential Strategies for Developing Visually Stunning Applications in the Era of Apple's VisionOS - Insights

![Apple Vision Pro headset at WWDC 2023](https://www.zdnet.com/a/img/resize/025f723fae72cfe10cd99a1fcdb86dabdd8a1c92/2023/06/06/48689ad3-bca3-447a-b958-bfea14736233/img-8838.jpg?auto=webp&width=1280)

Jason Hiner/ZDNET

As the calendar turns from 2023 to 2024, Apple is getting closer to releasing its shockingly expensive and entirely experimental [Vision Pro headset](https://www.zdnet.com/article/i-tried-apple-vision-pro-and-its-far-ahead-of-where-i-expected/). Just this week, Apple announced that the iPhone 15 Pro and Pro Max can [capture spatial video for the Vision Pro](https://www.zdnet.com/article/the-iphone-15-pro-can-officially-capture-spatial-video-for-the-apple-vision-pro/).

You could say that Apple's vision of artificial reality is getting closer to real reality. And yes, I am pretty proud of that sentence. 

**Also: [I tried Apple Vision Pro and it's far ahead of where I expected](https://www.zdnet.com/article/i-tried-apple-vision-pro-and-its-far-ahead-of-where-i-expected/)**

Recently, Apple also started to release design guidelines for developers. One that caught my eye is the company's "[Q&A: Spatial design for visionOS](https://developer.apple.com/news/?id=fi8ne6ji)." This document provides some best practices for developers creating apps for VisionOS. 

Since VisionOS is a very different beast from all of the other Apple OS implementations, particularly in the user interface department, I thought it would be interesting to share with you some of those best practice recommendations. 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

That way, if you're a developer, you can start thinking about how to build your apps. And if you're a user considering purchasing a set of these solid gold goggles, you'll have a better feel for how designers are constructing their apps and what your experience might be. 

Let's dig in, shall we? 

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  1\. Gradual immersion

Apple recommends you gradually introduce users to your app, starting with a window view within the augmented reality environment. 

That way, they're not suddenly dropped into a whole new world, but they can slowly get their "VR legs" and feel they have some level of control over their immersion level, at least until they get comfortable with their environment. 

**Also: [Two breakthroughs made 2023 tech's most innovative year in over a decade](https://www.zdnet.com/article/two-breakthroughs-made-2023-techs-most-innovative-year-in-over-a-decade/)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  2\. Identify your key moments

Let's say you're a developer who has an existing app for the iPad. Let's say you want to bring said iPad app into VisionOS. The iPad app, by its nature, is flat and rectangular. But VisionOS allows users to see all around. Is there anything in your app that clearly lends itself to VRification? 

**Also: [Inside VisionOS: 17 things developers need to know right now](https://www.zdnet.com/article/inside-visionos-17-things-developers-need-to-know-right-now/)**

Apple uses its Photos app as an example. A key moment for Apple's Photos app might be showing a panoramic photo by wrapping it around the user completely. Panoramas are a long-standing feature of the Photos app, but spatially wrapping the pano is something that would showcase the mixed-reality environment. 

In a writing app, VRification might involve going from a typical windowed user interface for most writing to a focus mode that shuts out the outside world and lets your users concentrate, by providing a calming background and perhaps some calming music. 

##  3\. Adjust UI elements to accommodate the new environment

Some UI elements translate directly from iPadOS to VisionOS, but others aren't an exact match. Apple has a [spatial design guidelines video](https://developer.apple.com/videos/play/wwdc2023/10072/) that's well worth watching to come up to speed. 

**Also: [Would you believe a VR headset outsold AirPods during Black Friday? It happened](https://www.zdnet.com/article/would-you-believe-a-vr-headset-outsold-airpods-during-black-friday-it-happened/)**

One area to pay particular attention to is when you use hover effects. When you hover over a button in a flat UI, you just need to see some highlighting. But when you hover over -- or in front of -- something in VR space, you've got the entire room to work in. So pay attention to how things look and feel, and try to avoid inducing vertigo by rapidly moving objects and buttons. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  4\. Utilize grid systems where appropriate

Apple says that apps designed with the [iPadOS grid system](https://developer.apple.com/design/human-interface-guidelines/designing-for-ios) will translate very nicely to the Vision Pro. The grid works well for designing windows. Point sizes translate well from the iPad to Vision Pro. 

But as you deal with more 3D-centric objects, grid systems break down. Once you're moving in 3D space, be careful about where you place your controls. For example, it can be somewhat confusing if you have nearby controls for a faraway object. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  5\. Incorporate sound design strategically

Sound -- that is, _audio_ \-- design plays a crucial role in spatial computing. Sound may not be as critical for flat UI experiences, but we humans rely on sound -- and the spatial awareness that sound provides -- to orient ourselves in our real-world environment. So keep in mind that sound not only makes your environment more interesting, it can serve as an orientation tool as well. 

To that end, even if you're building a non-entertainment app that would normally not focus on sound, consider how sound elements, no matter how subtle, might be used for user spatial orientation while in VR space. 

**Also: [Apple's Vision Pro: A concept prototype with this enormous potential](https://www.zdnet.com/article/apples-vision-pro-a-concept-prototype-with-this-enormous-potential/)**

And while you're at it, allow your users to control the sound, setting its volume and even turning it off. Give the sound cues that may be helpful, but give users control over how those cues are applied. Here's [a great resource from Apple on sound design](https://developer.apple.com/wwdc23/10271). 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  6\. Focus on key details, but don't overwhelm

Apple recommends always rendering a ground plane so users feel grounded. If you're putting someone inside a theatre, provide key details (like a stage, lighting, and curtains), but don't get carried away trying to reproduce the cola stains in the carpet or that unique crackle that comes from walking over scraps of petrified popcorn. If you're rendering an outdoor landscape, show slowly moving clouds but keep things subtle. 

Of course, if you're putting people into a game where the whole idea is to overwhelm them, then go for it. But Apple is much more interested in using VR and AR as an augmented tool, rather than purely as a gaming platform. And in that context, it's probably wise to avoid making your customers barf up their lunches inside their $3,500+ head-mounted [uncanny valley](https://en.wikipedia.org/wiki/Uncanny%5Fvalley)in a can. 

##  7\. Use the VisionOS simulator

There is, in fact, a VisionOS simulator available inside Xcode, Apple's development environment. Here's a [guide to all of the Xcode simulators](https://developer.apple.com/documentation/xcode/running-your-app-in-simulator-or-on-a-device). And here's a [guide to interacting with your app](https://developer.apple.com/documentation/visionos/interacting-with-your-app-in-the-visionos-simulator) inside the Xcode VisionOS simulator. 

So there you go. Seven helpful tips for keeping your users' insides inside. 

**Also: [The iPhone 15 Pro can officially capture spatial video for the Apple Vision Pro](https://www.zdnet.com/article/the-iphone-15-pro-can-officially-capture-spatial-video-for-the-apple-vision-pro/)**

What do you think? Are you building apps for VisionOS? Are you planning on buying a Vision Pro? Let us know in the comments below. 

---

_You can follow my day-to-day project updates on social media. Be sure to subscribe to my weekly update newsletter [on Substack](https://advancedgeekery.substack.com/), and follow me on Twitter at [@DavidGewirtz](https://twitter.com/davidgewirtz), on Facebook at [Facebook.com/DavidGewirtz](https://www.facebook.com/davidgewirtz), on Instagram at [Instagram.com/DavidGewirtz](https://www.instagram.com/DavidGewirtz/), and on YouTube at [YouTube.com/DavidGewirtzTV](https://www.youtube.com/user/DavidGewirtzTV)._

#### AR + VR

[I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back](https://www.zdnet.com/article/supernatural-on-meta-quest-hands-on/ "I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back")

[This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it](https://www.zdnet.com/article/this-finnish-startups-new-vr-headset-rivals-apples-vision-pro-and-business-users-will-love-it/ "This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it")

[Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers](https://www.zdnet.com/article/meta-quest-3-review/ "Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers")

[I tried Apple Vision Pro and it's far ahead of where I expected](https://www.zdnet.com/article/i-tried-apple-vision-pro-and-its-far-ahead-of-where-i-expected/ "I tried Apple Vision Pro and it's far ahead of where I expected")

[The best VR headsets right now (and they're not just from Meta)](https://www.zdnet.com/article/best-vr-headset/ "The best VR headsets right now (and they're not just from Meta)")

* [I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back](https://www.zdnet.com/article/supernatural-on-meta-quest-hands-on/ "I replaced my boring workouts with Meta Quest's Supernatural app, and can't imagine going back")
* [This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it](https://www.zdnet.com/article/this-finnish-startups-new-vr-headset-rivals-apples-vision-pro-and-business-users-will-love-it/ "This Finnish startup's new VR headset rivals Apple's Vision Pro - and business users will love it")
* [Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers](https://www.zdnet.com/article/meta-quest-3-review/ "Meta's $500 Quest 3 is the mainstream VR headset I've been waiting for, and it delivers")
* [I tried Apple Vision Pro and it's far ahead of where I expected](https://www.zdnet.com/article/i-tried-apple-vision-pro-and-its-far-ahead-of-where-i-expected/ "I tried Apple Vision Pro and it's far ahead of where I expected")
* [The best VR headsets right now (and they're not just from Meta)](https://www.zdnet.com/article/best-vr-headset/ "The best VR headsets right now (and they're not just from Meta)")

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-plating-perfection-30-unique-and-appealing-recipe-channels/"><u>[New] 2024 Approved Plating Perfection 30 Unique and Appealing Recipe Channels</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-stealthy-sound-suppression-techniques-for-fade-out/"><u>[New] Stealthy Sound Suppression Techniques for Fade-Out</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-advanced-techniques-for-quieter-video-calls-on-skype/"><u>[Updated] In 2024, Advanced Techniques for Quieter Video Calls on Skype</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-how-to-craft-top-quality-youtube-thumbnails-fast/"><u>[Updated] In 2024, How To Craft Top Quality YouTube Thumbnails Fast</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-nokia-g310-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/apple-unveils-groundbreaking-software-enhancements-during-wwdc-exclusive-breakdown-on-how-they-will-transform-your-experience-cnet-news/"><u>Apple Unveils Groundbreaking Software Enhancements During WWDC - Exclusive Breakdown on How They Will Transform Your Experience | CNET News</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/apples-projected-inexpensive-vision-pro-glasses-still-seem-more-myth-than-reality-an-analysis-by-zdnet/"><u>Apple's Projected Inexpensive Vision Pro Glasses Still Seem More Myth Than Reality – An Analysis by ZDNET</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-dialogue-with-chatgpt-and-macsynchrony/"><u>Enhancing Dialogue with ChatGPT & MacSynchrony</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/escape-monotonous-workdays-with-the-metaverse-shaping-tomorrows-careers-on-the-horizon-zdnet/"><u>Escape Monotonous Workdays with the Metaverse: Shaping Tomorrow's Careers on the Horizon - ZDNet</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/experience-reduced-ar-tech-worry-with-these-budget-friendly-xr-glasses-zdnets-inside-look/"><u>Experience Reduced AR Tech Worry with These Budget-Friendly XR Glasses - ZDNET's Inside Look</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/experience-vast-visuals-with-affordable-400-xr-glasses-ultimate-for-gaming-and-movie-viewing-insights-from-zdnet/"><u>Experience Vast Visuals with Affordable $400 XR Glasses: Ultimate for Gaming & Movie Viewing - Insights From ZDNet</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-things-you-should-know-when-unlocking-total-wireless-of-iphone-13-pro-by-drfone-ios/"><u>In 2024, Things You Should Know When Unlocking Total Wireless Of iPhone 13 Pro</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/tech-giants-join-forces-in-xr-space-anticipation-builds-as-apple-prepares-to-unveil-its-own-headset-according-to-zdnet-reports/"><u>Tech Giants Join Forces in XR Space: Anticipation Builds as Apple Prepares to Unveil Its Own Headset, According to ZDNet Reports</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/the-best-free-video-rotators-for-mov-files/"><u>The Best Free Video Rotators for MOV Files</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-highlights-from-ces-2024-expert-insights-and-editor-favorites-zdnet-review/"><u>Top Highlights From CES 2024: Expert Insights and Editor Favorites - ZDNet Review</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unexplained-vision-professional-system-failures-essential-steps-and-solutions-insights-from-zdnet/"><u>Unexplained Vision Professional System Failures: Essential Steps & Solutions - Insights From ZDNet</u></a></li>
</ul></div>

