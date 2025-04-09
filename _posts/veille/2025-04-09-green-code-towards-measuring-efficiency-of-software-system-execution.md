---
title: "Green code : towards measuring the efficiency of software system execution"
layout: post
category: 'veille'
tags: 
lang: french
ref: green-code-towards-measuring-efficiency-of-software-system-execution
link: https://lutpub.lut.fi/bitstream/handle/10024/164966/Thesis_Ahmed_Rifat_Final_modified.pdf?sequence=3&isAllowed=y
---

🪫 Comment produit-on un logiciel économe en énergie ? Sans surprise, il faut déjà que le besoin en soit exprimé. C'est une exigence non-fonctionnelle et aucun développeur ne s'en préoccupe si ça n'est pas formulé sous forme d'objectifs chiffrés. 

📏 Ensuite, il faut que le développeur puisse mesurer la consommation de son programme. Il faut de l'outillage pour cela, notamment en intégration continue. Hélas le papier reste en surface et ne nous dit pas lesquels.

⚡ Mesurer ne sert à rien si l'on ne peut pas agir. Les développeurs doivent se former à repérer les antipatterns énergétiques au niveau architectural, dans le design ou les structures de données. Certains patterns sont connus pour favoriser les économies d'énergie. Problème : certaines bonnes pratiques logicielles semblent alourdir le bilan energétique des projets, comme l'encapsulation, en tout cas sur certains langages. A l'inverse, le bon usage du multithreading permet souvent des économies importantes. Plus surprenant, la pratique du refactoring semble liée à une meilleure efficacité energétique.

👟 Tous les frameworks, bibliothèques et bases de données ne se valent pas, certains sont des gouffres énergétiques, l'auteur note hélas que ce sont souvent les dépendances les plus performantes qui sont aussi les moins efficientes. Cette tension se retrouve également dans les réglages des compilateurs C/C++ où les optimisations les plus aggressives ne sont pas toujours les plus vertes. Sans surprise, la conteneurisation, voire pire la virtualisation sont des gouffres énergétiques.

SOURCE

Rifat, Ahmed, Green code : towards measuring the efficiency of software system execution. School of Engineering Science, Tietotekniikka. 2022.