---
title: "Debugging reinvented"
layout: post
category: 'veille'
tags: methods
lang: french
ref: debugging-reinvented
doi: 10.1145/1368088.1368130
link: http://courses.cs.washington.edu/courses/cse503/11au/readings/KoM2008.pdf
---

🔍 Une fois localisée l'origine de l'erreur, celui qui débugge doit savoir pourquoi la valeur est erronnée. Les débuggers actuels sont laborieux car ils expliquent quelle est la valeur d'une variable, non qui la lui a donnée. Une équipe de Carnegie-Mellon a conçu un outil fonctionnel permettant de suivre les éditions successives d'une variable afin de répondre à la question la plus chronophage du debug : pourquoi ?

💣 Ils sont mêmes allés plus loin : parfois une valeur devrait changer, mais ne change pas. A l'aide d'heuristiques simples, ils ont pu répondre également à la question "pourquoi pas ?".

❓ A ce jour, je ne connais aucun outil de debug utilisant ce principe. Quelqu'un en connaît-il un ?

SOURCE

Ko, Amy J. and Brad A. Myers. “Debugging reinvented.” 2008 ACM/IEEE 30th International Conference on Software Engineering (2008): 301-310. DOI:10.1145/1368088.1368130