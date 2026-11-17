---
title: "Technical Debt Guild: Managing Technical Debt from Code up to Build"
layout: post
category: 'veille'
tags: methods
lang: french
ref: technical-debt-guild-managing-technical-debt-from-code-up-to-build
doi: 10.5753/jserd.2023.2417.
link: https://www.researchgate.net/publication/369053459_Technical_Debt_Guild_managing_technical_debt_from_code_up_to_build
---

🌳 La dette technique possède une forte dimension transversale. D’une part, certaines catégories de dette, comme la dette architecturale, sont globales par nature. D’autre part, même des formes de dette plus localisées peuvent se retrouver dans plusieurs projets en raison d’antipatterns organisationnels. Une équipe isolée ne peut donc souvent pas faire grand-chose si l’organisation continue de lui déverser sa dette.

🎸 Les guildes sont un modèle popularisé par Spotify pour traiter les sujets transversaux au sein d’une organisation technique. Une équipe brésilienne y a vu un moyen de s’attaquer au problème à la racine et a conçu une expérience en conditions réelles, menée sur plusieurs années au sein d’un éditeur de logiciels brésilien.

🛠️ Le premier cycle fut classique et, par conséquent, décevant : installation de SonarQube et inventaire automatisé de la dette. Or, SonarQube et les outils similaires ne traitent que les fruits les plus accessibles de l’arbre, pas nécessairement les plus juteux. Il faut bien commencer quelque part, même si un tel biais d’ancrage constitue probablement un handicap.

👥 Le deuxième cycle a permis une prise de recul. Des standards de code favorisant une certaine intercompréhension sont élaborés. Un plan de formation des développeurs est mis en place, ainsi qu’un sondage destiné à recueillir les retours de chacun. On passe ainsi du pur outillage du premier cycle à une approche davantage centrée sur l’humain.

🏗️ Le troisième cycle élargit encore le périmètre de la guilde à des artefacts qui échappent aux radars d’un outil comme SonarQube : dette de tests, dette de build et, plus timidement, problèmes organisationnels. Les problèmes les plus visibles ne sont pas nécessairement les plus coûteux.

🔬 L’étude présente évidemment un très faible niveau de preuve : absence de groupe contrôle, étude de cas unique, recrutement par cooptation et recours à une métrique particulièrement discutable — le nombre d’issues SonarQube fermées. Elle ouvre néanmoins une piste intéressante, à condition de sortir de la fascination pour les outils, qui finit par nous desservir.

SOURCE

Detofeno, Thober, Andreia Malucelli, and Sheila S. Reinehr. 2023. “Technical Debt Guild: Managing Technical Debt from Code up to Build.” *Journal of Software Engineering Research and Development* 11 (1): 1–15. DOI:10.5753/jserd.2023.2417.