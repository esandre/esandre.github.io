---
title: "Combating architectural degeneration: a survey"
layout: post
category: 'veille'
tags: architecture refactoring laws
lang: french
ref: combating-architectural-degeneration-a-survey
doi: 10.1016/j.infsof.2004.11.005
---

💢 Lorsqu'un logiciel vieillit, il prend en complexité, ce qui a pour conséquence de baisser la vélocité des développeurs : le code est de plus en plus difficile à changer. Une des explications à ce phénomène est la dégénérescence architecturale.

📐 Lorsqu'un logiciel est créé, il possède une architecture, consciemment définie ou émergente. Cette architecture possède une part variable de règles explicites et d'intentions implicites : les lois et l'esprit des lois. 

💫 Avec le temps, les développeurs oublient l'esprit des lois, c'est la dérive architecturale (architectural drift) et font des entorses de plus en plus fréquentes aux lois, c'est l'érosion (architectural erosion). Ce dernier phénomène est à rapprocher de l'hypothèse de la vitre brisée.

❓ Comment réaligner l'architecture et le code ? Les chercheurs donnent deux pistes : 

👁️‍🗨️ Extraire régulièrement l'architecture à l'aveugle par reverse engineering, pour la comparer au schéma d'architecture d'origine.

♻️ Effectuer du refactoring pour corriger le tir, ce qui implique la présence de tests automatisés à haut niveau.

SOURCE

Lorin Hochstein, Mikael Lindvall, Combating architectural degeneration: a survey, Information and Software Technology, Volume 47, Issue 10, 2005, Pages 643-656, ISSN 0950-5849, DOI:10.1016/j.infsof.2004.11.005.