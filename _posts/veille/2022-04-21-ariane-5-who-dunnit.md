---
title: "Ariane 5: Who Dunnit ?"
layout: post
category: 'veille'
tags: failures
lang: french
ref: ariane-5-who-dunnit
doi: 10.1109/MS.1997.589224
---

🚀 4 juin 1996. Ariane 5 décolle de la base de Kourou. 37 secondes plus tard, le lanceur explose avec à son bord des expériences scientifiques. Aucun humain n’était à bord, fort heureusement. A qui la faute ? A la gestion du logiciel dans le programme.

🐛 Une exception non rattrapée a provoqué une conversion incorrecte, puis un arrêt des systèmes du gyroscope. Ce logiciel avait été porté d’Ariane 4 vers Ariane 5 sans avoir été retesté. La faute à qui ? Comme dirait Jacques Ellul, à personne car le processus était trop complexe pour désigner un coupable. Nous pouvons cependant désigner des suspects.

💥 Les développeurs ont fait une erreur. Elle était dormante sur Ariane 4 et ne s’est déclenchée qu’une fois le logiciel porté sur Ariane 5. Ils ne pouvaient pas l’anticiper, les tests étant incapables de prouver l’absence de bugs. Elle aurait pu être évitée par l’usage d’un langage plus fortement typé, mais ils n’ont probablement pas eu le choix.

🧪 Les testeurs pourraient être coupables, mais ont-ils eu le budget et le temps de revérifier tous les systèmes portés d’Ariane 4 à Ariane 5 ? Le rapport indique qu’il n’y a pas eu de tests de cette partie, sans en indiquer la cause.

🪄 Comme d’habitude c’est la faute au process, donc à personne, sauf à la responsabilité individuelle, éventuellement.

SOURCE

Bashar Nuseibeh. 1997. Ariane 5: Who Dunnit? IEEE Softw. 14, 3 (May 1997), 15–16. DOI:10.1109/MS.1997.589224