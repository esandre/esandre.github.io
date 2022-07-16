---
title: "Programming with abstract data types"
layout: post
category: 'veille'
tags: histoire-informatique langages codesmithing
lang: french
ref: programming-with-abstract-data-types
doi: 10.1145/800233.807045
---

👵 Tout développeur connaît les principes SOLID. Peu connaissent l’auteur du troisième : le Principe de Substitution de Barbara Liskov. Cette grande dame inventa le premier langage de programmation supportant l’abstraction. Autant dire qu’elle a pavé la voie aux langages de haut-niveau modernes.  
  
📦 Son article de 1974 « Programming with abstract data types » est devenu un classique. Elle y détaille un paradigme de programmation, héritier de la programmation structurée de Dijkstra, dans lequel le développeur n’utilise pas directement les types fournis par le système. Ceux-ci sont encapsulés dans des types de plus haut-niveau, ne laissant filtrer que les détails pertinents du niveau précédent.
  
🎰 Ces types sont définis par les opérations que l’on peut réaliser sur eux (et non pas sur les données qu’ils contiennent !). Elle ne parle pas d’objet ou d’interface, concepts encore balbutiants à l’époque (Alan Kay travaille encore sur Smalltalk), mais l’idée est décidément dans l’air du temps.  
  
3️⃣ Son paradigme présente trois énormes avantages, déjà identifiés dans le papier :  
✔️ Protéger le développeur contre les erreurs d’inattention (additionner un int et un char par exemple).  
✔️ Réduire la charge mentale\* du développeur, qui peut se concentrer sur l’espace du problème sans se soucier des détails d’implémentation. Les types sont semblables aux oeillères des animaux de trait.  
✔️ Rendre le programme plus facile à tester\* : le jeu de tests\* est divisé en deux parties indépendantes, l’une vérifiant l’implémentation, l’autre que l’abstraction est appelée correctement. Cette seconde partie doit ignorer tout de l’implémentation.  
  
📝 Si la manière de concevoir des langages a vieilli (et donc la seconde partie du papier de Liskov), les principes fondamentaux sont toujours d’actualité, je ne peux qu’en conseiller la lecture.  
  
\* Ces termes n’existaient pas à l’époque  

SOURCE  
  
Liskov, Barbara and Stephen N. Zilles. “Programming with abstract data types.” SIGPLAN Notices 9 (1974): 50-59. DOI: 10.1145/800233.807045