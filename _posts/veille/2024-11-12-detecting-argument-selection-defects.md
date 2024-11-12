---
title: "Detecting Argument Selection Defects"
layout: post
category: 'veille'
tags: codesmithing
lang: french
ref: detecting-argument-selection-defects
doi: 10.1145/3133928
link: https://dl.acm.org/doi/pdf/10.1145/3133928
---

🔀 L'inversion de paramètres d'appel d'une fonction est un défaut courant, qui peut rester indétecté longtemps si la couverture de tests n'est pas bonne. Une équipe germano-américaine comptant des chercheurs de Google a voulu déterminer la meilleure approche pour détecter ce problème à l'aide d'un analyseur statique.

💡 L'outillage qu'ils ont développé obtient un score de détection honorable, mais là n'est pas le principal fruit du papier. Ils sont surtout démontré, si c'était encore nécessaire que l'usage de Builder doit toujours être préféré à des paramètres pléthoriques, qu'il faut respecter les conventions (expected avant actual dans les tests) et que l'héritage doit respecter l'ordre des paramètres.

🫙 J'ajoute que si les développeurs cessaient d'utiliser des primitives au profit de types encapsulés, ils n'auraient même pas à se poser la question. Avec 64% de la profession utilisant JS, c'est une utopie.

SOURCE

Andrew Rice, Edward Aftandilian, Ciera Jaspan, Emily Johnston, Michael Pradel, and Yulissa Arroyo-Paredes. 2017. Detecting argument selection defects. Proc. ACM Program. Lang. 1, OOPSLA, Article 104 (October 2017), 22 pages. DOI:10.1145/3133928