---
title: "Comparing non-adequate test suites using coverage criteria"
layout: post
category: 'veille'
tags: testing
lang: french
ref: comparing-non-adequate-test-suites-using-coverage-criteria
doi: 10.1145/2483760.2483769
---

🧮 La recherche sur les tests est gourmande en puissance de calcul. Elle fait appel dans de nombreux cas au score de mutation d'un jeu de tests afin d'en estimer l'efficacité réelle. Or cette opération est coûteuse, même si d'un ordre de grandeur plus précise que le coverage.

📊 Le papier du jour restreint la question : si l'on doit classer des jeux de tests du plus efficace au moins efficace, le coverage est-il une méthode acceptable ? Il ne s'agit pas ici de quantifier ou d'estimer, mais de classer par ordre d'adéquation.

💵 La réponse est oui, le coverage, bien moins couteux que le score de mutation, offre un moyen rapide de classer des jeux de test, par exemple pour éliminer ceux qui ne sont pas pertinents dans une étude, avant d'effectuer des mesures plus compliquées uniquement sur ceux retenus.

SOURCE

Gligoric, M., Groce, A., Zhang, C., Sharma, R., Alipour, M. A., & Marinov, D. (2013). Comparing non-adequate test suites using coverage criteria. In 2013 International Symposium on Software Testing and Analysis, ISSTA 2013 - Proceedings (pp. 302-313). (2013 International Symposium on Software Testing and Analysis, ISSTA 2013 - Proceedings). DOI:10.1145/2483760.2483769