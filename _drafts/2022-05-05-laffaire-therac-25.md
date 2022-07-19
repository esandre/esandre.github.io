---
id: 908
title: 'L&rsquo;affaire Therac-25'
date: '2022-05-05T12:08:07+02:00'
author: 'Enzo Sandré'
excerpt: 'Entre juin 1985 et janvier 1987, 6 personnes sont mortes irradiées à cause d''un logiciel médical défectueux. C''est l''affaire Therac-25, en tout cas telle qu''elle est résumée sur Internet. Les développeurs ont-ils du sang sur les mains ? C''est un peu court, nous allons le voir.'
layout: post
guid: 'https://blog.enzosandre.fr/?p=908'
permalink: /2022/05/05/laffaire-therac-25/
image: /wp-content/uploads/2022/05/1-gR63wwit_byL27THqpxojg.jpeg
categories:
    - Travaux
---

**Cet article est la compilation d’une série de posts LinkedIn, un nouveau format actuellement à l’essai.**

☢️ Dans les années 70, un premier appareil de radiothérapie, le Therac-20 fut conçu par la Compagnie Générale Radiographique (CGR) française et l’Atomic Energy Commission Limited (AECL) canadienne. Il fut un succès : aucun accident et d’excellents résultats thérapeutiques. Malgré cela, CGR et AECL se séparèrent, la conception du Therac-25, successeur du Therac-20 fut donc exclusivement canadienne.

🗃️ Le Therac-25 consiste en un portage du logiciel du Therac-20, de conception française, donc sans l’aide de ses développeurs d’origine, sur un nouveau matériel. Il s’agit de code assembleur, bien moins portable que nos langages modernes.

🤦 Le Therac-25 devait réduire les coûts et l’encombrement, en fusionnant une machine de radiothérapie et un accélérateur de particules. L’ensemble des contrôles de sécurité, redondants entre le software et le hardware sur le Therac-20, sont désormais confiés uniquement au logiciel. En 1983, il est installé dans 11 hôpitaux, sans aucun test indépendant. Les autorités le voient comme un simple Therac-20 mis à jour.

🤥 Une première vague de défauts a lieu en 1985, dont un fut mortel. Le fabricant, bien que mis au courant par les médecins, a nié avoir eu vent de cas similaires. Les ingénieurs ont systématiquement nié la possibilité même d’un problème alors que les opérateurs hospitaliers étaient habitués aux bugs et caprices de la machine.

🎺 Bien qu’étant incapable de reproduire le problème, car ne soupçonnant pas le logiciel à ce stade, AECL a déployé un « correctif ». Accompagné d’une explication savante, il devait « réduire les chances de défaut d’au moins cinq ordres de grandeur ». Mazette.

☠️ Après un décès, enfin la FDA se réveille ! Le Therac-25 va repasser sur le banc d’essai et cessera d’être une machine de mort ! En fait non. La FDA a émis un rappel de classe II, réservé aux « situations où un matériel défectueux peut dans certains cas provoquer des blessures légères ou réversibles ». Le décès et la nature des blessures ne figurent pas au rapport.

📖 Sans aucun audit logiciel, les autorités ont demandé à AECL de modifier le manuel d’utilisation afin d’augmenter le nombre de contrôles visuels par les opérateurs.

🤑 La cause racine n’ayant pas été identifiée ou corrigée, la machine a continué de semer la mort. AECL resta dans le déni pendant toute l’année 1986, malgré 2 morts et 4 blessés. Après les modifications effectuées, la machine ne pouvait pas être défectueuse !

🩹 Un second patch fut déployé, pour prévenir de prétendues erreurs des opérateurs. Il n’a pas empêché d’autres blessures, parfois mortelles. Le ridicule fut atteint lorsque AECL recommanda de mettre du scotch sous une touche du clavier pour empêcher des saisies invalides.

👌 Il faut attendre 1987 pour que AECL sorte enfin un véritable correctif sous pression des autorités. 4 systèmes critiques ont reçu des protections hardware tirées du Therac-20. Il n’y a plus eu de blessures rapportées ensuite.

🤐 Après 2 ans à semer la mort, le Therac-25 fait enfin l’objet d’une expertise sérieuse en 1987. Les pratiques de développement sont révoltantes sur une matière aussi grave.

💸 Le management a tout fait pour faire passer un nouveau produit pour une simple amélioration du Therac-20, afin d’éviter les audits et les contrôles. Les économies ont été faites en confiant au seul logiciel des opérations critiques. Et quel logiciel !

👉 Ce logiciel fut développé sans aucune politique de tests ! Il fut testé sur simulateur afin d’éliminer les bugs les plus grossiers, c’est tout.

👉 Le code est proprement illisible et ésotérique, même pour les développeurs d’AECL.

👉 L’orgueil des développeurs les a poussés à croire leur logiciel infaillible au point de supprimer tout contrôle matériel.

👉 Des patchs ont été déployés alors même que le bug n’avait pas été identifié.

👉 Des bugs visibles ont été laissés parce que jugés « peu critiques ».

👉 Aucun suivi de la qualité et des incidents n’existait chez AECL.

🤥 A cela il faut ajouter la responsabilité de la direction, qui a nié des incidents, menti, refusé des audits et a même produit des rapports de test bidon, sans qu’aucun test n’ait été réellement effectué. Les autorités sanitaires n’ont pas bronché, minimisant des incidents mortels. A ma connaissance, aucun responsable n’a connu la prison.

⚖️ La morale de cette histoire est simple : tous les procès du Therac-25 se sont réglés en dehors des tribunaux, avec les familles ou les victimes. Tant que la malfaçon logicielle n’aura pas de sévères conséquences pénales, ce genre de pratiques subsistera. Le meilleur entraînement et les meilleures pratiques ne sont rien face à l’appât du gain.

🪦 Le Therac-25 aurait du être notre Verdun : plus jamais ça. On sait depuis que la FDA n’est pas au courant de 99% des incidents survenant dans les hôpitaux. Le nombre de décès pourrait être bien pire.

SOURCE

Leveson, Nancy G. and Clark Savage Turner. “An investigation of the Therac-25 accidents.” Computer 26 (1993): 18-41.