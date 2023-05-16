---
title: "Explicit Namespaces"
layout: post
category: 'veille'
tags: langages naming
lang: french
ref: explicit-namespaces
doi: 10.1007/10722581_8
link: http://ivizlab.sfu.ca/arya/Papers/SW/ExplicitNamespaces.pdf
---

🗣️ La notion d'espace de nom est plus vaste que les "namespace" de C++ ou C#. Les packages de Java, les interfaces ou encore les scopes de Javascript sont des espaces de nom. Un espace de nom, pour étendre la définition, est un mécanisme permettant de retrouver un objet donné à partir d'un nom dans un contexte.

🪨 L'histoire commence avec des espaces de nom inflexibles. Deux globales ont le même nom ? Le programme plante. Vinrent ensuite les espaces de nom fixes, comme en java. Avec un préfixe unique à l'échelle d'Internet, chaque composant est libre d'utiliser les noms qu'il souhaite sans se soucier des autres. Les espaces de nom restreints suivent : c'est Python ou Javascript où chaque fichier possède son espace de nom. La globalisation nécessite un mot clé particulier. Enfin, l'état de l'art actuel utilise les conteneurs d'injection de dépendance afin de résoudre des dépendances nommées quand c'est nécessaire.

📦 Pour les auteurs, toutes ces méthodes doivent être dépassées par des langages incluant une gestion dynamique des espaces de nom : chaque composant s'exécute dans un contexte, incluant un espace de noms sur lequel l'appelant a un total contrôle. Le langage expérimental Piccola est de ceux-ci.

🧑‍🏫 L'inconvénient ? Les espaces de noms dynamiques sont extrêmement peu intuitifs pour nos cerveaux et un énorme effort pédagogique, absent de ce papier, est nécessaire. Un tel paradigme n'est prometteur qu'à mesure qu'il est utilisable par le commun des mortels.

SOURCE

Achermann, Franz and Oscar Nierstrasz. “Explicit Namespaces.” Joint Modular Languages Conference (2000). DOI:10.1007/10722581_8