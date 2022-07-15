---
title: "Improving evolvability through refactoring"
layout: post
category: 'veille'
tags: refactoring smells
lang: french
ref: improving-evolvability-through-refactoring
doi: 10.1145/1082983.1083155
---

🦨 Les odeurs du code sont passées dans la jargon courant des développeurs. A tel point qu’elles ont eu des déclinaisons. Les change smells par exemple, sont des odeurs que l’on ne remarque qu’en analysant l’historique des commits.

🕵️ Les chercheurs nous proposent le « Man In The Middle », où une même classe est modifiée sur la majorité des commits, même s’ils n’ont rien à voir fonctionnellement.

🗃️ On retrouve également le « Data Container », qui se remarque paire la présence d’un binôme de classes toujours modifiées ensembles, l’une portant des données, l’autre des comportements.

🔧 Les chercheurs n’ont pas établi un protocole vraiment solide pour vérifier la solidité de leur proposition, mais l’idée mérite d’être méditée par les développeurs et les éditeurs d’outils.

SOURCE

Jacek Ratzinger, Michael Fischer, and Harald Gall. 2005. Improving evolvability through refactoring. SIGSOFT Softw. Eng. Notes 30, 4 (July 2005), 1–5. DOI:10.1145/1082983.1083155