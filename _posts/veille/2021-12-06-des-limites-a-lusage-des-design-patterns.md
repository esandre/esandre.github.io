---
title: "Des limites à l'usage des design patterns"
layout: post
category: 'veille'
tags: patterns
lang: french
ref: des-limites-a-lusage-des-design-patterns
dois: 10.1109/TSE.2004.99 10.1049/iet-sen.2008.0105
---

🪄 Après l’enthousiasme des années 1990, les années 2000 furent une période d’intense remise en question des design patterns. Loin d’être la panacée ils se révélaient un boulet pour certains usages et la plupart des bénéfices que l’on en espérait étaient absents. Quoi de plus normal, dans une discipline ayant « No Silver Bullet » pour première loi.

🇳🇴 En 2004, le norvégien Marek Vokac énonce que les patterns seuls n’ont aucun pouvoir face à la complexité intrinsèque de certaines parties du code.

🇮🇹 En 2009, 3 italiens découvrent que la combinaison de certains patterns avec la présence de crosscutting concerns (logs, sécurité, cache, etc.) augmente le nombre de défauts, car ces patterns ont tendance à éparpiller la responsabilité.

➕ Aucun de ces chercheurs n’a remis en question le bénéfice net de l’usage de patterns. Tous appellent en revanche à la prudence : ils ne conviennent simplement pas à toutes les situations. Ce serait trop facile, sinon. Notre métier est immensément complexe. C’est une bonne nouvelle pour son avenir.

SOURCES

M. Vokac, « Defect frequency and design patterns: an empirical study of industrial code, » in IEEE Transactions on Software Engineering, vol. 30, no. 12, pp. 904-917, Dec. 2004, doi: 10.1109/TSE.2004.99.

Aversano, L. &amp; Cerulo, Luigi &amp; Di Penta, Massimiliano. (2009). Relationship between design patterns defects and crosscutting concern scattering degree: An empirical study. Software, IET. 3. 395 – 409. 10.1049/iet-sen.2008.0105.

Brooks, Frederick P. (1986). « No Silver Bullet—Essence and Accident in Software Engineering ». Proceedings of the IFIP Tenth World Computing Conference: 1069–1076.