---
title: "The trade-off between performance, cost and environmental impact in software development"
layout: post
category: 'veille'
tags: ecologie
lang: french
ref: the-trade-off-between-performance-cost-and-environmental-impact-in-software-development
doi: 10.5281/zenodo.21682065
link: https://jisom.rau.ro/Vol.20%20No.1%20-%202026/JISOM%2020.1_231-265.pdf
---

🧪 Je ne suis pas un grand fan des études « kikimeter » où des langages sont observés sous l’angle de la performance, même si c’est dans le but de mesurer un impact écologique. Cependant, ce papier roumain donne une tendance. Utiliser un langage à VM consommerait en moyenne quatre fois plus d’énergie qu’un langage compilé, même si les auteurs notent une énorme déviation. Autrement dit, il existe des VM optimisées et d’autres qui ne le sont pas du tout. Multipliez encore par quatre la consommation, vous obtenez les langages interprétés. Python, porte-drapeau de l’IA et du Big Data, fait légèrement mieux que Perl. Pour le Green IT, on repassera.

🪫 Bien entendu, le coût de développement compte. Sinon, nous développerions tous en C, un des langages les plus optimisés pour qui connaît les astuces. Les chercheurs ont récupéré le taux horaire et la vélocité moyenne des développeurs sur chaque langage étudié. Un développeur Python produit une fonctionnalité trois fois plus vite que son collègue utilisant Rust. Cette économie en main-d’œuvre est négligeable sur un produit ayant un peu de succès : les coûts énergétiques rattrapent largement la difficulté accrue de développer avec un langage compilé. Le facteur entre C et Python est de 65 fois, une paille.

🔄 Les auteurs ont poussé l’étude plus loin : cette différence justifie-t-elle une réécriture en Rust ? Sur une application web standard encaissant 32 requêtes par seconde, le gain énergétique amortit le coût d’une réécriture en six semaines. La réécriture elle-même a été chiffrée à 17 mois-homme. La suite du papier est une variation de ce calcul sur différents projets.

🧩 En conclusion, Python est un excellent langage pour prototyper, mais ne doit pas toucher à la production à cause de son coût environnemental prohibitif. Cela vaut en général pour tous les langages interprétés. Mon principal regret ? Aucun exemple n’estime l’intérêt des langages à VM, qui sont un compromis sur tous les tableaux et supportent souvent plusieurs modes d’optimisation, dont certains sont assez agressifs.


SOURCE

Năpruiu, Andrei, Flavius Petrache, Larisa Elena Florea, Ștefania Maria Fîntînă, Mădălina-Elena Tița, and Costin-Anton Boiangiu. “The Trade-Off between Performance, Cost and Environment Impact in Software Development.” Journal of Information Systems & Operations Management 20, no. 1 (May 2026): 231–265. DOI:10.5281/zenodo.21682065