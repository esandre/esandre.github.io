---
title: "A View of 20th and 21st Century Software Engineering"
layout: post
category: 'veille'
tags: 
lang: french
ref: a-view-of-20th-and-21st-century-software-engineering
doi: 10.1145/1134285.1134288
---

🧠 Si on analysait l'histoire du développement avec la méthode hégelienne ? Barry Boehm a essayé en 2006 et les leçons qu'il en tire sont intéressantes.

💽 Thése des années 1950 : l'ingénierie du logiciel est similaire à l'ingénierié hardware. L'humain est bien moins cher à l'heure que les ordinateurs, le développeur doit agir en ayant ce principe économique en tête : suroptimisation, vérification pointilleuse des programmes avant leur livraison. Le rapport nécessaire aux sciences, l'absurdité de la gestion de projet séquentielle et la rigueur sont les enseignements de cette période.

🪛 Antithèse des années 1960 : Code and fix (que Boehm appelle, improprement à mon avis "Crafting"). Les développeurs se sont rendus compte que le logiciel est infiniment plus facile à modifier que le matériel. De plus le coût des ordinateurs baisse drastiquement. L'idée d'un code en état de maintenance permanent fait son chemin, précurseure de l'agilité moderne. On commence à parler d'itérations par opposition aux méthodes linéaires.

🧱 Synthèse des années 70 et antithèse : formalisme. Face aux plats de spaghetti souvent hérités de la décennie précédente, mais également afin de ne pas revenir aux processus guindés des années 50, une vague méthodologique a déferlé dans la gestion de projet, donnant Waterfall et dans le design donnant la programmation structurée, le concept de couplage et les balbutiements de la qualité logicielle en général. Hélas, l'esprit Top-Down et réductionniste est venu gâcher la fête en considérant un logiciels comme un ensemble de silos.

♾️ Synthèse des années 80 : scalabilité. C'est l'époque des tests automatisés, de l'orienté objet, de l'architecture, des IDE ... La productivité des développeurs s'accroît d'un facteur 10. C'est la fin des obstacles accidentels à la vélocité des développeurs. Hélas le mouvement est allé trop loin, croyant se passer des développeurs, menant au ratage du WYSIWYG ou au mirage du Model-Based Software Enginering.

♻️ Antithèse des années 90 : recyclage. Les développeurs sont incontournables, mais lents, alors pour accélérer la livraison, il faut réutiliser au maximum. Cela est permis par le développement de l'orienté objet et de l'architecture. Il faut faire générique, trop parfois, quitte à créer d'infects frameworks d'entreprise. C'est aussi l'époque de la défiance envers la planification, jugée comme retardant le time-to-market, seule manière de savoir si le produit colle au besoin. C'est aussi l'âge d'Internet et de l'Open Source.

📝 Je vous laisse découvrir la suite, ainsi que les prédictions de Boehm dans le papier lui-même !

SOURCE

Barry Boehm. 2006. A view of 20th and 21st century software engineering. In Proceedings of the 28th international conference on Software engineering (ICSE '06). Association for Computing Machinery, New York, NY, USA, 12–29. DOI:10.1145/1134285.1134288