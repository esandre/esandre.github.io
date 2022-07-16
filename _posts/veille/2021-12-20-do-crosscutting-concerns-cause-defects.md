---
title: "Do Crosscutting Concerns Cause Defects ?"
layout: post
category: 'veille'
tags: codesmithing quality
lang: french
ref: do-crosscutting-concerns-cause-defects
doi: 10.1109/TSE.2008.36
---

💥 Plus une fonctionnalité est éparpillée dans le code, plus elle a de chances d’être défectueuse. Cela vaut aussi pour les Crosscutting Concerns (logs, sécurité, exceptions, etc.). Plus ils sont nombreux et moins ils sont modularisés, plus le code spaghetti guette !  
  
💣 Ce résultat, indépendant du nombre de lignes de code, a été obtenu en 2008 par plusieurs membres de l’organisation IEEE. Ils répondaient à la question « Les Crosscutting Concerns sont-ils source de défauts ? ». La réponse est bien oui, car ils sont difficiles à modulariser, difficiles à tester et sont donc très souvent implémentés avec insouciance par les développeurs, au motif que « ça n’est pas du code métier ».  
  
⚠️ Les Crosscutting Concerns sont partout et ne doivent pas être pris à la légère. Contrairement à la croyance courante, ils sont à confier aux plus expérimentés, pas aux juniors que l’on refuse de mettre sur le code métier.  
  
SOURCE  
  
Marc Eaddy, Thomas Zimmermann, Kaitlin D. Sherwood, Vibhav Garg, Gail C. Murphy, Nachiappan Nagappan, and Alfred V. Aho. 2008. Do Crosscutting Concerns Cause Defects? IEEE Trans. Softw. Eng. 34, 4 (July 2008), 497–515.