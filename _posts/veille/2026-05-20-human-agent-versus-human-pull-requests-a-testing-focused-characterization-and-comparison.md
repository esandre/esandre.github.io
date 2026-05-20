---
title: "Human-Agent versus Human Pull Requests: A Testing-Focused Characterization and Comparison"
layout: post
category: 'veille'
tags: testing
lang: french
ref: human-agent-versus-human-pull-requests-a-testing-focused-characterization-and-comparison
doi: 10.48550/arXiv.2601.21194
link: https://arxiv.org/abs/2601.21194
---

🧬 Les Pull Requests assistées par IA contiennent plus de tests que les P.R manuelles, révèle une analyse portant sur 10 000 P.R. Plusieurs langages sont représentés dans le corpus étudié, de même que plusieurs modèles d'agents différents. Mieux, la quantité de test smells ne varie pas entre les P.R manuelles et les P.R assistées par IA. Aurait-on trouvé un moyen de libérer les développeurs d'une tâche à laquelle ils répugnent souvent ? Pas si vite. 

📏 Premier biais : l'étude est purement quantitative. Or, une testbase peut être verbeuse, tout en ne testant pas grand-chose. Les chercheurs n'ont pas évalué le score de mutation obtenu, c'est bien dommage.

🪵 Second biais : les chercheurs notent que les humains tendent à remanier les tests, ce que ne fait jamais l'IA. Elle se contente d'empiler de nouveaux test cases, sans chercher à clarifier ou élaguer l'existant. Or, si les tests sont une spécification, l'IA ne rend pas un grand service en augmentant le volume brut.

🧯 Je suis d'avis de ne pas laisser une chose aussi importante que les tests à l'IA. Elle est bien meilleure lorsqu'on lui demande de générer un code passant des tests que l'inverse.

SOURCE

Milanese, R., Salzano, F., Spina, A., Vitale, A., Pareschi, R., Fasano, F., & Fazzini, M. (2026). Human-agent versus human pull requests: A testing-focused characterization and comparison. arXiv. DOI:10.48550/arXiv.2601.21194
