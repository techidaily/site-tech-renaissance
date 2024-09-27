---
title: Manifest V2 Extensions Face Obsolescence as Google Chrome Advances
date: 2024-08-30T14:38:08.532Z
updated: 2024-08-31T14:38:08.532Z
tags:
  - web
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/2-2.jpg
---

## Manifest V2 Extensions Face Obsolescence as Google Chrome Advances

Google introduced a new standard for Chrome browser extensions, Manifest V3, back in 2021\. Now, Google is finally saying goodbye to the older Manifest V2 standard, potentially leaving many extensions behind.

 Google said [last year](https://facebook-video-share.techidaily.com/updated-attract-more-viewers-boosting-your-youtube-following-for-2024/) that the phase-out period for Manifest V2 extensions would start around June 2024, and the company is sticking to that schedule. Starting on June 3, 2024, in the Chrome Beta, Dev, and Canary channels, older Manifest V2 extensions will display a warning about being unsupported. Over the next few months, those extensions will be fully turned off, and then eventually removed from the Chrome Web Store.

 The company’s blog post explained, “Like any big launches, all these changes will begin in pre-stable channel builds of Chrome first – Chrome Beta, Dev, and Canary. The changes will be rolled out over the coming months to Chrome Stable, with the goal of completing the transition by the beginning of next year. Enterprises using the ExtensionManifestV2Availability policy will be exempt from any browser changes until June 2025.”

[Manifest V3](https://developer.chrome.com/docs/extensions/mv3/intro/) is the latest software platform for Chrome extensions, intended to make extensions faster and more secure. The change has been controversial due to Google's removal of the webRequest API, which is used by content blocker extensions to filter out network traffic. The API was replaced with [declarativeNetRequests](https://developer.chrome.com/docs/extensions/reference/declarativeNetRequest/), which was initially far more limited (thus the controversy), but Google has made several upgrades over the past two years and fixed most of its issues. Most content blocker extensions now have Manifest V3 versions available.

 Google says that “over 85% of actively maintained extensions” in the Chrome Web Store are already updated to Manifest V3\. That number will likely go up a bit over the next month or two, as extension developers rush out updated versions before the clock runs out. You can check your own extensions by opening chrome://extensions-internals in Chrome and searching for “manifest\_version” on the page.

 Microsoft Edge is based on Chrome and uses many of the same extensions, but Microsoft has [not yet confirmed](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/developer-guide/manifest-v3) when Manifest V2 extensions will be kicked from Edge. Mozilla Firefox uses a different extension architecture with changes to Manifest V3, and it doesn’t have plans right now to remove Manifest V2 extensions.

 Source: [Chromium Blog](https://blog.chromium.org/2024/05/manifest-v2-phase-out-begins.html)

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



<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->