---
title: "Self-collaboration Code Generation via ChatGPT"
layout: post
category: 'veille'
tags: methods
lang: french
ref: self-collaboration-code-generation-via-chatgpt
doi: 10.48550/arXiv.2304.07590
link: https://arxiv.org/pdf/2304.07590
---

🤖 ChatGPT est à la mode, selon ses partisans capables de changer l'humanité. Revenons sur terre avec un papier proposant de générer du code à l'aide de 3 instances ChatGPT 3.5, promptées pour occuper 3 rôles classiques, bien que dépassés, de la production de logiciels : analyste, codeur et testeur.
 
🔮 Les auteurs y font collaborer 3 instances du célèbre modèle de langage afin de générer du code, avec de meilleurs résultats que les modèles génératifs les plus récents, meilleurs même que ChatGPT 4 pris seul. Est-ce l'avenir du développement ? Pas vraiment si l'on analyse le papier.

🧮 Afin d'évaluer le modèle, les auteurs comparent ses résultats à des catalogues de problèmes algorithmiques. L'enoncé est donné au ChatGPT-analyste, qui collabore avec ses deux collègues. La solution est comparée au corrigé. Il s'agit donc d'épreuves d'algorithmique, non de développement de logiciels, qui dépasse largement ce seul travail.

📝 L'expérimentation a deux variantes : dans la première le modèle reçoit seulement une description du problème en langage naturel. Dans la seconde, la signature de la méthode attendue et les tests unitaires lui sont fournis. Hélas, il est difficile de savoir à quelle variante les résultats présentés dans le papier sont attribuables.

🧠 De l'aveu même des auteurs, ce modèle n'offre pas de résultats satisfaisants à des niveaux d'abstraction supérieurs à la fonction. Or il s'agit de la majorité de la plus-value d'un développeur. Cependant ce papier offre une piste sérieuse à une hypothèse personnelle : les outils capables de générer un code minimal passant un test du rouge au vert sont proches, accélérant le cycle TDD. Le développeur pourra alors se concentrer sur les étapes où son cerveau est le plus pertinent : le refactoring et l'écriture dudit test.

SOURCE

Dong, Yihong, Xue Jiang, Zhi Jin and Ge Li. “Self-collaboration Code Generation via ChatGPT.” ArXiv abs/2304.07590 (2023), DOI: 10.48550/arXiv.2304.07590