---
title: "Partition testing does not inspire confidence"
layout: post
category: 'veille'
tags: testing
lang: french
ref: partition-testing-does-not-inspire-confidence
doi: 10.1109/32.62448
---

🤠 Dans la vie il y a deux types de testeurs : ceux qui utilisent l’aléatoire et ceux qui partitionnent. Ceux qui utilisent de l’aléatoire trouvent des bugs. Ceux qui partitionnent augmentent leur confiance.

🧠 Partitionner consiste à sélectionner soigneusement les valeurs utilisées lors des tests, contrairement à l’aléatoire qui les teste virtuellement toutes, sur la durée.

🎲 Dans un papier déjà ancien (1990), Hamlet et Taylor réaffirment que, moyennant une puissance de calcul que nous n’avons pas encore en 2022, le test aléatoire est la Rolls, car il permet de trouver plus de bugs.

🚵‍♂️ Attention cependant à ne pas caricaturer. Une Rolls consomme énormément et ne sert à rien sur les chemins de terre que l’on appelle « phase de spécification » !

🪧 Pour résumer grossièrement un papier que je vous recommande de lire :

1️⃣ Commencez par des tests partitionnés afin de définir votre domaine.

2️ « Hackez » les valeurs choisies pour vos tests dans le but de trouver des bugs.

3️⃣ Seulement dans un troisième temps, passez en aléatoire pour détecter des bugs résiduels.

🐛 Si chaque type de test est à sa place, les bugs seront bien gardés.

SOURCE

D. Hamlet and R. Taylor, « Partition testing does not inspire confidence (program testing), » in IEEE Transactions on Software Engineering, vol. 16, no. 12, pp. 1402-1411, Dec. 1990, doi: 10.1109/32.62448.