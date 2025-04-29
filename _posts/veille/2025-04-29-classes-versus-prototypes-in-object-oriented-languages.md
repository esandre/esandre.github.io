---
title: "Classes versus prototypes in object-oriented languages"
layout: post
category: 'veille'
tags: langages
lang: french
ref: classes-versus-prototypes-in-object-oriented-languages
doi: 10.5555/324493.324538
link: https://dl.acm.org/doi/pdf/10.5555/324493.324538
---

🤯 L'idée de baser l'orienté objet sur des prototypes plutôt que sur des classes date de 1986. C'est une réaction à l'introduction des métaclasses en Smalltalk, concept jugé très peu intuitif (les pythonistes modernes témoigneront). Borning affirme que les classes des langages orientés-objet portent bien trop de responsabilités : générateurs d'instances, descripteurs de protocoles, descripteurs de représentation, etc.

📑 La solution proposée est d'abolir les classes. Tout nouvel objet est la copie d'un ancien, qui peut ensuite être modifié à loisir. Cette copie peut être indépendante de la source, ou lui être liée par des contraintes. Ces contraintes peuvent lier ensemble les champs, le comportement ou le protocole des deux objets. Une copie contrainte sur les trois se nomme un descendant.

🚫 Aucune étude, même sur des étudiants, n'a été effectuée avant d'affirmer que ce modèle est plus clair que la POO "vanilla" ou les métaclasses. Pourtant l'auteur affirme qu'ayant moins de concepts à apprendre, le débutant sera moins perdu. Celui-ci est pourtant clairvoyant sur les défauts de sa proposition : elle n'est pas naturelle pour les pures abstractions comme les nombres. Quel est l'entier prototypal ? 0 ou 1 ? Un prototype de Stack ou de Queue fait-il sens ? Enfin, à l'époque, le copy-on-write n'existait pas et les performances d'un langage à prototype n'auraient pas été flamboyantes.

🏛️ La philosophie aristotélico-thomiste est gravée dans nos têtes d'occidentaux, pour le meilleur et pour le pire. Sortir de cette dualité objet/concept est une impasse en programmation, car cette dualité nous est enseignée depuis notre enfance. Qu'elle soit naturelle ou culturelle importe peu à ce stade.

SOURCE

A. H. Borning. 1986. Classes versus prototypes in object-oriented languages. In Proceedings of 1986 ACM Fall joint computer conference (ACM '86). IEEE Computer Society Press, Washington, DC, USA, 36–40. DOI:10.5555/324493.324538