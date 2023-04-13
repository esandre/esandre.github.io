---
title: "Locating user functionality in old code"
layout: post
category: 'veille'
tags: codesmithing testing
lang: french
ref: locating-user-functionality-in-old-code
doi: 10.1109/ICSM.1992.242542
---

🏚️ Outre leurs nombreux bienfaits, les tests permettent aussi de localiser les fragments de code legacy impliqués dans une fonctionnalité donnée. Le principe est le même que les marqueurs en médecine nucléaire : mettez sous surveillance l'ensemble du code, en journalisant tous les appels à toutes les méthodes. Les outils modernes de code coverage permettent un suivi ligne à ligne. Une fois ce harnais posé, écrivez un jeu de tests utilisant la fonctionnalité à éditer. 

💡 L'ensemble des méthodes appelées par votre test contiennent potentiellement des fragments de la fonctionnalité à éditer. Ce résultat reste à raffiner, mais la recherche montre un gain de temps potentiel par rapport à une recherche à la main.

SOURCE

Wilde, Norman, Juan Ángel Gómez, Thomas A. Gust and Don Strasburg. “Locating user functionality in old code.” Proceedings Conference on Software Maintenance 1992 (1992): 200-205. DOI: 10.1109/ICSM.1992.242542