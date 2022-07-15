---
title: "On the Danger of Coverage Directed Test Case Generation"
layout: post
category: 'veille'
tags: testing
lang: french
ref: on-the-danger-of-coverage-directed-test-case-generation
doi: 10.1007/978-3-642-28872-2\_28
---

✈️ Générer des tests automatiquement à partir d’une mesure de coverage est toujours une mauvaise idée. Pourtant c’est un standard dans l’aéronautique et le spatial, y compris sur le programme F-35.

🎲 La génération aléatoire avec régression ou la génération dirigée par coverage ne font pas mieux que le pur hasard en matière d’efficacité des tests. Cela signifie que des tests générés parfaitement aléatoirement obtiennent des résultats meilleurs (jusqu’à 2 fois) ou équivalents aux méthodes précédemment citées.

👽 Évidemment, l’étude est légèrement biaisée par l’usage de tests de mutation comme mètre-étalon, mais il est raisonnable de penser que si le coverage est incapable de créer des tests efficaces sur les défauts simples, il ne fera pas mieux que des bugs réels ou complexes.

⚠️ Les chercheurs recommandent de s’en tenir au consensus scientifique : le coverage ne doit être utilisé que comme révélateur des parties du code les moins testées. Pas plus.

SOURCE

Staats M., Gay G., Whalen M., Heimdahl M. (2012) On the Danger of Coverage Directed Test Case Generation. In: de Lara J., Zisman A. (eds) Fundamental Approaches to Software Engineering. FASE 2012. Lecture Notes in Computer Science, vol 7212. Springer, Berlin, Heidelberg. DOI:10.1007/978-3-642-28872-2\_28