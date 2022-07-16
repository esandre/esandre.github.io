---
title: "Rule-based Assessment of Test Quality"
layout: post
category: 'veille'
tags: smells testing patterns
lang: french
ref: rule-based-assessment-of-test-quality
doi: 10.5381/jot.2007.6.9.a12
---

🇫🇷🇨🇭 Comment évaluer la qualité d’un jeu de tests ? Le coverage ne suffit pas. Les tests de mutation n’attrapent que les erreurs triviales. Dans un papier de 2007, une équipe Franco-Suisse démontre que les odeurs des tests (Test Smells) sont un outil pertinent pour repérer les mauvais tests.  
  
🦨 Les Test Smells sont les cousins des Code Smells, qui matérialisent des problèmes de qualité potentiels dans un code. Moins connus, ils n’en ont pas moins été jugés efficaces par la recherche et ce papier l’appuie. La plupart des Test Smells sont attachés à un Antipattern de test. Ainsi les odeurs peuvent aider à découvrir qu’un test est trop long, obscur ou erratique. Les chercheurs ont ainsi identifié 27 odeurs reliés à un ou plusieurs antipatterns.  
  
✔️ Leur recherche visait à créer un outil automatisé de détection des tests. Ce faisant ils nous livrent des conclusions intéressantes en tant que praticiens :  
👉 Les Test Smells sont fréquents et nettement reliés aux antipatterns.  
👉 Plus un développeur écrit de tests, meilleurs ils sont.  
  
Leur outil mériterait d’être adapté dans nos langages, mais rien ne remplacera jamais l’oeil du praticien entraîné !  
  
SOURCE  
  
Reichhart, Stefan, Tudor Gîrba and Stéphane Ducasse. “Rule-based Assessment of Test Quality.” J. Object Technol. 6 (2007): 231-251. DOI:10.5381/jot.2007.6.9.a12