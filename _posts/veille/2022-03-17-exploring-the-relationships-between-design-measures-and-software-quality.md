---
title: "Exploring the relationships between design measures and software quality"
layout: post
category: 'veille'
tags: quality
lang: french
ref: exploring-the-relationships-between-design-measures-and-software-quality
doi: 10.1016/S0164-1212(99)00102-8
---

📏 Les années 90 ont laissé derrière elles pléthore de mesures quantitatives du code : CBO, RFC, MPC, DAC, ICP, etc. Elles sont passées de mode dès la décennie suivante, faute de preuves de leur efficacité contre les bugs. On leur doit tout de même l’abandon progressif de l’héritage en orienté-objet, plus avantageusement remplacé par la composition dans la plupart de ses usages.

🔎 Le papier du jour analyse l’efficacité de différentes mesures et leur corrélation avec la probabilité de découvrir des défauts. Si les mesures d’héritage ou de couplage s’en sortent bien, les mesures de cohésion ne semblent pas donner de résultats.

🐛 Autrement formulé, si les mesures de cohésion et d’héritage sont bien corrélées à la probabilité qu’il existe un défaut dans un classe, il n’y a aucune garantie que ces défauts quantitatifs soient corrélés à de vrais bugs, qualitativement ressentis comme tel. La plupart des études des années 2000 ont confondu ces notions, ce qui les rend caduques avec le recul.

SOURCE

Briand, Lionel Claude, Jürgen Wüst, John W. Daly and D. Victor Porter. “Exploring the relationships between design measures and software quality in object-oriented systems.” J. Syst. Softw. 51 (2000): 245-273. DOI : 10.1016/S0164-1212(99)00102-8