---
title: "Modeling readability to improve unit tests"
layout: post
category: 'veille'
tags: testing
lang: french
ref: modeling-readability-to-improve-unit-tests
doi: 10.1145/2786805.2786838
link: https://dl.acm.org/doi/10.1145/2786805.2786838
---

📚 Nous savons depuis Buse&Weimer que la lisibilité d'un code dépend de facteurs quasi-universels et qu'une métrique de lisibilité peut être calculée. Vaut-elle pour les tests ? Oui. Peut-elle être améliorée en y ajoutant des règles de lisibilité spécifiques ? Certainement.

🧪 Une équipe de chercheurs a vérifié l'influence de paramètres propres aux tests sur la lisibilité de ceux-ci par des humains : nombre d'assertions, gestion des exceptions, types de données des paramètres, etc. Pour cela, ils ont généré des jeux de tests, que des humains ont du comparer. Chaque évaluateur a indiqué sa préférence et a été chronométré alors qu'il devait expliquer ce que faisait le test.

🏷️ Sans aucune surprise, la qualité du nommage est le facteur le plus important. Attention cependant : un test lisible (readable) n'est pas toujours un test compréhensible (understandable), mais c'est une première étape.

SOURCE

Ermira Daka, José Campos, Gordon Fraser, Jonathan Dorn, and Westley Weimer. 2015. Modeling readability to improve unit tests. In Proceedings of the 2015 10th Joint Meeting on Foundations of Software Engineering (ESEC/FSE 2015). Association for Computing Machinery, New York, NY, USA, 107–118. DOI:10.1145/2786805.2786838