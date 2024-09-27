---
title: Future-Proofing Privacy with Apple's PQ3 Technology Against Upcoming Quantum Threats
date: 2024-08-30T14:40:43.826Z
updated: 2024-08-31T14:40:43.826Z
tags:
  - cutting-edge
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/52763018018_14074323db_o.jpg
---

## Future-Proofing Privacy with Apple's PQ3 Technology Against Upcoming Quantum Threats

The upcoming iOS 17.4 update brings [PQ3 encryption](https://security.apple.com/blog/imessage-pq3/) to iMessage. This cryptographic protocol anticipates future threats that may arrive in the era of quantum computing. In theory, the PQ3 implementation makes iMessage the most secure messaging platform in the world.

 iMessage was one of the first mainstream messaging platforms to implement [end-to-end encryption](https://extra-hints.techidaily.com/new-13-creative-ways-to-save-and-store-online-audio-broadcasts/) (E2EE) by default. When a message is protected by E2EE, it's turned into a mess of gibberish that can only be decoded by a set of cryptographic keys. The message's sender and recipient are the only ones who own these keys. If a hacker intercepts your message, or if an Apple employee decides to invade your privacy, they'll be met with an unreadable string of text.

 Cryptographic keys are based on math problems that today's computers cannot solve. But security experts believe that quantum computers, which do not exist yet, will solve these classical math problems. Hackers and governments may prepare for this development by collecting and storing encrypted data for decryption at a later date—a so-called "Harvest Now, Decrypt Later" scheme that would retroactively compromise E2EE messages.

 Therefore, a protocol that defends against quantum attacks needs to exist _before_ we enter the era of quantum computing. Signal introduced such a protocol, called [PQXDH](https://signal.org/blog/pqxdh/), back in September 2023\. Apple is now doing the same with PQ3 in iMessage.

 Like Signal's PQXDH protocol, PQ3 is a "post-quantum cryptography" method that uses new algorithms to generate keys. These algorithms—math problems—_should_ be too difficult for quantum computers to solve. Apple's method provides an additional layer of protection by regularly generating new keys with "PQC rekeying," meaning that only one portion of a conversation will be compromised if a key is cracked.

 The PQ3 method also retains the protections of "classical cryptography," specifically E2EE. And iMessage is still protected by [Contact Key Verification](https://support.apple.com/en-us/HT213465), a security protocol that prevents hackers from impersonating a message's sender or recipient.

 There isn't a standardized way to rank cryptography methods in the post-quantum era. So, Apple has created its own ranking system which designates E2EE as a "Level 1" protection method. Signal's PQXDH implementation is "Level 2," while Apple's PQ3 is "Level 3" because it utilizes PQC rekeying, which is currently unique to iMessage.

 Post-quantum cryptography will be enabled by default in the iOS 17.4 update, and it's already live in the 17.4 beta. For additional details on PQ3 in iMessage, check out [Apple's blog](https://security.apple.com/blog/imessage-pq3/).

 Source: [Apple](https://security.apple.com/blog/imessage-pq3/)

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
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->