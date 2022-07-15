---
title: "Cohesion and reuse in an object-oriented system"
layout: post
category: 'veille'
tags: codesmithing
lang: french
ref: cohesion-and-reuse-in-an-object-oriented-system
doi: 10.1145/223427.211856
---

💥Les classes les plus réutilisées dans un même système sont celles ayant le moins de cohésion. C’est la trouvaille de deux chercheurs du Colorado. Corrélation n’est pas causalité, mais ce résultat pourrait signifier :

Hypothèse 🅰️ : Qu’il existe une causalité encore à démontrer entre faible cohésion et réutilisation. Cela paraît assez peu probable.

Hypothèse 🅱️ : que les classes réutilisées partout sont souvent aussi atteintes d’une faible cohésion et inversement. Les God Classes qui polluent la plupart des codebases correspondent à ces deux définitions.

🥼 D’autres expériences seront nécessaires pour valider ou invalider ces hypothèses. Mon instinct penche vers la seconde, mais sait-on jamais.

SOURCE

James M. Bieman and Byung-Kyoo Kang. 1995. Cohesion and reuse in an object-oriented system. SIGSOFT Softw. Eng. Notes 20, SI (Aug. 1995), 259–262. DOI:10.1145/223427.211856