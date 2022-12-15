---
title: "Is mutation an appropriate tool for testing experiments ?"
layout: post
category: 'veille'
tags: epistemology
lang: french
ref: is-mutation-an-appropriate-tool-for-testing-experiments
doi: 10.1145/1062455.1062530
---

🔬 Contrairement à l'aviation ou à la pharmacologie, nous ne publions pas nos échecs. C'est un grand manque lorsqu'il s'agit de valider des hypothèses de recherche. Aussi les chercheurs remplacent de vrais bugs par des faux lorsqu'ils étudient les moyens de les combattre. Deux outils sont principalement utilisés : la mutation et l'introduction manuelle. 

👾 La mutation consiste à créer des mutants, des copies du code ayant subi un changement préprogrammé (inverser une condition, incrémenter une constante, supprimer une ligne, etc.)

🧑‍💻 L'introduction manuelle emploie un développeur expérimenté, payé pour introduire des bugs en amont de la recherche. Job de rêve s'il en est.

✔️ La mutation et l'introduction manuelle sont-ils des substituts légitimes aux vrais bugs ? Une équipe canadienne a vérifié. Les mutants obtiennent une bonne corrélation avec les vrais bugs, à condition que les opérateurs de mutation choisis soient correctement sélectionnés. L'introduction manuelle tend à introduire d'énormes biais. L'équipe recommande de toujours faire répliquer les études de basant sur cette seconde technique par d'autres chercheurs. Ce qui suppose de documenter le processus d'introduction des bugs.

SOURCE

J. H. Andrews, L. C. Briand, and Y. Labiche. 2005. Is mutation an appropriate tool for testing experiments? In Proceedings of the 27th international conference on Software engineering (ICSE '05). Association for Computing Machinery, New York, NY, USA, 402–411. DOI:10.1145/1062455.1062530