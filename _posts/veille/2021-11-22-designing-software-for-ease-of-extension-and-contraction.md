---
title: "Designing Software for Ease of Extension and Contraction"
layout: post
category: 'veille'
tags: laws codesmithing architecture
lang: french
ref: designing-software-for-ease-of-extension-and-contraction/
doi: 10.1109/TSE.1979.234169
---

👴 Je continue de découvrir l’immense David Parnas, au travers d’un second article, sur la manière de concevoir des logiciels afin qu’ils soient facile à étendre et à réduire selon les impératifs client. Il date de 1979, c’est l’information la plus dingue vu l’actualité du papier.  

## Règles de design 

📜 Parnas donne 4 règles permettant de garder une grande souplesse dans le design des logiciels :  
  
1️⃣ Commencer par un monolithe. Créer un module à chaque décision de design importante afin d’encapsuler cette décision et de rendre facile le changement si elle s’avérait peu judicieuse.  
  
2️⃣ Lister les éléments qui sont susceptibles de changer. S’assurer qu’ils sont absents des interfaces des modules que l’on conçoit.  
  
3️⃣ Ne pas subdiviser son programmes en étapes d’un traitement. Privilégier la conception par « machines virtuelles », où chaque module masque la complexité de la couche inférieure en ne laissant filtrer que ce qui est utile à des tâches plus élevées.  
  
4️⃣ Ne créer de dépendances que si elles sont utiles. Parnas entend par là que :  
1\) A est plus simple parce qu’il utilise B.  
2\) B n’est pas plus complexe si A l’utilise.  
3\) Il existe un programme utile incluant B, mais pas A  
4\) Il n’y a aucun programme utile contenant A, mais pas B.  
  
## Coûts de fonctionnement et de changement

💻 Nous connaissons tous la dynamique qui lie mémoire et CPU, de sorte que toute optimisation de l’un coûte de l’autre.  
Le même type de relation existe entre coût de fonctionnement et coût du changement. Je reviens sur le papier de Parnas posté il y a une semaine, car il révèle des trésors nouveaux à chaque lecture.  
  
📏 Un logiciel générique diffère d’un logiciel flexible. Le premier répond à plusieurs cas d’usage sans changement, alors que le second ne répond qu’à un cas d’usage mais peut être facilement adapté pour en couvrir d’autres.  
  
👉 La généricité a un surcoût de fonctionnement (le logiciel est forcément plus gros), mais un coût de changement nul.  
  
👉 La flexibilité a n’a aucun surcoût de fonctionnement, mais possède un coût de changement dépendant de la qualité de l’implémentation.  
💰 Le choix entre généricité et flexibilité est (normalement) purement stratégique et économique. Ce qu’un logiciel gagne d’un côté il le perd de l’autre. C’est une conséquence probablement indépassable de la VIIIème loi de Lehman : dans ce complexe d’interactions homme-machine, tout est gouverné par des boucles de rétroaction.  

SOURCE  
  
Parnas, David. (1979). Designing Software for Ease of Extension and Contraction. Software Engineering, IEEE Transactions on. SE-5. 128- 138. 10.1109/TSE.1979.234169.