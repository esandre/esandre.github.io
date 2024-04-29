---
title: "Using Program Slicing in Software Maintenance"
layout: post
category: 'veille'
tags: testing
lang: french
ref: using-program-slicing-in-software-maintenance
doi: 10.1109/32.83912
link: https://www.researchgate.net/publication/3187373_Using_Program_Slicing_In_Software_Maintenance
---

👎 Pour éviter les régressions, nous utilisons habituellement les tests. Même lorsqu'ils existent et sont de qualité, il s'agit rarement d'une assurance tous-risques. D'autres techniques peuvent les compléter pour s'assurer de ne rien casser. L'une d'elle est le slicing.

🍕 Une slice est une tranche de programme elle-même exécutable. Prenez un programme. Faites-le tourner avec des valeurs particulières jusqu'à un point d'arrêt. Supprimez tout le code qui n'a pas eu d'influence sur l'exécution. Vous avez une slice.

🧑‍🔬 Déjà utilisées en débogage, pour restreindre l'endroit du code où chercher les problèmes, les slices peuvent aussi être utilisées pour s'assurer de ne pas introduire de régressions lors d'une modification. La technique se fait en construisant 2 slices liées mathématiquement : la décomposition et son complément. La logique de construction de ces 2 slices assez complexe et plutôt réservée aux développeurs d'outils.

✅ Ce binôme de slices permet de prédire si une insertion ou une suppression de code aura des effets de bord. Le développeur effectue ses modifications, puis regénère à nouveau les deux slices. Si les compléments sont identiques avant et après les modifications, il est mathématiquement sûr qu'aucune régression n'a été introduite. Attention cependant : cela n'indique en rien que le changement lui-même est correct.

🔬 J'ignore si ce papier a eu une postérité, cela fera l'objet d'une recherche à part, tant l'idée a l'air novatrice.

SOURCE

Gallagher, Keith & Lyle, James. (1991). Using Program Slicing In Software Maintenance. Software Engineering, IEEE Transactions on. 17. 751-761. DOI:10.1109/32.83912