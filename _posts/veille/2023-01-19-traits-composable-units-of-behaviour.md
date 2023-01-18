---
title: "Traits : Composable Units of Behaviour"
layout: post
category: 'veille'
tags: langages
lang: french
ref: traits-composable-units-of-behaviour
doi: 10.1007/978-3-540-45070-2_12
---

🏹 L'héritage simple est trop limité. L'héritage multiple est trop dangereux. Les mixins sont maladroits. Si l'avenir était aux Traits ? Un trait est un ensemble de méthodes pures (au sens où elles ne mutent pas d'attributs) servant de blocs préfabriqués pour constituer des classes.

🧩 Un Trait peut spécifier des corps de méthodes, tant qu'elles n'accèdent pas aux données. Les Traits peuvent hériter et donc exiger la présence d'autres traits dans la classe. Un Trait n'a pas à être complet, il peut laisser certaines méthodes sans corps, afin que les classes les définissent.

📝 Plusieurs implémentations sont possibles, certains langages comme PHP adoptent un mot clé séparé, d'autres comme C# préfèrent simplement autoriser les méthodes dans les interfaces.


🧠 Le papier a en outre une définition originale et profonde de ce qu'est une classe, j'en recommande la lecture pour cette raison.

SOURCE

Schärli, Nathanael & Ducasse, Stéphane & Nierstrasz, Oscar & Black, Andrew. (2003). Traits: Composable Units of Behaviour. Proceedings ECOOP 2003. 2743. 248-274. DOI:10.1007/978-3-540-45070-2_12