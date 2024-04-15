---
title: "Formalizing style to understand descriptions of software architecture"
layout: post
category: 'veille'
tags: architecture
lang: french
ref: formalizing-style-to-understand-descriptions-of-software-architecture
doi: 10.1145/226241.226244
link: https://dl.acm.org/doi/pdf/10.1145/226241.226244
---

😣 Quiconque s'est un jour renseigné sur l'architecture l'a constaté : c'est une non-discipline où peu de standards existent et où chacun a sa propre manière de procéder. Le papier du jour, sorti en 1995, disait déjà sensiblement la même chose.

🖌️ Les praticiens sont globalement d'accord pour dire qu'il existe des composants et des connecteurs. La définition des premiers ne fait pas débat. Les composants sont les "endroits du calcul" chez quasiment tous les auteurs. La définition des connecteurs est bien plus problématique : Que sont-ils ? Comment les représenter dans un schéma ? Faites débattre deux architectes, vous obtiendrez trois définitions.

👓 Abowd, Allen et Garlan proposent d'acter cette diversité à travers la notion de "style d'architecture". Le style architectural a pour rôle d'attacher une sémantique à la syntaxe d'un schéma d'architecture. Prenez un schéma constitué de deux rectangles reliés par une flèche. Selon les lunettes que vous chausserez, vous verrez deux programmes s'envoyant des données, deux modules ayant une relation de dépendance ou encore un programme tirant ses données d'une source. Ces lunettes se nomment "style architectural".

🤯 L'idée est brillante, mais ne fait que déplacer le problème. Cherchez de la littérature sur les styles architecturaux, vous trouverez le même brouhaha que sur la discipline en général. Il reste encore du travail.

SOURCE

Abowd, Gregory D., Robert J. Allen and David Garlan. “Formalizing style to understand descriptions of software architecture.” ACM Trans. Softw. Eng. Methodol. 4 (1995): 319-364. DOI:10.1145/226241.226244