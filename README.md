# XMLHttpRequest Progress

>Un exercice pour manipuler au moins une fois "l'ancien" AJAX et écouter ses divers événements et surtout celui de progression

### Énoncé

- Vous devez requêter en **méthode `GET`** le fichier json (en cross-domain) "stocké" sur IPFS
- Vous devez écouter chaque évènement indiqué dans la liste ci-dessous avec une fonction de callback spécifique
- La fonction de callback du `progress` doit augmenter la valeur de l'élément progress html au fur et à mesure du chargement

--> ajouter en plus un pourcentage arrondi à 2 décimales

- La fonction de callback `loadend` doit afficher le contenu du fichier dans la div `output`

### Liste des événements à écouter

>Pour cet exercice il est exigé d'écouter les évènements avec la fonction `addEventListener`

- progress
- load
- loadend
- error

### Technologies utilisées

- [XMLHttpRequest](https://developer.mozilla.org/fr/docs/Web/API/XMLHttpRequest/Utiliser_XMLHttpRequest)
- [addEventListener](https://developer.mozilla.org/fr/docs/Web/API/EventTarget/addEventListener)
- [élement HTML progress](https://www.alsacreations.com/article/lire/1416-html5-meter-progress.html)

___

:bulb: Aide pour "simuler un long chargement du fichier"

- Il est conseillé d'utiliser Firefox pour éviter les problèmes de ~~restriction CORS~~
- Dans la section "Réseau" ou "Network" de Firefox, cliquez sur "_Désactiver le cache_"
- Toujours dans la section "Réseau" ou "Network" de Firefox, choisissez une limitation de bande passante "_Regular 3G_"

![firefox network tab](https://ipfs.infura.io/ipfs/QmcHiGbrs9uEWmpgNSn67FYV9WydoiP8jBycZLgn6rggfF)
