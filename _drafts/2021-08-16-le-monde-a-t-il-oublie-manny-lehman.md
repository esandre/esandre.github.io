---
id: 495
title: 'Le monde a-t-il oublié Manny Lehman ?'
date: '2021-08-16T12:56:21+02:00'
author: 'Enzo Sandré'
excerpt: 'Émises par Meir "Manny" Lehman, comme une tentative pour donner à la science du logiciel des assises théoriques solides, les 8 lois de Lehman ont été oubliées. Les générations de chercheurs qui les ont étudiées ne les ont pas invalidées, bien au contraire ! Il serait donc temps d''adopter ces lois, selon le vieux principe scientifique qui veut que toute hypothèse réfutable restée solide face aux tentatives de réfutation est temporairement une connaissance fiable.'
layout: post
guid: 'https://blog.enzosandre.fr/?p=495'
permalink: /2021/08/16/le-monde-a-t-il-oublie-manny-lehman/
image: /wp-content/uploads/2021/08/Meir_Manny_Lehman.jpg
categories:
    - Travaux
tags:
    - Informatique
---

*EDIT 19/08/2021 : mise à jour du texte de la 3ème loi, trop obscur. Ajout de références.*

Les lois de Lehman ont été émises tout au long du dernier quart du XXème siècle. Elles sont passées de trois au milieu des années 70 à huit en 1998. Les trois premières sont tirées d’une analyse des données de gestion de projet d’IBM en 1968. Les suivantes ont été ajoutées au fil du temps et des discussions de Lehman avec d’autres chercheurs.

Toutes décrivent les lois empiriques que suivent les développements de programmes de Type-E. Ces lois restent valides même si les développeurs les ignorent ou luttent contre (d’où le vocable de lois).

Les logiciels de Type-E sont les logiciels réalisés pour répondre à un besoin métier complexe dans le monde réel, par opposition aux programmes de type P et S.

## Les lois de Lehman

### I – Changement continu

*Un programme en cours d’utilisation doit être continuellement adapté où il deviendra de moins en moins satisfaisant.*

La première loi est simple et instinctivement connue des développeurs et du management. Le monde évolue autour du logiciel, le logiciel doit évoluer en permanence pour répondre aux exigences d’un monde qui change.

Un logiciel doit être maintenu dans le temps pour durer, par des actions de maintenance régulières et adaptées.

### II – Complexité croissante

*La complexité d’un programme augmente à chaque modification, tant qu’aucune action n’est entreprise pour réduire celle-ci.*

Cette seconde loi est tout aussi connue des développeurs. Elle est en revanche ignorée ou niée par les managers. De surcroît, les développeurs sont souvent bien incapables de l’expliquer à leurs décideurs, ils ne la connaissent que d’instinct.

<figure class="wp-block-image">![](https://www.commitstrip.com/wp-content/uploads/2021/06/Strip-Refractoring-du-code-650-final.jpg)</figure>Le drame est le lien entre complexité du logiciel et vélocité. Les équipes s’embourbent dans la gestion d’une complexité accidentelle évitable et ne parviennent plus à sortir de features. La pression du management s’accentue et la pire réponse est apportée presque à chaque fois : réduire le rythme du refactoring pour « gagner du temps ». Le schéma est ensuite toujours le même : surendettement, démotivation, turnover, retards, etc.

### III – Auto-régulation

*L’évolution d’un logiciel est un processus autorégulé. Les mesures des attributs des process et du produit suivent une distribution normale.*

Cette loi est la plus barbare de la série et ses nombreux changements de nom et de définition semblent indiquer que Manny Lehman lui-même a du mal à expliquer cette loi au public.

- 1978 : Loi de la croissance statistiquement régulière / *Law of Statistically Smooth Growth*
- 1980 : La loi fondamentale de l’évolution des grands programmes / *The Fundamental Law of Large-Program Evolution*
- 1998 : Auto-régulation / *Self-Regulation*

Cette loi décrit l’inertie des projets logiciels, inertie d’autant plus grande qu’ils impliquent un grand nombre d’acteurs. Pour Manny Lehman, plus un projet logiciel avance, moins les parties-prenantes ont de prise sur sur sa progression. Il exprime en 1980 la troisième loi sous cette forme :

**L’avenir d’un projet logiciel dépend plus de son passé que des choix présents.**

La loi a été remaniée par l’auteur en 1998, suite à l’ajout de la huitième loi. L’ancienne version de la troisième loi devient un lemme, qui facilite la compréhension de la nouvelle version.

<figure class="wp-block-image">![Curling Canada | Streifel ajoute une autre victoire à son ...](https://s2.qwant.com/thumbr/700x0/4/b/68b47ee05ef96652d56c72a0453fe5c4810423e6eebc7ba4aaa3b2778747fb/WJ-2017-Women-Day-2-Streifel-slide-left-FI.jpg?u=https%3A%2F%2Fwww.curling.ca%2Fwp-content%2Fblogs.dir%2F58%2Ffiles%2F2017%2F02%2FWJ-2017-Women-Day-2-Streifel-slide-left-FI.jpg&q=0&b=1&p=0&a=0)</figure>Un projet logiciel ressemble à une partie de curling. Le lancer initial détermine la majorité des facteurs qui feront la réussite ou l’échec d’un projet. Les balayeurs ont un rôle important, mais plus minime que le lanceur sur la direction et la longévité du projet. Si le lanceur a projeté la pierre vers les tribunes, aucun effort des balayeurs n’ira la remettre sur le chemin de la cible.

Autrement dit, après le lancer, les balayeurs ne peuvent plus choisir arbitrairement où ira la pierre. Leur rôle se bornera à une influence discrète sur la direction de celle-ci. C’est déjà beaucoup. Quelques centimètres séparent le centre de la cible, la réussite, d’une performance médiocre, le retard.

C’est cela que Lehman exprime par sa loi. Une fois le projet « sur les rails », les aiguillages sont rares. Aucune autorité ne peut décréter que la valeur de tel ou tel indicateur sera arbitrairement doublée ou triplée. Tout au plus l’équipe pourra influer sur certains indicateurs par petits incréments. <span style="text-decoration: underline;">Au prix, huitième loi oblige, d’une réaction inverse de d’autres indicateurs.</span>

<figure class="wp-block-image">![Wrapped normal distribution - Wikiwand](https://s1.qwant.com/thumbr/0x380/9/1/5df832875e692f325db451f4eca861ca217993cf600267b705351c177c7459/WrappedNormalPDF.png?u=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F6%2F69%2FWrappedNormalPDF.png&q=0&b=1&p=0&a=0)</figure>A un instant T, l’ensemble des indicateurs du projet suit toujours une distribution normale. La seule variable à portée de l’équipe et du management est σ. Faut-il laisser le projet suivre son cours, ou tenter de corriger un jeu de variables, au prix d’une réaction symétrique d’autres variables ?

Je prends un exemple : le management peut décider que le projet ne va pas assez vite et mettre la pression sur les développeurs. La variable « vitesse » va augmenter, au prix d’une baisse d’autres variables comme la qualité ou la vélocité à long terme. La distribution normale des variables reste respectée.

### IV – Conservation de la stabilité organisationnelle (taux de travail invariant)

*Le taux d’activité efficace global moyen sur un système en évolution est invariable dans le temps.*

Lehman décrit la Loi n°4 comme étant la plus contre-intuitive. Il énonce tout simplement que le management n’a aucune prise sur la vitesse d’évolution du logiciel ! Trop de boucles de rétroaction sont en jeu, macro (marché du travail, concurrence, etc.) et micro (Loi de Brooks, motivation, etc.) pour permettre le moindre changement à court ou moyen terme.

Prenons un exemple : votre projet est en retard et vous souhaitez ajouter un développeur. Sa rémunération sera prise sur autre chose (refacto, endettement, réserves). De plus, la loi de Brooks vous annonce que toute l’équipe va être handicapée par l’arrivée du nouveau pendant un bon moment. Une nouvelle personne ajoute un risque humain (conflits, mésentente, etc.). Si d’aventure l’intégration se passe bien et que le nouveau ajoute suffisamment de vélocité à l’équipe pour éponger le retard originel, celui dû à son intégration et justifier sa rémunération, ça ne sera statistiquement pas le cas chez dans l’équipe voisine ou au recrutement suivant.

Le **corollaire de la 4ème loi** est que le seul levier possible pour augmenter significativement la productivité d’une équipe est d’**adopter des pratiques plus efficaces**, donc d’éviter le plus de gâchis logiciel possible. Les extreme programmers ne sont pas des héros, juste des économes.

### V – Conservation de la familiarité

*Au cours de la vie active d’un logiciel, le contenu des livraisons successives est statistiquement invariant.*

A cause de boucles de rétroaction omniprésentes dans le développement, la quantité de valeur dans une livraison restera statistiquement la même au cours du temps.

Cette loi impitoyable ne laisse que deux leviers aux managers pour influencer le contenu des livraisons afin de coller au mieux au marché ou au besoin : la priorisation et la dette technique.

Cette loi est cruelle : tout manager qui met la pression sur ses développeurs pour livrer plus et plus vite se condamne inévitablement à réduire la valeur des livraisons lointaines. Jusqu’à rendre cette valeur négative lorsque plus de bugs sont livrés que de features, conduisant à un effondrement de la confiance des utilisateurs.

### VI – Croissance continue

*Le contenu fonctionnel d’un logiciel doit croître sans cesse pour maintenir la satisfaction des utilisateurs stable.*

Cette loi ressemble beaucoup à la première, sans lui être identique (même si les deux phénomènes sont liés). Quand un nouveau logiciel est développé, il répond d’abord aux besoins les plus évidents et pressants de ses utilisateurs, qui ne seront alors plus bloqués par une absence de solution. Ces utilisateurs seront alors bloqués par de nouveau problèmes, au fur et à mesure que les précédents seront adressés. La frustration sera sans cesse reportée sur l’attente de nouvelles features ou l’amélioration de l’existant. Si la croissance d’un logiciel vient à cesser, cette frustration n’a plus d’exutoire et la satisfaction des utilisateurs vient à diminuer.

Ce phénomène n’a pas de fin, car les utilisateurs ont tendance à pousser toujours plus loin l’intégration de leurs process dans le logiciel.

### VII – Déclin de la qualité

*Tout logiciel sera perçu comme en déclin de qualité s’il n’est pas rigoureusement maintenu et adapté à un environnement opérationnel changeant.*

Encore une loi ressemblant à la première, lui étant reliée, mais fondamentalement différente dans son objet. La 7ème loi est la conséquence du Principe d’Incertitude : *le résultat de l’exécution d’un programme dans le monde réel est intrinsèquement incertain et les domaines précis de cette incertitude ne sont pas non plus prédictibles.*

« Le monde change par glissement, de manière inéluctable mais prévisible » est la prémisse de la première loi.

« Le monde change aussi par ruptures, imprévisibles dans leur intensité et leur fréquence » est la prémisse de la septième loi.

Sa conséquence directe est la nécessité de garder le logiciel en permanence dans un état d’ouverture au changement maximal. Tout doit pouvoir être remis en cause du jour au lendemain si la satisfaction de l’utilisateur l’exige.

Statistiquement, le pire arrivera un jour. Et il faudra s’y adapter.

### VIII – Système rétroactif

*Les processus de développement des logiciels sont constitués de boucles de rétroaction récursives sur de multiples niveaux. Ils doivent être traités comme tel pour être modifiés ou améliorés avec succès.*

Cette loi peut être vulgarisée en présentant une équipe de développement comme un organisme vivant complexe. Appliquez-lui un changement, elle fera tout pour retrouver son état initial. Augmentez le rythme des livraisons, elles s’amaigriront. Pressez la cadence, la dette viendra engluer l’équipe sur le long terme. Recrutez un nouveau, les relations humaines entre les membres deviendront plus confuses et moins efficaces.

Cette loi avertit les managers tentés par le néo-taylorisme logiciel : les développeurs ne sont pas de ouvriers à la chaîne. On ne peut pas augmenter facilement la productivité d’une équipe. Toutes les solutions simples sont vouées à l’échec, même s’il n’arrive que plus tard. Tout changement doit avoir comme présupposé l’équipe actuelle et le changement doit venir d’elle.

Le logiciel n’obéit pas aux règles classiques de la gestion de projets industriels. La qualité logicielle est une discipline à part, complètement distincte, qui, c’est mon avis, ne peut être pratiquée que par des praticiens en développement correctement formés et expérimentés.

## Limites et controverses

Dès leur sortie dans les années 1970, les lois de Lehman ont provoqué deux types de controverses : celles sur le terme de lois et celles sur le contenu de celles-ci. Les débats ont été vifs jusqu’à l’aube des années 2000, avant qu’elles ne tombent dans l’oubli.

Les détracteurs de Lehman ont-ils réfuté les lois ? En 2013, 4 chercheurs ont réalisé une revue systématique à ce propos.

<div class="wp-block-image"><figure class="aligncenter is-resized">![Evidence pyramid](https://h5p.org/sites/default/files/h5p/content/577351/images/image-5d56c8e206200.png)</figure></div>**Le consensus actuel semble valider totalement les lois de Lehman pour les logiciels commerciaux. Cependant, la plupart des lois sont réfutées pour le développement Open-Source, qui semble suivre sa propre logique.**

Les lois de Lehman font partie de ce que la recherche en qualité logicielle a de plus solide à l’heure actuelle pour décrire et bâtir des équipes et process solides. **C’est un fait scientifique solide en l’attente de nouvelles preuves.**

Le terme de « Lois » utilisé par Lehman a créé son lot de controverses, auxquelles l’auteur lui-même a répondu dans son article de 1996, Laws of Software Evolution Revisited. Je ne souhaite pas allonger cet article en présentant cette controverse, qui n’apporte rien après 40 ans et des dizaines d’articles venant confirmer les lois de Lehman.

## Conclusions

Bien que tombées dans l’oubli, les lois de Lehman méritent de devenir une partie du corpus de règles de l’art qui gouvernent notre profession. Leur force probante est suffisante pour permettre à tout développeur de les opposer à sa hiérarchie ou à d’autres développeurs. Elles sont tout simplement au-dessus de l’avis de tout expert, même le plus reconnu et respectable. A l’heure des software-gurus, nous avons besoin de cette stabilité et de cette rigueur.

Je les enseigne à mes étudiants et j’invite tout développeur à les apprendre et à les comprendre. La recherche en qualité logicielle n’a pas atteint le niveau de rigueur de la recherche médicale (les méta-études sur ce champ de recherche se comptent sur les doigts de la main), cela ne signifie pas pour autant qu’elle ne démontre rien. L’appropriation des résultats de la recherche par les développeurs est un cercle vertueux. Plus nous exigerons des connaissances fiables pour guider notre profession, plus nous pousserons les chercheurs à les produire. N’hésitez d’ailleurs pas à remercier par un simple mail les chercheurs des études que vous lisez, d’expérience ils sont très heureux de voir des praticiens lire et appliquer leurs travaux.

Je compte continuer ce travail sur les lois et les règles de notre art, je le pense salutaire si vous voulons apprendre et sortir de l’enfance de notre profession.

Enzo Sandré

## Sources

```
<pre class="wp-block-preformatted">M. M. Lehman. 1996. Laws of Software Evolution Revisited. In <em>Proceedings of the 5th European Workshop on Software Process Technology</em> (<em>EWSPT '96</em>). Springer-Verlag, Berlin, Heidelberg, 108–124.
```

```
<pre class="wp-block-preformatted">M. M. Lehman, "Programs, life cycles, and laws of software evolution," in Proceedings of the IEEE, vol. 68, no. 9, pp. 1060-1076, Sept. 1980, doi: 10.1109/PROC.1980.11805.
```

```
<pre class="wp-block-preformatted">M.M. Lehman, On understanding laws, evolution, and conservation in the large-program life cycle, Journal of Systems and Software, Volume 1, 1979, Pages 213-221, ISSN 0164-1212, DOI:10.1016/0164-1212(79)90022-0.
```

```
<pre class="wp-block-preformatted">Israel Herraiz, Daniel Rodriguez, Gregorio Robles, and Jesus M. Gonzalez-Barahona. 2013. The evolution of the laws of software evolution: A discussion based on a systematic literature review. <em>ACM Comput. Surv.</em> 46, 2, Article 28 (November 2013), 28 pages. DOI:https://doi.org/10.1145/2543581.2543595
```