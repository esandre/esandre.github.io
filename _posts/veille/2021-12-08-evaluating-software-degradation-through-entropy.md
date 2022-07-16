---
title: "Evaluating software degradation through entropy"
layout: post
category: 'veille'
tags: laws quality
lang: french
ref: evaluating-software-degradation-through-entropy
doi: 10.1109/METRIC.2001.915530
---

🚮 L’entropie est aujourd’hui devenu un terme poli pour désigner la pourriture logicielle. Comme l’entropie thermodynamique, l’entropie du logiciel est une notion ayant une base théorique solide, négligée lors de son passage dans le langage courant. Aujourd’hui, un papier italien de 2001, offrant la première définition rigoureuse connue de ce phénomène.

🕸️ Les 4 chercheurs définissent l’entropie d’un logiciel comme la somme des couplages entre les modules. Ces couplages peuvent être directs ou indirects, structurels (dépendances de compilation) ou cognitifs (charge mentale de devoir penser à A en éditant B).

💣 Plus un code possède d’entropie, plus la portée d’une modification est grande. Nous en avons tous fait l’expérience : modifiez un détail sur un code endetté, vous obtenez des effets de bord imprévus et tout est à revoir.

🏚️ Dans la seconde partie du papier, les chercheurs apportent les premières preuves permettant d’affirmer qu’il s’agit d’une mesure pertinente pour évaluer le vieillissement d’un logiciel, donc la nécessité d’un rajeunissement par le refactoring.

SOURCE

A. Bianchi, D. Caivano, F. Lanubile and G. Visaggio, « Evaluating software degradation through entropy, » Proceedings Seventh International Software Metrics Symposium, 2001, pp. 210-219, doi: 10.1109/METRIC.2001.915530.