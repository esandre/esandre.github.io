---
title: "Toward a Catalogue of Architectural Bad Smells"
layout: post
category: 'veille'
tags: smells architecture
lang: french
ref: toward-a-catalogue-of-architectural-bad-smells
doi: 10.1007/978-3-642-02351-4\_10
---

🦨 Existe-t-il des « odeurs du code » au niveau architectural ? 4 chercheurs californiens proposent une première liste, qui ne sera validée qu’à la condition de les relier à des anti-patterns architecturaux connus.

👉 Connector Envy : Un Composant réalise des opérations normalement propres à un connecteur (Conversion, Coordination, Communication, Facilitation).

👉 Scattered Parasitic Functionality : Plusieurs composants sont chargées de la même fonctionnalité haut-niveau. Il s’agit souvent d’une manifestation d’un Crosscutting Concern.

👉 Ambiguous Interfaces : Les interfaces ne sont pas explicites, c’est à dire qu’un composant communique avec un autre en utilisant des canaux génériques, sans avoir typé les échanges.

👉 Extraneous Adjacent Connector : Il existe plus d’un connecteur reliant deux composants entre eux. Par exemple un appel direct et un bus.

SOURCE

Garcia, J., Popescu, D., Edwards, G., Medvidovic, N. (2009). Toward a Catalogue of Architectural Bad Smells. In: Mirandola, R., Gorton, I., Hofmeister, C. (eds) Architectures for Adaptive Software Systems. QoSA 2009. Lecture Notes in Computer Science, vol 5581. Springer, Berlin, Heidelberg. DOI:10.1007/978-3-642-02351-4\_10