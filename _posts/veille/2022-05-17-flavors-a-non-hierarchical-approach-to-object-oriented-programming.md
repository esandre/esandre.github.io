---
title: "Flavors : A non-hierarchical approach to object-oriented programming"
layout: post
category: 'veille'
tags: histoire-informatique langages
lang: french
ref: flavors-a-non-hierarchical-approach-to-object-oriented-programming
---

🍨 Parmi les tentatives pour remédier aux défauts de l’héritage, les mixins figurent en bonne place. Ce concept, créé entre 1979 et 1982 a survécu de nos jours, mais inspira aussi d’autres mécanismes comme les traits, les méthodes d’extension ou les méthodes d’interface.

🔷 Les mixins se présentent comme une solution au problème du diamant, casse-tête à la fois sémantique et pratique courant en POO.

🪟 Dans une interface graphique, vous avez des fenêtres. Certaines ont des labels, d’autres non. Certaines ont des bords, d’autres non. De qui hérite une fenêtre à bords avec label ?

❌ Les deux solutions instinctives sont l’héritage multiple et l’usage de patterns. Les deux apportent de la complexité et ne sont pas satisfaisantes sémantiquement. Une fenêtre n’est pas une fenêtre à bords et une fenêtre à label. C’est une fenêtre, avec des bords et un label.

🎨 Les mixins permettent cela. Sémantiquement, ils expriment une inclusion, non un héritage. Un même objet peut inclure plusieurs flavors, dont le mélange créé le mixin. Ces flavors peuvent hériter d’autres flavors, mais en aucun cas être instanciés seuls.

🤯 L’inconvénient de ce système est de laisser une grande place aux conventions, ce qui augmente la charge mentale qui pèse sur les développeurs et les équipes. En outre, ils ne protègent aucunement des paradoxes logiques comme le Diamant de Nixon.

SOURCE

Cannon, Howard I.. “Flavors : A non-hierarchical approach to object-oriented programming.” (2007).