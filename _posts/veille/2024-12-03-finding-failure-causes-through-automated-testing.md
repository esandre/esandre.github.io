---
title: "Finding Failure Causes through Automated Testing"
layout: post
category: 'veille'
tags: testing
lang: french
ref: finding-failure-causes-through-automated-testing
doi: 10.48550/arXiv.cs/0012009
link: https://arxiv.org/abs/cs/0012009
---

🐛 Une révision fonctionne, alors qu'une autre bugge. C'est presque une routine. Le développeur doit alors rechercher la cause racine du bug et la corriger. L'usage de tests dans ce processus est ancien, bien qu'il ne soit apparu dans la littérature scientifique qu'autour des années 2000. L'idée est simple : reproduire le bug dans un cas de test pour l'empêcher de revenir. C'est le defect testing. Hélas, cette technique n'aide pas à trouver la cause racine, ce qui représente 95% du temps de debug.

🧪 Deux chercheurs allemands proposent d'utiliser les tests afin de repérer la cause racine. Il faut pour cela deux révisions séparées par un delta. Dans la première, le test de défaut fonctionne, dans l'autre celui-ci est cassé. L'étape suivante est de trouver le scénario minimal dans lequel le bug se produit, en diminuant la quantité de changements du delta. Cette étape n'est pas obligatoire, mais réduit largement la quantité de calculs nécessaires ensuite. La dernière étape consiste à muter le code afin de trouver le plus petit jeu de changements provoquant le bug, donc faisant passer au rouge le test de défaut. Cette étape est extrêmement lourde en calculs, car le nombre de mutants à générer et tester est immense.

🗜️ Cette technique n'est pas utilisée en l'état par les praticiens, à ma connaissance. Elle pourrait cependant être à l'origine du shrinking utilisé en property-based testing.

SOURCE

Cleve, Holger and Andreas Zeller. “Finding Failure Causes through Automated Testing.” arXiv: Software Engineering (2000) DOI:10.48550/arXiv.cs/0012009