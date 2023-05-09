---
title: "Programmers use slices when debugging"
layout: post
category: 'veille'
tags: codesmithing
lang: french
ref: programmers-use-slices-when-debugging
doi: 10.1145/358557.358577
link: https://dl.acm.org/doi/pdf/10.1145/358557.358577
---

🐛 Lorsque nous débuggons, nous n'utilisons pas les mêmes représentations mentales que lorsque nous programmons. En réalisant un code, nous pensons les blocs que nous construisons. Lorsqu'il s'agit de le corriger, nous adoptons une autre représentation mentale que Mark Weiser nomme les Slices.

🔪 Une Slice s'obtient en retirant tout ce qui ne nous semble pas faire partie de la cause d'un bug dans un code. Ne restent à la fin qu'une poignée de variables et de méthodes éparses, que le développeur pense être de bons candidats pour l'origine du bug. Ces Slices sont rarement composés de morceaux de code contigus.

💡 Cette découverte n'apporte rien en elle-même, mais a ouvert la voie à de nombreux papiers en pédagogie du développement, en maintenance, en psychologie, etc.

SOURCE

Weiser, Mark D. “Programmers use slices when debugging.” Commun. ACM 25 (1982): 446-452. DOI:10.1145/358557.358577