# Les modules ES6

Un module ES6 est un fichier contenant du code JavaScript. Il n’y a pas de mot-clé spécifique module, un module est lu comme un script. Il y a deux différences :

Les modules ES6 sont considérés comme écrits en mode strict, même si vous n’écrivez pas "use strict";
Vous pouvez utiliser import et export dans les modules.

Les modules ES6 :

- ont une syntaxe simple et sont basés sur le découpage en fichiers (un module = un fichier),
- sont automatiquement en mode « strict »,
- offrent un support pour un chargement asynchrone.

## Export

Parlons d’abord d’`export`. Par défaut, tout ce qui est déclaré dans un module lui est local. Si vous voulez que quelque chose de déclaré dans un module soit public, afin que les autres modules puissent l’utiliser, vous devez l’exporter. Il existe plusieurs façons de faire. La plus simple est d’utiliser le mot-clé export.

Et c’est vraiment tout ce dont vous avez besoin pour écrire un module ! Vous n’avez rien à mettre dans un [IIFE](https://en.wikipedia.org/wiki/Immediately-invoked_function_expression) ou une fonction de rappel (callback). Allez-y et déclarez simplement ce qui est nécessaire. Puisque le code est un module et non un script, toutes les déclarations seront encapsulées dans ce module et ne seront pas visibles de façon globale pour les autres scripts et modules. Il suffit d’exporter les déclarations qui forment l’API publique de votre module.

## import

on peut également importer des modules.

## bibliographie et sources

- [https://tech.mozfr.org/post/2015/08/21/ES6-en-details-%3A-les-modules](https://tech.mozfr.org/post/2015/08/21/ES6-en-details-%3A-les-modules)
- [http://exploringjs.com/es6/ch_modules.html](http://exploringjs.com/es6/ch_modules.html)
- [https://laravel.sillo.org/es6-les-modules/](https://laravel.sillo.org/es6-les-modules/)
