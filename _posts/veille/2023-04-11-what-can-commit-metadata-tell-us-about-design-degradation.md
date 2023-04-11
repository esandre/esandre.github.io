---
title: "What can commit metadata tell us about design degradation ?"
layout: post
category: 'veille'
tags: codesmithing smells
lang: french
ref: what-can-commit-metadata-tell-us-about-design-degradation
doi: 10.1145/2501543.2501547
link: http://igor.pro.br/publica/papers/IWPSE2013.pdf
---

📏 Les métriques fiables et utiles manquent aux développeurs et l'analyse statique du code piétine. Cependant un second filon est plus prometteur : le minage de commits. Il consiste en l'analyse des changements sur un VCS. Quatre chercheurs brésiliens ont réussi à quantifier la fragilité et la rigidité d'un code, deux mesures de Robert C. Martin, en mesurant les propriétés d'une série de commits.

💥 Si un commit édite de nombreux fichiers, il est dit dense, ce qui est une odeur indiquant une rigidité potentielle. La notion se rapproche de la shotgun surgery.

🪢 Si un commit touche à de nombreux fichiers éloignés dans l'arborescence, il est dit dispersé, ce qui est un odeur indiquant une fragilité potentielle.

💎 La méthode fonctionne, mais rencontre deux limites : la première est son inapplicabilité sans pré-traitement des commits. Merge commits, changements de style, documentation ... ces changements polluent les mesures et les faussent, il faut donc un moyen de les exclure des calculs. La seconde est la nécessité pour les développeurs de respecter strictement le principe d'une feature par commit. Sans cela les facteurs de confusion rendent inopérante la méthode.

SOURCE

Oliva, Gustavo Ansaldi, Igor Steinmacher, Igor Scaliante Wiese and Marco Aurélio Gerosa. “What can commit metadata tell us about design degradation?” International Workshop on Principles of Software Evolution (2013).