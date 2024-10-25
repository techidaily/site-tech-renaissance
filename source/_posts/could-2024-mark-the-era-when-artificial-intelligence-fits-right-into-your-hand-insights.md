---
title: Could 2024 Mark the Era When Artificial Intelligence Fits Right Into Your Hand? Insights
date: 2024-10-21T20:17:23.482Z
updated: 2024-10-25T06:06:20.158Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c9308c3a6e3bd3b331c76fa1b44152ac54aefa6a4b58484c2ecd065884a25aa3.jpg
---

## Could 2024 Mark the Era When Artificial Intelligence Fits Right Into Your Hand? Insights

![man using phone](https://www.zdnet.com/a/img/resize/6cea2486f218870c083e8791504afe595f919250/2024/01/29/4ba711be-5530-4275-a6be-00ad401eea03/gettyimages-1440417504.jpg?auto=webp&width=1280)

Ippei Naoi/Getty Images

The world of [artificial intelligence](https://www.zdnet.com/article/what-is-ai-heres-everything-you-need-to-know-about-artificial-intelligence/) (AI) mostly exists in cloud-computing facilities and rarely touches your smartphone. When you use a tool like [ChatGPT to answer a prompt](https://www.zdnet.com/article/how-to-write-better-chatgpt-prompts-in-5-steps/), the hard work of training the program, so that it functions properly, has been done days, weeks, and months before, behind the scenes, in the enormous AI data centers built by Microsoft and others. 

However, 2024 could be the year the divide is crossed -- and it could be when AI starts to learn in your pocket. Efforts are underway to make it possible to train a neural net -- even a large language model (LLM) -- on your personal device, with little or no connection to the cloud. 

**Also: [I'm taking AI image courses for free on Udemy with this little trick - and you can too](https://www.zdnet.com/article/im-taking-ai-image-courses-for-free-on-udemy-with-this-little-trick-and-you-can-too/)**

The most obvious benefits of on-device training include: avoiding the delay incurred by having to connect to the cloud; learning from local information on a constant and personalized manner; and preserving privacy that would be violated by sending personal data to a cloud data center. 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

The impact of on-device training could be a transformation in the capabilities of neural networks. AI could be personalized to your own actions as you walk around, tapping, scrolling, and dragging. AI could learn from the environments you pass through during your daily routine, gathering signs about the world. 

**Also:** [**How Apple's AI advances could make or break the iPhone 16**](https://www.zdnet.com/article/how-apples-ai-advances-could-make-or-break-the-iphone-16/)

[Recent work by Apple engineers](https://www.zdnet.com/article/how-apples-ai-advances-could-make-or-break-the-iphone-16/) suggests the company is looking to bring larger neural networks, the "generative" kind represented by OpenAI's [ChatGPT](https://www.zdnet.com/article/what-is-chatgpt-and-why-does-it-matter-heres-everything-you-need-to-know/), to run locally on the iPhone.

More broadly, Google introduced a radically scaled-down AI approach called [TinyML](https://www.zdnet.com/article/google-ai-executive-sees-a-world-of-trillions-of-devices-untethered-from-human-care/) several years ago. TinyML can run neural nets in devices with as little as a milliwatt of power, such as smart sensors placed on machinery. 

The greater challenge for technology companies is to make those kinds of neural networks not just perform predictions on a phone, but also learn new things on a phone -- to carry out training locally. 

That effort takes far more processing power, far more memory, and far more bandwidth for any computer to train a neural net than to use the finished neural net to make predictions.

**Also:** [**Machine learning at the edge: TinyML is getting big**](https://www.zdnet.com/article/machine-learning-at-the-edge-tinyml-is-getting-big/)

Efforts have been underway to conquer that computing mountain by doing things such as selectively updating only portions of the neural net's "weights" or "parameters." A signature effort there is MIT's [TinyTL](https://hanlab.mit.edu/projects/tinytl), which uses what's called transfer learning as a way to refine a neural net that is already mostly trained. 

TinyTL has so far been used for small things, such as facial recognition. But the state of the art is now moving to tackling the LLMs of generative AI, including OpenAI's [GPT-4](https://www.zdnet.com/article/what-is-gpt-4-heres-everything-you-need-to-know/). The LLMs have hundreds of billions of neural weights that need to be kept in memory, and then passed to the processor to be updated as new information comes in. This training challenge takes place on a scale never before attempted. 

**Also: [7 ways to make sure your data is ready for generative AI](https://www.zdnet.com/article/7-ways-to-make-sure-your-data-is-ready-for-generative-ai/)**

[A research report this month](https://www.mdpi.com/2079-9292/13/2/402) by staff at European chip-making giant STMicroelectronics makes the case that it's not enough in these training efforts to perform inference on mobile devices -- instead, the client device must also train the neural network to keep it fresh.

"Enabling only model's inference on the device is not enough," write Danilo Pietro Pau and Fabrizio Maria Aymone. "The performance of the AI models, in fact, deteriorates as time passes since the last training cycle; phenomenon known as concept drift," for which the solution is to update the program with new training data. 

**Also:** [**How Google and OpenAI prompted GPT-4 to deliver more timely answers**](https://www.zdnet.com/article/how-google-and-openai-prompted-gpt-4-to-deliver-more-timely-answers/)

The authors suggest slimming down a neural net, so it's easier to train a model on a memory-constrained device. Specifically, they experiment with removing what's called "back-propogation", the mathematical method in LLMs that is the most compute-intensive part of training. 

Pau and Aymone found that replacing back-propogation with simpler math could reduce the amount of on-device memory needed for the neural weights by as much as 94%.

Some scientists advocate for splitting up the training task among many client devices, which is called "federated learning".

Federated learning in action.

QMUL

Researchers Chu Myaet Thwal and team at Kyung Hee University [this month adapted](https://arxiv.org/pdf/2401.11652.pdf) a form of LLM used for image recognition across as many as 50 workstation computers, each running a single Nvidia GPU gaming card. Their code took less memory on the device to train than the standard version of the neural net without losing accuracy.

Some experts, meanwhile, argue network communications will have to be adjusted, so mobile devices can communicate better when performing federated learning. 

**Also:** [**AI will change software development in massive ways, says MongoDB CTO**](https://www.zdnet.com/article/ai-is-going-to-change-software-development-in-massive-ways-says-mongodb-cto/)

Scholars at the Institute for Electrical and Electronic Engineering [this month hypothesized](https://arxiv.org/pdf/2401.02662.pdf) a communications network using the forthcoming 6G standard, where the bulk of LLM training is completed first in a data center. Then, the cloud coordinates a bunch of client devices that "fine-tune" the LLM with local data.

Such "federated fine-tuning", where each device learns some portion of an LLM, without starting from scratch, can be done with a lot less processing power on the battery-powered device than in full training.

Many approaches aim to reduce the memory and processing required for each neural weight. The ultimate approach is what's called "binary neural networks", where instead of each weight having a numeric value, the weights have only a one or a zero, which vastly reduces the amount of on-device storage required.

**Also:** [**Problems scaling AI? MIT proposes sub-photon optical deep learning at the edge**](https://www.zdnet.com/article/problem-scaling-ai-mit-proposes-sub-photon-optical-deep-learning-at-the-edge/)

A lot of the technical concerns mentioned above sound abstract, but consider some of the use cases of training a neural net locally. 

A team at Nanyang Technological University in Singapore [this month used on-device learning](https://arxiv.org/abs/2401.11968) to counter cyber threats by having each individual device train its own local version of an AI-based "intrusion-detection system" or IDS, which is a common cybersecurity program.

Instead of the client devices having to interact with a central server, the team was able to download an initial draft of the IDS code and then fine-tune it for local security conditions. Not only is such training more specific to a local security threat, it also prevents the passing of sensitive security information back and forth over the network, where it could be intercepted by malicious parties.

Apple is [rumored to be eyeing greater on-board AI functionality](https://www.zdnet.com/article/how-apples-ai-advances-could-make-or-break-the-iphone-16/) for iOS devices and has offered clues to what could be completed in a mobile context. 

In [a paper in August](https://arxiv.org/abs/2308.08726), Apple scientists described a way to automatically learn the qualities of mobile apps, called the Never-ending UI Learner. The program runs on a smartphone and automatically presses buttons and undertakes other interactions to determine which kinds of controls a user interface requires. 

Apple

The aim is to use each device to automatically learn, rather than relying on a bunch of human workers who spend their time pressing buttons and annotating app functions.

The experiment was undertaken in a controlled setting by Apple staff. If the trial was attempted in the wild using real customers' iPhones, then "a privacy-preserving approach would be needed (e.g., on-device training)," the authors write.

Another mobile-based concept was [described by Apple scientists in 2022](https://arxiv.org/abs/2207.08988) in a paper titled "Training Large-Vocabulary Neural Language Models by Private Federated Learning for Resource-Constrained Devices". 

Their goal was to train speech-recognition AI on mobile devices using the federated learning approach. 

**Also:** [**Nvidia makes the case for the AI PC at CES 2024**](https://www.zdnet.com/article/nvidia-makes-the-case-for-the-ai-pc-at-ces-2024/)

Each person's device uses samples of interactions with a "voice assistant" (probably Siri) to train the neural net. Then, the neural network parameters developed by each phone are sent to the network, where they're aggregated to make one improved neural net.

The big takeaway from all these research efforts is that scientists are hard at work trying to find ways of compressing and dividing the work of training to make it feasible on battery-operated devices with less memory and less processing power than workstations and servers. 

Whether this research effort breaks through in 2024 remains to be seen. However, what's already clear is that the training of neural networks is going to move out of the cloud and, quite possibly, into the palm of your hand.

#### Artificial Intelligence

[How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work](https://www.zdnet.com/article/how-chatgpt-scanned-170k-lines-of-code-in-seconds-and-saved-me-hours-of-work/ "How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work")

[6 ways to write better ChatGPT prompts - and get the results you want faster](https://www.zdnet.com/article/6-ways-to-write-better-chatgpt-prompts-and-get-the-results-you-want-faster/ "6 ways to write better ChatGPT prompts - and get the results you want faster")

[6 digital twin building blocks businesses need - and how AI fits in](https://www.zdnet.com/article/6-digital-twin-building-blocks-businesses-need-and-how-ai-fits-in/ "6 digital twin building blocks businesses need - and how AI fits in")

[Google's Gems are a gentle introduction to AI prompt engineering](https://www.zdnet.com/article/googles-gems-are-a-gentle-introduction-to-ai-prompt-engineering/ "Google's Gems are a gentle introduction to AI prompt engineering")

* [How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work](https://www.zdnet.com/article/how-chatgpt-scanned-170k-lines-of-code-in-seconds-and-saved-me-hours-of-work/ "How I used ChatGPT to scan 170k lines of code in seconds and save me hours of detective work")
* [6 ways to write better ChatGPT prompts - and get the results you want faster](https://www.zdnet.com/article/6-ways-to-write-better-chatgpt-prompts-and-get-the-results-you-want-faster/ "6 ways to write better ChatGPT prompts - and get the results you want faster")
* [6 digital twin building blocks businesses need - and how AI fits in](https://www.zdnet.com/article/6-digital-twin-building-blocks-businesses-need-and-how-ai-fits-in/ "6 digital twin building blocks businesses need - and how AI fits in")
* [Google's Gems are a gentle introduction to AI prompt engineering](https://www.zdnet.com/article/googles-gems-are-a-gentle-introduction-to-ai-prompt-engineering/ "Google's Gems are a gentle introduction to AI prompt engineering")

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
<li><a href="https://fox-friendly.techidaily.com/updated-from-start-to-end-mastering-the-art-of-fading-in-pro/"><u>[Updated] From Start to End Mastering the Art of Fading in Pro</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-cutting-edge-podcasting-garageband-edition/"><u>[Updated] In 2024, Cutting Edge Podcasting GarageBand Edition</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/apple-iphone-xs-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>Apple iPhone XS Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/best-group-video-conference-tools-of-the-year/"><u>Best Group Video Conference Tools of the Year</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722883401913-eliminate-that-humsong-from-your-subwoofers-with-these-simple-fixes/"><u>Eliminate That Humsong From Your Subwoofers with These Simple Fixes!</u></a></li>
<li><a href="https://article-posts.techidaily.com/exploring-vr-landscapes-perks-pitfalls-and-pivots/"><u>Exploring VR Landscapes Perks, Pitfalls and Pivots</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/free-entertainment-awaits-navigating-through-trial-periods-and-offers-on-netflix/"><u>Free Entertainment Awaits: Navigating Through Trial Periods and Offers on Netflix</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-boost-picture-clarity-on-an-iphone-with-low-megapixels/"><u>How to Boost Picture Clarity on an iPhone with Low Megapixels?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Motorola Razr 40? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-iphone-14-prevention-and-solution-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of iPhone 14 Prevention & Solution</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-ultimate-list-of-idevice-screen-recorders/"><u>In 2024, Ultimate List of iDevice Screen Recorders</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/iphone-not-playing-sounds-heres-what-you-need-to-know-and-fixes/"><u>IPhone Not Playing Sounds? Here's What You Need to Know and Fixes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-the-shift-a-beginners-walkthrough-for-establishing-your-x-presence/"><u>Navigating the Shift: A Beginner’s Walkthrough for Establishing Your X Presence</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/os-melhores-softwares-para-aprimorar-seu-portfolio-foto-em-2024-selecao-final-dos-melhores-da-industria/"><u>Os Melhores Softwares Para Aprimorar Seu Portfólio Foto Em 2024 - Seleção Final Dos Melhores Da Indústria</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722871991298-samsungs-newest-marvel-the-z-fold-er-4-find-out-when-it-drops-how-much-to-pay-and-its-features/"><u>Samsung's Newest Marvel - The Z Fold Er 4: Find Out When It Drops, How Much to Pay, and Its Features!</u></a></li>
<li><a href="https://driver-install.techidaily.com/solve-conflicts-for-windows-and-hp-printer-integration-woes/"><u>Solve Conflicts: For Windows and HP Printer Integration Woes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/transferring-visuals-from-mac-to-tv-mastering-the-art-of-airplay-connections/"><u>Transferring Visuals From Mac to TV: Mastering the Art of AirPlay Connections</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-guide-resolving-the-error-0x80004005-on-your-device/"><u>Troubleshooting Guide: Resolving the 'Error 0X80004005' On Your Device</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/what-to-know-about-the-new-iphone-17-expected-costs-release-schedule-tech-specs-and-hidden-gossip/"><u>What to Know About the New iPhone 17: Expected Costs, Release Schedule, Tech Specs & Hidden Gossip</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

