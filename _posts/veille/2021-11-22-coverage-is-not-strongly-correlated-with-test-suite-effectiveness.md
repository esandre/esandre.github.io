---
title: "Coverage is not strongly correlated with test suite effectiveness"
layout: post
category: 'veille'
tags: testing
lang: french
ref: coverage-is-not-strongly-correlated-with-test-suite-effectiveness
doi: 10.1145/2568225.2568271
---

🔬Arrêtez de scruter la couverture de vos tests ! C’est une perte de temps. Laura Inozemtseva et Reid Holmes ont sorti en 2014 un papier qui l’affirme, mais confirme aussi les résultats de nombreux autres chercheurs : une faible couverture prouve que les tests sont mauvais. Une forte couverture ne prouve pas qu’ils sont bons.  
  
🎯 On retrouve ici une situation où la Loi de Goodhart s’applique : plus vous prenez le coverage comme un objectif, plus vous vous plantez.  
  
Comment s’assurer d’avoir de bons tests ? En remettant le coverage à sa place.  
✔️ Comparer le coverage actuel et le coverage précédent avant chaque commit permet de voir si le développeur n’a pas oublié de tester son code.  
✔️ Sous les 80%, le coverage indique une forte dette de tests.  
❌ Au-dessus de 80% la coverage ne signifie rien d’utile et le suivre peut même coûter cher, en augmentant artificiellement la taille du jeu de tests, qu’il faudra ensuite maintenir.  
❌ Les méthodes de calcul du coverage longues ou élaborées n’ont pas démontré leur utilité. Allez au plus simple, si vous utilisez correctement le coverage, ça suffira.  
  
SOURCES  
  
Laura Inozemtseva and Reid Holmes. 2014. Coverage is not strongly correlated with test suite effectiveness. In Proceedings of the 36th International Conference on Software Engineering (ICSE 2014). Association for Computing Machinery, New York, NY, USA, 435–445. DOI:10.1145/2568225.2568271