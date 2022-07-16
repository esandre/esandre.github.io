---
title: "Une revue sur les odeurs du code"
layout: post
category: 'veille'
tags: smells patterns
lang: french
ref: une-revue-sur-les-odeurs-du-code
dois: 10.1109/TSE.2012.89 10.1109/ICSM.2012.6405253 10.1109/WCRE.2009.28 10.1109/ICSM.2010.5609564 10.1016/j.jss.2006.10.018
---

🦨 Odeur du code ! Antipattern ! Si le capitaine Haddock était développeur, il abuserait sans doute d’un tel vocabulaire. Mais qu’en est-il de la recherche ? Ces notions sont-elles pertinentes, ou juste des caprices de développeurs ?  
  
📝 J’ai récupéré 5 papiers, écrits entre 2009 et 2013, qui en parlent. Pour être d’accord sur la définition, une odeur du code est une indication d’un potentiel problème plus profond, l’antipattern. Fowler, qui a inventé le terme, différencie bien les deux. L’antipattern est une mauvaise solution clairement identifiée. L’odeur est un indice, ne menant pas toujours à un antipattern. Et tous les antipatterns ne « sentent » pas, certains ne sont visibles que via une analyse poussée.  
  
🐛 Dans la littérature, les classes porteuses d’odeurs sont en général plus défectueuses et moins compréhensibles que les autres.  
Cependant, les études se contredisent sur leur résistance et leur exposition au changement, qui s’explique au moins partiellement par leur plus grande taille, une variable mieux corrélée que le nombre d’odeurs à ces indicateurs.  
  
💣 Les antipatterns sont moins étudiés, mais semblent corrélés à un plus grand nombre d’erreurs et une plus grande exposition au changement. En d’autres termes, ils changent plus souvent et leurs changements sont plus véreux que la moyenne.  
  
🔄 La recherche montre également que toutes les odeurs ne se valent pas, certaines sont faiblement corrélées à des antipatterns, d’autres très fortement.  
  
✔️ En résumé, les code smells indiquent bien quelque chose sur la qualité du code, mais ils ne peuvent pas se passer d’une analyse des développeurs ! Fowler a vu juste, comme souvent.  

SOURCES  
  
D. I. K. Sjøberg, A. Yamashita, B. C. D. Anda, A. Mockus and T. Dybå, "Quantifying the Effect of Code Smells on Maintenance Effort," in IEEE Transactions on Software Engineering, vol. 39, no. 8, pp. 1144-1156, Aug. 2013, doi: 10.1109/TSE.2012.89.

Steffen M. Olbrich, Daniela S. Cruzes, and Dag I. K. Sjoberg. 2010. Are all code smells harmful? A study of God Classes and Brain Classes in the evolution of three open source systems. In Proceedings of the 2010 IEEE International Conference on Software Maintenance. DOI:10.1109/ICSM.2010.5609564
  
Bavota, Gabriele &amp; Qusef, Abdallah &amp; Oliveto, Rocco &amp; Lucia, Andrea &amp; Binkley, David. (2012). An empirical analysis of the distribution of unit test smells and their impact on software maintenance. IEEE International Conference on Software Maintenance, ICSM. 56-65. 10.1109/ICSM.2012.6405253  
  
F. Khomh, M. Di Penta and Y. Gueheneuc, « An Exploratory Study of the Impact of Code Smells on Software Change-proneness, » 2009 16th Working Conference on Reverse Engineering, 2009, pp. 75-84, doi: 10.1109/WCRE.2009.28.  
  
Li, Wei and Raed Shatnawi. “An empirical study of the bad smells and class error probability in the post-release object-oriented system evolution.” J. Syst. Softw. 80 (2007): 1120-1128. DOI:10.1016/j.jss.2006.10.018