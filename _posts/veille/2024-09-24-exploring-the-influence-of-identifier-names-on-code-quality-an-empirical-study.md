---
title: "Exploring the Influence of Identifier Names on Code Quality: An empirical study"
layout: post
category: 'veille'
tags: quality naming
lang: french
ref: exploring-the-influence-of-identifier-names-on-code-quality-an-empirical-study 
doi: 10.1109/CSMR.2010.27
link: https://oro.open.ac.uk/19224/1/butler10csmr.pdf
---

🌥️ Un nommage obscur est fortement corrélé à un code de piètre qualité, au point même de pouvoir estimer la qualité d'un code ainsi en première lecture. C'est la conclusion d'un papier anglais de 2010.

🤖 Un nommage obscur n'est pas difficile à détecter, même par une machine : encodage, identifiants trop courts ou trop longs, abbréviations, casse dissonnante, etc. La plupart des analyseurs statiques ont largement automatisé cela. L'oeil humain vient analyser en dernier lieu quand la machine a dégrossi le travail. L'équipe de chercheurs a procédé ainsi pour caractériser un nommage défaillant dans son travail.

👎 La qualité logicielle est plus difficile à quantifier : les chercheurs ont choisi la très décriée complexité cyclomatique, ainsi qu'un score FindBugs. C'est rapide et facile à obtenir, mais cela affaibit grandement le papier.

⚠️ Enfin il est important de noter que seuls des projets open-source ont été inclus dans les données de l'étude. Les chercheurs avertissent que les résultats (confidentiels) obtenus avec des projets commerciaux semblent ne pas suivre du tout la même tendance. Prudence, donc !

SOURCE

Butler, Simon; Wermelinger, Michel; Yu, Yijun and Sharp, Helen (2010). Exploring the Influence of Identifier Names on Code Quality: An empirical study. In: 14th European Conference on Software Maintenance and Reengineering, 15-18 Mar 2010, Madrid, Spain, pp. 156–165. DOI:10.1109/CSMR.2010.27