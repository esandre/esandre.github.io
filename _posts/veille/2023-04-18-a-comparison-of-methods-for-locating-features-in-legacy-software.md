---
title: "A comparison of methods for locating features in legacy software"
layout: post
category: 'veille'
tags: codesmithing testing
lang: french
ref: a-comparison-of-methods-for-locating-features-in-legacy-software
doi: 10.1016/S0164-1212(02)00052-3
link: http://www.cs.wayne.edu/~severe/publications/Wilde.JSS.2003.Comparison.pdf
---

🏚️ Lorsqu'il s'agit de savoir quels morceaux de code legacy sont reliés à une feature que l'on veut éditer, nous avons plusieurs outils à notre disposition, tous complémentaires.

🔍 Le plus simple est le bon vieux Ctrl+F/grep. Rapide, mais peu précis, il est très dépendant à la qualité du nommage, rarement exemplaire dans le code legacy. Les auteurs le recommandent en première intention, pour se familiariser avec le code.

🔦 Vient ensuite la reconnaisance logicielle, utilisant des tests afin de repérer quelles parties du code sont appelées par ceux-ci. Cette méthode est détaillée sur cette veille [10.1109/ICSM.1992.242542]({% link _posts/veille/2023-04-13-locating-user-functionality-in-old-code.md %}). Il s'agit de la méthode la plus fiable, mais aussi de la plus lourde à mettre en place. Elle est en outre incapable de repérer des concepts, contrairement aux deux autres.

🪢 Enfin, les graphes de dépendance peuvent parfois servir, mais il dépendent d'une bonne structuration du code en module, rarement présente dans les code legacy.

🧰 Ces trois outils se complètent dans la boîte à outils du développeur faisant face au code legacy.

SOURCE

Wilde, Norman, Michelle Buckellew, Henry Page, Václav Rajlich and LaTreva Pounds. “A comparison of methods for locating features in legacy software.” J. Syst. Softw. 65 (2003): 105-114. DOI:10.1016/S0164-1212(02)00052-3