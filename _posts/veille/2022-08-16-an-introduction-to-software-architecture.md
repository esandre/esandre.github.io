---
title: "An Introduction to Software Architecture"
layout: post
category: 'veille'
tags: methods
lang: french
ref: an-introduction-to-software-architecture
doi: 10.1142/9789812798039_0001
---

🏗️ Aussi étrange que cela paraisse, l'architecture logicielle n'est pas une discipline unifiée ou clairement définie. Une des définitions est celle donnée il y a 30 ans par Garlan et Shaw. Pour eux, l'architecture est la réponse à la complexité de certains logiciels, qu'un bon design ne peut plus juguler. Il faut alors ajouter une couche d'abstraction.

⛔ L'architecte ignore volontairement le code, encapsulé dans des blocs de design. Chaque bloc, nommé composant, interagit ou n'interagit pas avec les autres, selon des règles définies par l'architecte. L'ensemble de ces règles d'architecture détermine la forme du système. L'architecture, pour Garlan et Shaw, consiste à sculpter le système par des règles, qui viennent restreindre la manière dont peuvent se connecter les composants.

🪠 Un exemple ? Obligez les composants à avoir x entrées et y sorties dans un format standardisé. N'autorisez que les connecteurs reliant l'entrée d'un composant à la sortie d'un autre. Vous obtenez une architecture Pipes&Filters omniprésente dans la BI, le low-code ou les shells Unix.

👁️ La vision de Garlan&Shaw donne des règles sur la manière dont les composants ne doivent pas agir. Aux développeurs de les respecter. Elle s'oppose à l'architecture positive, qui inverse la logique : l'architecte dit comment les composants doivent interagir, explicitement. Ces deux visions donnent deux types d'architectes très différents. L'architecte négatif pose des règles, l'architecte positif détermine à chaque instant le comportement des équipes.

SOURCE

Garlan, David and Mary Shaw. “An Introduction to Software Architecture.” Advances in Software Engineering and Knowledge Engineering (1993). DOI: 10.1142/9789812798039_0001