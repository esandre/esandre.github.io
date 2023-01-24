---
title: "Managing the development of large software systems"
layout: post
category: 'veille'
tags: histoire-informatique methods
lang: french
ref: managing-the-development-of-large-software-systems
link: http://www.cs.umd.edu/class/spring2003/cmsc838p/Process/waterfall.pdf
---

🤖 A l'origine de la méthode Waterfall et de ses descendants, dont le célèbre cycle en V, on trouve un homme : Winston Walker Royce. Peu après la conférence de Garmisch-Partenkirchen de 1968, il produisit une méthode révolutionnaire afin "d'utiliser au mieux les ressources en programmeurs". Le vocabulaire annonce la couleur : le développeur doit se tayloriser.

🔃 Son idée repose sur l'ajout d'étapes précédant la boucle analyse/programmation, qui suffit aux petits projets. Il s'agit des phases de spécification, analyse, architecture et autres analyses plus ou moins détaillées. Rendons cependant justice à Royce, qui avait bien compris que les étapes de programmation et de tests allaient lever de nombreux problèmes, nécessitant de remonter de nombreuses étapes en arrière dans les phases de spécification. Son erreur a été de sous-estimer la fréquence de ces retours : il pensait que la majorité des problèmes seraient détectés dans l'étape suivant immédiatement celle qui les a causés.

💣 La seconde erreur de Royce est de croire en la linéarité de la relation entre la taille d'un problème et l'importance des changement qu'il occasionnera. Tout son argumentaire repose sur ce mythe : si un problème est petit, il n'occasionnera que de petits changements et la majorité du travail réalisé avant sa détection sera conservé. Il est donc rentable de tout spécifier par raffinements successifs jusqu'à rendre la tâche du programmeur triviale. Avec le recul, nous savons qu'un petit problème d'implémentation peut invalider des centaines d'heures de conception sur plusieurs étapes.

📚 La troisième erreur de Royce est de croire que la documentation remplace la collaboration. Il prône une médiation universelle des différents métiers à l'oeuvre sur un logiciel par le document papier. Il y voit deux avantages : trouver les responsables des erreurs et spécialiser les tâches. Si un acteur rédige une documentation en amont, il est possible de diviser le travail en aval grâce à une photocopieuse. Chacun a son exemplaire de documentation, son silo et ses tâches spécialisées à effectuer. Il illustre en évoquant les tests "réalisables par des acteurs moins coûteux que les programmeurs". De plus, vu que chacun est forcé de décrire son avancement sur une documentation, il est facile de remonter à la source, donc de blâmer.

🧠 Il est difficile de jeter la pierre à Royce, car les études venues invalider ses préjugés n'étaient pas sorties. Il aurait cependant pu faire preuve de plus de prudence avant d'appliquer au développement de logiciels tous les lieux communs de son époque. Le leçon, pour nous, est justement là. Appliquons-nous benoîtement la dernière méthode dans l'air du temps, ou bien avons-nous des preuves empiriques ?

SOURCE

Royce, Winston. “Managing the development of large software systems: concepts and techniques.” International Conference on Software Engineering (1987).