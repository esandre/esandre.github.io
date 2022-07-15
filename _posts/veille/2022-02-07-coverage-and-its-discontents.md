---
title: "Coverage and Its Discontents"
layout: post
category: 'veille'
tags: testing
lang: french
ref: coverage-and-its-discontents
doi: 10.1145/2661136.2661157
---

Pour bien enfoncer des portes ouvertes, encore un papier sur le lien entre coverage et qualité des tests :

❌ Attacher une prime ou un objectif quelconque au coverage est la pire des idées. Elle poussera les développeurs à faire de mauvais tests.

❌ Branch-coverage, statement-coverage, etc. Aucun ne sort du lot en matière de bugs découverts.

❌ Les tests de mutation semble posséder les mêmes biais que le coverage. D’autres recherches sont nécessaires.

✔️ Le Coverage restera toujours un meilleur indicateur que le nombre de tests ou leur temps d’exécution.

✔️ Le Coverage permet de repérer les parties du code sous-testées, c’est son principal (seul ?) avantage.

💡 En résumé, utilisez le coverage pour repérer les oublis de votre politique de tests, pas comme indicateur d’absence de bugs !

SOURCES

Groce, Alex &amp; Alipour, Mohammad &amp; Gopinath, Rahul. (2014). Coverage and Its Discontents. 10.1145/2661136.2661157.