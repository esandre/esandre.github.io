---
title: "The coupling effect: fact or fiction"
layout: post
category: 'veille'
tags: testing
lang: french
ref: the-coupling-effect-fact-or-fiction
doi: 10.1145/75308.75324
---

🧪 En théorie des tests, l'effet de couplage (Coupling Effect) désigne l'hypothèse selon laquelle un jeu de tests ne laissant pas passer des fautes simple ne laissera que marginalement passer des fautes complexes. Enoncée en 1978, il faut attendre 1989 et une étude d'Offutt pour l'appuyer à l'aide de preuves expérimentales.

👾 En utilisant le principe des tests de mutation, l'auteur valide l'hypothèse sus-mentionnée. Il va même plus loin en montrant que l'hypothèse du Programmeur Compétent n'est qu'une version extrême de l'effet de couplage.

🃏 L'hypothèse du Programmeur Compétent énonce qu'un développeur produira en général des logiciels "presque corrects". Personne n'écrit le code d'un système d'exploitation par erreur en voulant développer un compilateur. Autrement dit, un développeur tend à écrire des mutants de rang faible (ayant peu de différences) par rapport au programme visé. Un bon jeu de test cherche à attraper ces erreurs, donc n'a aucun intérêt à attraper les mutants de rangs supérieurs. Cela reviendrait à vérifier que notre compilateur n'est pas, par erreur, devenu un système d'exploitation, soit une situation hautement improbable.

SOURCE

A. Offutt. 1989. The coupling effect: fact or fiction. In Proceedings of the ACM SIGSOFT '89 third symposium on Software testing, analysis, and verification (TAV3). Association for Computing Machinery, New York, NY, USA, 131–140. DOI:/10.1145/75308.75324