# Les motifs de conception

Le nombre d'applications développées avec des technologies orientées objets augmentant, l'idée de réutiliser des techniques pour solutionner des problèmes courants a abouti aux recensements d'un certain nombre de modèles connus sous le nom de motifs de conception (design patterns).

Il est habituel de regrouper ces modèles communs dans trois grandes catégories :

- les modèles de création (creational patterns)
- les modèles de structuration (structural patterns)
- les modèles de comportement (behavioral patterns)


## Les modèles de créations

Dans cette catégories, il existe 5 modèles principaux :

| Nom | Rôle
| ----------- | ----------- |
| Fabrique (Factory) | Définit une interface pour la création d’objets dans une classe mère, mais délègue aux sous-classes le choix des types d’objets à créer |
| Fabrique abstraite (abstract Factory) | Permet de créer des familles d’objets apparentés sans préciser leur classe concrète |
| Monteur (Builder) | Permet de construire des objets complexes étape par étape. Ce patron permet de construire différentes variations ou représentations d’un objet en utilisant le même code de construction  | 	 
| Prototype (Prototype) |	Permet de créer de nouveaux objets à partir d’objets existants sans rendre le code dépendant de leur classe |
| Singleton (Singleton) |	Permet de garantir que l’instance d’une classe n’existe qu’en un seul exemplaire, tout en fournissant un point d’accès global à cette instance. |


### Fabrique (Factory)

