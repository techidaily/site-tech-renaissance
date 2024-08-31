---
title: Guide to Integrating Self-Taken Pictures Into the MidJourney Experience
date: 2024-08-26 17:35:50
updated: 2024-08-29 10:54:50
tags:
  - cutting-edge
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/mj-image-prompt.png
---

## Guide to Integrating Self-Taken Pictures Into the MidJourney Experience

### Key Takeaways

1. Upload your image to the Discord server.
2. Copy the link to the image you've uploaded.
3. Write a normal MidJourney prompt but insert your image link after the "/imagine" command.
4. To further influence the style and composition of the generated art, set the image weight and aspect ratio parameters.

 We've marveled as MidJourney just keeps improving, but it's still hard to have precise control of what you get after your prompt is submitted. By starting off with an existing image, you can steer what sort of art you get.

 In this guide, I assume you already know the basics of how to use MidJourney. If you don't, it's a good idea to read our [MidJourney primer](https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/) first.

##  Sending Your Image to The MidJourney Discord Bot

 Assuming that you have an existing image that's close to what you want (e.g. a person in the right pose) you first need to send that image to the MidJourney Discord Bot.

 Don't submit any sensitive or private images into the Discord chat with the MidJourney Discord bot. If you're using the cheapest tier of the MidJourney service which does not have "stealth" mode, your output images are public, and there's no guarantee that your source image won't ever end up where it shouldn't. Only ever send images in any chat app that you're 100% comfortable showing to anyone.

 Using the [Discord desktop app](https://extra-lessons.techidaily.com/best-of-the-best-ultimate-list-of-gopro-casings-for-2024/), simply upload your image using the "+" upload button, or drag and drop the image into the chat.

![Click or tap the + (addition sign) icon to upload a photo to the MidJourney Discord server.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/screenshot-2023-07-27-at-13-36-21.png) 

Adding an image to the Discord Chat

##  Getting the Image Link

 Now that you've uploaded your image to the Discord servers and its visible in your chat, we need to extract the link pointing directly at the image file. To do this, [right-click](https://desktop-recording.techidaily.com/updated-the-art-of-recording-fun-6-techniques-to-document-minecraft-for-2024/) on the image and select "Copy link". (If you're on the mobile app, tap and hold the image, then select "Copy media link.") Be careful not to click "Copy image" since this copies the image itself to the clipboard rather than the hyperlink.

![Copy the link to the image you just uploaded.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/screenshot-2023-07-27-at-14-15-22.png) 

Copying a Discord image link

 If you paste the contents of the clipboard into your chat box or any other text field, you'll see this long string ending in an image extension, in this case .[JPG](https://change-location.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-vivo-y27s-drfone-by-drfone-virtual-android/).

##  Constructing Your Prompt

 Start your prompt the usual way by typing "/imagine" and then pressing the spacebar.

![Start typing a regular prompt in the Discord server.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/screenshot-2023-07-27-at-13-36-28.png) 

Starting a MidJourney Prompt

 Now, paste the image link as the very first part of the prompt.

![Paste the link to your image.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/screenshot-2023-07-27-at-13-36-31.png) 

Pasting image link into MidJourney prompt

 Now you can write the actual prompt. While you can write anything you like, the idea here is to write something that makes sense based on the image you uploaded. MidJourney will start with your image as the initial point rather than random noise, so in most cases you should get something that resembled the composition of your image.

 In this case, I snapped a photo of one of my Star Trek models, and so for this prompt we'll go with "Starship Enterprise Star Trek flying in space epic concept art".

![Type your prompt after the image link.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/screenshot-2023-07-27-at-13-36-46.png) 

Adding Prompt to image link in MidJourney

 Don't submit the prompt yet, because we have to include two more important parameters.

##  Setting the Image Weight and Aspect Ratio

 The _image weight_ parameter tells MidJourney how closely it should stick to the original picture. The image weight parameter for [MidJourney V5](https://instagram-clips.techidaily.com/2024-approved-visual-storytelling-on-social-media-crafting-an-effective-plan/) (5.2 is the latest as of this writing) can range from 0-2\. With an image weight of 2, the result will be strongly inspired by the image prompt, but something like 0.5 will only loosely inspire it.

 Here we're going to add the parameter "--iw 2" at the end of our prompt.

![Use weight parameters to modify how the output image will look.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/screenshot-2023-07-27-at-13-36-52.png) 

Adding Image Weights to MidJourney

 Next, we'll specify the aspect ratio. MidJourney makes square images by default, but that's not always what you need. Our image prompt is square as well, but we're going to widen it to 16:9, which is the most common widescreen [aspect ratio](https://youtube-lab.techidaily.com/gateway-to-youtube-entrepreneurship-the-best-10-easy-to-create-channels/). To do this, we add "--ar 16:9" to the end of the prompt.

![Specify the aspect ratio you want for the output image.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/screenshot-2023-07-27-at-13-37-06.png) 

MidJourney aspect ratio paramter

 Now, finally, we're ready to submit.

![Photo of a Starship Enterprise model slightly modified by MidJourney.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/gendowasright_starship_enterprise_star_trek_flying_in_space_epi_604c28b5-c888-4b76-9500-9373b72c9e18.png) 

MidJourney / How-To Geek / Sydney Butler

 This hasn't turned out very well at all! This is because the image weight setting is too high. So let's run the same prompt again, but this time at 1.5.

![Starship Enterprise image generated by MidJourney.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/gendowasright_starship_enterprise_star_trek_flying_in_space_epi_9bf9a007-76d2-4a6e-a62e-f88ae8120e47.png) 

MidJourney / How-To Geek / Sydney Butler

 Much better! Let's try again at 0.5.

![An image of the Starship Enterprise generated by MidJourney with space in the background.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/gendowasright_starship_enterprise_star_trek_flying_in_space_epi_b3e39e49-1e28-4a03-8089-e08e1b2cb912.png) 

MidJourney / How-To Geek / Sydney Butler

 And now we have a pretty cool result!

 Using image prompts isn't an exact science, and it's not like other generative AI techniques such as inpainting, but it does give you significantly more control over where MidJourney starts its process, making more creative choices possible.

---

 If you want to do more with Midjourney, check out [our guide to Midjourney models](https://instagram-clips.techidaily.com/2024-approved-visual-storytelling-on-social-media-crafting-an-effective-plan/), or [how to make awesome wallpapers with MidJourney](https://youtube-lab.techidaily.com/gateway-to-youtube-entrepreneurship-the-best-10-easy-to-create-channels/).

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
