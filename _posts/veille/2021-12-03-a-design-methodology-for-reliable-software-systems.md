---
title: "A design methodology for reliable software systems"
layout: post
category: 'veille'
tags: architecture codesmithing
lang: french
ref: a-design-methodology-for-reliable-software-systems
doi: 10.1145/1479992.1480018
---

👵 Encore un papier de Barbara Liskov. J’ai déjà parlé d’elle dans un post précédent (lien à la fin). Dans ce papier de 1972 extrêmement actuel, elle nous explique comment produire des logiciels fiables, car testés, donc testables. Le raisonnement est long, mais rémunérateur pour qui le suit jusqu’au bout.

🐛 Elle constate d’abord que le débogage intensif n’a jamais rien résolu. Il faut des tests automatisés couvrant l’ensemble des cas utiles.

🧮 Elle ajoute qu’il serait trop complexe d’obtenir des preuves formelles qu’un logiciel complexe fonctionne, à cause du nombre trop grand d’états. Des preuves informelles peuvent suffire à condition de structurer le programmes correctement, afin qu’ils soient le plus testables et prévisibles possibles.

✔️ La testabilité est donc, pour Barbara Liskov, une question de design.

✂️ L’idée de découper le programme en modules est bonne, mais insuffisante. Un découpage bancal ajoute plus de complexité qu’il n’en masque.

2️⃣ Elle donne deux règles, tirées des travaux de Dijkstra et Parnas, déjà évoqués ici :

👉 S’appuyer sur le principes des machines virtuelles de Parnas, où chaque niveau d’abstraction s’appuie sur celui immédiatement en dessous pour réaliser des oéprations plus complexes et proches du métier.

👉 Faire de la programmation structurée, sans goto donc. L’abolition du goto qui est évidente pour nous en 2021 était encore une bataille rangée en 1972.

🔪 La combinaison de ces deux règles permet une indépendance des modules par le découplage.

✨ On obtient ainsi un programme qu’il est possible de tester comme suit :

👉 Chaque module est individuellement testé par un ensemble de tests X.

👉 Chaque assemblage de modules complet est testé par un ensemble de tests Y.

➕ Grâce au design qu’elle recommande, le nombre de cas de tests nécessaires n’est pas X\*Y, mais bien X+Y pour atteindre une couverture satisfaisante, ce qui est à la portée des développeurs.

SOURCE

Liskov, Barbara. “A design methodology for reliable software systems.” AFIPS ’72 (Fall, part I) (1972). DOI: 10.1145/1479992.1480018