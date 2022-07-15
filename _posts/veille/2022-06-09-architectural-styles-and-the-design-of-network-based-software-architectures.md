---
title: "Architectural Styles and the Design of Network-based Software Architectures"
layout: post
category: 'veille'
tags: architecture histoire-informatique thesis
lang: french
ref: architectural-styles-and-the-design-of-network-based-software-architectures
long_post: True
---

🌐 Si Tim Berners-Lee est le papa du Web, alors le parrain en est Roy Fielding. Sa thèse 👇 devrait être lue par tout développeur web. Dans le chapitre 4, notamment, il définit avec précisions les problèmes que doit résoudre l’architecture dont le web a cruellement besoin en l’an 2000 : REST.

💥 Posons le décor : dans les années 90 il est évident que le web va sortir largement du monde de la recherche et que les usages personnels et commerciaux vont faire exploser la non-architecture existante. L’ancien monde est mort, il faut une architecture qui soit décentralisée pour être capable d’encaisser le boom d’Internet.

🦑 Le défi est ambitieux : l’architecture du Web doit permettre l’interconnexion de machines hétéroclites (terminaux, serveurs, supercalculateurs, etc.). Les informations sont encore plus diverses : textes, images, vidéos, ainsi que tous les formats inconnus que l’avenir réserve.

🚧 La barrière à l’entrée doit être minime, car le web est en plein boom : un standard qui n’est pas simple sera rejeté. Cela signifie des références pouvant être communiquées avant même l’existence de la ressource, simplement et entre humains. Il faut que tout soit du texte, afin que l’outillage réseau existant permette de tester.

🧩 Enfin, tout doit être déployable de manière indépendante, les ressources, les serveurs ou les références. Seule la décentralisation peut encaisser une telle charge.

🏅 Un pari fou ? Dans le prochain post, nous verrons comment Fielding a relevé le défi, en proposant l’architecture REST.

💯 Le défi que le Web doit relever au début des années 2000 paraît insurmontable. Pour ne pas exploser, il faut lui concevoir une architecture compatible avec tous les formats, tous les appareils, décentralisée, mondiale, extensible et simple à utiliser.

🏆 Il faut trouver le graal de l’architecte. Rien de moins que ça. Quand Roy Fielding soutient sa thèse en 2000, il ne livre pas un misérable bocal à anchois, mais bien une architecture de maître, REST, basée sur un principe terriblement efficace : la scalabilité anarchique.

😶‍🌫️ Le paradigme de l’informatique du XXème siècle est la centralisation. Un système est sous contrôle d’une autorité centrale et tous ses éléments sont ordonnés à la même fin. Avec l’émergence d’un réseau global, ce paradigme mène à un effondrement.

1️⃣ Tous les clients ne peuvent pas maintenir à jour une liste de tous les serveurs et réciproquement.

2️⃣ Il n’est pas possible de faire confiance à une autre machine sans authentification.

3️⃣ L’authentification dégradant la scalabilité, le web doit nécessiter le moins de confiance possible.

🅰️ Roy Fielding nomme ce principe « scalabilité anarchique ». Chaque nouvel acteur peut exister sans avoir à demander d’autorisation aux autres. Les autres réagiront à sa présence a posteriori, selon leurs propres règles. Ce principe est à la base du Web moderne, même si le contrôle américain sans partage en a gâté les principes.

☘️ Qui n’a pas entendu parler de REST ? Beaucoup de gens en réalité, car l’architecture de Fielding a été terriblement mal interprétée et enseignée. Encore un leprechaun, mais aussi la marque d’un échec : Fielding n’a pas réussi à atteindre la simplicité qu’il souhaitait pour son architecture.

🔌L’idée de REST est d’atteindre la scalabilité anarchique par la définition d’une interface commune à tous. Chacun implémente comme il le souhaite son application, pourvu que l’interopérabilité respecte quelques principes simples.

1️⃣ Client-Serveur : REST s’occupe de faire transiter la donnée, l’afficher n’est pas son affaire tant la matière est spécifique à chaque client.

2️⃣ Stateless : aucune requête ne doit dépendre du contexte stocké sur un serveur. Toutes les informations de contexte nécessaires doivent être contenues dans la requête elle même.

3️⃣ Cachable : tout échange compatible doit pouvoir être mis en cache. Cette propriété n’existe pas dans un système non-Stateless. En REST/HTTP la cachbilité se signale par le verbe utilisé.

⚠️ Les années 2000 ont largement piétiné ces deux derniers principes. Les langages à session (Java et PHP en tête) ont violé le principe du Stateless, le manque de formation des développeurs a achevé toute idée de cache efficace.

🛬 Déjà esquintée à sa sortie par l’opacité de ses 3 premières règles pour les débutants, REST a définitivement perdu son public avec les 3 suivantes. L’architecture de Fielding est certainement brillante, mais certainement pas simple, comme il la souhaitait. L’enseigner est d’ailleurs un calvaire.

4️⃣ Interface Uniforme. REST définit seulement un contrat commun, charge aux développeurs de l’implémenter comme bon leur semble.

5️⃣ Architecture en couches. REST demande que le contrat commun soit dans une couche dédiée, qui appelle ensuite le véritable système.

😵 Ces deux règles auraient été comprises, si REST avait défini ce « langage commun » comme étant HTTP dès le départ. Or ça n’est pas le cas. REST/HTTP est seulement une implémentation majoritaire de REST. Dans la thèse de Fielding, ces points étaient simplement trop abstraits pour la majorité des développeurs, débutants ou non.

6️⃣ Code à la demande. Une application REST doit pouvoir fournir aux clients un snippet de code permettant de l’appeler, dans le langage de leur choix.

💀 Cette contrainte, décrite dès le départ comme « optionnelle » n’a en réalité jamais vraiment fait partie de REST. J’ai l’intuition que Fielding s’est dès le début rendu compte qu’il était allé trop loin.

🧟 REST était trop ambitieux. L’avenir nous dira s’il peut exister une architecture à la fois simple et universelle, ce que n’est pas l’architecture de Fielding. Ses mauvais clones ont rapidement remplacé l’idée originale, faisant de ce coup de génie un autre Leprechaun.

SOURCE

Fielding, Roy T.. “Architectural Styles and the Design of Network-based Software Architectures »; Doctoral dissertation.” (2000).