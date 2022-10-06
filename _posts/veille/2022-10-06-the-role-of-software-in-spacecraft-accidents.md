---
title: "The Role of Software In Spacecraft Accidents"
layout: post
category: 'veille'
tags: failures
lang: french
doi: 10.2514/1.11950
ref: the-role-of-software-in-spacecraft-accidents
---

🚀 Connaissez-vous le point commun entre le premier vol d'Ariane 5, Mars Climate Orbiter, Mars Polar Lander, Titan IV B-32 et SOHO ? Ce sont des missions spatiales ratées à cause de problèmes logiciels.

🤑 Dans tous ces cas, le risque associé aux défaillances logicielles a été minimisé ou nié afin de privilégier le respect des délais ou du budget.

💥 Cela a pris des formes multiples, mais récurrentes dans les accidents étudiés :

💣 Une diffusion de la responsabilité et de l'autorité. Les années 90 ont remplacé une culture de la supervision par une culture de l'incitation dans l'air du temps, sans pour autant s'assurer de son efficacité. De plus, en cas de dépassement de budget, le premier poste coupé était la sécurité, jugée redondante.

📧 La diffusion des informations était mauvaise. Les canaux étaient inadaptés à la gravité des informations. Sur SOHO, l'information sur le changement du logiciel des gyroscopes responsables de l'accident avait bien été transmise au pilotage ... noyée dans des dizaines de mails.

🤠 Les spécifications étaient incomplètes, manquantes ou jamais mises à jour au cours du projet. Certaines parties du code étaient héritées de développeurs partis depuis longtemps, pratiquant le Cowbay Programming à haut niveau.

💋 KISS ? Connais pas. Le spatial c'est compliqué, alors quoi de mieux que des fonctionnalités compliquées et souvent inutiles ? Tous les projets accidentés avaient un code source encombré par de telles choses, souvent "au cas où".

⛏️ Des morceaux de code ont simplement été minés dans les dépôts des anciennes missions et réutilisés sans tests, sur du matériel différent. Après tout, ça a fonctionné ! On retrouve ici le même schéma qu'avecle Therac-25, étudié par la même Nancy Leveson.

🤨 Les mauvaises pratiques furent légion, comme la non-séparation de systèmes critiques ou l'affichage de messages d'erreur distincts des informations normales. A ce stade, qui est étonné ?

🧪 Last but not least, le code ne comportait souvent aucun test automatisé. Nous sommes dans les années 90, pour rappel. Les campagnes de relecture du code et de tests manuels étaient effectuées sans trop de moyens ou de sérieux, pour économiser le budget.

🤦 Le rapport entier mérite la lecture, tant les similitudes entre les accidents spatiaux et le quotidien du développeur lambda sont édifiantes. Certaines anecdotes prêteraient à rire si elles n'avaient pas crashé des millions de $ d'argent public.

SOURCE

Leveson, Nancy G.. “Role of Software in Spacecraft Accidents.” Journal of Spacecraft and Rockets 41 (2004): 564-575.