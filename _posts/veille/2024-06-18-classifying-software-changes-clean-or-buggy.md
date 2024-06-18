---
title: "Classifying Software Changes: Clean or Buggy ?"
layout: post
category: 'veille'
tags: testing
lang: french
ref: classifying-software-changes-clean-or-buggy
doi: 10.1109/TSE.2007.70773
link: http://www.soe.ucsc.edu/~ejw/papers/kim-tse-2008.pdf
---

🔮 Prenez un commit, il serait miraculeux d'avoir un "oracle" capable de dire avec précision les chances d'y trouver des bugs, exactement comme les indices au démineur. C'est possible grâce au Machine Learning, au moins en conditions de laboratoire.

🤖 Il faut pour cela entraîner un modèle, le classificateur, à partir des changements sur un VCS. La procédure exacte est détaillée dans le papier. Le modèle est évalué en vérifiant si de véritables bugs, présents puis corrigés sur des projets open-source, sont détectés.

🛠️ J'ignore si des outils contemporains utilisent de telles techniques. L'article date de 2008, bien avant la hype sur l'IA.

SOURCE

Kim, Sunghun, E. James Whitehead and Yi Zhang. “Classifying Software Changes: Clean or Buggy?” IEEE Transactions on Software Engineering 34 (2008): 181-196.