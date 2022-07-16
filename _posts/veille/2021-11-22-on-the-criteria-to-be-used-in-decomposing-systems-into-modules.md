---
title: "On the Criteria To Be Used in Decomposing Systems into Modules"
layout: post
category: 'veille'
tags: architecture codesmithing
lang: french
ref: on-the-criteria-to-be-used-in-decomposing-systems-into-modules
doi: 10.1145/361598.361623
---

🎺 « Si les développeurs chantaient des hymnes, le plus populaire serait l’hymne de la modularité » c’est ainsi que David Parnas commence son article « On the Criteria to be used in Decomposing Systems into Modules » en 1971. Un article que toute personne tentée par les microservices doit lire.  
  
✂️ Après une démonstration, il conclut en priant les développeurs d’arrêter de découper leurs programmes à l’avance sur la base d’un organigramme. Cela ne fonctionne pas mieux en 2021 qu’en 1971. Il encourage plutôt à commencer par un monolithe, qui sera découpé au besoin lorsqu’une décision de design importante sera prise.  
  
🔀 Cette décision sera masquée au programme principal, ce qui permet de n’avoir qu’un module à changer si cette décision s’avérait mauvaise et qu’il fallait prendre une autre voie.  
  
SOURCE :  
  
Parnas, David. (1972). On the Criteria To Be Used in Decomposing Systems into Modules. Communications of the ACM. 15. 1053-. 10.1145/361598.361623.