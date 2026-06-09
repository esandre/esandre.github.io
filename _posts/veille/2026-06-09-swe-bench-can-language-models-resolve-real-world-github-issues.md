---
title: "SWE-bench: Can Language Models Resolve Real-World GitHub Issues?"
layout: post
category: 'veille'
tags: methods
lang: french
ref: swe-bench-can-language-models-resolve-real-world-github-issues
doi: 10.48550/arXiv.2310.06770
link: https://arxiv.org/abs/2310.06770
---

🧪 Les LLM les plus avancés pourraient-elles résoudre des issues sur GitHub, en remplacement des contributeurs ? Avant de vous présenter les résultats obtenus par des chercheurs de Princeton, parlons de la manière dont ils ont construit un benchmark pertinent.

🧰 Les chercheurs ont choisi des projets Python populaires, ce qui introduit déjà un biais de sélection. Les PR tendent à être bien plus claires et complètes que sur des repos plus petits et obscurs. L'ensemble des PR de ces repos sont scannées et filtrées pour ne retenir que celles dont la solution acceptée contient de nouveaux tests.

🧷 Les tests de la solution sont extraits, ils serviront à valider le travail du LLM. LLama, ChatGPT 3.5 et 4 et Claude 2 sont comparés sur cette tâche.

📉 Les résultats sont décevants : le meilleur modèle, Claude 2, ne parvient pas à dépasser les 1.97% d'issues résolues correctement. Une réplication ultérieure avec Claude 3 Opus obtient 3.79%.

🖼️ Une partie de l'explication est contextuelle : beaucoup d'issues comportent des images, que l'outil de benchmark ne parvient pas à faire lire au modèle. Ce n'est que 2% des issues.

🧵 La taille du contexte des LLM est également une barrière, sur des gros repos, les modèles de l'époque étaient bien incapables de localiser correctement le code problématique. En ne leur donnant que les fichiers édités par la véritable P.R, le score de résolution passe à 5.93% sur Claude 2.

🛂 Même en prenant en compte ces facteurs, le score reste faible, d'autant que la résolution d'une issue engage le contributeur : sans une fiabilité proche de la perfection, utiliser un LLM ne peut servir qu'à débroussailler un problème, la validation manuelle reste toujours nécessaire.

SOURCE

Jimenez, Carlos E., et al. “SWE-bench: Can Language Models Resolve Real-World GitHub Issues?” arXiv, 2024, DOI:10.48550/arXiv.2310.06770