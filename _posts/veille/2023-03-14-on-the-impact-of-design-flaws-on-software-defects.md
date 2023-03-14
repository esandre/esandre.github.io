---
title: "On the Impact of Design Flaws on Software Defects"
layout: post
category: 'veille'
tags: smells
lang: french
ref: on-the-impact-of-design-flaws-on-software-defects
doi: 10.1109/QSIC.2010.58
---

🦨 Les odeurs du code (ici nommées Design Flaws) sont corrélées positivement aux défauts des logiciels. Le plus fréquente des odeurs est la jalousie fonctionnelle (Feature Envy). Ces deux conclusions d'une équipe Suisse n'étonneront pas qui a l'habitude de lire des sources de projets legacy.

👀 La jalousie fonctionnelle désigne le fait, pour une classe, de faire plus appel aux attributs/getters d'autrui qu'à ses propres données. Elle augmente fortement le couplage et nuit à la lisibilité des classes. Elle est un signe d'une formation parcellaire ou insuffisante à l'orienté objet.

💪 Le remède ? Essayez de développer le jeu de la vie ou un bowling avec les règles Object Callisthenics, c'est radical.

SOURCE

M. D'Ambros, A. Bacchelli and M. Lanza, "On the Impact of Design Flaws on Software Defects," 2010 10th International Conference on Quality Software, 2010, pp. 23-31, doi:10.1109/QSIC.2010.58.