---
title: "Les « alternet » sont-ils viables ?"
layout: post
category: 'blog'
tags: af2000 securite histoire-informatique
lang: french
ref: les-alternet-sont-ils-viables
---

![](http://blog.enzosandre.fr/wp-content/uploads/2017/09/https-_blueprint-api-production.s3.amazonaws.com_uploads_card_image_469418_e5582afd-4887-478d-8043-0071299682c3.jpg)S’estimant privés de leur liberté d’expression, les groupes d’alt-right américains s’organisent face à la censure des géants de la Silicon Valley, très marqués à gauche. Posséder son propre serveur n’est aujourd’hui plus suffisant : les entreprises gérant l’infrastructure d’Internet n’hésitent pas à filtrer jusque dans les couches les plus basses du net : déconnexion de serveurs, retrait de noms de domaine, etc. Stormfront et The Daily Stormer, deux sites d’information de l’alt-right ont eu leur domaine retiré. Le site d’écoute musicale Spotify, le site de rencontre OkCupid et Paypal bannissent les prétendus « nazis » hors du web. Facebook et AirBnb ont supprimé les comptes liés à la manifestation de Charlottesville. Des centaines de comptes Facebook et Twitter sont suspendus chaque jour, y compris en France.

Pour l’instant, la censure extra-judiciaire ne concerne que les terroristes et « la haine », réelle ou soupçonnée. Les hypocrites défenseurs de la neutralité du net peuvent donc encore faire semblant de croire que cette dernière, morte depuis des années, existe toujours.

## Une réussite très élitiste

Le réseau social [Gab](https://gab.ai/) ![](http://blog.enzosandre.fr/wp-content/uploads/2017/09/Official_Gab_Social_Network_Logo-150x150.png), fer de lance de la contestation, a proclamé le 10 août dernier la naissance de la « Free Speech Tech Alliance ». Cette alliance de professionnels doit permettre à terme la création d’un véritable « Alternet » : une partie d’Internet débarrassée de la Silicon Valley et de sa censure morale. Sur le papier, le projet sonne bien, mais sa viabilité est questionnable.

D’autres ont essayé avant eux, la réputation sulfureuse en moins. Depuis les années 90 les groupes crypto-anarchistes combattent l’Internet centralisé qui a accouché des fameux GAFA. Leur credo ? Les méthodes de chiffrement utilisées massivement doivent permettre la protection des échanges. Si vous envoyez un message chiffré, ce message est suspect pour d’éventuels attaquants, qui tenteront de le déchiffrer. Si vous chiffrez tout jusqu’à votre liste de courses, le volume de données sera trop important pour être traité.

Le succès de ces activistes est mitigé, malgré leur présence très importante dans le monde du logiciel libre. C’est une réussite technique très élitiste : l’essor des crypto-monnaies, des réseaux cachés, des darknets et des blockchains le prouve. Leurs seules réussites « grand public » sont la généralisation du protocole web chiffré HTTPS (car largement soutenu par la banque et le e-commerce) et la généralisation de messageries instantanées supportant le chiffrement de manière limitée (Telegram, Messenger …)

## Difficile de réformer internet

Le projet de la Free Speech Tech Alliance est plus ambitieux. Une poignée de militants peut parfaitement communiquer à l’insu des services de renseignement, Daech et les fameux « hackers russes » de la campagne américaine l’ont prouvé. Pour toucher un public plus large, donc bien moins formé, il faut des outils plus conviviaux, ayant une certaine masse critique pour se faire connaître, mais surtout contrôlant toutes les couches du réseau.

Les réseaux informatiques fonctionnent comme un empilement de couches techniques ([modèle OSI](https://fr.wikipedia.org/wiki/Mod%C3%A8le_OSI)). La plus basse est la liaison physique, le signal électrique, lumineux, radio qui permet d’acheminer les données. La plus haute est constituée des programmes utilisant le réseau. Chaque couche est en principe indépendante des autres : on peut faire passer la même information par différents chemins sur le réseau, utilisant diverses technologies (fibre, ADSL, 4G) sans que cela change quoi que ce soit à l’arrivée.

Celui qui contrôle les couches les plus basses peut toujours censurer les couches au-dessus. Coupez le câble réseau, l’application la plus performante tombe. Un site Internet, un service de noms de domaine (DNS) se situent tous sur la dernière couche du réseau. Les géants du net contrôlent les couches inférieures : ils peuvent censurer à volonté.![](http://blog.enzosandre.fr/wp-content/uploads/2017/09/osi_simplifié.png)

Si l’alt-right a pour ambition de créer son propre *safe-space* sur Internet, elle devra bâtir toute une infrastructure. Elle doit donc posséder *à minima* : ses hébergeurs[\[1\]](#_ftn1), ses bureaux d’enregistrement de noms de domaine[\[2\]](#_ftn2), ses autorités de certification[\[3\]](#_ftn3), ses fournisseurs d’accès à Internet[\[4\]](#_ftn4) et ses transiteurs de contenu[\[5\]](#_ftn5). Tous ces acteurs doivent être utilisés par une certaine masse de sites lambda afin d’être indispensables à la vie d’Internet et ne pas se faire censurer. S’ils ne sont utilisés que par l’alt-right, ils seront rapidement mis au ban d’Internet. Chacun de ces acteurs nécessite des millions de dollars d’investissements, plusieurs années de dissimulation et des centaines de professionnels. L’alt-right a-t-elle les épaules de ses ambitions ?

Je n’ai évoqué ici que les cas des USA. Dans les pays où l’état se mêle de liberté d’expression comme en France, il faut aller bien plus loin, parfois contre la loi ce qui rend toute solution grand public complètement irréaliste. Dans notre pays, l’Internet libre ne sera toujours qu’un fantasme. Sauf changement politique radical, la liberté d’expression ne pourra qu’être le luxe d’une avant-garde de techniciens.

[\[1\]](#_ftnref1) Mettent des machines connectées 24/24 à disposition de clients : sites Internet ou logiciels divers.

[\[2\]](#_ftnref2) Permettent de retrouver une ressource à partir d’un nom simple à retenir : enzosandre.fr par exemple

[\[3\]](#_ftnref3) Délivrent des certificats permettant de s’assurer qu’un contenu est bien émis par qui de droit

[\[4\]](#_ftnref4) Connectent les particuliers au réseau Internet, ils sont la première ligne de la censure.

[\[5\]](#_ftnref5) Les « plombiers » du net : ils connectent tous les acteurs ci-dessus entre eux via de vastes réseaux régionaux