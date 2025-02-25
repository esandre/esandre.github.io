---
title: "Designing Reusable Classes"
layout: post
category: 'veille'
tags: expert codesmithing
lang: french
ref: designing-reusable-classes
link: https://www.researchgate.net/publication/215446177_Designing_Reusable_Classes
---

🧊 Certains papiers sont des instantanés des erreurs de leur époque et méritent leur place ici principalement pour cela. Le début de celui-ci est une description claire et impeccable de ce qu'est l'orienté-objet à la fin des années 80. Presque rien n'a changé depuis, seulement quelques additions mineures.

🔗 La suite porte sur les frameworks : ils y sont correctement décrits comme étant plus que de simples boîtes à outils. Tout framework lie irrévocablement le code qui l'utilise à une architecture. L'auteur rappelle une distinction aujourd'hui oubliée entre frameworks white-box et black-box, les premiers ayant presque disparu du marché.

✅ La fin du papier liste des "bonnes pratiques" de l'époque, certaines aujourd'hui réfutées. L'usage de hiérarchies d'héritage profondes est recommandée, alors que nous savons désormais que le nombre de niveaux d'héritage est corrélé au nombre de bugs. La création d'un maximum de code générique et même de frameworks y est encouragée, bien que décrite comme dangereuse, afin de réutiliser au maximum le code. Aujourd'hui il est recommandé d'attendre qu'un besoin de réutilisation existe pour entamer une telle démarche.

🧑‍🔬 Il est dommage que l'auteur n'ait pas cherché de preuves de l'efficacité de ces différentes règles, mais se soit simplement fait l'écho de l'esprit du temps.

SOURCE

Johnson, Ralph & Foote, Brian. (1988). Designing Reusable Classes. Journal of Object-Oriented Programming.