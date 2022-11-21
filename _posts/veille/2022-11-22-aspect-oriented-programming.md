---
title: "Aspect-Oriented Programming"
layout: post
category: 'veille'
tags: codesmithing
lang: french
ref: aspect-oriented-programming
doi: 10.1145/242224.242420
---

🔏 Les logs, le monitoring ou la sécurité ne sont pas de la responsabilité d'une seule partie du code. Ce sont des responsabilités de l'ensemble du code. Or, SRP et DRY, principes fondamentaux du design, nous interdisent de surcharger chaque classe pour prendre en compte tous ces soucis. Ils sont appelés *crosscutting concerns* ou soucis transversaux en français.

📦 A l'aube des années 2000, la complexité croissante des logiciels a descillé les yeux des développeurs sur ces problèmes. Plusieurs tentatives ont été faites. L'une d'entre-elles, Aspect-Oriented Programming, postule qu'il manque une couche d'abstraction entre les classes et les modules : les composants.

🪡 Ces composants, exprimés à l'aide d'une syntaxe propre, tissent (*weaving*) les classes et les agencent afin de répondre aux soucis transversaux sans violer SRP.

🌫️ AOP se voyait comme l'itération suivante de l'orienté-objet. Avec 20 ans de recul AOP a été très peu adopté, principalement à cause de l'obscurcissement du code qu'il provoque. Les développeurs sont difficilement capables de prédire le fonctionnement d'un programme à cause du tissage qui fait un usage massif de réflexion. Les IDE sont souvent aussi perdus, et incapables d'assister le refactoring d'un tel code.

💉 Cependant, on doit à AOP un vocabulaire (aspect, crosscutting-concern, etc.) et il a ouvert la voie à l'injection de dépendances moderne, qui offre un moyen plus lisible de gérer les mêmes problèmatiques.

SOURCE

Lopes, Cristina & Kiczales, Gregor & Lamping, John & Mendhekar, Anurag & Maeda, Chris & Loingtier, Jean-marc & Irwin, John. (1999). Aspect-Oriented Programming. ACM Computing Surveys. 28. DOI:10.1145/242224.242420 