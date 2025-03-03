---
title: "The Ins and Outs of Ray Tracing: What You Need to Know"
date: 2025-02-26T01:05:33.872Z
updated: 2025-03-02T19:13:26.572Z
categories:
  - BestProducts
description: "This Article Describes The Ins and Outs of Ray Tracing: What You Need to Know"
excerpt: "This Article Describes The Ins and Outs of Ray Tracing: What You Need to Know"
thumbnail: https://thmb.techidaily.com/34062c0c76761441d1daaab882479cf039a7dd266a5c393fca1f08310200c903.jpg
---

## The Ins and Outs of Ray Tracing: What You Need to Know

Close 

 Games are more vivid than ever. This article explains how ray tracing makes the difference.  

## What is Ray Tracing? 

 Ray tracing is a technique for[ rendering](https://www.lifewire.com/what-is-rendering-1954) computer graphics that creates an image by tracing rays' path through a scene. The rays can interact with objects in the scene, bouncing off them and gaining properties, such as color.

## How Ray Tracing Works 

 Ray tracing emulates real-world lighting. The light we see is the result of photons emitted from energy sources, like the sun. Photons can bounce and scatter as they collide with objects. A mirror is all you need to see this in action. Light hitting a mirror creates a reflection.

 Ray tracing simulates this. The number of rays traced is paltry compared to the real world, where millions of photons bounce across our field of view. Modern games trace somewhere between one and four rays per pixel. Still, that's enough to simulate the real world.

![Vending machines in the game Cyberpunk 2077](https://www.lifewire.com/thmb/x9KVYNkfR_Bw9Oh5se9jeI8JiMQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/cyberpunk2077-2c97987534994d32afabd764b09bd682.jpg) 

CD Projekt Red

 Tracing the path of a ray also lets it interact with the game world. A ray that bounces off a red object can be influenced by that color, casting a red glow nearby. Rays can scatter in different ways based on the properties a game’s artists give to objects, allowing realistic semi-reflective or rough surfaces.

 Ray tracing is a significant step forward for 3D graphics. It creates a realistic image by simulating the path of rays as they move through a game.

 This leads to lighting that can interact with the environment even when the environment isn’t visible to the player. Ray tracing doesn’t require purpose-built hardware to function, but it's only practical on a video card or game console that can accelerate ray tracing because it's very demanding.

##  Ray Tracing vs. Rasterization 

 You may still be confused even if you understand this explanation. Reflections were present in past games, even those now several decades old. How is ray tracing different?

 Past 3D games, and most modern games, use rasterization. Rasterization combines the elements of a 3D game world visible to the player into a 2D image. It only renders what should be visible to the player, as any performance used to generate what the player can’t see is wasted. However, this creates a problem.

![Ray tracing in Battlefield 5](https://www.lifewire.com/thmb/r2mdM8eBZAKw6HdVsRn7mgJq7zQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/rtxraytracebattlefield5-50d78dc8c3a14f9cb996f5d83b2a3726.jpg) 

Nvidia

 Let’s return to the example of a mirror. The player's environment and the player character aren’t visible to the player (in a first-person game, at least). With rasterization, there’s nothing for the mirror to reflect.

 Of course, mirrors exist in modern games. They render the scene twice. One pass is from the player’s point of view, while another is from a different perspective. That doubles the performance needed to render a scene, however.

 Screen space reflections, a technique in popular 3D game engines, use on-screen data to create a reflection. This technique is ideal for reflective surfaces at an angle to the player’s perspective, such as water. However, reflected objects disappear if the item reflected moves off-screen.

 Ray tracing doesn’t share these problems because, unlike rasterization, it can trace outside the player's perspective.

 Also, in games that allow rays to interact with surfaces, ray tracing can display realistic color bleed and semi-reflective surfaces difficult for rasterization to handle.

[ What to Look For in a Gaming PC ](https://www.lifewire.com/what-to-consider-before-buying-a-gaming-pc-5221042) 

##  What Hardware Does Ray Tracing Require? 

 Ray tracing isn't a new idea.[ Computer scientists experimented with ray tracing in the early 1980s](https://news.developer.nvidia.com/ray-tracing-from-the-1980s-to-today-an-interview-with-morgan-mcguire-nvidia/) , creating static images with realistic lighting, reflections, and shadows. Unfortunately, they took hours to render.

 A video game needs real-time ray tracing at 30 frames per second or higher. That’s only possible with a video card designed to accelerate ray tracing.

![Nvidia RTX 3080 graphics card on a black background](https://www.lifewire.com/thmb/QGQ2tBbyAIp9z2q6B2ZLBc7rQyU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/nvidiartx3080-43baad1d3a1e415a8e3760e81b0c5de0.jpg) 

Nvidia

 Nvidia’s RTX ray tracing relies on silicon called a Tensor Core. Tensor Cores are only found in RTX video cards. Nvidia’s GTX cards can render a game using ray tracing because, as said, ray tracing doesn’t require purpose-built silicon. However, performance is abysmal compared to RTX cards. And some games, like[ Minecraft with RTX ray tracing](https://www.lifewire.com/minecraft-gets-ray-tracing-update-windows-10-4802711) , require an RTX video card because of the specific way they enable ray tracing.

 AMD cards that accelerate ray tracing don’t have specific branding and don’t have dedicated silicon. Instead, they use hardware tweaks and software updates for better results. It’s more difficult to identify AMD cards that accelerate ray tracing, so pay attention to the details.

[  Xbox Series X vs Xbox Series S: How to Pick the Console Right for You ](https://www.lifewire.com/xbox-series-x-vs-xbox-series-s-5083862) 

 Sony’s[ PlayStation 5](https://www.lifewire.com/is-ps5-worth-it-8629161) and Xbox Series X and S have graphics hardware from AMD that can accelerate ray tracing. It’s up to developers to enable, however, and many games don’t. A notable example is[ _Cyberpunk 2077_ ](https://www.lifewire.com/cyberpunk-2077-has-everything-it-needs-to-be-great-5085210) , which supported RTX ray tracing on PC at launch but didn’t support ray tracing on next-gen consoles.

[ What Is an RTX Graphics Card? ](https://www.lifewire.com/rtx-graphics-card-8642473) 

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[ Subscribe ](https://www.lifewire.com/#) 

Tell us why!

 Other  Not enough details  Hard to understand 

 Submit 

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
<li><a href="https://youtube-data.techidaily.com/umpstarting-your-youtube-dreams-setting-up-personalbusiness-channels-on-mobile-for-2024/"><u>[New] Jumpstarting Your YouTube Dreams Setting Up Personal/Business Channels on Mobile for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-rapid-rendering-sounds-with-visuals/"><u>[Updated] Rapid Rendering Sounds with Visuals</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-revolutionizing-content-creation-the-future-of-live-video-on-facebook/"><u>2024 Approved Revolutionizing Content Creation The Future of Live Video on Facebook</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/all-about-apples-latest-audio-enabled-wearable-expected-retail-price-arrival-date-specs-deep-dive-and-whispered-theories/"><u>All About Apple's Latest Audio-Enabled Wearable: Expected Retail Price, Arrival Date, Specs Deep Dive & Whispered Theories</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722881712723-apple-music-continuous-streaming-learn-how-to-pause-it/"><u>Apple Music Continuous Streaming? Learn How to Pause It</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/basketball-bonanza-unleashed-experience-the-thrills-of-march-madness-and-final-four-live/"><u>Basketball Bonanza Unleashed: Experience the Thrills of March Madness & Final Four Live!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/complete-tutorial-setting-up-windows-10-for-the-first-time-on-a-new-drive/"><u>Complete Tutorial: Setting Up Windows 10 for the First Time on a New Drive</u></a></li>
<li><a href="https://tech-revival.techidaily.com/demystifying-ai-driven-text-creation-and-enterprise-usage/"><u>Demystifying AI-Driven Text Creation and Enterprise Usage</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-world-of-connected-televisions-and-web-capabilities/"><u>Exploring the World of Connected Televisions and Web Capabilities</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-concept-to-delivery-using-luts-with-adobe-ae-for-2024/"><u>From Concept to Delivery Using LUTs with Adobe AE for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/installing-windows-10-on-a-brand-new-drive-made-simple/"><u>Installing Windows 10 on a Brand-New Drive Made Simple</u></a></li>
<li><a href="https://solve-hot.techidaily.com/key-precautions-when-modifying-the-registry-expert-advice-from-yl-software-experts/"><u>Key Precautions When Modifying the Registry: Expert Advice From YL Software Experts</u></a></li>
<li><a href="https://sound-issues.techidaily.com/rec-room-headset-malfunction-fixing-mic-issues-on-pc/"><u>Rec Room Headset Malfunction: Fixing Mic Issues on PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722871915048-the-next-big-thing-from-apple-discover-the-latest-gossip-on-home-robot-releases-and-features/"><u>The Next Big Thing From Apple? Discover the Latest Gossip on Home Robot Releases and Features.</u></a></li>
</ul></div>

