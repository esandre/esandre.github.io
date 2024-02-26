---
title: "Program Comprehension During Software Maintenance and Evolution"
layout: post
category: 'veille'
tags: psychology
lang: french
ref: program-comprehension-during-software-maintenance-and-evolution
doi: 10.1109/2.402076
link: https://www.researchgate.net/publication/2954431_Program_comprehension_during_software_maintenance_and_evolution
---

🧠 Avec l'expérience, un développeur acquiert des connaissances générales sur son métier, mais aussi des connaissances spécifiques à divers projets sur lesquels il a oeuvré. Ces connaissances spécifiques prennent la forme d'un modèle mental du code, constitué de chunks. Cette construction, déjà abordée dans cette veille désigne un "paquet" compressé d'informations, pouvant contenir des connaissances très variées, mais aussi des pointeurs vers d'autres chunks.

📜 Le modèle mental contient des élements statiques et dynamiques. Parmi les élements statiques, nous trouvons la connaissance textuelle, stockée dans la mémoire à long terme et responsable de notre connaissance instructionnelle du code (ce que font chacune des instructions). Nous y trouvons également les plans, qui désignent nos attendus lorsque nous interprétons une structure. Un algorithme que nous connaissons ou un pattern seront stockés dans notre cerveau sous cette forme.

🪡 Nous mobilisons des éléments statiques lorsque nous tentons de comprendre un code, afin de générer des éléments dynamiques propres à celui-ci. Deux mécanismes sont à l'oeuvre, le chunking, grâce auquel nous créons des chunks de plus haut niveau à partir de connaissances statiques de plus bas niveau et le cross-referencing, qui nous permet de lier plusieurs éléments de niveaux d'abstraction différents dans une relation de tout à parties.

❇️ Si nous reconnaissons un pattern derrière un bloc de code, c'est grâce à des balises, des indices laissés par le rédacteur du code. Par conséquent, un algorithme valide, mais de forme inhabituelle sera dur à comprendre y compris pour un expert, d'où l'intérêt des conventions. L'expérience amène plus de souplesse mentale dans ce processus et une plus grande vélocité.

🥼 La suite du papier décrit plusieurs modèles cognitifs proposés par divers chercheurs, avant de les confronter. Cette analyse intéressera surtout les chercheurs en psychologie du développement. On peut cependant tirer quelques enseignements : D'une part, on sait que la connaissance n'est pas unidirectionnelle du métier vers le code. Le code rétroagit et nous apprend des choses sur le métier. D'autre part, la compréhension du code est un mélange de bottom-up et de top-down. Le développeur effectue de nombreux allers-retour entre les niveau d'abstraction afin de comprendre.


SOURCE

Anneliese von Mayrhauser and A. Marie Vans. 1995. Program Comprehension During Software Maintenance and Evolution. Computer 28, 8 (August 1995), 44–55. DOI:10.1109/2.402076