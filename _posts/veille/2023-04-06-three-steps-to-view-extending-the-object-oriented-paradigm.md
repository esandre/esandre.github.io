---
title: "Three steps to views: extending the object-oriented paradigm"
layout: post
category: 'veille'
tags: langages
lang: french
ref: three-steps-to-view-extending-the-object-oriented-paradigm
doi: 10.1145/74877.74914
link: http://www.researchgate.net/profile/Peter_Sweeney/publication/234793238_Three_steps_to_views_extending_the_object-oriented_paradigm/links/00463519103032ebec000000.pdf
---

💡 Le papier du jour décrit un mécanisme d'extension du paradigme objet n'ayant pas eu de suite, mais là encore, intéressant tant historiquement, car ses prémisses ont été implémentées, que comme point de vue novateur sur nos logiciels.

🧠 Pour les auteurs, la difficulté intellectuelle principale du code est notre capacité limité à nous représenter de gros objets ou un grand nombre de petits objets en interaction. Afin d'être manipulé, un tel système pourrait être synthétisé sous forme d'une vue, ne présentant que les éléments utiles au problème à résoudre.

👀 Le concept de vues est antérieur, il vient du monde des bases de données. Les auteurs proposent d'implémenter un mécanisme similaire dans les langages objet. Pour cela il faut 3 éléments successifs, qui manquaient à l'appel dans les langages objet de l'époque.

1️ Le premier élément est la capacité d'une classe à implémenter plusieurs interfaces. Ce point est évident pour nous en 2023, il ne l'était pas en 1989.

2️ Le second élément est la visibilité différenciée des variables d'un objet selon l'interface consommée. Là encore, rien de novateur pour nos yeux de 2023, C# le fait depuis les années 2000 avec les propriétés, que l'on peut définir en lecture seule dans une interface et en écriture dans une autre.

3️ Le dernier élément est la capacité pour les objets d'offrir une copie différente de leurs variables à chaque invocation d'une interface. A quoi cela sert ? A versionner, chaque instance de vue est une réprésentation du système à un moment, rafraîchir la vue revient à demander à celle-ci une nouvelle instance d'elle-même.

⏭️ Ce dernier élément n'est pas passé à la postérité, même si on peut le considérer comme un précurseur des techniques d'event sourcing.

🤝 Pour les auteurs, le principal bénéfice de ce système est la capacité pour une entité à éditer des composants logiciels ayant seulement des vues pour contrat. Ainsi libre à cette entité de refondre complètement l'implémentation sous-jacente sans se soucier des consommateurs tant que la vue ne change pas.

SOURCE

Shilling, John J. and Peter F. Sweeney. “Three steps to views: extending the object-oriented paradigm.” Conference on Object-Oriented Programming Systems, Languages, and Applications (1989). DOI:10.1145/74877.74914