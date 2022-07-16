---
title: "When Does a Refactoring Induce Bugs ? An Empirical Study"
layout: post
category: 'veille'
tags: refactoring
lang: french
ref: when-does-a-refactoring-induce-bugs-an-empirical-study
doi: 10.1109/SCAM.2012.20
---

🛠️ Contrairement à un mythe tenace, le refactoring, même automatisé par l’IDE, présente des risques d’introduire des bugs ! La seule parade est un jeu de tests de qualité.  
  
🤌 6 chercheurs italiens ont sorti en 2012 un papier à ce sujet. Tous les refactoring ne sont pas égaux. Renommer est souvent anodin. Manipuler les hiérarchie est le plus glissant, jusqu’à 40% des actions de type Pull Up Method et Extract Subclass introduisent des bugs, contre 15% pour le refactoring en général.  
  
✔️ On ne répétera jamais assez l’importance des tests en logiciel, il sont le filet de sécurité qui permet au développeur de remanier son travail jusqu’à le rendre satisfaisant.  
  
SOURCE :  
  
M. Fowler, K. Beck, J. Brant, W. Opdyke, D. Roberts, Refactoring : Improving the Design of Existing Code. Addison Wesley, 1999  
  
G. Bavota, B. De Carluccio, A. De Lucia, M. Di Penta, R. Oliveto and O. Strollo, « When Does a Refactoring Induce Bugs? An Empirical Study, » 2012 IEEE 12th International Working Conference on Source Code Analysis and Manipulation, 2012, pp. 104-113, doi: 10.1109/SCAM.2012.20.