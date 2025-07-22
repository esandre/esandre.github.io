---
title: "Testing, abstraction, theorem proving: better together !"
layout: post
category: 'veille'
tags: testing
lang: french
ref: testing-abstraction-theorem-proving-better-together
doi: 10.1145/1146238.1146255
link: https://gretay.github.io/papers/issta06full.pdf
---

🔎 L'analyse dynamique (les tests) ne pourra jamais valider tous les comportements possibles d'un programme : elle sous-approxime. A l'inverse, l'analyse statique tend à sur-approximer et à produire un grand nombre de faux-positifs. Est-il possible de prendre le meilleur des deux mondes ? Des chercheurs proposent un moyen d'y parvenir.

🤖 Les tests sont d'abord exécutés afin d'obtenir un jeu d'états concrets du programme. Ce jeu d'états est généralisé en un jeu d'états abstraits, représentant l'ensemble des états dans lequel le programme peut potentiellement se trouver. Un démonstrateur de théorème automatisé va ensuite vérifier que ce jeu d'états abstrait vérifie certaines propriétés désirables et passe lui-même une version  généralisée des tests. Si ça n'est pas le cas, le démonstrateur va générer des contre-exemples permettant au développeur d'augmenter la couverture.

🔧 Je n'ai pas trouvé d'outil appliquant ce principe. Les tests de mutation ont mis 25 ans à passer du laboratoire aux IDE, je pense que les prochaines années verront ce type d'outils venir renforcer nos pratiques.

SOURCE

Greta Yorsh, Thomas Ball, and Mooly Sagiv. 2006. Testing, abstraction, theorem proving: better together! In Proceedings of the 2006 international symposium on Software testing and analysis (ISSTA '06). Association for Computing Machinery, New York, NY, USA, 145–156. DOI:10.1145/1146238.1146255