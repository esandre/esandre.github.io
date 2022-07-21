---
title: "Opposer artisanat et ingénierie est une idiotie"
layout: post
category: 'blog'
lang: french
tags: artisanat technocritique
ref: opposer-artisanat-et-ingenierie-est-une-idiotie
image: /resources/images/content/Armee_de_terre_cuite_fouille_du_tombeau_de_lempereur_Qin_Xian.jpg
---

{% include helper_image.html src="/resources/images/content/lewis-mumford.jpg" size=2 float="end" caption="Lewis Mumford (1895-1990)" %}

L’idée que l’industrie est l’évolution nécessaire de tout artisanat est un lieu commun fortement ancré dans la mentalité contemporaine. Dans la seconde moitié du XXème siècle, une lame de fond trouvant son origine chez Lewis Mumford[\[i\]](#_edn1) parcourt la plupart des disciplines que l’on croyait acquises à l’industrie : architecture, mobilier et même agriculture. Elle se nomme vernacularisme [\[ii\]](#_edn2)et tente de réconcilier science et tradition, productivité et beauté.

Mon métier, le développement de logiciels, n’était pas né lors de l’émergence du courant vernaculaire et son inclusion dans ce débat n’intervient que dans les années 2000, avec le mouvement de l’artisanat logiciel (Software Craftmanship). Le débat fut vif entre tenants d’une ingénierie logicielle « tayloriste » et ceux d’un artisanat logiciel[\[iii\]](#_edn3) qui n’allait pas tarder à se séparer du mouvement Agile. L’enjeu du débat est d’imposer sa grille de lecture à l’informatique des années 70 à 90. L’échec qualitatif historique du développement logiciel, qui fait les choux gras du Standish Group[\[iv\]](#_edn4), fut analysé par les deux camps, chacun ayant son explication.

{% include helper_image.html src="/resources/images/content/synthese-chaos-2015.png" size=4 float="start" caption="Les méthodes des années 70 sont un facteur d’échec certain pour la profession." %}

L’artisanat du logiciel, explique que le désastre trouve son origine dans l’abandon des pratiques artisanales des années 60 au profit de méthodologies en tunnel. Dans ces dernières, la valeur est le fruit d’un processus industriel rationalisé dans lequel le développeur n’a pas de rôle moteur. Cette école plaide pour une conception itérative et incrémentale des logiciels, où la petite équipe décide collectivement avec le client de l’ensemble des choix de design. Pour Paul Taylor[\[v\]](#_edn5), cette rhétorique est intégralement issue du vernacularisme et s’appuie sur un empirisme clairement assumé par les praticiens. La présence importante d’anciens hippies dans la profession, sensibles aux thèses de Marcuse et Illich, n’est sans doute pas étrangère à l’origine de ce courant, mais il s’agit là d’une hypothèse personnelle. A ma connaissance aucune étude de l’origine de ce courant de pensée n’a été réalisée.

{% include helper_image.html src="/resources/images/content/architecture-vernaculaire-alsace.webp" size=3 float="end" caption="Architecture vernaculaire, ou architecture sans architecte. L’analogie s’est étendue à d’autres disciplines, dont le développement." %}

A contrario, pour les partisans de l’ingénierie, dont les arguments sont résumés par Ivar Jacobson et Ed Seidewitz[\[vi\]](#_edn6), le développement a échoué par manque de rigueur dans ses méthodes. Les auteurs ne dénigrent pas les artisans, qui sont à l’origine des très belles choses. Cependant ils considèrent que tout travail artisanal est par nature inefficient, car non-répétable et donc très faiblement ouvert à l’optimisation. C’est la pratique de l’ingénierie, un « artisanat supporté par une théorie », qui permettra au développement de sortir de la crise. L’ingénierie, selon les auteurs, uniformise les pratiques des différents maîtres et des différentes écoles derrière une théorie commune.

Ce débat soulève deux questions. D’abord, l’artisan est-il si allergique à la science que ça ? Autrement formulé, accuser la transmission traditionnelle des connaissances d’aller contre la science n’est-il pas fallacieux ? Ensuite, nous étudierons le lieu commun affirmant que tout artisanat se doit de progresser en une ingénierie, toute pratique vernaculaire en une industrie et toute tradition en une science. Enfin ce papier conclura sur l’opportunité ou non pour un développeur de s’identifier à la figure de l’artisan.

## L’artisan est-il un technophobe qui s’ignore ?

Au XIVème siècle, Étienne Marcel, alors prévôt des marchands de Paris, tenait le Roi de France en respect ! Celui qui était alors le chef des petits artisans et compagnons, majoritaires dans le Paris de l’époque, se savait plus puissant que le Roi, qu’il souhaitait faire contrôler par les guildes, trois siècles avant la Glorieuse Révolution Britannique. C’est en grande partie lui qui associa dans notre imaginaire les maîtres-artisans à un Moyen-Âge où ils furent tout-puissants.

{% include helper_image.html src="/resources/images/content/daniel-bernouilli.png" size=4 float="start" caption="Daniel Bernouilli (1700-1782); Médecin, physicien, mathématicien et astronome. Un savant polymathe typique de son époque." %}

Quelle chute lorsque les corps de métiers sont rayés d’un simple trait de plume le 14 juin 1791 par la Loi Le Chapelier[\[vii\]](#_ednref7) ! Or c’est également à la fin du XVIIIème que la méthode scientifique moderne a déployé ses ailes, refermant peu à peu la période des grands savants de l’Époque Moderne. Les grands génies polymathes cèdent la place à des armées de spécialistes, physiciens, biologistes, archéologues, etc.

A cause de cette corrélation temporelle, l’imaginaire populaire associe en un tout indissociable « l’Ancien Régime », période allant du Haut Moyen-Âge à l’Époque Moderne, avec ses artisans réunis en guildes, ses mousquetaires, ses carrosses et ses perruques. La culture fantasy et médiévaliste n’a pas aidé en liant définitivement l’artisan à cette « époque ».

Or, corrélation n’est pas causalité. Cet argument ne peut pas, à lui seul, coller définitivement aux artisans une étiquette « antiscience » ou les condamner au suranné.

Un second argument contre l’artisanat consiste à accuser la transmission des savoirs par apprentissage, ou transmission par Tradition. Il lui est reproché de créer des silos nuisibles au partage universel des connaissances techniques. Oui, les maîtres-artisans avaient leurs secrets, que la fragile transmission à un seul apprenti pouvait perdre. Toutefois, ne s’agit pas d’un problème propre aux artisans, mais à toute entreprise vivant d’un savoir. Les secrets industriels, brevets et autres revues académiques hors de prix ont succédé à l’opacité des corporations, il ne s’agit donc pas d’un argument qui puisse servir contre l’artisanat seul.

{% include helper_image.html src="/resources/images/content/alexandra_elbakyan.png" size=4 float="start" caption="Sans Alexandra Elbakyan, l’accès à la littérature scientifique mondiale serait impossible sans payer de lourdes redevances à des éditeurs dispensables." %}

Je défends la thèse qu’il s’agit en grande partie d’une question de technologie disponible, et qu’à niveau technologique égal, l’industrie n’aurait pas fait mieux que l’artisanat des siècles passés. Ce sont les revues scientifiques permises par les progrès de l’impression et de l’édition qui ont permis le développement des circuits de production de connaissances actuels. A notre siècle, l’accès à la littérature académique n’a jamais été aussi facile, beaucoup de revues sont consultables gratuitement, même s’il faut parfois employer des moyens plus légitimes que légaux[\[viii\]](#_edn8) pour cela.

De nos jours, qui veut travailler en se basant sur les faits scientifiques peut le faire, que son mode de production soit artisanal ou industriel. Tous les professionnels qui m’entourent, qu’ils soient dans l’informatique, l’art ou le bâtiment, basent leurs œuvres sur des connaissances acquises lors de leur formation initiale. Le maçon ou le charpentier connaît des rudiments de mécanique, l’enlumineur possède des bases de chimie et le développeur doit bien s’intéresser un peu aux bonnes pratiques. Aucun de ces professionnels ne peut se permettre d’être trop en retard sur les connaissances du moment. Cette observation vaut autant pour les salariés de l’industrie que pour les artisans, d’ailleurs souvent issus des mêmes formations.

C’est après les études que la question se complique. Très peu de professionnels poursuivent leur formation et rares sont ceux qui s’intéressent à la littérature académique. Tous attendent la sortie de normes contraignantes pour se former, faute d’avoir d’autres incitatifs. On observe hélas le même comportement chez les médecins, pourtant théoriquement tenus de se former en permanence. Il s’agit probablement d’une affaire de culture et les artisans sont ici logés à la même enseigne que les industriels.

Chez les développeurs, en dehors des universitaires, l’intérêt pour les travaux académiques se retrouve principalement dans le mouvement artisanal du *software craftsmanship*. Je possède un fort biais dû à mes fréquentations, mais je n’ai jamais rencontré de collègue réalisant une veille académique dans l’industrie, bien plus obnubilée par le dernier outil/langage/framework à la mode.

{% include helper_image.html src="/resources/images/content/arxta_sticker.jpg" size=3 float="end" caption="Cet autocollant humoristique pourrait taper bien plus juste que prévu." %}

Finalement, une fois les arguments simples épuisés, il ne reste contre l‘artisanat qu’un discours très ancien dans l’histoire des idées, opposant frontalement science et tradition, souvent en accusant cette dernière de dogmatisme, d’irrationalité ou d’immobilisme. Déconstruire ce discours occupera la seconde partie de cet article.

## L’artisan n’est pas un ingénieur imparfait.

{% include helper_image.html src="/resources/images/content/Lorenzo-Cifonelli.webp" size=4 float="start" caption="Lorenzo Cifonelli, maître-artisan tailleur. Son existence n’est pas incompatible avec celle d’une industrie du vêtement. Assurément un artisanat de civilisation." %}

Toutes les industries actuelles sont issues d’une discipline autrefois artisanale, quand elles ne sont pas des créations récentes. Je ne connais aucune discipline ayant parcouru le chemin inverse. Cependant, toutes les industries connues cohabitent avec un double artisanal plus ancien, qui a toujours survécu dans une logique de qualité et de haut niveau de personnalisation. Le textile, l’automobile, la boucherie ou la restauration partagent tous le point commun de posséder une industrie majoritaire qui n’a jamais éliminé ce que Bruno Lussato appelle un « artisanat de civilisation »[\[ix\]](#_edn1).

L’artisanat est vieux comme l’outil et ne disparaître vraiment jamais au profit de l’industrie. C’est son principal avantage qui garantit sa survie dans les périodes de vaches maigres : sa résilience. L’artisan est un généraliste d’une matière, non un spécialiste en process (ce qu’est l’ingénieur). Il ne produit pas un bien précis, mais possède une connaissance étendue d’une matière et des outils nécessaires à la façonner. En un mot, il peut s’adapter.

{% include helper_image.html src="/resources/images/content/monoculture.png" size=4 float="start" caption="Monoculture = mono-débouché." %}

La crise du Covid confirme cette théorie : ce sont les artisans qui furent à l’avant-garde de la production de masques, bien avant que les industriels ne parviennent à réorienter leur production, quand les machines qu’ils possédaient le leur permettaient. Ce sont aussi les agriculteurs les plus diversifiés et les moins industrialisés qui ont le mieux traversé la crise (sans gaspillage d’argent public, j’entends).

L’artisan n’aura jamais l’optimisation de l’industriel, ce qui le rend moins compétitif lors des périodes fastes, pour les domaines où le bas coût en masse est une obligation. C’est par la résilience et l’adaptabilité qu’il se rattrape sur le long cours, étant moins sensible aux aléas que l’industrie. L’artisan est un producteur complet, ouvrier et cadre en une même personne, souvent en contact direct avec ses clients. Taylor remarque que cela rend la boucle de rétroaction produit très agile, l’artisan étant capable de concevoir par très petits incréments, n’ayant pas la lourdeur du process industriel à supporter.

L’artisanat n’est pas un métier, mais un mode de production, qui préexiste et coexiste avec l’industrie depuis au moins le Xème siècle. Il n’est pas une industrie baroque ou diminuée, mais bien une autre manière de produire, moins optimisée, mais plus résiliente. Industrie et artisanat ne sont aucunement mutuellement exclusifs sur une filière donnée. Toutes les filières de luxe sont des industries incluant une grande part d’artisanat en bout de chaîne. La part d’artisanat et d’industrie sur une filière est une question essentiellement politique et stratégique. Éradiquez les artisans, vous chasserez les coûts, au prix d’une absence totale de résilience et d’adaptabilité, voire d’une absence de civilisation pour Lussato. Interdisez l’industrie, vous obtenez une société mal armée pour la guerre économique et pour la guerre moderne tout court, incapable de défendre ses choix politiques face aux puissance étrangères.

Je vais plus loin : aucune filière stratégique ne peut se permettre d’être complètement industrielle ou complètement artisanale. Opposer les deux est bête, surtout dans un pays comme la France, possédant une vraie culture hybride, rayonnant à l’international par son savant mélange d’artisanat et d’industrie. Une économie-monde perd toujours à choisir l’un ou l’autre.

{% include helper_image.html src="/resources/images/content/2014_produits_la_france_exportation_treemap.png" size=12 caption="Exportations de la France en 2014. Un mélange d’artisanat et d’industrie. Source : Wikipedia." %}

## Conclusion

Cette complémentarité entre artisanat et industrie se retrouve entre leurs sous-jacents cognitifs : la tradition et la science. Trop souvent (bêtement) opposés, ces deux modes de production de la connaissance sont indissociables.

{% include helper_image.html src="/resources/images/content/Xixia.jpg" size=4 float="end" caption="Pyramides chinoises de Xixia, encore un coup des Atlantes ?" %}

- D’abord, parce qu’aucune industrie n’existe sans tradition et aucun artisanat sans science. Pourquoi l’écartement ferroviaire contemporain standard ? Parce que les essieux des chars romains ont été normalisés il y a bien longtemps[\[x\]](#_edn1). Pourquoi certaines structures, comme les pyramides, se retrouvent partout sur le globe, malgré une absence d’interactions entre leurs bâtisseurs ? <s>Parce qu’une race de reptiles se déplace sous la surface terrestre depuis des millénaires.</s> Parce que les bâtisseurs, où qu’ils soient, ont déduit des lois empiriques de l’étude de la nature, bien avant l’apparition de la méthode scientifique. Celle-ci n’a pas inventé la science, elle n’a été qu’une étape vers plus de rigueur, mais tout artisanat repose sur des connaissances théoriques depuis les tailleurs de silex.

- Ensuite parce que la science pure n’est pas applicable en l’état. Elle doit être appliquée pour servir aux praticiens. Appliquée à quoi ? A un corpus de connaissances, transmis de manière traditionnelle, précisément. La science vient amender et augmenter les connaissances d’un métier au fil des découvertes, mais ce sont bien des professionnels, formés par des professeurs et des maîtres, qui doivent effectuer ce travail.
- Enfin, parce qu’une tradition figée ne survit pas, sauf éventuellement dans les musées. Un métier qui cesse d’amender son corpus de traditions à chaque génération meurt. En matière économique, le traditionalisme figé n’est pas viable, mais cela va même plus loin : le métier qui ne fait pas évoluer la manière dont il amende sa tradition à chaque génération n’est pas viable. A chaque génération, la manière dont science et tradition interagissent doit aussi se renouveler !

L’artisanat et l’industrie n’ont pas de différence fondamentale dans leur rapport à la science. Du moins, pas en nature, éventuellement en degré. L’artisan a éventuellement une approche plus conservatrice que l’industriel. La différence fondamentale entre ces deux personnages réside dans le mode de production, donc dans les qualités du produit final.

{% include helper_image.html src="/resources/images/content/software_runaways_glass.jpg" size=3 float="start" caption="Un livre qui devrait faire l’objet d’études de cas pas les étudiants." %}

C’est exactement cette conclusion que je vais appliquer au développement de logiciels. Un artisan-développeur n’est pas un anti-ingénieur, niant les meilleures pratiques certifiées™ au profit de l’enseignement d’obscurs gourous. Il n’a pas de problème avec la science, qu’il utilise bien volontiers (plus que la moyenne des développeurs) pour garder un regard critique sur ce qu’enseigne tel ou tel membre de la communauté, maître reconnu ou simple pair.

L’artisan-développeur, surtout, n’a pas l’énorme passif d’échecs méthodologiques de ces 40 dernières années à assumer. Il était là dès les origines de la programmation, fut éclipsé à l’ère des méthodes en tunnel pour mieux renaître depuis les années 2000. La littérature académique donne raison aux artisans sur des pratiques adoptées dans leurs communautés depuis des décennies. Pire : l’impasse dans laquelle toutes les tentatives de faire du logiciel une discipline formelle, aux bases théoriques et mathématiques solides, ne semblent pas avoir de sortie.

Nous continuons de bâtir des châteaux de vent, des édifices de pensée, de manière purement empirique. La matière que nous sculptons est tellement particulière qu’il serait légitime de se demander, finalement, si ça n’est pas l’ingénierie du logiciel qui manque de sens ? Il existe quelques métiers qui ne s’envisagent pas autrement que dans une logique industrielle. Peut-être tenons-nous avec le développement un cas de métier qui n’est qu’artisanal.

Opposer artisanat et industrie à l’échelle d’une branche ou d’une nation est idiot. Cela n’exclut pas la possibilité de métiers pour lesquels l’une ou l’autre de ces formes est contre-productive. Je soutiens que le développement en fait partie, dans l’état actuel de nos connaissances.

- - - - - -

[\[i\]](#_ednref1) [*Technique et Civilisation*](https://fr.wikipedia.org/wiki/Technique_et_Civilisation) (1934) ; Paris, Le Seuil, 1950 ; Marseille, Parenthèse, 2016

[\[ii\]](#_ednref2) [https://fr.wikipedia.org/wiki/Architecture\_vernaculaire](https://fr.wikipedia.org/wiki/Architecture_vernaculaire)

[\[iii\]](#_ednref3) <http://manifesto.softwarecraftsmanship.org/>

[\[iv\]](#_ednref4) The Standish Group, CHAOS Report

[\[v\]](#_ednref5) Taylor, P. (1). Vernacularism in Software Design Practice: does craftsmanship have a place in software engineering?. *Australasian Journal of Information Systems*, *11*(1). <https://doi.org/10.3127/ajis.v11i1.143>

[\[vi\]](#_ednref6) Jacobson, Ivar &amp; Seidewitz, Ed. (2014). What happened to the promise of rigorous, disciplined, professional practices for software development?. Queue. 12. 10.1145/2685690.2693160.

[\[vii\]](#_ednref7) [https://fr.wikipedia.org/wiki/Loi\_Le\_Chapelier](https://fr.wikipedia.org/wiki/Loi_Le_Chapelier)

[\[viii\]](#_ednref8) <https://fr.wikipedia.org/wiki/Sci-Hub>

[\[ix\]](https://blog.enzosandre.fr/wp-admin/post.php?post=741&action=edit#_ednref9) Lussato Bruno, La Troisième Révolution

[\[x\]](https://blog.enzosandre.fr/wp-admin/post.php?post=741&action=edit#_ednref1) Il est tout à fait possible que cette explication elle-même, impossible à sourcer, soit une tradition. Elle existe parce qu’aucun chercheur n’est venu la vérifier, dans un sens ou l’autre. Encore une illustration du lien intime entre science et tradition.