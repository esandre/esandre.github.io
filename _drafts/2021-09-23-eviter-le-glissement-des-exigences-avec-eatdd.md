---
title: "Éviter le glissement des exigences avec EATDD"
layout: post
category: 'veille'
tags: testing
lang: french
ref: eviter-le-glissement-des-exigences-avec-eatdd
doi: 
---

Prêt à broyer votre cahier des charges ? Hier, j’ai évoqué Executable Acceptance Test Driven Design comme étant le recueil du besoin de demain. Aujourd’hui je présente mes sources (dont deux méta-études, donc du solide) et je nuance un peu.

A des fins de vulgarisation, je fusionne volontairement les concepts d'(E)ATDD, de STDD et de BDD, les nuances sont assez minimes. Le principe ? Remplacer la spécification documentaire par des tests de haut niveau, élaborés itérativement avec les représentants des utilisateurs.

Commençons par un constat : une spécification fige un besoin qui aura déjà changé pendant l’implémentation. Plus le temps entre la spécification et le déploiement est long, plus grande sera la chute.  
C’est l’essence du papier de Henderson \[1\], écrit en 2010, mais le phénomène est connu au moins depuis Winston Walker Royce dans les années 1970. Le papier fondateur du Waterfall, Managing The Development of Large Software Systems \[2\] voyait d’ailleurs la nouvelle méthode comme un enfant de l’école itérative et incrémentale. C’est dire si le papier a été mal compris.

Écrire des tests plutôt que de la documentation ne change pas ce constat et aucun chercheur ne l’affirme !

L’intérêt des tests est d’accélérer le feedback entre le code et le besoin, en enlevant un intermédiaire, la spécification papier. Ce que le client valide est instantanément exécutable, ce qui présente quatre avantages :  
-Le développeur a déjà un test prêt. Il n’a plus qu’à le passer au vert. Il n’a pas besoin de lire une specification pour écrire son test.  
-Le fonctionnel voit en temps réel l’avancement du développement, chauque test passé servant de milestone \[4\].  
-Le glissement des exigences est mieux pris en compte : il suffit de modifier les tests, directement, sans avoir à rééditer de spécification.  
-La communication est meilleure entre développeurs et fonctionnels. Les tests de haut niveau sont un langage commun. \[5,6\]

Passons aux inconvénients, ils sont les mêmes que pour toute démarche d’agilité.  
-Si vous n’avez pas de représentant des utilisateurs fortement engagés dans l’équipe, la démarche EATDD n’est pas pour vous. \[6\]  
-Si votre code est fortement endetté, il faudra vous armer de patience, vous ne verrez pas les bénéfices avant longtemps.  
-Enfin, si les membres fonctionnels de l’équipe sont incapable de lire et d’exécuter les tests de haut niveau (manque de formation, ou manque de clarté des tests), alors la démarche perd une bonne partie de son intérêt \[5\].

–SOURCES–

\[1\] Henderson, P. (2010). Why Large IT Projects Fail

\[2\] Royce. W. W. (1970). Managing The Development of Large Software Systems

\[3\] Park, Maurer : Communicating Domain Knowledge in Executable Acceptance Test Driven Development

\[4\] Park, Maurer : A litterature review on Story Test Driven Development

\[5\] Nasir : Acceptance Testing in Agile Software Development

\[6\] Weiss, Schill, Richter, Mandl : Littérature review of empirical research studies within the domain of acceptance testing