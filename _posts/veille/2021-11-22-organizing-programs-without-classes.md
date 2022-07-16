---
title: "Organizing Programs Without Classes"
layout: post
category: 'veille'
tags: langages histoire-informatique
lang: french
ref: organizing-programs-without-classes
doi: 10.1007/BF01806107
---

😱 En 1986 naît la programmation orientée prototype, célèbre grâce à JavaScript. Paradoxalement, ce paradigme est relativement inconnu, voire fui par les développeurs JS qui préfèrent oublier son existence ! Quel échec pour celui qui était vu comme révolutionnaire en 1991, au sens littéral du terme : il visait l’abolition des classes.  
  
🤳 Aujourd’hui un papier historique de 4 chercheurs de Stanford, dont David Ungar, le créateur de Self, premier langage orienté prototype.  
  
🗑️ Les auteurs y défendent une thèse osée : les classes sont inutiles à la programmation orientée objet, voire même gênantes. Tout ce que font les classes peut être fait plus simplement par la copie de prototypes : héritage, composition, encapsulation, polymorphisme. Mieux, les prototypes apportent l’héritage dynamique et la modification du comportement hérité par les enfants.  
  
🕵️ L’intérêt de ce papier est surtout historique, 30 ans après, un bilan s’impose :  
❌ Les classes sont bien vivantes et les pratiques actuelles tendent vers des systèmes de typage de plus en plus forts.  
❌ JavaScript vit sans assumer son paradigme historique (cocasse pour quelque chose de révolutionnaire), en témoigne le succès des diverses surcouches et frameworks (NodeJS, TypeScript, etc.).  
❌ L’héritage dynamique n’a pas trouvé d’usage.  
❌ La modification du comportement hérité est vue comme un antipattern en Orienté Objet car il brouille la compréhension.  
❌ En dehors de LUA, tous les autres langages orienté prototype sont tombés dans l’oubli.  
✔️ Le principal héritage de l’orienté prototype est l’idée de traits, présents dans la plupart des langages OO de nos jours, sous diverses formes.  
✔️ La notion de délégué pourrait venir de l’orienté prototype mais son origine est plus floue.  
  
🛑 Bien qu’élégante sur le papier, l’idée des langages a prototypes a souffert de sa courbe d’apprentissage exécrable, totalement incompatible avec la cible de son principal porte-drapeau : JS, le langage des débutants par excellence. Peu sont même au courant du paradigme auquel obéit ce langage. La plupart ont adopté les codes de la programmation fonctionnelle ou impérative lorsqu’ils programment en JS.  
  
SOURCE  
  
Chambers, Craig &amp; Ungar, David &amp; Chang, Bay-Wei &amp; Hölzle, Urs. (1991). Organizing Programs Without Classes.. Lisp and Symbolic Computation. 4. 223-242. 10.1007/BF01806107.