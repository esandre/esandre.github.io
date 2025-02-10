---
title: "Evaluation of Approaches for Documentation in Continuous Software Development"
layout: post
category: 'veille'
tags: methods testing
lang: french
ref: evaluation-of-approaches-for-documentation-in-continuous-software-development
doi: 10.5220/0011846200003464
link: https://www.researchgate.net/publication/370273634_Evaluation_of_Approaches_for_Documentation_in_Continuous_Software_Development
---

📖 Même un code exemplaire a besoin d'être accompagné d'une documentation. Concevoir c'est faire des choix, qui doivent être consignés quelque part pour être compris dans le futur. A l'heure actuelle, deux approches ont le vent en poupe : "Just enough Upfront" et "Executable Documentation". Elles sont trop récentes pour en évaluer les résultats, mais il est cependant possible de baliser le terrain et de savoir de quoi il en retourne.

🖼️ Just enough up Front utilise des supports de documentation déstructurés en amont du développement : présentations, description d'interfaces, schémas. Le développement démarre dès que suffisamment d'informations sont récoltées, et utilise l'abstraction pour garder le code extrêmement perméable au changement. La documentation *in fine* est le code lui-même, ainsi que les messages de commits.

🧪 Executable Documentation utilise massivement les méthodes de recueil du besoin piloté par les tests, les spécifications et exigences exécutables tout au long du cycle de vie du logiciel. Le *reverse engineering* est une méthode d'extraction de la connaissance adaptée avec une telle couverture du code.

🧭 Tandis que Just enough up Front est déjà bien installé en entreprise, Executable Documentation souffre de l'obsession mondiale pour les tests unitaires, incapables de supporter cette méthode. C'est dommage car les deux méthodes se complètent bien. L'une permet de savoir où l'on va, l'autre de ne pas oublier ce que l'on voulait accomplir.

📍 Git est le lieu parfait pour documenter du code dans le cadre de ces deux démarches, notent les chercheurs. Les messages de commits sont sous-cotés.

SOURCE

Theunissen, Theo & Hoppenbrouwers, Stijn & Overbeek, Sietse. (2023). Evaluation of Approaches for Documentation in Continuous Software Development. 404-411. DOI:10.5220/0011846200003464.