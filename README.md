# Proposition de changement de programme pour la formation S2I

## Premier semestre

Le premier semestre devrait faire confronter les étudiants aux limites du possible de l'informatique classique, et cela afin qu'ils comprennent la nécessité de l'intelligence artificielle. Nous pensons que cette formation réussie déjà à faire passer ce message. Cependant, concernant ce semestre, le problème majeur est que nous avons l'impression que le programme ne tient pas en compte le fait que la quasi-totalité de ses étudiants sont issus d'une formation en licence informatique. On se retrouve donc à refaire énormément de notions que connaissance de base.

Dans ce qui suit, nous allons discuter les différents modules, et allons essayer de proposer des améliorations.

- **Algorithmique Avancée et Complexité :** Dans ce module, nous pensons que le rythme est très lent. La majorité de ce cours consiste à implémenter des algorithmes très simples comme des algorithmes tri et de calculer leur complexité. Cela étant dit, les étudiants savent déjà faire ça depuis la L2. Ce n'est que vers la fin du module que nous avons un rapide aperçu sur les classes de problèmes : P, NP, etc. qui sont de nouvelles notions pour nous. Ce que nous attendons de ce cours et de voir des techniques d'algorithmique plus complexes et de nous entrainer à les résoudre rapidement, car c'est ce qui est demandé lors des entretiens techniques des entreprises. Aussi, nous aurions aimé nous attarder beaucoup plus sur l'aspect informatique, théorique et mathématique du chapitre des classes de problèmes, ce qui pourrait être très utile pour les étudiants désirant faire de la recherche.

- **Résolution de problèmes :** Niveau contenu, ce module est assez intéressant. Cependant, nous pensons qu'il est primordial d'ajouter un TP afin de pratiquer les algorithmes vu en cours.

- **Compilation :** Comme expliqué précédemment, les étudiants en M1 ont tous eu un module de compilation en licence. Nous refaisons une bonne partie de ce module que nous avons déjà fait en Licence. Même si nous n'avons pas fait la génération de code en Licence. Nous pensons qu'il n'est pas intéressant d'ajouter tout un module juste pour faire la génération de code. Car nous avions déjà une idée de comment il faut faire avant de commencer ce module, ce qui est largement suffisant. C'est pour ça qu'à la place de ce module, nous proposons de le remplacer par un module **Machine Learning** où tous les algorithmes de base du Machine Learning seront expliqués en consacrant le temps nécessaire à l'aspect mathématique. Cela permettrait aussi d'alléger le module de Machine Learning prévu pour le deuxième semestre qui est surchargé.

- **Systèmes d'exploitation :** Ce module introduit de bonnes notions concernant l'implémentation des Systèmes concurrent. Cependant, nous pensons qu'il est inutile d'enseigner à nouveau la gestion de mémoire, etc. car c'est des notions que nous connaissions très à l'issue de la Licence. À la place, nos proposons de renommer ce module en **"Système concurrent et distribués"** et enseigner les notions adéquates. Et pourquoi pas introduire des notions de cloud computing, ce qui pourrait servir les personnes désirant exercer le métier de Data engineering.

- **Modélisation et évaluation des performances des systèmes :** Nous pensons qu'il serait très important de remplacer ce module par "**Statistiques inférentielles**". En effet, la maitrise des statistiques inférentielles est **primordiale** pour exercer le métier de Data scientist. Malheureusement, nous n'avons pas fait de statistiques inférentielles ni en Licence ni en Master. Pour cela, il est important d'y remédier.

- **Architecture et administration de bases de données :**
Les notions enseignées dans ce module sont totalement maitrisées par les étudiants, et particulièrement par les étudiants en ISIL. C'est pour ça que nous proposons de le remplacer par un module **Entrepôt de données**.



## Deuxième semestre

Ce semestre devrait être une introduction à l'intelligence artificielle et aux outils nécessaire à ce dernier.

- **Réseaux de neurones et apprentissage automatique :** Il y a tellement de notions à couvrir durant ce module que c'est impossible de le faire en un semestre. C'est pour cela que nous avons proposé l'introduction du module **Machine Learning** durant le premier semestre. Ce qui nous permet de remplacer ce module par **"Advanced Machine Learning"** où des notions plus avancées seront introduites, comme les architecture de deep learning : CNN, Transformers, etc.

- **Méta-heuristiques et algorithmes évolutionnaires :** Nous pensons que ce module est important. Nous aimerions cependant que l'algorithme **"NEAT"** (Neuroevolution of augmenting topologies) soit introduit. C'est un algorithme de réseaux de neurones basé sur les algorithmes génétique qui a des applications intéressantes et obtient des résultats remarquables. Par ailleurs, au début de ce module, nous refaisons trop de notions que nous avions vu dans le module "Résolution de problème". Il faut que les module soit complémentaire et pas en concurrence, il est important de faire attention à ne pas refaire des notions qu'on a déjà vues dans un autre module.

- **Représentation des connaissances et raisonnement 1 :** Bien que ce module introduise des notions intéressantes, nous pensons qu'il est inutile d'avoir RCR 1 et RCR 2. Nous pensons que RCR 1 suffit largement. Nous proposons de remplacer RCR 1 ou RCR 2 par le module **"Théorie de l'information"** qui introduit des notions très importantes en intelligence artificielle comme l'entropie. En même, cela reste dans la même thématique que RCR.

- **Technologie des agents :** Ce module est assez bien, nous demandons de mettre plus l'accent sur le Reinforcement Learning et le Deep Reinforcement Learning. Et avec un TP plus consistant ou les différents types d’agent enseigné en cours seront mis en pratique au lieu de limiter le TP uniquement aux systèmes experts et multi-agent.

- **Commerce électronique et services web :** Le "e-commerce" n'est qu'un cas spécifique du développement web. Nous proposons de le renommer en **"Web avancé"** où des frameworks modernes comme : **FAST API**, **Django** et **Vue.js** seront enseignés. En effet, les Data scientist doivent être de bons développeurs afin qu'ils puissent présenter et déployer leurs résultats de la meilleure manière possible. Nous demandons que la notion de API REST, soit plus mise en avant au détriment du service web soap. Et une introduction aux micro services serait un plus non négligeable, ainsi que tous les outils nécessaires au développement et au déploiement, comme : git, docker, et Kubernetes, ainsi que toutes les bonnes pratiques de développement. Inutile de perdre une seule minute à   enseigner Axis et J2EE qui sont des outils presque totalement inutilisés. Aussi, Il faudrait enlever le chapitre "Théorie des jeux" car il est déjà enseigné dans le module "Technologie des agents". Encore une fois, il est important à veiller à ce que les modules ne rentrent pas en conflit.

- **Bases de données avancées :** Bon module, nous demandons juste à approfondir la partie Big data du module. Une introduction à la notion de cloud computing qui est très importante en ce moment serait aussi un grand plus.

- **Sécurité informatique :** Module intéressant, cependant, nous demandons à faire moins de cryptographie et de plus nous introduire aux vulnérabilités des applications web et comment les éviter.

## Troisième semestre
Ce semestre devrait être consacré à l'utilisation des connaissances acquises pour des applications spécifiques de l'IA.

- **Vision artificielle** : Très bon module. Pas de remarques particulières.

- **Programmation par contraintes :** Nous pensons que ce module reprend beaucoup de notions du module "résolution de problème" vu en S1. Nous pensons aussi qu'avec les connaissances que nous avions déjà, et avec un peu de recherche, il est vite facile de déduire les algorithmes enseignés dans ce module. Nous pensons qu'il serait davantage intéressant de le remplacer par un module d'actualité comme : **"Internet of Things"**.

- **Recherche d’information :**  Bon module. Néanmoins, nous demandons à des méthodes plus modernes soient enseignées.

- **Data Mining :** Le module est très intéressant, cependant, au lieu de faire du data mining, nous passons la majorité de notre temps à refaire des notions vu dans d'autre module, à savoir ; résolution de problème et machine learning. Ce qui est une perte de temps et nous empêche de nous approfondir dans le Data mining. Nous demandons donc à ce que le module soit consacré au data mining uniquement.

- **Représentation de connaissances et raisonnement 2 :** Comme expliqué précédemment, nous demandons à ce que soit RCR1 ou RCR2 soit remplacé par le module **"Théorie de l'information"**. Par conséquent, remplacer ce module durant le 3 ème semestre par un module de MLOps serait préférable.

- **OCR :** Nous pensons que c'était une grave erreur de remplacer le module **NLP** par OCR. Car OCR n'est qu'une application du module **vision artificielle**.  Nous demandons donc que le module **NLP** soit rétabli au plus vite.


## Remarques générales

- **Pour le module d'anglais**, il est inutile d'enseigner des leçons de grammaire. Nous pensons qu'il serait mieux de remplacer les cours traditionnels par des sessions de discussion en anglais par petits groupes, et que l'examen soit similaire au test **IELTS**.

- **En ce qui concerne TP :** Veuillez SVP arrêter l'utilisation de JAVA, et préféré l'utilisation du langage **PYTHON** et de toutes les librairies qui viennent avec. Une amélioration considérable de l’implication et la qualité des TP a été remarqué cette année par le passage de certain TP de java vers python a été remarqué, il est donc important de généraliser ça pour l’ensemble des modules.

- Il est important que les responsables de spécialité veillent à ce que les modules soient complémentaires et non conflictuels. Car dans l'état actuel du programme, beaucoup de chapitres sont enseignés en double dans des modules différents.

- Nous sommes conscients qu'il est peut-être difficile pour les professeurs de changer le contenu de leur module. Cependant, c'est un effort nécessaire, et nous préférons être introduit aux nouvelles technologies quitte à ce que le cours ne soit pas parfait. L'enseignant pourra le peaufiner au fil des années.

