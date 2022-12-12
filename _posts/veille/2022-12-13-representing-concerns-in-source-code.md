---
title: "Representing concerns in source code"
layout: post
category: 'veille'
tags: codesmithing thesis
lang: french
ref: representing-concerns-in-source-code
doi: 10.1145/1189748.1189751
---

🔍 Pierre Boutang considérait la politique comme souci. Martin Robillard, lui, fait de même avec le code. Lorsque nous voulons l'éditer, il nous faut d'abord savoir quelles parties seront sous notre scalpel. Ce que nous recherchons alors, à coup de lecture de tests pour les plus chanceux ou de rétro-ingénierie pour les plus audacieux, ce sont des soucis (concerns en V.O). 

❌ Chaque souci est un aspect du problème global résolu par le projet dans son ensemble. Hélas, il arrive fréquemment qu'un même souci soit adressé par plusieurs parties du code, on parle alors de "scattered concern", un souci éparpillé. L'inverse survient quand un même code adresse plusieurs souci à la fois, on parle de "tangled concerns", de soucis enchevêtrés.

✔️ Les canons du design conceptuel nous enseignent qu'un faut une bijection concept-problème pour faire un bon logiciel. Martin Robillard affirme qu'il faut également une bijection souci-module. Ces deux bijections sont des généralisations à des échelles différentes du plus grand principe de l'orienté-objet : Single Responsibility Principle (SRP).

SOURCE

Robillard, Martin & Murphy, Gail. (2007). Representing concerns in source code. ACM Trans. Softw. Eng. Methodol.. 16. 10.1145/1189748.1189751. 