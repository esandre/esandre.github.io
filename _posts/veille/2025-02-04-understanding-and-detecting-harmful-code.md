---
title: "Understanding and Detecting Harmful Code"
layout: post
category: 'veille'
tags: smells
lang: french
ref: understanding-and-detecting-harmful-code
doi: 10.1145/3422392.3422420
link: https://leopoldomt.github.io/assets/pdf/2020-sbes-2.pdf
---

🐛 La plupart des odeurs du code ne sont pas corrélées à la présence de bugs et inversement, la plupart des bugs ne sont pas liés à des odeurs du code. Ces deux concepts désignent des réalités différentes. Une seule odeur du code ressort du lot en étant modérément corrélée à l'apparition de bugs : l'appel de méthodes abstraites depuis le constructeur. S'il faut prioriser un refactoring c'est bien celui-ci.

🔎 Le papier vise surtout à améliorer les outils de détection de bugs. En remontant depuis les odeurs jusqu'aux métriques permettant de les détecter automatiquement, les chercheurs en ont sélectionné plusieurs qui sont modérément corrélées à l'apparition de bugs. Rien de surprenant pour un développeur chevronné : nombre excessif de paramètres, nombre excessif de méthodes par classes, complexité ou longueur extrême d'une méthode. Rien de nouveau sous le soleil.

SOURCE

Rodrigo Lima, Jairo Souza, Baldoino Fonseca, Leopoldo Teixeira, Rohit Gheyi, Márcio Ribeiro, Alessandro Garcia, and Rafael de Mello. 2020. Understanding and Detecting Harmful Code. In Proceedings of the XXXIV Brazilian Symposium on Software Engineering (SBES '20). Association for Computing Machinery, New York, NY, USA, 223–232. DOI:10.1145/3422392.3422420