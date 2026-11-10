---
title: "Microservices: yesterday, today, and tomorrow"
layout: post
category: 'veille'
tags: architecture
lang: french
ref: microservices-yesterday-today-tomorrow
doi: 10.48550/arXiv.1606.04036
link: https://arxiv.org/abs/1606.04036
---

🤖 L’idole du moment est l’IA. Il est redevenu possible de critiquer les microservices. Le papier du jour a 10 ans d’âge et a largement participé à cette hype.

🧓 L’introduction commence par déprécier injustement les monolithes, avec une téléologie discutable et de nombreux hommes de paille : un monolithe n’est jamais modulaire ; Le monolithe est l’ancêtre du microservice, créé dans un âge sombre où l’on ne comprenait pas encore tout. C’est d’autant plus dommage que les auteurs n’ignoraient pas l’abondante littérature sur l’architecture logicielle des années 1990.

🧑‍🌾 L’article vient ensuite attribuer aux microservices des propriétés désirables dont ils n’ont aucune responsabilité. Un exemple ? La possibilité de montées en version graduelles, sans downtime. Ce sont les reverse proxies et les progrès du déploiement continu, pas les microservices, qui permettent cela. Les auteurs le reconnaissent d’ailleurs en attachant cette propriété aux architectures SOA, vues comme un simple ancêtre imparfait des microservices.

🎯 À partir de la partie 3, le papier devient remarquablement lucide, sourcé et honnête. Il peut servir de référence sur les avantages et inconvénients de ce style architectural. Seule la partie sur les performances a pris de l’âge : l’outillage de 2017 était primitif.

SOURCE

Dragoni, Nicola, Saverio Giallorenzo, Alberto Lluch Lafuente, Manuel Mazzara, Fabrizio Montesi, Ruslan Mustafin, and Larisa Safina. “Microservices: Yesterday, Today, and Tomorrow.” arXiv:1606.04036, 2017. DOI:10.48550/arXiv.1606.04036
