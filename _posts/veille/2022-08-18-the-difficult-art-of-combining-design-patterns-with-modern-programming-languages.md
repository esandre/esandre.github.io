---
title: "The Difficult Art of Combining Design Patterns with Modern Programming Languages"
layout: post
category: 'veille'
tags: patterns langages thesis
lang: french
ref: the-difficult-art-of-combining-design-patterns-with-modern-programming-languages
---

🩹 Les langages de programmation et les design patterns ont une relation compliquée. Déjà à l'époque du Gang of Four, Peter Norvig signalait que la plupart des patterns n'étaient que des rustines autour de langages trop pauvres. Les lambda des langages fonctionnels dispensent d'utiliser des factory, par exemple. Certains langages supportent nativement certains patterns et d'autres non ? Trop binaire et réducteur nous répond Eirik Emil Neesgaard Årseth.

🎨 A une vision binaire, il répond en classifiant les relations entre langages et patterns en 4 groupes, dans son mémoire de master (!). Ceertains langages incluent certains patterns dans leur syntaxe, nativement. D'autres absolument pas. Entre ces deux extrêmes, certains langages facilitent certains patterns sans les proposer pour autant. Par exemple, Javascript et son système de types facilite grandement le pattern Prototype. Enfin, certains langages ne proposant pas le support d'un pattern sont rattrapés par leur bibliothèque standard. Que serait C# sans Linq, par exemple.

🦽 Alors, les patterns sont-ils des prothèses pour des langages déficients ? Certains, assurément, mais il est abusif d'employer cette formule pour l'ensemble. Alors que les patterns créationnels sont presque tous des features manquantes, l'auteur prend le pari que les patterns structurels sont là pour de bon.

SOURCE

Årseth, Eirik Emil Neesgaard. The Difficult Art of Combining Design Patterns with Modern Programming Languages. Master thesis, University of Oslo, 2020