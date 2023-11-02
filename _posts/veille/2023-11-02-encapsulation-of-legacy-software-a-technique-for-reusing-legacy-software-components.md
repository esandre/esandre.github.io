---
title: "Encapsulation of legacy software: A technique for reusing legacy software components"
layout: post
category: 'veille'
tags: patterns architecture
lang: french
ref: encapsulation-of-legacy-software-a-technique-for-reusing-legacy-software-components
doi: 10.1023/A:1018989111417
link: https://www.researchgate.net/profile/Harry-Sneed-2/publication/220300651_Encapsulation_of_legacy_software_A_technique_for_reusing_legacy_software_components/links/549905ea0cf2eeefc30fa0f3/Encapsulation-of-legacy-software-A-technique-for-reusing-legacy-software-components.pdf?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIn19
---

🏚️ Parmi les composants obsolètes*, les plus difficiles à gérer sont ceux dont la technologie sous-jacente est dépréciée, voire abandonnée.

📦 Faut-il reprendre ou refaire de tels composants ? La question n'admet aucune réponse générale, trop de paramètres sont contextuels. Dans le cas où l'on choisit de reprendre, deux options s'offrent à nous : encapsuler ou adapter. Plus exactement, il s'agit d'un continuum, car l'encapsulation parfaite, celle qui ne requiert aucune adaptation, n'existe souvent pas.

🧑‍⚕️ L'encapsulation peut s'effectuer à plusieurs niveaux. Dans le plus grossier, le programme est lancé avec des entrées forgées, ses sorties sont converties dans le format du nouveau système. Dans le plus fin, le code du composant obsolète est modifié afin d'accepter les entrées telles que le requiert le nouveau sytème. Ce dernier est bien plus chronophage que le premier niveau.

⌛ La technologie était déjà mûre en 2000 quand ce papier a été écrit. Encapsuler est bien moins coûteux qu'un redéveloppement, mais au prix d'une fuite en avant. Maintenir le composant obsolète sous cloche sera de plus en plus difficile avec le temps. Ca n'est jamais une solution définitive, mais un moyen d'acheter du temps, afin de refaire le composant ou de modifier le besoin qui en est à l'origine.

\* L'auteur utilise le terme de Legacy, impropre ici.

SOURCE

Sneed, H.M. Encapsulation of legacy software: A technique for reusing legacy software components. Annals of Software Engineering 9, 293–313 (2000). DOI:10.1023/A:1018989111417
