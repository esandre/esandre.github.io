---
title: "Object-oriented programming with flavors"
layout: post
category: 'veille'
tags: histoire-informatique langages
lang: french
ref: object-oriented-programming-with-flavors
doi: 10.1145/960112.28698
---

🍦L’orienté-objet n’est pas né d’une traite. Son histoire est jalonnée de prototypes, qui ont pavé la voie à ce qu’il est aujourd’hui. Les flavors en font partie. Ancêtre direct des mixins/traits modernes, ils n’ont jamais été implémentés hors de LISP.

🧑‍🔬 Outre l’intérêt historique du papier, il me permet d’évoquer le creuset de ce paradigme : OOPSLA. Il s’agit d’une conférence annuelle de chercheurs en langages de programmation. Aujourd’hui fondue dans SPLASH, elle était autrefois indépendante.

🧠 En sont sortis une grande partie des papiers présentés ici et beaucoup de grands noms de la profession y ont développé leurs idées : Barbara Liskov, John Vlissides, Kent Beck, David Parnas et j’en passe.

💮 C’est à l’OOPSLA 1986 que David Moon et Howard Cannon ont proposé l’idée des Flavors. Il s’agit d’une manière de faire partager des méthodes et attributs communs entre deux classes, sans qu’elles ne dépendent d’un parent commun.

🧩 L’héritage simple est débattu depuis longtemps. L’abandon de l’héritage multiple, expérience malheureuse de C++, et l’insuffisance de la composition, jugée lourde par certains praticiens, ont abouti à l’idée de « traits » partagés par plusieurs classes sans lien hiérarchique. On les retrouve aujourd’hui en Kotlin, PHP, Ruby, Rust, Scala, pour ne citer que les principaux.

💣 Plus suprenant, C# et Java implémentent un système de traits sans l’assumer, en permettant la définition de méthodes dans les interfaces. L’idée aura mis 20 ans à percer, nul doute qu’elle ne sera pas correctement utilisée avant encore 20 ans. Tout ce qui rend passionnant ce métier en somme.

SOURCE

David A. Moon. 1986. Object-oriented programming with flavors. SIGPLAN Not. 21, 11 (Nov. 1986), 1–8. DOI:10.1145/960112.28698