---
title: "A rational design process: How and why to fake it"
layout: post
category: 'veille'
tags: methods
lang: french
ref: a-rational-design-process-how-and-why-to-fake-it
doi: 10.1109/TSE.1986.6312940
link: https://www.cs.tufts.edu/~nr/cs257/archive/david-parnas/fake-it.pdf
---

🧮 *Errare humanum est*, dit la locution. Les auteurs ne croyaient déjà pas à la possibilité d'une méthode formelle de développement logiciel en 1986. Nous ne seront jamais des mathématiciens déduisant un théorème à partir d'axiomes, car si le logiciel est écrit dans un langage strict, son objet est ô combien humain.

📚 Parnas et Clements soutiennent cependant l'utilité de feindre la rationalité, autrement dit de produire au cours du projet la même qualité de documentation que celle qui aurait été nécessaire pour produire un logiciel valide du premier coup. C'est un effort substantiel, mais payant selon eux.

📑 Quelles sont les propriétés d'une bonne documentation ? Elle est organisée hiérarchiquement afin d'optimiser la recherche d'informations, non l'écriture. Elle contient le moins possible de prose, remplacée par des diagrammes, schémas, formules, etc. Elle est complète et ne contient qu'une seule fois chaque information. Elle utilise des espaces de noms pour éviter la confusion de termes équivoques. 

✅ Toutes ces propriétés se retrouveront 20 ans plus tard dans les recommandations pour écrire de bons tests d'acceptation : il n'y a pas de mystère, un test d'acceptation n'est pas autre chose qu'une documentation exécutable.

SOURCE

David Lorge Parnas and Paul C. Clements. 2001. A rational design process: how and why to fake it. Software fundamentals: collected papers by David L. Parnas. Addison-Wesley Longman Publishing Co., Inc., USA, 355–368. DOI:10.1109/TSE.1986.6312940