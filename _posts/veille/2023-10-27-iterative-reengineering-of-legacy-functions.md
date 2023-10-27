---
title: "Iterative reengineering of legacy functions"
layout: post
category: 'veille'
tags: patterns architecture
lang: french
ref: iterative-reengineering-of-legacy-functions
doi: 10.1109/ICSM.2001.972780
link: https://www.researchgate.net/profile/Alessandro-Bianchi-2/publication/3929891_Iterative_reengineering_of_legacy_functions/links/00b4952566d6a8293b000000/Iterative-reengineering-of-legacy-functions.pdf?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIn19
---

Ce que l'on connaît aujourd'hui sous le nom de Strangler Pattern en architecture trouve ses racines en 2001 dans un papier de 4 chercheurs italiens. Pour rappel, il s'agit d'encapsuler un composant Legacy afin de remplacer une à une ses fonctionnalités par leur équivalent dans une codebase propre. Les deux codebase cohabitent jusqu'à la fin du processus et la mort du Legacy se produit quand plus rien ne peut en être extrait.

Le papier décrit en détail le processus et donne un exemple. Le principe de tests d'équivalence, cousins des tests de non-régression est évoqué, afin de s'assurer que le nouveau système remplit le même service que l'ancien.

SOURCE

A. Bianchi, D. Caivano, V. Marengo and G. Visaggio, "Iterative reengineering of legacy functions," Proceedings IEEE International Conference on Software Maintenance. ICSM 2001, Florence, Italy, 2001, pp. 632-641, doi:10.1109/ICSM.2001.972780