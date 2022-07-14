---
title: "Bad Smells in Software – a Taxonomy"
layout: post
category: 'veille'
tags: smells
lang: french
ref: bad-smells-in-software-a-taxonomy
---

🦨 Il est temps de ranger les odeurs du code ! Perdu par leur trop grand nombre et par leur manque de formalisation, le chercheur Mika Mäntylä s’est attelé à les classifier dans sa thèse qui figure au rang des classiques. Son classement a même été repris par des sites grand public comme Sourcemaking ou Refactoring Guru.

💩 Les Bloaters désignent les objets qui sont devenus trop gros pour pouvoir être appréhendés par notre esprit. Méthodes longues, God Classes, mais également plus étonnant, Primitive Obsession et Data Clumps.

📦 Tout ce qui contrevient aux principes de l’orienté-objet est rangé dans la catégorie Object Orientation Abusers. Les switchs, champs temporaires, refus d’héritages y figurent, avec les duplications d’interfaces.

⛓️ Les odeurs ralentissant ou entravant le changement sont nommées Change Preventers.

🗿 Tout ce qui est inutile, mort ou contrevenant au principe YAGNI est un Dispensable.

🪢 Le couple Message Chains/Middle Man, est appelé Encapsulators.

🖇️ Les Couplers, eux, créent du couplage superflu, donc néfaste, entre les classes.

🪄 Cette classification a des défauts dont était déjà conscient Mäntylä : catégories pour 2 odeurs, odeurs ne rentrant dans aucune. Il s’agit d’un outil perfectible, mais pas dépassé depuis 20 ans à ma connaissance.

SOURCE

Mäntylä, Mika & Vanhanen, Jari. (2003). Bad Smells in Software – a Taxonomy and an Empirical Study.