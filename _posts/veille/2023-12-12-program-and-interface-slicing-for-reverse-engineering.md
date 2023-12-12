---
title: "Program and interface slicing for reverse engineering"
layout: post
category: 'veille'
tags: methods
lang: french
ref: program-and-interface-slicing-for-reverse-engineering
doi: 10.1109/ICSE.1993.346015
link: https://dl.acm.org/doi/pdf/10.5555/257572.257682
---

🔨 Les développeurs sont condamnés à éternellement devoir pratiquer l'ingénierie inverse (reverse engineering). De mauvais systèmes seront toujours produits par le bois tordu de l'humanité. Même un bon code aujourd'hui pourrait paraître archaïque dans quelques décennies à peine.

🧠 Pratiquer l'ingénierie inverse requiert 2 compétences distinctes : savoir déchiffrer l'intention derrière un design d'une part et pouvoir comprendre le comportement d'algorithmes d'autre part. Nous savons depuis Weiser qu'une telle opération requiert la création de modèles mentaux sous forme de slices : des morceaux discontinus de logiciels obtenus en rassemblant dans notre tête l'ensemble des endroits que nous pensons reliés au problème étudié.

🎛️ Beck et Eichmann, deux chercheurs américains, proposent de dériver ce concept de slices afin de mieux coller à la réalité de l'ingénierie inverse. Au lieu de chercher les morceaux de code reliés à un souci, ils proposent aux développeurs de repérer les morceaux de code participant à une interface, c'est à dire ceux offrant une fonctionnalité au monde extérieur. Ils nomment cette technique *interface slicing*.

🤖 L'avantage ? Il est facile de s'aider d'outils capables de prendre une interface donnée et de mettre en évidence les slices y étant reliées. Ces travaux servent donc surtout aux développeurs d'outils.

SOURCE

J. Beck and D. Eichmann, "Program and interface slicing for reverse engineering," Proceedings of 1993 15th International Conference on Software Engineering, Baltimore, MD, USA, 1993, pp. 509-518, doi:10.1109/ICSE.1993.346015.