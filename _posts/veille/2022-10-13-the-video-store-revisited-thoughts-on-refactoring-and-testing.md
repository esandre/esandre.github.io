---
title: "The Video Store Revisited – Thoughts on Refactoring and Testing"
layout: post
category: 'veille'
tags: refactoring testing laws
lang: french
ref: the-video-store-revisited-thoughts-on-refactoring-and-testing
---

🪙 La règle d'or du refactoring est l'interdiction d'éditer à la fois le code et à la fois les tests. Soit on refactore le code, et les tests garantissent de n'avoir rien cassé lors du processus. Soit on refactore les tests à code égal. Cette théorie est belle, mais irréaliste.

💣 Arie van Deursen et Leon Moonen nous expliquent que certains refactorings changent une interface de manière non rétrocompatible. Il est donc rigoureusement impossible de ne pas éditer le code ET les tests en les exécutant.

🧰 Ces refactorings, qu'ils appellent "Type E", comptent hélas parmi les plus utiles de notre outillage : Extract Subclass, Inline Method, Replace Error Code with Exception et bien d'autres.

🌐 Comment s'en sortir ? Les auteurs ne le précisent pas. Pour ma part, je recommande de tester son code le moins unitairement et le plus fonctionnellement possible pour laisser le maximum de liberté de mouvement aux interfaces. Utiliser son IDE pour effectuer les refactorings réduit le risque d'erreur mais ne l'annule hélas pas.

SOURCE

Deursen, Arie van and Leon Moonen. “The Video Store Revisited – Thoughts on Refactoring and Testing.” (2002).