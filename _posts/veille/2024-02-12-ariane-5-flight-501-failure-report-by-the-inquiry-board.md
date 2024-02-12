---
title: "Ariane 5 : Flight 501 Failure Report By The Inquiry Board"
layout: post
category: 'veille'
tags: failures
lang: french
ref: ariane-5-flight-501-failure-report-by-the-inquiry-board
link: https://esamultimedia.esa.int/docs/esa-x-1819eng.pdf
---

💥 Le 4 juin 1996, le premier vol d'Ariane 5 se termine par une autodestruction. La mémoire collective retient un désastre logiciel, mais est-ce bien honnête ? Pour qui se plonge dans le rapport d'enquête, rien n'est moins sûr.

📰 La couverture médiatique de l'évènement se résume à cela : 40 secondes après le début du compte à rebours, les deux centrales inertielles de la fusée s'éteignent successivement après un même plantage. La fusée désorientée prend une trajectoire dangereuse, nécessitant sa destruction. Avant même d'étudier les causes du plantage, une aberration ressort : comment se fait-il que ces composants critiques soient matériellement et logiciellement identiques ? En de pareils cas, l'état de l'art recommande déjà à l'époque de confier le développement à deux équipes distinctes, ayant les mêmes spécifications, afin de minimiser les chances de bug identique.

😶‍🌫️ Le brouillard des responsabilités s'épaissit lorsque l'on apprend que les centrales inertielles n'ont pas été testées avec les paramètres de vol d'Ariane 5. Les ingénieurs ont considéré que les excellents états de service de ce composant sur Ariane 4 valaient qualification. Or Ariane 5 est d'un ordre de grandeur plus puissante que Ariane 4, ce qui a provoqué un dépassement d'entier lors d'une conversion non-protégée. La faute est partagée entre les ingénieurs et les développeurs : ces derniers auraient dû documenter cette limitation, présente en raison de problématiques de performance.

🐛 Chez Ariane, les exceptions ne sont pas utilisées, sauf pour rapporter une erreur matérielle par définition aléatoire. Elles ne sont donc pas gérées, sauf pour produire un rapport de plantage. Les développeurs doivent écrire un code qui n'en lance pas. Ceux-ci n'avaient pas anticipé que le langage Ada en émet en cas de dépassement d'entier. C'est cette conjonction qui provoqua le plantage.

📍 Le clou du spectacle ? Le code fautif ne sert pas sur Ariane 5, il a été conservé d'Ariane 4 afin de ne pas avoir à retester les centrales inertielles. Les développeurs sont-ils coupables ? Méritent-ils d'avoir le nez et les mains coupés ? Mon avis en commentaire.

SOURCE

Lyons, J. L. and Yvan Choquer. Ariane 5 : Flight 501 Failure Report By The Inquiry Board Paris, 19 July 1996.

---- Avis

Pour moi, l'erreur principale a été de ne pas tester les centrales inertielles sur Ariane 5 avant le vol inaugural. Cependant, je ne dédouane pas totalement les développeurs : Une limitation technique comme une conversion non-protégée aurait dû être documentée. Si elle l'avait été, cela aurait mis la puce à l'oreille des ingénieurs lors de la décision de qualifier le composant pour Ariane 5 sans tests. A mon avis, les responsabilités sont partagées à 75/25 entre ingénieurs et développeurs.