# Proposition de changement de programme pour la formation S2I

## Premier semestre

Le premier semestre devrait faire confronter les étudiants aux limites du possible de l'informatique classique, et cela afin qu'ils comprennent la necessité de l'intelligence artificielle. Nous pensons que cette formation réussi déjà à faire passer ce message. Cependant, concernant ce semestre, nous le problème majeur est que nous avons l'impression que le programme ne tient pas en compte le fait que la quasi totalité de ses étudiants sont issus d'une formation en licence informatique, où ont les prérequis necessaire. On se retrouve donc à refaire énormément de notions que connaissance de base.

Dans ce qui suit, nous allons discuter les différents modules, et allons essayer de proposer des améliorations.

- **Algorithmique Avancée et Complexité :** Dans ce module, nous pensons que le rythme est très lent. La majorité de ce cours consiste à implémenter des algorithmes très simples comme des algorithmes tri et de calculer leur complexité. Cela étant dit, les étudiants savent déjà faire ça depuis la L2. Ce n'est que vers la fin du module que nous avons un rapide aperçu sur les classes de problemes : P, NP, etc. qui sont de nouvelles notions pour nous. Ce que nous attendons de ce cours et de voir des techniques d'algorithmique plus complexes et de nous entrainer à les résoudre rapidement car c'est ce qui est demandé lors des entretiens techniques des entreprises. Et aussi, nous attarder beaucoup plus sur l'aspect informatique théorique et mathématique du chapitre des classes de problemes, ce qui pourrait être très utile pour les étudiants désirant faire de la recherche.

- **Résolution de problèmes :** Niveau contenu, ce module est assez interessant. Cependant, nous pensons qu'il est primordial d'ajouter un TP afin de pratiquer les algorithmes vu en cours.

- **Compilation :** Comme expliqué précedamment, les étudiants en M1 on tous eu un module de compilation un licence. Nous refaisons une bonne partie de ce module que nous avons déjà fait en Licence. Même si nous n'avons pas fait la génération de code en Licence, nous pensons qu'il n'est pas interessant d'ajouter tout un module juste pour faire la génération de code, car nous avions déjà une idée de comment il faut faire avant de commencer ce module, ce qui est largement suffisant. C'est pour ça qu'à la place de ce module, nous proposons de le remplacer par un module **Machine Learning** où tous les algorithmes de base du Machine Learning seront expliqués en consacrant le temps necessaire à l'aspect mathématique. Cela permettrait aussi d'alléger le module de Machine Learning prévu pour le deuxième semestre qui est surchargé.

- **Systèmes d'exploitation :** Ce module introduit de bonne notions concernant l'implémentation des Systèmes concurrent. Cependant, nous pensont qu'il est inutile de ré-enseigner la gestion de mémoire etc. car ce sont des notions que nous connaissions très à l'issus de la Licence. À la place, nos proposons de renommer ce module en **"Système concurrent et distribués"** et enseigner les notions adéquate. Et pourquoi pas introduire des notion de cloud computing, ce qui pourrait servir les personnes désirant exercer le métier de Data engineering.

- **Modélisation et évaluation des performances des systèmes :** Nous pensons qu'il serait très important de remplacer ce module par "**Statistiques inférentielle**". En effet, la maitrise des statistiques inférentielles est **primordial** pour exercer le métier de Data scientist. Malheureusement, nous n'avons pas fait de statistiques inférentielle ni en Licence ni en Master. Pour cela, il est important d'y remédier.

- **Architecture et administration de bases de données :**
Les notions enseignées dans ce module sont totalement maitrisées par les étudiants, et particuliérement par les étudiant en ISIL. C'est pour ça que nous proposons de le remplacer par un module **Entrepôt de données**.



## Deuxième semestre

Ce semestre devrait être une introduction à l'intelligence artificielle et aux outils neceesssaire à ce dernier.

- **Réseaux de neurones et apprentissage automatique :** Il y a tellement de notions à couvrir durant ce module que c'est impossible de le faire ne un semestre. C'est pour cela que nous avons proposer l'introdution du module **Machine Learning** durant le premiere semestre, ce qui nous permet de remplacer ce module par **"Advanced Machine Learning"** où des notions plus avancées seront introduites, comme les architecture de deep learning : CNN, Transformers, etc.

- **Méta-heuristiques et algorithmes évolutionnaires :** Nous pensons que ce module est important. Nous aimerions cependant que l'algorithme **"NEAT"** (Neuroevolution of augmenting topologies) soit introduit. C'est un algorithme de réseaux de neurones basé sur les algorithme génétique qui a des applications intéressante et obtient des résultats remarquables. Par ailleurs, au début de ce module, nosu refaisons trop de notions que nous avions vu dans le module "Résolution de problème" Il faut que les module soit complémentaire et pas en concurrence, il est important de faire attention à ne pas refaire des notions qu'on a déjà vu dans un autre module.

- **Représentation des connaissances et raisonnement 1 :** Bien que ce module introduise des notions interessante, nous pensons qu'il est inutile d'avoir RCR 1 et RCR 2. Nous pensons que RCR 1 suffit largement. Nous proposons de remplacer RCR 1 ou RCR 2 par le module **"Théorie de l'information"** qui introduit des notions très importante en intelligence artificielle comme l'entropie. En même, cela reste dans la même thématique que RCR.

- **Technologie des agents :** Ce module est assez bien, nous demandons de mettre plus l'accent sur le Reinforcement Learning et le Deep Reinforcement Learning.

- **Commerce électronique et services web :** Le "e-commerce" n'est qu'un cas spécifique du developpement web. Nous proposons de le renommer en **"Dev Web"** où des framework modernes comme : **Fast API**, **Django** et **Vue.js** seront enseigné. En effet, les Data scientist doivent être de bons développeur afin qu'ils puissent présenter et déployer leur résultats de la meilleur manière possible. Nous demandons que la notions de API Rest, soit enseigné, ainsi que tous les outils neceesssaire au developpement  et au deploiement, comme : git, docker, et kubernetees ainsi que toutes les bonnes pratiques de developpement. Inutile de perdre une seule minute à   enseigner Axios et J2EE qui sont des outils presque totalement inutilisés. Aussi, Il faudrait enelver le chapitre "Théorie des jeux" car il est déjà enseigné dans le module "Technologie des agents". Encore une fois, il est important à veiller à ce que les modules ne rentrent pas en conflit.

- **Bases de données avancées :** Bon module, nous demandons juste à introduire la notion de cloud computing qui est très importante en ce moment.

- **Sécurité informatique :** Module intéressant, cependant, nous demandons à faire moins de cryptographie et de plus nous introduire aux vulnerabilites des applications web et comment les éviter.

## Troisième Semestre
Ce semestre devrait être consacré à l'utilisation des connaissances acquises pour des applications spécifique de l'IA.

- **Vision artificielle** : Très bon module. Pas de remarques particuliére.

- **Programmation par contraintes :** Nous pensons que ce module reprend beaucoup de notions du module "résolution de problème" vu en S1. Nous pensons aussi qu'avec les connaissances que nous avions déjà, et avec un peu de recherche, il est vite facile de déduire les algorithmes ensigné dans ce module. Nous pensons qu'il serait plus interessant de le remplacer par une module d'actualité comme : **"Internet of Things"**.

- **Recherche d’information :**  Bon module. Cependant, nous demandons à que des méthodes plus modernes soient enseignées.

- **Data Mining :** Le module est très interessant, cependant, au lieu de faire du data mining, nous passons la majorité de notre temps à refaire des notions vu dans d'autre module, à savoir ; résolution de probleme et machine learning. Ce qui est une perte de temps et nous empeche de nous approfondir dans le Data mining. Nous demandons donc à ce que le module soit consacré au data mining uniquement.

- **Représentation de connaissances et raisonnement 2 :** Comme expliqué précedamment, nous demandons à ce que soit RCR1 ou RCR2 soit remplacé par le module **"Théorie de l'information"**.

- **OCR :** Nous pensons que c'était une grave erreur de remplacer le module **NLP** par OCR. Car OCR n'est qu'une application du module **vision artificielle**.  Nous demandons donc que le module **NLP** soit rétabli au plus vite.


## Remarques générales :

- **Pour le module d'anglais**, il est inutile d'enseigner des leçons de grammaire. Nous pensons qu'il serait mieux de remplacer les cours traditionel par des sessions de discussion en anglais par petits groupes, et que l'exemen soit similaire au test **IELTS**.

- **En ce qui concerne TP :** Veuillez SVP arrêter l'utilisation de JAVA, et préferez l'utilsation du langage **PYTHON** et de toutes les libraries qui viennent avec.







