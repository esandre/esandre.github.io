---
title: "Chiffrer en Artisan : Le forfait agile"
layout: post
category: 'blog'
tags: developpement artisanat 
lang: french
ref: chiffrer-en-artisan-forfait-agile
image: /resources/images/content/forfait-agile.png
---

Travailler en indépendant sans céder aux sirènes du pseudo-salariat des contrats en régie est compliqué. La principale barrière est financière. Les logiciels sont des produits complexes, qu’il est impossible de chiffrer avec exactitude. En régie, le risque de bugs ou de dépassement du temps est assumé par le client. Le développeur est payé comme un journalier, avec obligation de moyens, non de résultat. Certains clients ne veulent pas assumer ce risque. Certains développeurs ne veulent pas être ainsi déresponsabilisés. Je vais détailler ma méthode de chiffrage permettant d’intégrer le risque des logiciels dans le prix, afin d’être rentable en forfait.

*⚠️ Cet article est une démarche pédagogique, non une démarche de transparence. La méthode de calcul présentée est authentique. Cependant, je ne souhaite pas dévoiler mon TJM ou les taux que je pratique pour compenser le risque. Si vous voulez un prix, demandez-moi un devis.
Si vous ne vous intéressez qu’à la méthode de calcul, sans justification théorique, allez directement à la partie 2 : Compenser les risques.*

## Les risques du métier

Les développeurs sont nuls en estimation. Ce n’est pas un accident, mais bien l’essence même de notre profession qui l’explique.

Les estimations logicielles ont une capacité prédictive inversement proportionnelle à la complexité du logiciel réalisé. Vous avez bien lu : du logiciel. La fonctionnalité à implémenter n’est pas le seul facteur de complexité, il faut également compter dans la complexité l’ensemble de l’existant. Autrement dit, **plus votre logiciel a du vécu, plus il est compliqué d’estimer le temps que prendra l’ajout d’une fonctionnalité nouvelle**, a fortiori complexe.

A cela il faut ajouter le vieillissement du logiciel, décrit par [Parnas](https://ieeexplore.ieee.org/document/296790), [Lehman]({% link _posts/blog/2021-08-16-le-monde-a-t-il-oublie-manny-lehman.md %}) et [Henderson]({% link _posts/veille/2022-08-04-why-large-it-projects-fail-requirements-drift.md %}). Pendant qu’il est développé, votre logiciel se dégrade de deux manières : 
- Parce que, n’étant pas un demi-dieu, vous développez de manière imparfaite.
- Parce que le monde bouge autour de votre logiciel. Plus le développement dure, plus il faut inclure à celui-ci des phases de mise à jour des dépendances ou d’adaptations diverses à un monde qui bouge. Tout cela prend du temps.
- Parce que le besoin à l’origine de la spécification que vous implémentez change certes imperceptiblement chaque jour, mais cela représente un décalage énorme au bout de quelques mois.

Les facteurs humains ne sont pas non plus à négliger comme le rappelle [Fred Brooks](https://archive.org/details/mythicalmanmonth00broo) : votre travail n’est pas réductible à une somme de jours/homme, encore moins en équipe. Certaines heures seront plus productives que d’autres, par exemple. Plus vous serez nombreux dans l’équipe, plus la variabilité de la productivité sera grande.

**Pour ces raisons (et bien d’autres), il est impossible d’estimer précisément le temps d’implémentation d’une fonctionnalité non-triviale sur un logiciel non-trivial. C’est une loi empirique du logiciel. Toute action basée sur une estimation représente une prise de risque.**

### Qui est responsable ?

S’il est impossible d’avoir des prédictions fiables sur le coût d’un développement, contractualiser est une gageure. Quelqu’un doit accepter le risque et payer éventuellement les dépassements. Pour un salarié, c’est facile : il n’a qu’une obligation de moyens, l’employeur paie son salaire. Un freelance en régie est dans la même position : il est payé à la journée, pas à la tâche. Seules d’éventuelles pressions psychologiques peuvent venir perturber l’équation, mais ça n’est pas le sujet de cet article.

La régie n’est pas toujours souhaitable cependant. Certains clients font appel à un indépendant afin d’externaliser un développement dont ils ne souhaitent pas s’occuper. Ils veulent du clé-en-main. 

L’inverse de la régie est le forfait. Le développeur donne un prix et une envergure. Il assume l’intégralité du risque de dépassement à ses frais et prend une marge en échange. Ce risque, nous l’avons vu n’est pas négligeable pour des projets simples et courts. Il est suffisamment important pour que **le développement de projets complexes ou longs soit assimilable à un processus chaotique**. Un forfait simple ne peut pas convenir pour autre chose que les petits projets triviaux sur lesquels il s’applique déjà (sites vitrine, moulinettes de données, etc.). Le risque, donc la marge prise, seraient trop importants, ne justifiant pas le service rendu par le logiciel.

La seule possibilité pour les projets complexes est le [développement itératif et incrémental (IID)]({% link _posts/veille/2021-11-22-iterative-and-incremental-development-a-brief-history.md %}). C’est une autre loi empirique du développement, appliquée avec succès par des équipes salariées et vérifiée par la recherche académique. Il réduit l’incertitude de l’estimation en la bornant volontairement à une plage de temps courte.

### Il n’y a que deux manières de faire des logiciels

{% include helper_image.html src="/resources/images/content/project-diamond.png" size=6 float="start" caption="Un projet possède 4 variables et ne peut pas en bloquer plus de 3. Un projet logiciel en bloque 2 par sa nature même." %}

Que l’on soit en régie ou au forfait, il ne faut pas perdre de vue qu’il n’existe que deux manières de produire des logiciels fiables : donner un délai fixe, mais accepter une livraison incomplète ou donner une liste ferme de fonctionnalités, mais accepter un délai incertain.

Nous savons depuis plusieurs décennies que la qualité logicielle est un primat, sauf dans de rares cas (prototypes ou dette technique bien comprise). Ne pas viser l’excellence n’a aucun sens tant la vélocité à moyen et long terme des développeurs est abaissée.

Nous savons également qu’il est inutile d’ajouter des moyens à un projet démarré : c’est la [Loi de Brooks](https://fr.wikipedia.org/wiki/Loi_de_Brooks). Le développement est une œuvre intellectuelle. Modifier l’équipe en charge d’un logiciel va ralentir à court et moyen terme la production de manière brutale.

Il ne reste que deux variables libres dans les projets logiciels. **Bloquez-en une, vous savez laquelle restera pour encaisser l’incertitude du projet.**

## Compenser les risques

Depuis la Babylone antique, les hommes ont adopté un outil simple pour compenser les risques financiers dans le temps : les taux d’intérêt. Je ne compte pas réinventer la roue, car le concept est connu de tous.

### Le forfait simple

Pour calculer des intérêts, il faut une somme, une durée et un taux périodique.

Pour obtenir la somme, il faut réaliser une estimation. Il s’agit d’une durée en jours ouvrés, correspondant au temps que vous pensez dépenser pour réaliser les fonctionnalités demandées. Cet article ne traite pas d’estimations, aussi je ne donnerai pas de méthode. Adoptez celle que vous souhaitez. La nature même des estimations logicielles fait que vous allez vous tromper. Ça n’est pas grave, la suite de cet article vous expliquera comment vous tromper de moins en moins à chaque projet. Si vous débutez, acceptez de perdre du temps et de l’argent à cause de vos premières estimations. Cela fait partie du jeu.

La durée est le nombre de jours **calendaires** entre le début du projet et la livraison. Elle peut être très supérieure au nombre de jours ouvrés dans le cas de projets en pointillés ou à temps partiel. Cela est justifié par le vieillissement du logiciel de Parnas et par le glissement des exigences d’Henderson : plus le temps passe, **que le logiciel soit en production ou non**, plus il faut déployer d’efforts pour le garder satisfaisant.

Le taux, quant à lui, représente le risque projet. C’est un taux journalier appliqué à la durée susmentionnée. Le calcul de ce taux est purement empirique : la valeur doit être assez haute pour vous permettre d’être rentable, mais assez basse pour ne pas rebuter les clients. J’ai mon taux de base, qui n’est pas celui de l’illustration et que je ne souhaite pas communiquer.

Vous noterez que ce mécanisme dissuade très vite les clients de rester en forfait simple au-delà d’une certaine complexité.

{% include helper_image.html src="/resources/images/content/chiffrage-forfait.png" size=11 %}

Les intérêts sont composés. On obtient le total après intérêts en appliquant la formule [décrite par Wikipédia](https://fr.wikipedia.org/wiki/Int%C3%A9r%C3%AAts_compos%C3%A9s).

L’argent gagné avec les intérêts vous assure contre le risque de travailler plus qu’estimé, et donc facturé. Je pars du principe que votre client ne vous impose pas de pénalités de retard en cas de non-respect de la date de livraison.

### Le forfait agile

Comment gérer des projets de plus grande envergure en artisan ? En les découpant en itérations. **La réponse est universelle dans notre métier.**

Le forfait agile a pour but de masquer la majorité de la complexité de l’agilité. **Il s’adresse à des clients qui veulent externaliser un développement trop gros pour un forfait classique et qui sont prêts à payer un léger surcoût pour ne pas avoir à mettre les mains dans la gestion de ce projet.** Il est un compromis entre l’embauche d’une équipe de développement et un forfait simple dont le prix serait prohibitif pour un gros projet.

Le forfait agile démarre comme un forfait classique : le client et le développeur s’accordent sur le contenu d’une livraison. Le développeur précise au client qu’il s’agit d’une première version qui sera augmentée ensuite. L’itération est chiffrée exactement de la même manière qu’un forfait classique. Le système d’intérêts composés dissuade naturellement le client d’opter pour des livraisons trop espacées.

Contrairement à un forfait classique, le client priorise les fonctionnalités qu’il souhaite. Une fois la date de livraison arrivée, le développeur présente au client le travail effectué. Celui-ci peut accepter la livraison ou bien demander au développeur de terminer l’itération à ses frais, sans cependant pouvoir lui imposer un délai. Ce mécanisme permet de reporter la responsabilité du calcul de la vélocité sur le développeur et de l’épargner au client. Le développeur est ainsi incité à être prudent dans la gestion de ses itérations s’il ne veut pas travailler pour rien.

{% include helper_image.html src="/resources/images/content/forfait-agile-2.png" size=11 %}

Les itérations sont facturées avec les mêmes règles qu’un forfait classique. Ce seul fait représente déjà une économie substantielle par rapport à un forfait monolithique.

### Déterminer les taux

Le développeur peut agir sur ce système par le biais de deux variables : l’estimation en elle-même et le taux d’intérêt à appliquer.

L’estimation requiert une expérience de pensée : imaginons que rien ne change au cours du projet, ni les spécifications, ni les langages ou les dépendances. Combien demanderiez-vous ? Il n’y a pas de réponse universelle à cette question. Vous pouvez calculer le temps que vous pensez y passer et appliquer un TJM. Vous pouvez aussi réfléchir à la somme que votre client est prêt à dépenser ou même à l’argent que doit rapporter votre logiciel. Chacun a sa méthode pour estimer. **La seule règle est d’ignorer le changement, afin de ne pas appliquer une double peine au client.**

Le taux, lui, vient compenser les incertitudes liées au temps. Rappelez-vous, le monde change autour de votre logiciel. Plus un logiciel est complexe, plus il a de prise au réel. Pensez à un avion, dont la traînée augmente avec la taille et le nombre d’excroissances germant de son fuselage. Il s’agit du premier critère : adaptez votre taux au logiciel sur lequel vous intervenez.

Le deuxième critère est le client. Si vous savez qu’il sera injoignable, indécis ou posera des difficultés, augmentez votre taux. Le taux est un excellent incitatif : expliquez à votre client qu’en restant joignable, il baissera le prix et il aura un logiciel plus satisfaisant, vous le motiverez bien plus qu’avec la seule pédagogie.

Le dernier critère est la présence de pénalités de retard en cas de mauvaise estimation. Cette pratique tend à disparaître, mais si vous en êtes victime, utilisez votre taux pour contrebalancer.

### Réévaluer les taux

Notez minutieusement le temps travaillé sur chaque projet et comparez-le avec vos estimations. Calculez périodiquement trois indicateurs :
- La différence entre les jours estimés (JE) et les jours travaillés (JT) multipliée par votre TJM donne les pertes dues au risque.
- La moyenne du taux de dépassement de chaque projet. Le taux de dépassement se calcule comme suit : (JT – JE) / JT.
- La somme des intérêts perçus sur l’ensemble des projets, moins les éventuelles pénalités de retard donne les recettes sur le risque.

La moyenne du taux de dépassement vous indique votre tendance à sous-estimer ou à surestimer vos projets. La solution est de mieux travailler vos estimations pour comprendre là où vous avez tendance à mal estimer le temps passé. Commencez par améliorer ce point, le paragraphe suivant ne vous sera pas utile à ce stade.

En soustrayant les pertes dues au risque aux recettes dues au risque, vous obtenez une information importante sur votre taux. Si vous avez perdu de l’argent sur le risque, **tout en ayant réalisé des estimations justes**, vous sous-évaluez votre taux sur au moins quelques projets. Si, à l’inverse, vous avez réalisé de gros bénéfices, cela signifie que vous pouvez vous permettre une réduction des taux d’au moins certains clients, ce qui peut d’ailleurs être un excellent argument de fidélisation.

### La maintenance des projets

Ce modèle ne serait pas complet si je n’évoquais pas la maintenance des projets.

Après chaque livraison, à moins qu’une autre ne commence dans un avenir proche, proposez un contrat de maintenance périodique. Plus le temps s’écoule entre 2 maintenances, plus le risque augmente, les taux le reflètent naturellement.

{% include helper_image.html src="/resources/images/content/forfait-agile-3.png" size=11 %}

Si l’itération suivante doit commencer dans un avenir proche, j’ai tendance à ne pas compter la maintenance du tout.

En cas de retard de maintenance, la même logique s’applique. Bien entendu, j’avertis régulièrement le client du danger de sa situation. Imaginons qu’un client revienne 2 ans plus tard avec un projet qu’il veut faire évoluer : la note peut être salée.

{% include helper_image.html src="/resources/images/content/forfait-agile-4.png" size=11 %}

### La reprise de projets

Le cas le plus épineux est incontestablement la reprise de projets développés par autrui. Ce modèle n’est pas prévu pour y faire face, bien qu’il s’agisse d’une part non-négligeable du marché actuel.

Après une première lecture du code, il m’arrive de refuser de reprendre. Lorsque j’hésite, il m’arrive de conditionner la reprise du projet à une régie transitoire. Le client paie à la journée le temps que d’arriver à déterminer un taux empiriquement, à partir de l’écart-type de ma vélocité sur plusieurs itérations du projet. Cette période me permet également de vérifier si le projet n’est pas tout simplement surendetté et déjà mort. Il serait alors malhonnête d’accepter de le reprendre, mieux vaut annoncer son décès et proposer au client d’anticiper son remplacement.

**Le but est de revenir à une situation « normale », avec des estimations et un taux d’intérêt**, même si la réalité peut être parfois très cruelle.

{% include helper_image.html src="/resources/images/content/forfait-agile-5.png" size=11 %}

Sur ce genre de projets, je recommande une grande pédagogie concernant les taux. Expliquez au client qu’ils sont élevés car le projet que vous avez accepté de reprendre est en mauvaise posture. Expliquez-lui que le taux n’est pas une fatalité, mais un indicateur de l’état du projet à votre arrivée. Enfin, informez-le qu’il est possible de diminuer ce taux en investissant du temps à nettoyer le projet.

{% include helper_image.html src="/resources/images/content/forfait-agile-6.png" size=11 %}

Notez que les sessions de pur refactoring ont un taux de zéro, afin d’inciter le client à y recourir. Les clients ne sont en général pas à l’aise avec l’idée qu’un développeur travaille pour ne rien livrer. Ce second incitatif n’est donc pas de trop pour les motiver.

## Conclusion

Ce long article présente mes deux bottes secrètes pour rester rentable malgré le refus total de toute forme de régie à temps plein. 

Les risques que je prends à la place de mes clients sont chiffrés et réajustés périodiquement, indépendamment de mon TJM. La clé est de ne pas mélanger les chiffres : le but d’un TJM est de payer le salaire et les charges de l’artisan, son évolution reflète le niveau d’expérience du praticien. Le but de l’estimation et de lier la valeur produite et le temps passé. Il faut un outil à part pour encaisser le risque inhérent au logiciel : les taux d’intérêt. Leur nom n’est pas vendeur, mais je n’ai pas trouvé mieux, tant le concept est familier à tout le monde. Qui n’a pas un crédit sur sa voiture ou sa maison ?

Le forfait agile permet de viser de plus gros projets que les basiques sites vitrine et autres moulinettes, de faible valeur ajoutée et dont le marché est saturé de développeurs à bas coût. Cet article n’a rien de scientifique : il s’agit de ma manière de procéder, peut-être est-elle applicable à d’autres, peut-être pas.

Ces deux méthodes ne sont pas une formule magique pour faire de l’argent. Ce sont des outils incitant le client et le développeur à avoir une attitude mutuellement profitable à propos de leur logiciel. Enfin, je rappelle que tout ce qui a été décrit ici n’existe qu’**adossé à une clause contractuelle garantissant au client la résolution à vos frais des bugs sur une certaine période**. Sans elle, vous serez tenté de prendre des raccourcis douteux pour augmenter vos marges.