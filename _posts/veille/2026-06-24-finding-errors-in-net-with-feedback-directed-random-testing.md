---
title: "Finding errors in .net with feedback-directed random testing"
layout: post
category: 'veille'
tags: testing
lang: french
ref: finding-errors-in-net-with-feedback-directed-random-testing
doi: 10.1145/1390630.1390643
link: http://www.bodden.de/wordpress/wp-content/uploads/wlw-images/ISSTA2008recap_D661/p87.pdf
---

🎲 Le random testing est-il capable de trouver des bugs sur un composant déjà extrêmement bien testé ? Pour le savoir, un chercheur du MIT a collaboré avec Microsoft, pour avoir accès à l'un des composants les mieux testés de l'environnement .NET. 40 ingénieurs ont déjà qualifié ce composant, jugé extrêmement robuste. 

🔎 L'usage de tests générés aléatoirement à partir du code ont permis de trouver 30 erreurs classées comme sérieuses en moins de 15h de travail. Mieux, des erreurs ont été détectées dans l'outillage de test lui-même, qui était incapable de vérifier certains scénarios correctement. La random testing est un excellent oracle permettant d'évaluer la qualité d'une démarche de test, pour un coût modique.

SOURCE

Pacheco, Carlos, S. Lahiri and Thomas Ball. “Finding errors in .net with feedback-directed random testing.” International Symposium on Software Testing and Analysis (2008). DOI:10.1145/1390630.1390643