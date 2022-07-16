---
title: "Qu'est-ce que l'appartenance du code ?"
layout: post
category: 'veille'
tags: psychology methods
lang: french
ref: quest-ce-que-lappartenance-du-code
dois: 10.1145/2025113.2025119 10.1145/2915970.2916002
---

🔏 L’appartenance du code désigne le sentiment de responsabilité d’un développeur ou d’une équipe sur un morceau de code. Une forte appartenance est corrélée avec un plus faible nombre de défauts.  
  
⛓️ La forte appartenance désigne un modèle où un code est presque exclusivement édité par ses contributeurs majeurs, à savoir des développeurs s’identifiant comme experts sur cette partie précise du logiciel.  
Elle s’oppose à la faible appartenance, où la part des modifications réalisées par des contributeurs mineurs est grande.  
Il existe également un phénomène de non-appartenance, désignant l’abandon de parties entières du code, assimilable au code legacy.  
  
🪲 Dans leur étude de 2011, Bird et al. démontrent qu’un modèle de faible appartenance provoque plus de défauts, principalement à cause du manque de connaissance métier des contributeurs mineurs. La littérature précédente appuie ce point : la productivité d’un développeur dépend bien plus de la connaissance du métier de de son expérience précédente.  
  
🧠 Sedano et al. reprennent ces résultats en prenant en compte les critiques de Brendan Murphy : le lien entre qualité et appartenance n’est pas seulement causé par la connaissance du métier, mais également par la psychologie. Un développeur ayant le sentiment d’être responsable d’un code y prêtera plus d’attention car il s’y identifiera (Quality with a Name).  
  
📐 Délimiter arbitrairement des « parties du code » et nommer des responsables n’a qu’un effet très marginal sur la qualité et augmente le Facteur Bus, donc le risque projet !  
  
✔️ Combattre l’apathie logicielle suppose la compréhension des ressorts psychologiques derrière le sentiment d’appartenance. Ultimement, Sedano et al. défendent la propriété collective du code comme une pratique vertueuse, mais la démonstration est pour demain !  
  
— SOURCES —  
  
Todd Sedano, Paul Ralph, and Cécile Péraire. 2016. Practice and perception of team code ownership. In Proceedings of the 20th International Conference on Evaluation and Assessment in Software Engineering (EASE ’16). Association for Computing Machinery, New York, NY, USA, Article 36, 1–6. DOI:10.1145/2915970.2916002
  
Christian Bird, Nachiappan Nagappan, Brendan Murphy, Harald Gall, and Premkumar Devanbu. 2011. Don’t touch my code! examining the effects of ownership on software quality. In Proceedings of the 19th ACM SIGSOFT symposium and the 13th European conference on Foundations of software engineering (ESEC/FSE ’11). Association for Computing Machinery, New York, NY, USA, 4–14. DOI:10.1145/2025113.2025119
  
B. Murphy Code ownership more complex to understand than research implies. Software, IEEE, 32(6):19, Nov 2015  
  
J. Shore, Quality With a Name, 2006