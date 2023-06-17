---
title: "An approach for experimentally evaluating effectiveness and efficiency of coverage criteria for software testing"
layout: post
category: 'veille'
tags: testing
lang: french
ref: an-approach-for-experimentally-evaluating-effectiveness-and-efficiency-of-coverage-criteria-for-software-testing
doi: 10.1007/s10009-007-0059-5
---

🧪 Un jeu de tests peut être efficace sans être efficient. L'efficacité désigne la capacité à détecter des défauts ou des régressions. L'efficience consiste à maximiser cette capacité de détection en fonction du nombre de tests. Cette distinction est important : les tests coûtent à écrire et personne ne veut voir 15 tests passer au rouge à la première évolution de son code.

🇮🇳 Deux chercheurs indiens ont voulu vérifier la corrélation entre critère de coverage (branch, statement ...) et efficience du jeu de test minimal permettant de le satisfaire sur un code donné. 

📶 L'intérêt de l'expérience est plutôt limitée pour le praticien, le coverage n'étant pas un indicateur fiable de la qualité d'une suite de tests. Les résultats en revanche sont intéressants : ils montrent une relation quasi-linéaire entre effort de test et efficicacité. Autrement dit nous ne connaissons pas de méthode de test miracle, offrant une efficience d'un ordre de grandeur supérieure aux autres. Nous sommes, dans l'état actuel des connaissances, condamnés à devoir tester plus pour sécuriser plus.

⚠️ Cette conclusion doit néanmoins être prise avec du recul : l'usage de mutants et la génération automatisée de tests confine ces conclusions au monde des tests unitaires. Il est impossible de déduire quoi que ce soit pour les tests de niveau supérieurs, souvent les plus utiles aux praticiens. Ce papier servira donc principalement à d'autres chercheurs, non aux développeurs.

SOURCE

Gupta, Atul & Jalote, Pankaj. (2008). An approach for experimentally evaluating effectiveness and efficiency of coverage criteria for software testing. STTT. 10. 145-160. DOI:10.1007/s10009-007-0059-5. 