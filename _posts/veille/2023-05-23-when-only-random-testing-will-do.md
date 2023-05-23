---
title: "When Only Random Testing Will Do"
layout: post
category: 'veille'
tags: testing
lang: french
ref: when-only-random-testing-will-do
doi: 10.1145/1145735.1145737
---

🎲 Les tests aléatoires sont mal vus. Au mieux un moyen de découvrir des bugs supplémentaires, au pire une stratégie de la dernière chance. Dick Hamlet tente de les réhabiliter et d'en faire la méthode de test de première intention pour deux classes de problèmes.

🎆 Lorsque le nombre de cas de test possibles pour un composant est trop élevé et qu'il n'est pas possible de repérer des valeurs limites pertinentes, on parle d'éparpillement des échantillons (sparse sampling). Il s'agit du premier cas dans lequel l'aléatoire s'en sort mieux que le déterminisme.

💾 Quant un programme manipule un état persistent, les développeurs tendent à abstraire celui-ci afin de contourner le problème. Ce faisant ils ne s'y attaquent pas vraiment. L'aléatoire peut résoudre ce problème. Il faut voir un test comme une série d'actions réalisées à partir d'un état persistent de départ. Ici, l'aléatoire concerne quelles actions seront réalisées dans quel ordre, non les valeurs injectées. Cette seconde partie est plus exigeante à lire.

🔀 L'auteur souligne que les méthodes présentées ne remplacent pas les tests déterministes, mais les complètement. Ainsi un même composant peut parfaitement être testé sous ces deux modes pour en tirer le meilleur. 

SOURCE

Dick Hamlet. 2006. When only random testing will do. In Proceedings of the 1st international workshop on Random testing (RT '06). Association for Computing Machinery, New York, NY, USA, 1–9. DOI:10.1145/1145735.1145737