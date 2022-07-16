---
title: "Analyses of Regular Expression Usage in Software Development"
layout: post
category: 'veille'
tags: thesis codesmithing
lang: french
ref: analyses-of-regular-expression-usage-in-software-development
---

Les expressions régulières (Regex) sont massivement utilisées, mais très peu testées car difficilement testables, donc d’une fiabilité douteuse.  
  
Cette conclusion est celle de la thèse (2021) de Peipei Wang, une doctorante en informatique de Caroline du Nord.  
  
Je conseille aux non-chercheurs la lecture des chapitres 1, 3, 4, 5.  
  
Vous y apprendrez que :  
-Dans la réalité, personne ne teste ces $\*x% de regex (17% sur les projets open-source étudiés).  
-Elles sont une importante source de bugs vicieux.  
-Elles sont encore imparfaitement portables à travers les langages.  
-Les outils pour correctement les tester sont encore peu diffusés (Rex pour ne citer que lui). Elles sont encore trop testées simplement par branch coverage ou statement coverage, ce qui est erroné.  
-Les développeurs en ont peur et y touchent très rarement dans leur code. Lorsqu’ils y sont contraints (bug ou évolution), ile préfèrent les supprimer et les remplacer par un parser (ce qui n’est pas toujours une mauvaise solution d’ailleurs).

<https://repository.lib.ncsu.edu/handle/1840.20/39015>