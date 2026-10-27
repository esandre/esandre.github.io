---
title: "How Do AI Coding Agents Contribute to Software Development? An Empirical Study of Agentic Pull Requests"
layout: post
category: 'veille'
tags: ai
lang: french
ref: how-do-ai-coding-agents-contribute-to-software-development-an-empirical-study-of-agentic-pull-requests
doi: 10.48550/arXiv.2607.21832
link: https://arxiv.org/abs/2607.21832
---

🌊 Les IA ont inondé les pull requests de nombreux projets, épuisant les reviewers et provoquant des polémiques. Une équipe de Polytechnique Montréal a cherché à savoir combien de ces PR sont effectivement acceptées, sur quelles tâches le recours aux IA est le plus fréquent et quel est leur impact en termes de qualité logicielle.

📈 84 % des PR générées avec Claude sont acceptées, contre seulement 59 % avec Copilot. Le modèle compte énormément, mais les ténors du marché s'en tirent plutôt bien. Les chercheurs notent que Claude obtient ce résultat alors qu'il est employé sur des projets en moyenne plus gros et plus complexes que ceux de ses concurrents.

⚖️ Le score est impressionnant, mais il faut tempérer ce résultat. La seconde partie de l'étude montre que les IA sont employées en priorité sur des tâches jugées à la fois répétitives et complexes : la documentation, la mise à jour de dépendances et, à mon grand regret, les tests (alors que d'autres études montrent l'incurie des LLM sur le sujet).

🧹 Les tâches pour lesquelles une IA a le plus de chances de voir sa PR acceptée sont des tâches sans grande valeur ajoutée : gestion d'assets, renouvellement de tokens, rédaction de licences, édition de pipelines de CI. La plupart de ces tâches, même si elles sont triviales, restent critiques, ce qui explique peut-être le faible recours aux IA pour les traiter.

🧑‍💻 Sur le cœur de métier d'un développeur, les IA passent moins facilement la barrière de la review. Est-ce par phobie anti-IA ? Avec les métriques choisies par les chercheurs, il n'est pas possible de conclure. Les modèles sont tous très différents dans leur manière d'interagir avec les humains et le code. Certains modèles questionnent beaucoup, d'autres non. Certains touchent de nombreux fichiers, d'autres non. Etc.

🐛 Enfin, sur le taux de bugs, une fois la PR acceptée, la différence entre les humains et les IA est négligeable.

🎯 Que conclure ? Avec un bon modèle, il n'est pas aberrant de confier les tâches répétitives aux LLM, afin de nous concentrer sur notre cœur de métier : le développement de features. Tout le monde y trouvera son compte, les développeurs dispensés de boilerplate comme les reviewers qui auront moins d'AI-crap à relire.

SOURCE

Mazloomzadeh, Iren, Mohammad Mehdi Morovati, and Foutse Khomh. “How Do AI Coding Agents Contribute to Software Development? An Empirical Study of Agentic Pull Requests.” arXiv, July 23, 2026. DOI:10.48550/arXiv.2607.21832.