---
title: "Purposes, concepts, misfits, and a redesign of git"
layout: post
category: 'veille'
tags: codesmithing
lang: french
ref: purposes-concepts-misfits-and-a-redesign-of-git
doi: 10.1145/2983990.2984018
link: https://spderosso.github.io/oopsla16.pdf
---

🙊 Git est un bon outil, mais le nombre d'appels à l'aide sur StackOverflow prouvent que son design est affreux. Deux chercheurs du MIT nous expliquent où le bât blesse à l'aide des techniques de design conceptuel.

🛑 Quiconque a pratiqué un peu connaît les défauts de git : difficile de changer de branche avec du travail en cours, de créer des variations locales sans les commiter, de comprendre l'état de tête détachée, etc. Pourquoi ? Car une régle fondamentale du design a été violée par git : la bijection concept/motif.

💭 Un concept est quelque chose que l'utilisateur doit comprendre pour utiliser un logiciel. Dans un bon design, chaque concept règle un problème, que l'on nomme son motif.

👉 Un concept sans motif est une complexité inutile.

👉 Un concept qui prétend régler plusieurs problèmes bâcle souvent les deux.

👉 Un problème qui n'est le motif d'aucun concept rend le logiciel incomplet.

👉 Un problème qui motive plusieurs concepts créé la confusion.

4️⃣ Git possède ces 4 catégories de défauts, analysés dans le papier. Il constitue une vraie leçon de design qui devrait être enseignée dans les écoles.

🌠 Les auteurs poursuivent en proposant à des utilisateur de tous niveaux de git l'essai de Gitless, un fork de Git respectant les canons du design conceptuel. Les résultats en matière de prise en main sont bien meilleurs.

SOURCE

Santiago Perez De Rosso and Daniel Jackson. 2016. Purposes, concepts, misfits, and a redesign of git. SIGPLAN Not. 51, 10 (October 2016), 292–310. DOI:10.1145/3022671.2984018