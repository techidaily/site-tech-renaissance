---
title: Comment Effacer Le DRM Dans Un Fichier ePub À L'aide De ineptkey.pyw ?
date: 2024-08-20T10:30:04.599Z
updated: 2024-08-21T10:30:04.599Z
categories:
  - epubor
thumbnail: https://thmb.techidaily.com/d777118ee07b1ed845aaf5d08e4c5e0d9e2577a0d16959440201a2f851a46ee8.jpg
---

## Comment Effacer Le DRM Dans Un Fichier ePub À L'aide De ineptkey.pyw ?

[Accueil](http://www.epubor.com/fr/) \> [Guide](https://tools.techidaily.com/epubor/products/) \> [ineptkey.pyw télécharger](https://tools.techidaily.com/epubor/products/)

## Comment Utiliser ineptkey.pyw pour Supprimer DRM ePub

Voici donc la méthode simple, comme promis. On va utiliser un script Python pour décrypter le fichier, ce qu’il signifie qu’il faudra installer Python. Il n’y a rien de plus compliqué dans cette méthode qu’installer des logiciels, créer des dossiers et y déplacer des fichiers. Allons-y !

### Supprimer DRM ePub avec Python

Une fois le livre numérique téléchargé dans **Adobe Digital Editions**grâce à notre **ID Adobe**, on récupère le fichier ePub équivalent qui se trouve dans le dossier **Digital Editions** (par défaut dans notre dossier système **Documents**).

On télécharge et on installe [**Python**](http://www.python.org/download/) (logiciel permettant de faire tourner les scripts en langage python). On télécharge et on installe [**PyCrypto**](http://www.voidspace.org.uk/downloads/pycrypto-2.0.1.win32-py2.6.exe) (logiciel de cryptographie écrit en langage python).

Attention à bien prendre la version de **PyCrypto**correspondant à la version de **Python** que vous avez installée (actuellement, la 2.7).

On télécharge les scripts Python **ineptkey.pyw** et **ineptepub.pyw** qui vont permettre de décrypter notre fichier ePub. On les trouve très facilement en cherchant sur Google.

On double-clique sur le fichier **ineptkey.pyw** : celui-ci va récupérer la clé qu’utilise **Adobe Digital Editions** pour crypter les fichiers et créer avec un nouveau fichier **adeptkey.der** (ADEPT pour _Adobe Digital Experience Protection Technology_, les fameux DRM d’Adobe)

On double-clique ensuite sur le fichier **ineptepub.pyw**, qui nous propose trois champs à remplir : _Key file_, qui contient par défaut le fichier**adeptkey.der** que l’on vient de créer (on n’y touche pas), _Input file_, où l’on pourra sélectionner notre fichier ePub protégé et _Output file_, dans lequel on choisira où enregistrer le nouveau fichier ePub sans DRM.

Une fois les trois fichiers sélectionnés, on clique sur **Decrypt**, et c’est terminé !

(Si vous obtenez l’erreur **Problem decrypting session key**, il est possible que votre version du fichier **ineptkey.pyw** soit trop ancienne, téléchargez une version la plus récente. A l’heure où j’écris ces lignes, la bonne est la 4.3 pour Adobe Digital Editions 1.7.2.).

Nous voilà maintenant avec un beau fichier ePub dépourvu de DRM ! On peut l’utiliser sur n’importe quel support de lecture gérant le format ePub (soit à peu près toutes, sauf le Kindle d’Amazon) y compris ceux ne gérant pas les DRM Adobe, comme l’iPhone.

#### Tips:

* [Supprimer DRM d'Amazon Kindle. AZW eBooks](https://tools.techidaily.com/epubor/products/)
* [Supprimer les Adobe DRM des eBooks PDF et ePub](https://tools.techidaily.com/epubor/products/)
* [Partager Le Kindle Ebook Avec Des Amis](https://tools.techidaily.com/epubor/products/)
* [Comment Lire eBooks Kindle sur Kobo Vox](https://tools.techidaily.com/epubor/products/)
* [Comment Lire Google eBooks sur Kindle Fire](https://tools.techidaily.com/epubor/products/)
  
  
Copyright © 2011-2021 www.epubor.com. Tous droits réservés. 

[Accueil](http://www.epubor.com/fr/) | [Contact](http://www.epubor.com/fr/mailto:support@epubor.com)

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
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->