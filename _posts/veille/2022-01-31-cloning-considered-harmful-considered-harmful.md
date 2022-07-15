---
title: "« Cloning Considered Harmful », Considered Harmful"
layout: post
category: 'veille'
tags: codesmithing
lang: french
ref: cloning-considered-harmful-considered-harmful
doi: 10.1007/s10664-008-9076-6
---

🍸 DRY : Don’t Repeat Yourself. Un slogan rabâché aux étudiants du monde entier, souvent comme un dogme. Largement sorti de son sens original (ne pas dupliquer de connaissance), il devient souvent une chasse aux sorcières anti-duplication du code, créant des monstres.

🇨🇦 Deux chercheurs canadiens ont décortiqué ce problème en distinguant plusieurs buts à la duplication, chacun présentant un bilan plus ou moins positif en faveur de la duplication.

🍴 Le forking, où le clone vit indépendamment de sa source, pose très peu de problèmes, tant que les deux codebases sont régulièrement nettoyées et qu’elles n’ont pas d’interactions entre elles.

🗋 Le templating, simple copier-coller d’un snippet pour en reproduire les effets présente deux grands dangers : multiplier les coûts de maintenance et dupliquer un code buggé. Il est déconseillé sauf si les avantages contrebalancent ce choix.

🪄 La customisation est une simple inspiration, avec ou sans copier-coller, d’un code qui sera remanié ensuite pour résoudre le problème. Elle est un bon moyen de gagner du temps à court-terme, mais créé une dette technique qui devra être tracée et résorbée.

🧪 Les auteurs ne parlent pas de duplication dans les tests, qui sont un 4ème cas à ajouter au papier : on sait qu’il vaut mieux un test dupliqué qu’un test obscur, la clarté primant sur tout le reste.

📝 Chacune de ces catégories est subdivisée plus finement, je vous encourage à lire le papier pour avoir une vision plus fine du sujet que LinkedIn ne le permet !

SOURCES

Hunt, Thomas, Pragmatic Programmer, The: From Journeyman to Master. Pearson. 2000.

Kasper, C. and Godfrey, M.W. (2008) Cloning Considered Harmful, Considered Harmful: Pattern of Cloning in Software. Empirical Software Engineering, 13, 645-692 DOI:10.1007/s10664-008-9076-6