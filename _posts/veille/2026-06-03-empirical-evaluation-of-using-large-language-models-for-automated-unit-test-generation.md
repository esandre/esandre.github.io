---
title: "An Empirical Evaluation of Using Large Language Models for Automated Unit Test Generation"
layout: post
category: 'veille'
tags: testing
lang: french
ref: empirical-evaluation-of-using-large-language-models-for-automated-unit-test-generation
doi: 10.48550/arXiv.2302.06527
link: https://arxiv.org/abs/2302.06527
---

🧪 Si l'on demande à des LLM de générer des tests unitaires couvrant un programme, le résultat ressemble peu ou prou à ce qu'un développeur moyen ferait : un statement coverage médian de 70%, un branch coverage médian de 53%.

📊 Ce score seul ne nous apprend rien, il est connu depuis des décennies qu'un bon coverage n'est pas un indicateur fiable de la qualité des tests. Aussi les chercheurs ont calculé une deuxième métrique : le pourcentage d'assertions triviales. Sur l'ensemble des projets, la médiane est de 39% de tests générés qui ne vérifient rien d'utile. C'est énorme.

⚠️ Le verdict s'alourdit lorsque l'on considère les tests non-passants, une métrique discrètement écartée par les chercheurs : seuls 44% des tests sont à la fois passants et non-triviaux. C'est un score décevant.

🧠 Les LLM sont capables de générer des tests donnant l'illusion de fonctionner, c'est bien plus dangereux que si les tests étaient manifestement mauvais. Des développeurs n'y prenant pas garde pourraient condamner leur projet en vérolant sa base de tests. Les auteurs semblent très optimistes quant à la capacité des LLM à générer de tests. Ils repoussent l'évaluation de la qualité de ceux-ci à un article ultérieur.

SOURCE

Schäfer, M., Nadi, S., Eghbali, A., and Tip, F. 2023. An Empirical Evaluation of Using Large Language Models for Automated Unit Test Generation. arXiv preprint arXiv:2302.06527. DOI:10.48550/arXiv.2302.06527.