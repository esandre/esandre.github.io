---
title: "Iterative enhancement : A practical technique for software development"
layout: post
category: 'veille'
tags: histoire-informatique methods
lang: french
ref: iterative-enhancement-a-practical-technique-for-software-development
doi: 10.1109/TSE.1975.6312870
---

🔁 Le développement itératif et incrémental (IID), souvent rebrandé « Agilité », n’est certainement pas une technique nouvelle sur laquelle nous n’aurions pas de recul. Avant que l’OTAN ne créé l’ingénierie du logiciel en 1968, les développeurs ont accumulé de beaux succès avec une méthode que Basili et Turner ont synthétisée en 1975.

🦴 Tout commence avec « une implémentation initiale d’un squelette de sous-problème », autrement dit peu de choses. Les développeurs viennent ensuite dépiler des tâches présentes sur une liste, pour bâtir itérativement le logiciel.

8️⃣ A tout moment, 8 règles doivent être respectées :

👉 S’il y a une difficulté, le refactoring doit faciliter sa résolution

👉 Si les modifications ne sont pas circonscrites à un module, il faut redesigner.

👉 Même chose pour les tables

👉 Plus une itération progresse, plus la modification doit être simple à achever. Sinon il faut refacto.

👉 La durée de vie d’un patch ne doit jamais dépasser 2 itérations

👉 Le code doit être relu fréquemment à la lumière des objectifs

👉 Les outils d’aide au développement doivent être utilisés le plus fréquemment possible, pas seulement à la fin d’une itération

👉 Il faut en permanence collecter les retours utilisateurs et améliorer l’implémentation.

🗑️ Cette méthode n’a jamais cessé d’être appliquée, même si les années 80 ont préféré recourir massivement aux méthodes Waterfall, gonflant les taux d’échec et ruinant la réputation de notre profession.

SOURCES

Basili, Victor R. and Albert J. Turner. “Iterative enhancement: A practical technique for software development.” IEEE Transactions on Software Engineering SE-1 (1975): 390-396. DOI : 10.1109/TSE.1975.6312870