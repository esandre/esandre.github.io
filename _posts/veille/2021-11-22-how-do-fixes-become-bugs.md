---
title: "How do fixes become bugs ?"
layout: post
category: 'veille'
tags: quality
lang: french
ref: how-do-fixes-become-bugs
doi: 10.1145/2025113.2025121
---

🐞 Certains bugs ne doivent surtout pas être résolus dans la précipitation, même s’ils bloquent une fonction vitale en production. Le risque que le hotfix soit un bug encore plus gros est bien trop grand.  
  
C’est l’alerte levée par le papier, déjà ancien (2011) de Yin et al.  
  
3️⃣ Ces familles de bugs tiennent en 3 lettres : CMS.  
-Concurrency (Locks, Tasks, Sync, etc.)  
-Memory (Allocation, Overflow, Pointers, etc.)  
-Semantic (Application-specific)  
Respectivement 40%, 14% et 17% des patchs devant résoudre ces bugs sont eux-mêmes buggés !  
  
🔒 Pire, sur les verrous, sujet très dangereux en développement, les chercheurs ont noté que 14% des patchs venant corriger un bug introduit par un autre patch sont eux-mêmes buggés !  
  
🧠 Testez vos bugs, Defect Testing évite énormément de problèmes sur ces sujets où nos cerveaux sont dépassés par la complexité du code.   
SOURCE :  
  
Zuoning Yin, Ding Yuan, Yuanyuan Zhou, Shankar Pasupathy, and Lakshmi Bairavasundaram. 2011. How do fixes become bugs? In Proceedings of the 19th ACM SIGSOFT symposium and the 13th European conference on Foundations of software engineering (ESEC/FSE ’11). Association for Computing Machinery, New York, NY, USA, 26–36. DOI: 10.1145/2025113.2025121