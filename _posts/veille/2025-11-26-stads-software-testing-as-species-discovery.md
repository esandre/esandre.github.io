---
title: "STADS: Software Testing as Species Discovery"
layout: post
category: 'veille'
tags: testing
lang: french
ref: stads-software-testing-as-species-discovery
doi: 10.48550/arXiv.1803.02130
link: https://mboehme.github.io/paper/TOSEM18.pdf
---

🕵️ Comment savoir si la recherche de bugs sur un système touche à sa fin ? Avec des entrées complexes, il est manifestement impossible de tout essayer par bruteforce. Le fuzzing consiste à envoyer des données ayant un maximum de chances de provoquer une erreur dans un système. C'est une branche du random testing. Cependant même avec un bon fuzzer, les test peuvent être longs, voire infiniment longs.

🪹 On sait depuis plusieurs décennies qu'un fuzzer remontera des bugs selon un courbe logarithmique : plus le temps passe, moins il y aura de bugs découverts. Comment savoir quand l'énergie consommée par le fuzzer sera plus coûteuse que le retour sur investissement potentiel ?

🦋 Un réponse prometteuse vient de la zoologie, qui a le même genre de problèmes : comment savoir combien d'espèces restent à découvrir sur une zone donnée ? Une formule mathématique permet d'extrapoler le nombre d'espèces restant à découvrir (vues 0 fois) à partir de celles vues une fois et de celles vues deux fois.

🪲 Est-ce applicable aux bugs et autres vulnérabilités ? Oui, mais avec prudence car s'il est facile de savoir si l'on a 2 occurrence du même animal, il est compliqué de dire si deux bugs sont du même type ou non. Cependant la méthode offre des résultats intéressants.

SOURCE

Marcel Böhme. 2018. STADS: Software Testing as Species Discovery. ACM Trans. Softw. Eng. Methodol. 27, 2, Article 7 (April 2018), 52 pages. DOI:10.1145/3210309