---
title: "On the relation of refactorings and software defect prediction"
layout: post
category: 'veille'
tags: refactoring
lang: french
ref: on-the-relation-of-refactorings-and-software-defect-prediction
dois: 10.1145/1370750.1370759 10.1145/1985793.1985815
---

🔄 Le refactoring est craint par les managers, qui pensent que les développeurs le pratiquent par pur perfectionnisme, sans preuve de son efficacité. Et pourtant, cela fait plus de 10 ans que la recherche a tranché : après un refactoring, plus de bugs sont corrigés et le temps moyen pour les résoudre diminue !  
  
⚠️ Attention cependant aux faux-refactorings. Le refactoring modifie la structure du code, sans modifier son comportement. C’est cette technique qui a été validée par la recherche. Pas le remaniement à la fourche de larges morceaux de code. Deux moyens sont possibles :  
-Refactoring assisté, où l’IDE sécurise les changements, le développeur ne touche pas au code à la main.  
-Refactoring libre, sur un code piloté par les tests. Les tests garantissent que le code n’a pas été altéré dans le service rendu.  
  
🪲 Tout autre style de remaniement n’est pas du refactoring, juste du rework. Ce dernier ne bénéficie d’aucune validation par la recherche et pourrait même engendrer plus de bugs que ceux qu’il corrige !  

SOURCES :  
  
Jacek Ratzinger, Thomas Sigmund, and Harald C. Gall. 2008. On the relation of refactorings and software defect prediction. In Proceedings of the 2008 international working conference on Mining software repositories (MSR ’08). Association for Computing Machinery, New York, NY, USA, 35–38. DOI:10.1145/1370750.1370759 
  
Miryung Kim, Dongxiang Cai, and Sunghun Kim. 2011. An empirical investigation into the role of API-level refactorings during software evolution. In Proceedings of the 33rd International Conference on Software Engineering (ICSE ’11). Association for Computing Machinery, New York, NY, USA, 151–160. DOI:10.1145/1985793.1985815
  
1999\. Refactoring: improving the design of existing code. Addison-Wesley Longman Publishing Co., Inc., USA.