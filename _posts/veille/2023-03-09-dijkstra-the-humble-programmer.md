---
title: "The Humble Programmer"
layout: post
category: 'veille'
tags: codesmithing expert
lang: french
ref: dijkstra-the-humble-programmer
link: https://www.cs.utexas.edu/~EWD/transcriptions/EWD03xx/EWD340.html
---

👴 Dijkstra est une personnalité du développement. Il est notre Confucius, largement cité, rarement lu. Un de ses plus célèbres papiers, The Humble Programmer raconte son histoire avec la programmation. Dans sa seconde partie, il disserte sur l'avenir de notre profession et sa condition de survie : atteindre la performance. Cela signifie que les développeurs ne doivent pas passer la majorité de leur temps à débugger, donc que les développeurs ne doivent plus mettre de bugs dans leurs programmes, tout simplement.

🐛 Comment atteint-on cette performance ? En créant des programmes intellectuellement maniables. Comment fait-on cela ? En remettant la célèbre citation de Dijkstra dans son contexte : "Tester peut être une manière efficace de trouver des bugs, mais jamais de prouver leur absence". 

🧪 Dijkstra parle ici des tests manuels après le développement. Il recommande plutôt de développer la preuve de validité et le programme main dans la main, car il s'agit de la seule manière de ne pas avoir de bugs. Un programme dont les tests sont l'ultime spécification n'a pas de bugs, seulement des tests manquants. Il suffit d'écrire ces tests pour ne jamais voir revenir ce "bug".

♻️ Mieux, lorsque l'on a écrit une preuve de validité, il est possible d'itérer afin de trouver le programme valide le plus intellectuellement maniable. Le mot "refactoring" n'existe pas encore, mais le concept est posé. Alors, Dijkstra, un précurseur de TDD ?

SOURCE

Edsger W. Dijkstra, The Humble Programmer, ACM Turing Lecture 1972, EWD340