---
title: "The Impact of using a Contract-Driven, Test-Interceptor based Software Development Approach"
layout: post
category: 'veille'
tags: codesmithing testing
lang: french
ref: the-impact-of-using-a-contract-driven-test-interceptor-based-software-development-approach
doi: 10.5121/csit.2022.120704
link: https://www.researchgate.net/publication/360165231_The_Impact_of_using_a_Contract-Driven_Test-Interceptor_based_Software_Development_Approach
---

📃 La programmation par contrats est impopulaire, malgré ses preuves d'efficacité. Pour la rendre sexy, des chercheurs ont envisagé d'utiliser les contrats comme moyen de générer des tests avant le code, comme alternative à Behavior-Driven-Design. Ils ont évidemment appelé leur découverte Contract Driven Design selon la coutume.

🚧 Des intercepteurs sont utilisés afin de vérifier que les pré-conditions, les post-conditions et les invariants sont respectés sur le composant, dont seule l'interface est visible. Le dépôt git n'étant plus accessible, je n'ai pas pu voir en détail comment ces intercepteurs sont appelés par le moteur de tests, mais l'idée ressemble grosso modo au Property-Based Testing, apparu en 1997 dans la littérature et vers 2015 chez les praticiens.

🤔 PBT a l'avantage de ne pas encombrer le code avec les annotations contactuelles, qui doivent être maintenues et bloquent le refactoring. Ces annotations appartiennent plus naturellement au monde des tests qu'au code. Le second inconvénient, pour qui veut concurrencer BDD, est l'opacité des contrats pour le client, alors que l'intérêt de BDD est justement de pouvoir dialoguer avec lui sur un terrain commun. Enfin, l'expérience contenue dans le papier est très faible, pour ne pas dire qu'elle ne prouve rien.

SOURCE

Posthuma, Justus & Solms, Fritz & Watson, Bruce. (2022). The Impact of using a Contract-Driven, Test-Interceptor based Software Development Approach. 39-58. DOI:10.5121/csit.2022.120704.