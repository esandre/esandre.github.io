---
title: "Two Meta-Analysises"
layout: post
category: 'veille'
tags: pair-programming testing
lang: french
ref: two-meta-analysises
dois: 10.1109/TSE.2012.28 10.1016/j.infsof.2009.02.001
---

🔍 Les Méta-Analyses, plus haut niveau de preuves en science, sont assez rares en qualité logicielle. J’en ai une sur l’efficacité de TDD et l’autre sur le Pair Programming. Analysons-les ensemble.  
  
⚠️ Ces deux analyses se rejoignent sur l’absence de standardisation des concepts étudiés et de la manière de les étudier, ce qui rend compliquée l’isolation des variables. Il est donc compliqué de conclure, sauf à avoir de très nombreuses études source.  
  
❓ Rappel : « non concluant », « ne prouve rien » et autres formules de ce style signifient que rien ne peut être conclu. Ni l’efficacité, ni l’inefficacité.  
  
🤝 Sur Pair Programming, des conclusions surprenantes : il est plus rapide d’être deux sur des tâches simples, mais la qualité va baisser. Sur des tâches complexes, être deux produira un meilleur code, au prix d’une baisse de productivité.  
C’est contre-intuitif autant pour les partisans que pour les détracteurs de pair-programming. Cela signifierait que si la qualité compte, il est mieux de laisser les développeurs seuls sur les tâches simples. Si c’est la productivité qui compte, il faut pairer sur les plus triviales !  
  
☑️ Sur TDD, il a un effet positif sur la qualité d’autant plus grand que la tâche est grande, en revanche, il n’a aucun résultat concluant sur la productivité. Ce résultat est plus appuyé dans l’industrie (probablement car les développeurs ont plus de bouteille qu’à l’université) et quand d’autres pratiques d’XP sont utilisées avec TDD.  
  
🕰️ Sur ces deux sujets, les chercheurs déplorent l’absence de papiers sur les effets long-terme de ces deux techniques.  

SOURCES  
Y. Rafique and V. B. Mišić, « The Effects of Test-Driven Development on External Quality and Productivity: A Meta-Analysis, » in IEEE Transactions on Software Engineering, vol. 39, no. 6, pp. 835-856, June 2013, doi: 10.1109/TSE.2012.28.  
  
Jo E. Hannay, Tore Dybå, Erik Arisholm, Dag I.K. Sjøberg, The effectiveness of pair programming: A meta-analysis, Information and Software Technology, Volume 51, Issue 7, 2009, Pages 1110-1122, ISSN 0950-5849, DOI:10.1016/j.infsof.2009.02.001