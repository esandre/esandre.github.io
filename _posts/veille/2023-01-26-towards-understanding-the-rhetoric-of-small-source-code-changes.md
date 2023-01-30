---
title: "Toward understanding the rhetoric of small source code changes"
layout: post
category: 'veille'
tags: quality epistemology
lang: french
ref: towards-understanding-the-rhetoric-of-small-source-code-changes
doi: 10.1109/TSE.2005.74
---

🤫 Des chercheurs ont étudié statistiquement les changements d'une seule ligne de code, bref les "ça va, c'est une petite modification" que nous connaissons si bien. Accrochez-vous les chiffres sont contre-intuitifs.

♻️ 95% du code sera édité au moins une fois tout au long du projet. Aucun code ne doit être réalisé avec pour condition de ne jamais changer.

📝 95% des changements au cours d'un projet font moins de 50 lignes. Les petits changements sont plus fréquents que vous ne l'envisagez lors de la première release.

💣 Un changement d'une seule ligne n'a que 4% de chances d'introduire un défaut. C'est donc la répétition qui fait le poison en la matière. Le chiffre monte à 40% si le changement vient résoudre un bug existant. Le Defect Testing est donc bien votre ami.

✂️ Il n'y a aucune preuve qu'une suppression de moins de 10 lignes de code puisse engendrer un bug. La leçon la plus importante est donc de prendre les études statistiques avec des pincettes.

SOURCE

R. Purushothaman and D. E. Perry, "Toward understanding the rhetoric of small source code changes," in IEEE Transactions on Software Engineering, vol. 31, no. 6, pp. 511-526, June 2005, doi:10.1109/TSE.2005.74.