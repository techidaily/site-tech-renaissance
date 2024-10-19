---
title: Unveiling the Concepts Behind Ray Tracing
date: 2024-10-13T23:08:40.654Z
updated: 2024-10-19T02:56:36.766Z
categories:
  - BestProducts
description: This Article Describes Unveiling the Concepts Behind Ray Tracing
excerpt: This Article Describes Unveiling the Concepts Behind Ray Tracing
thumbnail: https://www.lifewire.com/thmb/1-Yp1JIoL4O5iudaQ-YSTZFzypk=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/raytracingstarwars-b548b699b36b4bb8b4334d66a964ede9.jpg
---

## Unveiling the Concepts Behind Ray Tracing

Close 

 Games are more vivid than ever. This article explains how ray tracing makes the difference.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is Ray Tracing?

 Ray tracing is a technique for[ rendering](https://www.lifewire.com/what-is-rendering-1954) computer graphics that creates an image by tracing rays' path through a scene. The rays can interact with objects in the scene, bouncing off them and gaining properties, such as color.

## How Ray Tracing Works

 Ray tracing emulates real-world lighting. The light we see is the result of photons emitted from energy sources, like the sun. Photons can bounce and scatter as they collide with objects. A mirror is all you need to see this in action. Light hitting a mirror creates a reflection.

 Ray tracing simulates this. The number of rays traced is paltry compared to the real world, where millions of photons bounce across our field of view. Modern games trace somewhere between one and four rays per pixel. Still, that's enough to simulate the real world.

![Vending machines in the game Cyberpunk 2077](https://www.lifewire.com/thmb/x9KVYNkfR_Bw9Oh5se9jeI8JiMQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/cyberpunk2077-2c97987534994d32afabd764b09bd682.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

CD Projekt Red

 Tracing the path of a ray also lets it interact with the game world. A ray that bounces off a red object can be influenced by that color, casting a red glow nearby. Rays can scatter in different ways based on the properties a game’s artists give to objects, allowing realistic semi-reflective or rough surfaces.

 Ray tracing is a significant step forward for 3D graphics. It creates a realistic image by simulating the path of rays as they move through a game.

 This leads to lighting that can interact with the environment even when the environment isn’t visible to the player. Ray tracing doesn’t require purpose-built hardware to function, but it's only practical on a video card or game console that can accelerate ray tracing because it's very demanding.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105877/7443" target="_top" id="2105877">
  <img src="//a.impactradius-go.com/display-ad/7443-2105877" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105877/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Ray Tracing vs. Rasterization

 You may still be confused even if you understand this explanation. Reflections were present in past games, even those now several decades old. How is ray tracing different?

 Past 3D games, and most modern games, use rasterization. Rasterization combines the elements of a 3D game world visible to the player into a 2D image. It only renders what should be visible to the player, as any performance used to generate what the player can’t see is wasted. However, this creates a problem.

![Ray tracing in Battlefield 5](https://www.lifewire.com/thmb/r2mdM8eBZAKw6HdVsRn7mgJq7zQ=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/rtxraytracebattlefield5-50d78dc8c3a14f9cb996f5d83b2a3726.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-free-auditory-gamespace-vaults-copyright-free/"><u>[New] In 2024, Free Auditory Gamespace Vaults (Copyright-Free)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-tailoring-the-frame-how-to-optimize-videography-for-instagram/"><u>[Updated] Tailoring the Frame How to Optimize Videography for Instagram</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-virtual-streets-best-video-games-mimicking-gta-v/"><u>2024 Approved Virtual Streets Best Video Games Mimicking GTA V</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-create-stunning-movies-online-for-free-top-9-options/"><u>In 2024, Create Stunning Movies Online for Free Top 9 Options</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-language-bridge-builders-top-18-tools-that-turn-videos-into-text/"><u>In 2024, Language Bridge Builders Top 18 Tools That Turn Videos Into Text</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-infinix-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Infinix Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-chrome-profile-correction-for-pc-users/"><u>Mastering Chrome Profile Correction for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-performance-selecting-the-best-five-no-cost-drivers/"><u>Maximizing PC Performance: Selecting the Best Five No-Cost Drivers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-challenges-when-running-the-windows-computer-wellness-app/"><u>Overcoming Challenges When Running the Windows Computer Wellness App</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resetting-your-windows-11-passwords-a-comprehensive-guide-four-methods-explored/"><u>Resetting Your Windows 11 Passwords: A Comprehensive Guide - Four Methods Explored</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-windows-10-monochrome-screen-issues-tips-and-tricks-to-restore-colors/"><u>Resolving Windows 10 Monochrome Screen Issues: Tips & Tricks to Restore Colors</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/revive-your-chatgpt-experience-using-our-5-easy-fixes/"><u>Revive Your ChatGPT Experience Using Our 5 Easy Fixes!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/secure-your-connection-detect-and-track-your-ip-address-for-free/"><u>Secure Your Connection: Detect and Track Your IP Address for Free</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simple-steps-update-your-usb-device-drivers-on-windows-11-and-earlier-versions/"><u>Simple Steps: Update Your USB Device Drivers on Windows 11 and Earlier Versions</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-surprising-instantaneous-banning-of-chatgpt-in-italy/"><u>The Surprising Instantaneous Banning of ChatGPT In Italy</u></a></li>
</ul></div>

