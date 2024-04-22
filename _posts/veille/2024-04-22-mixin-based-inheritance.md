---
title: "Mixin-Based Inheritance"
layout: post
category: 'veille'
tags: langages
lang: french
ref: mixin-based-inheritance
doi: 10.1145/97945.97982
link: https://dl.acm.org/doi/pdf/10.1145/97946.97982
---

🍨 Les mixins sont un moyen surprenant d'ajouter des fonctionnalités à une classe, sans en hériter et sans la modifier. La technique est longtemps restée du domaine du "hack", tant en LISP, d'où elle tire son nom, que sur des langages plus récents. 

🪄 Un mixin en LISP est une classe abstraite, dont les méthodes invoquent un parent que le mixin ne possède pas. La magie opère lorsqu'une classe tierce hérite à la fois du mixin et d'un parent compatible avec celui-ci. La linéarisation des parents, un mécanisme propre à Lisp, "insère" le mixin entre la classe concrète et son parent dans la relation d'héritage.

💡 Le papier va plus loin, en montrant que les mixins sont un mécanisme bien plus universel que la manière dont les langages orientés objet gèrent l'héritage. Les chercheurs proposent donc d'envisager l'héritage comme un usage particulier des mixins. L'idée n'a pas pris, mais le regain de notoriété des mixins dans les années 2000 a permis des implémentations plus propres, comme les méthodes d'extension de C#, les inclusions en Ruby ou l'héritage de Python. Les traits modernes héritent directement des mixins.

SOURCE

Bracha, Gilad and William R. Cook. “Mixin-based inheritance.” OOPSLA/ECOOP '90 (1990). DOI:10.1145/97946.97982