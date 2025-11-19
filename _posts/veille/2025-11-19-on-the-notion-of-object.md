---
title: "On the notion of object"
layout: post
category: 'veille'
tags: langages
lang: french
ref: on-the-notion-of-object
doi: 10.1016/0164-1212(93)90013-N
---

📦 Le concept d'objet dans les langages orientés-objet est difficile à définir. Les divergences entre les différentes "saveurs" d'orienté-objet et le drama entre auteurs explique en partie le problème. Les américains tendent à y voir seulement un mécanisme de modélisation efficace, tandis que les européens tendent à rechercher une certaine esthétique philosophique dépassant la stricte nécessité technique.  

🏺 Pour comprendre ce qu'est un objet, il faut étudier la notion sous plusieurs angles, n'ayant pas tous un rapport direct à l'informatique, nous serions même parfois plus proches des mathématiques, de la psychologie et de la philosophie.

😶‍🌫️ Un objet peut être vu comme une substance attachée à une identité permettant de le distinguer des autres. Toujours dans la même veine ontologique, un objet peut aussi être défini comme l'inverse d'une valeur. Cette dernière est éternelle, immuable, universelle et sans identité. Hélas la plupart des langages ne l'entendent pas ainsi et la moindre valeur, même une primitive, est alors un objet comme un autre. En informatique, "Objet" est un terme équivoque, zut.

🛡️ L'objet peut aussi être défini comme l'inverse des fonctions. La fonction n'a aucune mémoire, elle est pure et sans effet de bord. L'objet stocke un état. Mais ce serait insuffisant car les objets exposent des opérations qui protègent l'état qu'ils contiennent contre l'écriture de valeurs invalides. Parce qu'il n'est pas référentiellement transparent, l'objet est une abstraction, masquant une partie de la complexité qu'il contient derrière une façade : son interface. Hélas encore une fois, le concepte d'abstraction de données et celui d'objet ne sont pas identiques et ne se recouvrent pas complètement. Caramba, encore raté !

🔢 Essayons alors la définition purement technique : un objet est un dictionnaire de propriétés, chacune étant un tableau d'octets que l'on regarde à travers des lunettes qui permettent de l'interpréter. Ce point de vue est probablement le plus exact, mais aussi le plus insatisfaisant, sauf peut-être pour un développeur Javascript.

➗ Essayons alors les mathématiques. Un objet est alors une machine à états finis, possédant des fonctions transformant un état en un autre. L'objet peut être décrit comme un tuple à 4 éléments : son identité, son type, son état actuel et l'ensemble des identifiants y faisant référence. L'identité est immuable, le type l'est souvent, l'état peut varier selon les règles qu'impose le type. Le type peut parfaitement imposer à l'état d'un objet une totale immutabilité, ce qui le rend référentiellement transparent. Les identifiants quant à eux sont un tableau associant des noms à un objet donné.

🧑‍🏫 Pris isolément, aucun de ces points de vue n'a la moindre utilité pratique au développeur. Tous ces points de vue sont complémentaires et offrent un éclairage complet sur un phénomène bien plus complexe qu'il n'y paraît. L'auteur cite Marvin Minsky : nous ne comprenons rien tant que nous ne l'avons pas appris de plusieurs manières.

SOURCE

Antero Taivalsaari. 1993. On the notion of object. J. Syst. Softw. 21, 1 (April 1993), 3–16. DOI:10.1016/0164-1212(93)90013-N