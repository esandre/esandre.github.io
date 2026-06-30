---
title: "Software Testing With Large Language Models: Survey, Landscape, and Vision"
layout: post
category: 'veille'
tags: methods
lang: french
ref: software-testing-with-large-language-models-survey-landscape-and-vision
doi: 10.1109/TSE.2024.3368208
link: https://arxiv.org/pdf/2307.07221
---

📚 En 2024, une équipe internationale a produit une revue de littérature sur l’usage des LLM dans les tests. Voici leurs conclusions :
- La génération de tests complets par des LLM n’est pas satisfaisante en l’état. Les résultats oscillent entre des tests plausibles mais incorrects et une couverture de code très faible.
- La génération d’assertions seules, dans des tests existants, donne des résultats comparables à ceux d’un développeur humain. Autrement dit, les LLM sont efficaces pour vérifier la validité de la sortie d’un morceau de code.
- Les LLM peuvent compléter les fuzzers pour générer des variantes de tests existants. Ils détectent des bugs que les fuzzers traditionnels ne couvrent pas, en particulier lorsqu’ils sont alimentés par les résultats d’outils de mutation testing.
- Les LLM peuvent dédoublonner des bugs et effectuer un triage sommaire, facilitant la vie des mainteneurs.
- Les LLM identifient relativement bien la cause des bugs, mais ne parviennent à en corriger qu’une faible proportion, et ce au prix d’un coût computationnel élevé.

🎯 Les auteurs notent d’importants biais dans certains résultats. Le plus problématique est la fuite de données de benchmark : les LLM ont probablement été entraînées sur des jeux de données contenant les cas de test utilisés pour les évaluer. C’est comparable à un étudiant ayant accès au sujet d’examen à l’avance.

🌉 Le passage du laboratoire à la réalité est difficile : les modèles deviennent rapidement obsolètes, et l’infinité des prompts possibles rend les résultats peu reproductibles pour un praticien. Cette difficulté est accentuée par le fait que la recherche se concentre surtout sur les tests end-to-end et unitaires, en délaissant les tests d’intégration et d’acceptation, pourtant souvent les plus utiles. Les tests de performance ou d’accessibilité sont quasiment absents de la littérature.

🧾 Le papier est difficile à lire, car les auteurs ne distinguent pas clairement les études solides des simples tentatives. J’ai écarté les passages qui ne présentaient pas de résultats clairs. Il n'est pas improbable que les études mentionnées dans cette revue de littérature soient recensées ici à l'avenir.

SOURCE

Wang, Junjie, Yuchao Huang, Chunyang Chen, Zhe Liu, Song Wang and Qing Wang. “Software Testing With Large Language Models: Survey, Landscape, and Vision.” IEEE Transactions on Software Engineering 50 (2023): 911-936. DOI:10.1109/TSE.2024.3368208