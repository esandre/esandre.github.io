---
title: "A Metric for Software Readability"
layout: post
category: 'veille'
tags: codesmithing naming
lang: french
ref: a-metric-for-software-readability
doi: 10.1145/1390630.1390647
link: http://www.cs.virginia.edu/~weimer/p/weimer-issta2008-readability.pdf
---

🧶 La lisibilité d'un code est-elle universelle ? Autrement dit, classerions-nous tous de manière identique une série de snippets du plus lisible au plus obscur ? Deux américains ont tenté l'expérience et semblent montrer qu'une corrélation modérée existe.

✂️ Les chercheurs ont ensuite recherché les caractéristiques faisant un code lisible. La taille des identifiants n'a aucune corrélation avec la lisibilité. allonger ceux-ci sans but précis n'apporte rien à la compréhension. Les commentaires sont faiblement corrélés à la lisibilité, probablement car ceux-ci tendent à documenter un code peu lisible. La principale métrique corrélée à la lisibilité semble être le nombre d'instructions par ligne. La quantité de lignes vides arrive peu après.

🎶 Aérer son code semble être le meilleur conseil pour le rendre plus lisible. Comme dans un beau poème, l'aération et le placement des mots a un sens.

SOURCE

Buse, Raymond P. L. and Westley Weimer. “A metric for software readability.” International Symposium on Software Testing and Analysis (2008). DOI: 10.1145/1390630.1390647