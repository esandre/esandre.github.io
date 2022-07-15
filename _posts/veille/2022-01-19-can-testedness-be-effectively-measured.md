---
title: "Can testedness be effectively measured ?"
layout: post
category: 'veille'
tags: testing
lang: french
ref: can-testedness-be-effectively-measured
doi: 10.1145/2950290.2950324
---

🔨 C’est dans les vieilles controverses que l’on trouve les meilleurs papiers. 5 chercheurs démontrent que le score de mutation ne fait pas mieux que le coverage pour éviter des bugs futurs. Leur résultat va à l’encontre du consensus établi. Artefact statistique ? Non, nouvelle méthode de calcul et critique rigoureuse des précédents travaux.

🐛 La méthode de calcul précédemment admise, consistait à introduire des bugs dans un programme, puis à vérifier le pourcentage de ces bugs couverts par la méthode testée (branch coverage, statement coverage, mutation score, etc.).

🪲 Pour les auteurs, il n’y a qu’une très faible corrélation avec les bugs réels. Ils ont préféré miner les sources de logiciels Open Source et vérifier, pour chaque bug résolu, si le code fautif était couvert par la méthode testée.

🏆 Le résultat renvoie le score de mutation au niveau des autres méthodes : utile pour repérer les parties sous-testées, pas plus. Le champion tombe de son piédestal.

📝 Évidemment, une étude ne changera pas le consensus, elle devra être répliquée, mais il s’agit d’une belle avancée de la recherche.

SOURCES

Ahmed, Iftekhar, Rahul Gopinath, Caius Brindescu, Alex Groce and Carlos Jensen. “Can testedness be effectively measured?” Proceedings of the 2016 24th ACM SIGSOFT International Symposium on Foundations of Software Engineering (2016): n. pag.