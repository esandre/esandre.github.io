---
title: "Contracts: specifying behavioral compositions in object-oriented systems"
layout: post
category: 'veille'
tags: langages
lang: french
ref: contracts-specifying-behavioral-compositions-in-object-oriented-systems
doi: 10.1145/97945.97967
link: https://dl.acm.org/doi/pdf/10.1145/97945.97967
---

📃 Les contrats ont été inventés en 1990 afin de compléter les interfaces des classes. Ces dernières donnent les signatures des méthodes exposées par une classe, mais ne disent rien du comportement que chacune des parties attend de l'autre. Les commentaires sont largment insuffisants, car il faut que de telles spécifications soient exécutables.

🌱 La première idée émise par les chercheurs fut d'intégrer les contrats dans les langages de programmation eux-mêmes. Cette idée n'a pas pris, mais les contrats sont loin d'être morts ! Les tests fonctionnels sont les héritiers directs de ce morceau d'histoire du logiciel. Plus éloignés, certains types de foncteurs (Maybe, Lazy, Either, ...) ou les systèmes de Tasks/Promises peuvent se rattacher à des contrats.

SOURCE

Richard Helm, Ian M. Holland, and Dipayan Gangopadhyay. 1990. Contracts: specifying behavioral compositions in object-oriented systems. SIGPLAN Not. 25, 10 (Oct. 1990), 169–180. DOI:10.1145/97946.97967