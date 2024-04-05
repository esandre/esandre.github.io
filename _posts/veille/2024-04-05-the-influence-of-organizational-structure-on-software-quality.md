---
title: "The influence of organizational structure on software quality"
layout: post
category: 'veille'
tags: quality management
lang: french
ref: the-influence-of-organizational-structure-on-software-quality
doi: 10.1145/1368088.1368160
link: https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-2008-11.pdf
---

📖 La Loi de Conway énonce que les systèmes qu'une organisation produit sont la copie de sa structure de communication. Brooks n'est pas plus tendre en reliant la qualité des logiciels à la qualité des relations dans l'équipe. Cependant aucun n'apporte de preuves empiriques.

📏 Mesurer une telle corrélation n'est pas simple. Il faut déjà quantifier la qualité. A la lecture de cette proposition, la plupart des philosophes se sont crevés les yeux. Nous savons cependant approximer la qualité à l'aide d'un cocktail de métriques : la complexité du code, son niveau de beurdassage (code churn en anglais, je trouve la traduction saintongeaise plus transparente que le français), le coverage, le nombre de dépendances ou le taux de bugs. Ces mesures ont toutes de gros défauts, mais mises ensemble elles sont une mesure acceptable de qualité. Côté relationnel, il a fallu inventer 8 métriques, quantifiant des indicateurs découverts par d'autres travaux. 

⚠️ Les chercheurs ont découvert que la structure de l'organisation portant le projet prédit mieux la probabilité de défaut que l'ensemble des métriques de qualité listées plus haut. Ces résultats sont à prendre avec beaucoup de prudence : un seul projet a servi d'étude de cas, les métriques organisationnelles sont crées pour l'occasion et la quantification de la qualité est périlleuse. Cependant ces résultats sont encourageants et appellent à répliquer cette étude.

SOURCE

Nagappan, Nachiappan, Brendan Murphy and Victor R. Basili. “The influence of organizational structure on software quality.” 2008 ACM/IEEE 30th International Conference on Software Engineering (2008): 521-530. DOI: 10.1145/1368088.1368160