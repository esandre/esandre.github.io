---
title: "Is Design Dead ?"
layout: post
category: 'veille'
tags: codesmithing expert refactoring methods
lang: french
ref: is-design-dead-fowler
---

🤠 On reproche à eXtreme Programming d'être revenu à l'ancien temps du "Code&Fix" en rejetant la notion de planification du design. Martin Fowler rétorque qu'en effet, l'équipe qui ferait du cherry-picking dans les pratiques d'XP s'expose bien à un retour à l'ère des cowboy programmers. Dans un long plaidoyer, il explique que se libérer d'UML et de son cortège de diagrammes est absurde sans adhérer d'abord au coeur d'eXtreme Programming : 3 pratiques primant temporellement sur toutes les autres.

1️ Les Tests, sans lesquels tout le reste est impossible, car friable et invérifiable.

2️ L'Intégration Continue, qui permet de ne pas se marcher dessus à plusieurs. Elle nécessite les tests.

3️ Le Refactoring qui procède des tests et de l'intégration continue. Il est la clé permettant de diminuer suffisamment le coût du changement d'un système complexe afin qu'un design émerge en cours de route. Il permet de changer un aggrégat de solutions ad-hoc en design révélateur d'intentions, à comportement visible égal.

🆙 Ce n'est qu'une fois ces pratiques acquises qu'une équipe peut adhérer à d'autres pratiques d'eXtreme Programming.

SOURCE

Fowler, Martin. “Is design dead.” (2001).