---
title: "On the effectiveness of unit tests in test-driven development"
layout: post
category: 'veille'
tags: testing
lang: french
ref: on-the-effectiveness-of-unit-tests-in-test-driven-development
doi: 10.1145/3202710.3203153
---

🔥 J’ai trouvé la perle rare : une étude sur TDD qui compare cette méthode à Test-Last ! La plupart ont le biais de comparer TDD vs Pas de tests. Malgré son faible échantillon, elle obtient des résultats positifs : TDD serait plus efficace pour obtenir une couverture acceptable que Test-Last.

👾 Cependant l’étude a un biais : la mesure servant à comparer les deux méthodes est le score de mutation. Or, on sait que celui-ci n’est pas totalement corrélé aux fautes réelles.

🏢 Cette étude va dans le bon sens, mais notre profession manque cruellement d’études de cas sur le long-terme, faute de dialogue entre chercheurs et entreprises. Si vous êtes manager, aidez-les ! Contactez l’université la plus proche pour leur proposer de vous étudier.

SOURCES

René Just, Darioush Jalali, Laura Inozemtseva, Michael D. Ernst, Reid Holmes, and Gordon Fraser. 2014. Are mutants a valid substitute for real faults in software testing? In Proceedings of the 22nd ACM SIGSOFT International Symposium on Foundations of Software Engineering (FSE 2014). Association for Computing Machinery, New York, NY, USA, 654–665.

Tosun, A., Ahmed, M., Turhan, B., &amp; Juristo, N. (2018). On the effectiveness of unit tests in test-driven development. In M. Kuhrmann, R. V. O’Connor, D. Houston, &amp; R. Hebig (Eds.), ICSSP 2018 – May 26-27 – Gothenburg, Sweden: Proceedings of the 2018 International Conference on Software and System Process (pp. 113-122). Association for Computing Machinery (ACM). DOI:10.1145/3202710.3203153