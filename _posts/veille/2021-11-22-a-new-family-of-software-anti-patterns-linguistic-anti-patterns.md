---
title: "A New Family of Software Anti-Patterns: Linguistic Anti-Patterns"
layout: post
category: 'veille'
tags: patterns codesmithing naming
lang: french
ref: a-new-family-of-software-anti-patterns-linguistic-anti-patterns
doi: 10.1109/CSMR.2013.28
---

👅Le code n’est pas écrit pour les machines, qui se contentent de signaux électriques, mais pour les humains ! Il est donc normal de retrouver des antipatterns linguistiques et autres dettes de langage dans un code.  
  
4 chercheurs ont tenté de classifier les antipatterns linguistiques dans le code. Ils ont trouvé 6 familles, 3 pour les attributs, 3 pour les méthodes.  
1\) Les méthodes qui font plus qu’elles ne disent (effets de bord).  
2\) Les méthodes qui disent plus qu’elles ne font.  
3\) Les méthodes qui font l’opposé de ce qu’elles disent.  
4\) Les attributs dont le nom promet plus qu’ils ne contiennent  
5\) Les attributs qui contiennent plus que ce que promet leur nom  
6\) Les attributs qui contiennent l’opposé de ce qu’indique leur nom  
  
Ces familles contiennent des antipatterns, comme ces Get impurs qui sont bien plus que des accesseurs, ces ‘IsX’ qui renvoient autre chose qu’un booléen, ces commentaires qui contredisent ce qu’ils illustrent ou encore ces méthodes de transformation qui ne retournent rien.  
  
Bien entendu leur travail n’est qu’un premier pas, il existe de nombreux autres antipatterns, sur les noms des classes par exemple. Mais il a le mérite de lancer le sujet, inexploré avant eux.  

SOURCE  
  
Arnaoudova, Venera &amp; Di Penta, Massimiliano &amp; Antoniol, Giuliano &amp; Guéhéneuc, Yann-Gaël. (2013). A New Family of Software Anti-Patterns: Linguistic Anti-Patterns. Proceedings of the European Conference on Software Maintenance and Reengineering, CSMR. 10.1109/CSMR.2013.28.