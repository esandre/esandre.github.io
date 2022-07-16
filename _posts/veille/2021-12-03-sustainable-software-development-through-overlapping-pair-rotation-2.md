---
title: "Sustainable Software Development through Overlapping Pair Rotation"
layout: post
category: 'veille'
tags: management pair-programming
lang: french
ref: sustainable-software-development-through-overlapping-pair-rotation
dois: 10.1145/2961111.2962590 10.5555/377517.377531
---

👥 Aujourd’hui, deux papiers, dont l’un est devenu un classique, qui listent les bénéfices, attendus ou plus surprenants, du pair programming. Certains sont peu connus et justifient largement les 15% de surcoût observé par rapport à une équipe classique (et non 100%, comme le pense la croyance managériale).

- Le taux de défauts en production est bien plus bas.
- Le pair programming coût moins cher que les code review à résultat égal.
- Les solutions trouvées sont meilleures et plus simples, donc plus maintenables.
- La vélocité d’une paire est plus élevée que celle d’un développeur seul.
- Les développeurs se sentent mieux à leur poste.
- L’apprentissage est plus rapide, même un expert apprendra au contact d’un novice (et inversement, bien entendu)

📚 Enfin, bien moins connu, le pair programming augmente la résilience de l’équipe sans nécessiter des camions entiers de documentation, très coûteuse à maintenir et empiriquement jamais à jour.

♻️ Sedano, Ralph et Péraire appellent cette propriété « Développement durable du logiciel ». En travaillant par paires a minima tournantes, les développeurs partagent la connaissance du code « naturellement » et l’ensemble de l’équipe finit par obtenir la responsabilité collective de l’ensemble du code au bout de quelques mois.

Pour obtenir cette propriété, la rotation des paires doit être fréquente ! Des paires fixes et affinitaires ne fonctionnent pas et créent des silos. A minima, les paires doivent se chevaucher, mais la meilleure technique consiste à « polliniser » le savoir en s’assurant que toutes les paires possibles ont été pratiquées sur une itération par exemple.

SOURCES

Todd Sedano, Paul Ralph, and Cécile Péraire. 2016. Sustainable Software Development through Overlapping Pair Rotation. In Proceedings of the 10th ACM/IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM ’16). Association for Computing Machinery, New York, NY, USA, Article 19, 1–10. DOI: 10.1145/2961111.2962590

Alistair Cockburn and Laurie Williams. 2001. The costs and benefits of pair programming. Extreme programming examined. Addison-Wesley Longman Publishing Co., Inc., USA, 223–243. DOI: 10.5555/377517.377531