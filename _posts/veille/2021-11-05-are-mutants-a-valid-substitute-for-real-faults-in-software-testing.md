---
title: "Are mutants a valid substitute for real faults in software testing"
layout: post
category: 'veille'
tags: testing
lang: french
ref: are-mutants-a-valid-substitute-for-real-faults-in-software-testing
dois: 10.1109/ICSTW.2009.30 10.1145/2635868.2635929
---

👾 Les indicateurs classiques de couverture du code ne sont pas corrélés à l’efficacité des tests\*. En revanche, le score de mutation l’est significativement, pour un effort de tests moindre. Pourtant, malgré des outils efficaces, la mutation n’est pas une pratique courante en développement.  
  
🔧 Ils se nomment Stryker en .NET, PIT ou Jumble en Java, mais tous les grands langages possèdent un outil de mutation simple d’utilisation. Les CPU modernes ainsi que les langages intermédiaires (MS IL, Bytecode) rendent ces outils suffisamment rapides pour les faire tourner avant chaque commit en mode partiel, et à chaque intégration en mode complet. Pourtant ils demeurent largement méconnus des développeurs.  
  
🪄 Il ne s’agit pas d’une technique parfaite (No Silver Bullet, rappelez-vous). Ils ne détectent que les bugs issus du code, pas les problèmes d’algorithmique et les effets de bord complexes, mais c’est déjà énorme vu le très faible investissement qu’ils représentent.  
  
💻 Intégrés dans un IDE ou dans une plateforme de CI, ils dévoilent tout leur potentiel et sont le complément parfait de TDD. Essayez, vous serez rapidement conquis !  
  
\* Voir le post d’il y a 6 jours : [Coverage is not strongly correlated with test suite effectiveness]({% link _posts/veille/2021-11-22-coverage-is-not-strongly-correlated-with-test-suite-effectiveness.md %})

SOURCES  
  
N. Li, U. Praphamontripong and J. Offutt, « An Experimental Comparison of Four Unit Test Criteria: Mutation, Edge-Pair, All-Uses and Prime Path Coverage, » 2009 International Conference on Software Testing, Verification, and Validation Workshops, 2009, pp. 220-229, doi: 10.1109/ICSTW.2009.30.  
  
René Just, Darioush Jalali, Laura Inozemtseva, Michael D. Ernst, Reid Holmes, and Gordon Fraser. 2014. Are mutants a valid substitute for real faults in software testing? In Proceedings of the 22nd ACM SIGSOFT International Symposium on Foundations of Software Engineering (FSE 2014). Association for Computing Machinery, New York, NY, USA, 654–665. DOI:10.1145/2635868.2635929