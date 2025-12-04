---
title: "Chaos Engineering"
layout: post
category: 'veille'
tags: testing
lang: french
ref: chaos-engineering
doi: 10.48550/arXiv.1702.05843
link: https://arxiv.org/pdf/1702.05843
---

🐒 Si vous voulez prouver qu'un système distribué est tolérant aux pannes, vous devrez essayer de le mettre en panne, en production. Que se passe-t-il si le reverse proxy tombe ? Si une région AWS entière est indisponible ? Les humains ont tendance à esquiver inconsciemment les véritables scénarios problématiques, il faut donc permettre à un robot, le Chaos Monkey, de provoquer des pannes aléatoires en injectant des données erronnées, en ajoutant de la latence ou en coupant des machines. Complétement idiot ? Non, cette technique que l'on appelle Chaos Engineering est utilisée par toutes les organisations qui se préparent sérieusement à l'inattendu. Shit happens.

📝 La manière de mener de telles campagnes de test est assez cadrée. Le papier qui en parle est assez court, je ne ferai que de le paraphraser en le résumant.

SOURCE

A. Basiri et al., "Chaos Engineering," in IEEE Software, vol. 33, no. 3, pp. 35-41, May-June 2016, DOI:10.1109/MS.2016.60.