Méthodes de développement
Plan de développement logiciel
# Sommaire
1 - OBJET DU GUIDE ................................................................................................. 2
2 - OBJECTIF DU PDL ............................................................................................... 2
3 - PLAN TYPE DU PDL .............................................................................................. 2
4 - TRAVAUX DE PRÉPARATION DU PDL ...................................................................... 2
4.1 Choix de méthode de développement.................................................................... 2
4.2 Identification des taches...................................................................................... 3
4.2.1 Les taches et leur utilisation............................................................................3
4.3 Estimation des charges de travail et délais des taches............................................ ...4
4.4 Planification................................. ...................................................................... 5
4.5 Organisation de l'équipe....................................................................................5
5 - RÉDACTION DU DOCUMENT ................................................................................. 6
6 - PRÉSENTATION DU CONTENU DES TACHES............................................................. 7
7 - EXEMPLE DE PDL ................................................................................................. 9



# 1 - OBJET DU GUIDE
Ce guide est destiné à aider dans la rédaction d'un plan de développement logiciel (PDL). Il est
illustré par un plan rédigé en partie.

# 2 - OBJECTIF DU PDL
Le plan de développement est rédigé au tout début du développement du logiciel pour planifier les
travaux nécessaires au développement du logiciel.
Il peut être aussi utilisé pour le suivi de l'avancement de ces travaux. Les calendriers devront alors
être mis à jour en fonction de l'avancement réel des travaux.
Il peut aussi être rédigé à l'état de projet lors de la préparation du projet pour montrer les méthodes et
calendrier prévus. Dans ce cas il sera mis à jour et complété au début du développement.

# 3 - PLAN TYPE DU PDL
Le plan type du plan de développement dépend de la méthode de développement choisi. Dans le cas
d'un développement itératif ou d'un développement par étapes on pourra utiliser le plan type suivant
:
1 Introduction
1.1 Objet
1.2 Terminologie et sigles utilisés
1.3 Documents de référence
2 Organisation du projet
3 Méthode de développement et calendrier directeur
4 Plans d'itérations (ou d'étapes)
4.x Plan pour l'itération (ou l'étape) x
4.x.1 Taches et calendrier
4.x.2 Contenu des taches
4.x.3 Produits réalisés
5 Maîtrise des risques
6 Méthodes, techniques et outils
7 Infrastructures et moyens


# 4 - TRAVAUX DE PRÉPARATION DU PDL
## 4.1 Choix de méthode de développement
La méthode de développement a des incidences sur les délais, les coûts, les fournitures, le découpage
en taches... Elle doit donc être choisie dans son principe

En fonction des contraintes du client, en particulier au niveau des délais, et de l'expérience de l'équipe,
on choisira un cycle en V simple, une méthode avec prototype, une méthode itérative par prototypes
successifs, une méthode incrémentale...
Il faudra préciser les objectifs et contenu de chaque étape ou chaque itération (si la méthode est
itérative), les activités, les documents produits...
## 4.2 Identification des taches
### 4.2.1 Les taches et leur utilisation
Les taches sont la base de la gestion de projet. Elles sont utilisées pour la planification et le suivi
des délais, et pour l'estimation et le suivi des coûts. Tous les travaux prévus et réalisés dans le projet
doivent faire partie d'une tache du projet. Toutes les fournitures prévues au projet doivent être des
produits en sortie d'une tache du projet.
Une tache est un ensemble de travaux auxquels on peut attribuer :
- un responsable unique,
- un objet clair, un début et une fin,
- des produits en entrée et des produits en sortie.
### 4.2.2 Hiérarchisation des taches
On peut dans un projet vouloir avoir un découpage plus ou moins fin en taches afin d'assurer un
suivi plus fin de certaines parties du projet. Pour cela on peut décomposer certaines taches en taches
plus petites, et redécomposer certaines taches...
On obtient ainsi une structure arborescente de taches. Un certain nombre de règles doivent alors
être respectées :
- le niveau de chaque tache doit être clairement indiqué (niveau 1 pour le premier niveau de
décomposition, puis niveau 2, niveau 3...,
- lorsqu'une tache est décomposée, l'ensemble des activités composant cette tache doit se retrouver
dans une des taches de décomposition, et la somme des activités des taches de décomposition
doit être identique aux activités de la tache décomposée,
- on peut attribuer à chaque tache résultant de la décomposition un responsable unique, un objet
clair, un début et une fin, des produits en entrée et des produits en sortie.
### 4.2.3 Découpage d'un projet logiciel en taches
Le découpage en taches d'un projet logiciel est fait à partir des activités de développement du
logiciel ou du système, des activités projet, de l'organisation de l'équipe et ses sous-groupes, et des
itérations ou étapes de la méthode.
Le nombre de taches à définir varie avec la taille du projet. On considère que pour un petit projet, en
dehors des méthodes de type incrémental, le découpage en une dizaine de taches de premier niveau
permet un bon suivi du projet.
On peut définir une tache de premier niveau par activité du cycle en V (analyse des exigences,
conception de l'architecture, conception détaillée, codage et essais, intégration, validation). On
complétera cette première liste de taches par les activités complémentaires au niveau du système ou du
projet tels que la mise en place des plates-formes, l'évaluation des outils, la gestion de projet...

On pourra ensuite décomposer certaines taches en taches de niveau 2, par exemple décomposer les
conceptions détaillées, codage et essais par sous-groupe de réalisation.
### 4.2.4 Découpage dans les méthodes incrémentales ou itératives
Dans une méthode incrémentale ou itérative, le premier niveau de taches correspondra aux étapes
de la méthode, et on pourra découper chaque étape en une dizaine de taches en examinant l'objectif
et les travaux à réaliser (sur la base des activités du cycle en V et activités complémentaires).
### 4.2.5 L'organigramme des taches et l'index WBS
Dans un grand programme, il peut y avoir beaucoup de produits et des centaines de taches à gérer.
Il faut alors structurer les produits et les taches. On dispose pour cela d'un outil, l'organigramme des
taches (ou WBS Work Breakdown Structure).
L'organigramme des taches s’appuie sur une décomposition arborescente du système (sous-systèmes,
matériels, logiciels, modules de logiciels...) dite arborescence technique.
Pour chaque niveau de l’arborescence, on fait l’inventaire :
- des produits
- des taches
- et des moyens
nécessaires pour obtenir le produit de niveau supérieur.
Pour identifier chaque produit, tache ou moyen, on associe à chacun un index. Cet index est un chiffre
ou une lettre au premier niveau, et à chaque niveau on ajoute un chiffre ou une lettre à l'index de
l'élément du niveau supérieur de rattachement.
Il n'est pas utile de réaliser un organigramme des taches dans un petit projet, mais il est recommandé
d'utiliser les principes de l'index WBS pour identifier les taches (voir exemple en annexe 1).
Nota
Attention si vous faites un planning avec un outil de type MS Project. En effet dans un planning (voir
l'exemple), on représente en général les taches du projet et des "jalons" (évènements significatifs du
projet), et MS Project représente les jalons comme des taches de durée nulle faisant partie du projet.
N'utilisez pas les codes WBS générés automatiquement qui prennent en compte les jalons, et faites votre
codage WBS en ne codant que les taches.
## 4.3 Estimation des charges de travail et délais des taches
Pour dimensionner l'équipe, l'organiser, et planifier le projet, il faut estimer la charge de travail (heures
d'ingénieurs) et le délai de réalisation de chaque tache.
Pour l'estimation des charges de travail, il n'y a pas de recette miracle, il faut se baser sur l'expérience
de la société. Si l'on peut trouver un projet antérieur de même nature pour lequel les données ont été
archivées, on comparera les tailles estimées, les complexités... pour extrapoler les chiffres du projet
antérieur, et on corrigera de l'augmentation estimée de productivité.

A défaut, on essaiera d'estimer la charge totale de travail (nombre de personnes de l'équipe prévue x durée
du projet) et on appliquera des ratios pour les diverses activités : 20 à 30 % pour l'analyse des exigences,
20 à 30 % pour la conception, 15 à 20 % pour codage et essais, 20 à 30 % pour l'intégration, 10 à 20 %
pour la qualification (si cette activité est retenue).
On pourra faire une première estimation du délai de réalisation de chaque tache à partir de la charge de
travail, du nombre de personnes qui peuvent être affecté à la tâche, de leur pourcentage d'activité pour
la tâche, et des autres contraintes (par exemple la durée de certains essais). Cette première estimation
pourra être corrigée lors de la planification.
## 4.4 Planification
Après avoir estimé la charge de travail et la durée de réalisation de chaque tache, on recensera toutes
les conditions pour pouvoir commencer la tache (fin d'autres tâches, arrivée de matériels...).
A partir de ces estimations et des contraintes imposées par le client (délais imposés pour certaines
fournitures), on pourra construire un premier calendrier prévisionnel du projet en s'aidant d'un outil de
planification. Pour les petits projets, on pourra utiliser MS PROJECT ou MAC PROJECT ; pour les
gros projets, on trouve sur le marché des outils plus élaborés.
L'outil de planification peut sortir le calendrier sous forme de GANTT (voir exemple en annexe) qui
montre comment les taches se placent en fonction du temps, ou sous forme de PERT (voir exemple en
annexe) qui montre l'enchaînement des taches et les chemins critiques. L'outil peut aussi indiquer
l'utilisation des ressources (personnel, plates-formes...).
A partir de ce premier calendrier, on pourra mettre des contraintes sur les ressources, ajuster les
contraintes entre taches, éventuellement modifier le découpage en taches, et itérer avec l'outil jusqu'à
obtenir un calendrier prévisionnel satisfaisant.
Pour les méthodes incrémentales et itératives, il est recommandé de décomposer le calendrier en un
calendrier général montrant l'enchaînement des étapes et itérations, et un calendrier par étape ou
itération. (voir l'exemple).
Nota :
Le planning à définir est le planning de réalisation du projet, et débute au démarrage du projet, il
ne doit donc pas contenir la préparation du projet.
## 4.5 Organisation de l'équipe
La conduite d'un projet complexe par un groupe nécessite de mener en parallèle de nombreuses activités
pour organiser et suivre le projet, réaliser les logiciels, mettre en place l'infrastructure...
Il faut un chef de projet, et celui-ci doit déléguer des responsabilités
La mise en place de l'organisation demande donc :
- d'identifier les responsabilités à déléguer,

- d'attribuer chacune de ces responsabilités à une personne (ce ne correspond pas en général
à un travail à temps plein, et plusieurs responsabilités peuvent être déléguées à une même
personne)
- designer les responsables des sous-groupes de réalisation ou d'intégration, et les membres
de ces sous-groupes.
Pour les activités de réalisation (conception détaillée, codage et tests unitaires), l'équipe projet
doit être divisée en sous-groupes de une ou deux personnes (éventuellement trois) en vue de
pouvoir confier à chaque sous-groupe la responsabilité de réalisation d'un ou plusieurs sous-
systèmes du logiciel.
Pour les travaux d'intégration, on désignera un responsable d'intégration et un sous-groupe
pour préparer et piloter les travaux d'intégration. Ce sous-groupe sera assisté par les
réalisateurs lors des travaux d'intégration.
Nota
Si l'équipe projet est de taille très réduite, il n'y a pas à identifier des sous-groupes
# 5 - RÉDACTION DU DOCUMENT
1 1.1 Objet
Indiquer l'objet du document et le projet concerné
1.2 Terminologie et sigles utilisés
Définir les abréviations employées et les termes qui ont un sens particulier.
1.3 Documents de référence
Indiquer les documents auxquels le PDL se réfère (cahier des charges, plan qualité,
documents de standards...).
2 La présentation de l'organisation indiquera :
- la place de l'équipe projet dans la société,
- la composition de l'équipe projet,
- les principales responsabilités déléguées,
- la répartition en sous-groupes pour les activités de réalisation et d'intégration, et les
activités confiées à chaque sous-groupe.
L'organisation sera illustrée par un organigramme.
(voir exemple)
3 Indiquer les grandes étapes de la méthode de développement (itérations dans un
processus itératif) et leurs objectifs, les activités dans chaque grande étape, et les
fournitures prévues.
Préciser les objectifs calendaires (fournitures au client, recettes, démonstrations...) et
les autres contraintes importantes identifiées dans le projet (disponibilité de matériels
ou d'outils logiciels...) et présenter un calendrier général de type diagramme de
GANTT montrant les objectifs calendaires et les grandes étapes.
4.x.1 Indiquez les taches identifiées dans l'itération et leur rôle, faire un calendrier des taches
de type GANTT montrant l'exécution de ces taches et les objectifs calendaires de
l'itération
4.x.2 Indiquer pour chaque tache identifiée dans l'itération :
- le responsable,
- les travaux prévus,
- les documents et produits en sortie,
- les contraintes éventuelles pour le commencement ou la réalisation de la tache.
La présentation pourra être faite sous forme de tableaux ou de fiches de taches
annexées.
4.x.3 Indiquer le rôle de chaque document et produit en sortie
Pour les logiciels, préciser les fonctions du logiciel issu de l'étape.
5 Identifier les principaux risques (tenue des délais, utilisation de certains outils,
matériels et outils imposés...), et indiquer les actions prévues pour les limiter.
6 Lister les standards dont l'application est demandée pour la spécification, la conception,
le codage...
Indiquer les outils nécessaires pour réaliser le projet
7 Faire une synthèse des infrastructures et moyens nécessaires pour réaliser le projet
: matériels, outils logiciels, réseaux, bâtiments...
Préciser la disponibilité de ces infrastructures et moyens, et, pour les infrastructures ou
autres moyens à acheter ou développer, les travaux à réaliser et leur calendrier.

# 6 - PRÉSENTATION DU CONTENU DES TACHES
Le contenu des taches présente pour chaque tache identifiée :
- le responsable,
- les travaux prévus,
- les documents et produits en sortie,
- les contraintes éventuelles pour le commencement ou la réalisation de la tache.
Une technique utilisable pour de petits systèmes est de faire un tableau par itération pour toutes
ces informations (voir l'exemple).
Cependant une autre technique couramment utilisée dans l'industrie pour les projets
importants est de faire une fiche par tache en complétant un formulaire.
Ce formulaire fiche de tache peut avoir la présentation suivante :

Code WBS : Nom de la tache :
Responsable :
Date de début prévue: Durée estimée :
Charge de travail estimée :
Travaux prévus:
Documents en entrée :
Documents et produits en sortie :
Contraintes 