---
title: "Le Refactoring comme modèle de couplage homme-machine : technique, sémiotique, mémoire"
layout: post
category: 'veille'
tags: thesis codesmithing
lang: french
ref: refactoring-comme-modele-couplage-homme-machine-technique-semiotique-memoire
---

👨‍🏫 Un de mes anciens professeurs, Ophir Paz, a publié sa thèse il y a presque 2 ans. C'est dense, j'ai donc choisi de la résumer par chapitres. J'ignore volontairement les premiers chapitres, introductifs, afin de débuter par le troisième, qui mêle sémiotique et développement.

# Chapitre 3 : Différents niveaux de sens

⌨️ Comprendre du code a tout du parcours initiatique ! Il ne suffit pas de comprendre ce que font les instructions pas à pas pour en saisir le sens. A vrai dire, celui qui en reste au niveau instructionnel ne fait qu'effleurer la surface. Avec l'expérience, un développeur déchiffre le sens invariant de groupes d'instructions, c'est-à-dire la fonction attachée habituellement à une construction donnée. Par exemple, la plupart des développeurs savent qu'une boucle for où l'indice est une position dans un tableau sert à itérer sur celui-ci.

🧠 La majorité du sens que porte un code est encore au-delà : il s'agit du sens social. Que signifie un bloc de code pour l'équipe qui doit la maintenir ? Quel est son rôle dans le projet, c'est à dire par rapport au contexte : expérience des développeurs, exigences, histoire du code, etc. La part déterminante de la signification d'un code se trouve ici.

💣 Ce chapitre m'a permis d'affiner ma définition du Principe de Moindre Surprise (Principle of Least Astonishment en anglais). Respecter ce principe, c'est écrire du code ayant un sens social compatible avec le sens invariant communément admis des instructions qu'il contient.

# Chapitre 4 : Grammaire de construction

🤢 Un code peut être syntactiquement valide, c'est-à-dire compilable, sans pour autant être socialement convenable au sein d'une communauté de développeurs. Le phénomène à l'oeuvre est le même qu'en français ou dans toute autre langue : "Combien d'années avez-vous ?" sonne mal, on lui préférera "Quel âge avez-vous ?". De même for(int i=0 ; i<10 ; i = 1 + i) dissonne.

🗣️ Ophir Paz décortique ce phénomène en utilisant les grammaires de construction, une branche de la linguistique. Pour les auteurs de cette école, les locuteurs d'une langue apprennent et manipulent des constructions, c'est-à-dire des appairages forme-sens. L'expression "Comment vas-tu ?" lorsque l'on salue quelqu'un de familier n'est pas à interpréter littéralement. De même, l'incrémentation d'un pointeur (\*p++) possède un sens invariant pour les développeurs C++ chevronnés : celui de parcourir un tableau séquentiellement.

😕 Ces constructions ont un sens instructionnel clair, qui sera exécuté par le compilateur, mais aussi un sens invariant non-prédictible, c'est à dire ne pouvant pas être déduit des seules instructions. C'est un problème pour le profane, qui lit un code qu'il n'a pas les codes pour comprendre. A cela s'ajoute un sens social, connu des seuls développeurs, pouvant contredire le sens invariant communément admis par la profession.

🪄 Ainsi, pour comprendre un programme, il ne suffit pas de partager les sources. Il faut également posséder des connaissances concernant les expressions idiomatiques répandues au sein de la communauté. Les programmes sont écrits à l'aide de ces constructions et en partant du principe que le futur lecteur les connaît également. De même pour les constructions plus confidentielles, propres à une équipe de développement, même si ces dernières doivent être limitées afin de garder le code reprenable.

# Chapitre 5 : Sémiotique constructive du code

📡 En 1949, Claude Shannon propose son modèle de communication éponyme. Il régna sur la psychologie de la programmation pendant un demi-siècle, continué par les approches cognitivistes. Son postulat de base est la symétrie du message entre émetteur et destinataire. Appliqué au développement de logiciels, ce modèle voit le programmeur comme le récepteur de spécifications non-ambigues, qu'il est chargé de traduire en code non-ambigu destiné à une machine.

😶‍🌫️ Cette représentation, à l'origine de la famille de méthodes Waterfall (contenant le Cycle en V) est empiriquement erronnée. Ni le code, ni les spécifications ne sont des messages symétriques. Chaque développeur appairera un sens différent aux formes qu'il lit. Les formes elles-mêmes sont souvent polysémiques ("grand" n'a pas le même sens dans "un grand vin" et "un grand enfant", de même pour le mot clé static en C).

🧠 Ophir Paz propose de dépasser ce modèle à l'aide d'une approche issue de la linguistique cognitive de Lakoff et Johnson, à la frontière de la sémiotique. Pour cette école, notre cerveau agit comme un moteur d'inférence lorsqu'il lit un code. Il associe les symboles à un sens en fonction du contexte, lui-même constitué des symboles entourant le premier et du contexte plus général du projet. Le langage n'est pas un signal, il est la pensée elle-même ! Nous apprenons et restituons nos connaissances par le biais de métaphores, qui ne sont pas de simples figures de style, mais l'incarnation de la pensée abstraite. La manière dont les enfants apprennent l'arithmétique, par analogie avec des collections d'objets ou les design patterns sont autant d'indices de la validité de ce modèle.

🤝 Chacun interprète le code en fonction de son système de métaphores propre, difficilement reformatable. Travailler en équipe suppose donc une négociation du sens entre les parties. Chacun doit miser sur ce que l'autre comprendra au moment d'écrire un code. Ne pouvant être dans tête de ses collègues, chaque développeur est amené à évoluer par essais et erreurs, à ajuster la structure du code sans en changer le fonctionnement, afin de le clarifier pour autrui, mais également pour soi, lorsque le temps aura effacé une partie de notre mémoire. Cette procédure, les développeurs la nomment refactoring et Ophir Paz en donne une nouvelle compréhension.

# Chapitre 6 : Le code en tant qu'outil

📚 Le code n'est pas seulement la traduction du besoin en un langage intelligible par une machine. C'est un objet technique à part entière, forgé à partir de pièces plus simples, en perpétuelle évolution. Parfois cet objet est réutilisé en dehors de son cadre d'usage et devient un standard, à l'instar des langages de programmation ou des bibliothèques populaires.

🦾 Le code n'est pas le logiciel, mais la prothèse permettant au développeur qui s'en saisit de produire un logiciel. Il est l'interface entre le logiciel et les schémas mentaux dudit développeur. Refactorer le code c'est aligner les grilles de lecture de chacun, afin que toute l'équipe comprenne bien la même chose en lisant le code. Ce processus augmente la capacité à travailler ensemble autour d'une oeuvre commune, gage de vélocité et de résilience.

🧠 On se méprend sur ce phénomène en pensant que seul le code s'améliore dans ce processus. Le développeur en sort également transformé. L'invention de l'écriture n'a pas seulement permis de coucher sur support ce qui était transmis oralement. De nouvelles formes d'expressions sont apparues et ont augmenté les possibles offerts à notre espèce et par voie de conséquence le champ du concevable s'est dilaté. On retrouve ce phénomène à plus petite échelle dans l'apprentissage des nouveaux développeurs : ils apprennent par imitation d'une base de code existante, en appairant un sens qui leur est propre à des constructions récurrentes, afin de les réutiliser plus tard.

🗣️ La prochaine fois que vous verrez une équipe de developpement discuter au lieu de coder, n'ayez crainte, ils sont simplement en train d'augmenter leur productivité collective. Le principal produit de l'activité de développement n'est pas le logiciel, mais le développeur lui-même. Cette paraphrase de Frédéric Le Play conclut ce résumé d'une thèse que j'ai eu plaisir à lire.

SOURCE

Le refactoring comme modèle du couplage homme-machine / Ophir Paz ; sous la direction de Jean-Baptiste Guignard. Thèse de doctorat : Automatique, Productique, Signal et Image, Ingénierie cognitique : Bordeaux : 2022.