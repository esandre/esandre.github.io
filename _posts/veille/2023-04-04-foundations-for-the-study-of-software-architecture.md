---
title: "Foundations for the study of software architecture"
layout: post
category: 'veille'
tags: histoire-informatique 
lang: french
ref: foundations-for-the-study-of-software-architecture
doi: 10.1145/141874.141884
---

🏗️ Perry et Wolf n'ont pas à proprement parler inventé l'architecture. L'honneur revient à Schwanke qui, le premier, eut l'idée de connecter des composants pour créer ce niveau supérieur d'abstraction. Cependant, Perry et Wolf ont réellement fondé cette discipline aux côtés de Garlan en Shaw, déjà évoqués ici.

🏛️ Il ont pris pour modèle l'architecture en bâtiment, après avoir éliminé l'idée de prendre l'architecture hardware ou encore réseau, en raison de leurs différences inconciliables avec le logiciels. Peu naïfs, ils furent conscients des problématiques propres au logiciel et n'ont pas niaisement copié le savoir-faire de bâtisseurs de gratte-ciel.

🎨 Alors que le code est plus souple que le béton, chaque nouveau système est par essence sa propre architecture. Il est possible de trouver des traits communs, les styles architecturaux, mais les jeux de contraintes appliqués à chaque système sont trop dépendants du besoin pour être reproduits. Prudents, les auteurs ne s'avancent pas sur le caractère essentiel ou accidentel de cette propriété (contrairement aux partisans de l'ingénierie du logiciel).

🔗 L'architecture logicielle s'inspire mais ne copie pas. Pour Perry et Wolf, nous disposons de 3 éléments simples, les composants qui traitent la donnée, les connecteurs qui relient les composants et la donnée elle-même. Définir une architecture c'est donc créer un jeu de contraintes, définissant quelles catégories de composants peuvent être reliés à quelles autres et dans quelles conditions.

💡 S'arrêter là serait incomplet et ménerait à la dégénérescence ou à l'érosion de l'architecture ainsi conçue au fil des itérations. Il faut également expliciter le raisonnement derrière l'architecture et le diffuser, sinon les designers et développeurs vont à coup sûr rater la cible lors de l'implémentation. Pourtant, combien de maniaques du schéma format A1 font exactement cela en entreprise, se croyant supérieurs aux développeurs ?

SOURCE

Perry, Dewayne E. and Alexander L. Wolf. “Foundations for the study of software architecture.” ACM SIGSOFT Softw. Eng. Notes 17 (1992): 40-52. DOI:10.1145/141874.141884