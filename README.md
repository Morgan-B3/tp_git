# TP GIT

## Etapes du projet
- Création du répot (local puis distant)
- Création de la branche develop
- Création des branches des différentes features (orders, users, products)
- Dans chaque branche, création d'un fichier markdown détaillant le contenu de la fonctionnalité
- Commits puis fusion de chaque branche feature vers la develop, puis vers la main
- Création d'une branche hotfix et correction de bugs
- Commit et fusion de la branche hotfix vers la develop, puis vers la main
- Création d'un tag pour la v1.0
- Résolution de bugs sur la hotfix
- Commit et fusion de la hotfix vers la develop, puis vers la main
- Création d'un tag pour la v1.1
- Modification du fichier index.html depuis la branche users
- Fusion de users vers develop
- Modification du fichier index.html depuis la branche products
- Fusion de products vers develop **[conflit]**
- Résolution du conflit
- Fusion de develop vers main
- tag v1.2

## WorkFlow
Le projet a été réalisé en utilisant le workflow Gitflow. Deux branches principales ont été créées (main et develop), ainsi que diverses branches features (users, orders, products) et une branche hotfix. Une fois chaque fonctionnalité ou résolution de bug terminé, la branche en question est fusionnée vers la branche develop, puis la branche main. Une fois la branche main mise à jour, un nouveau tag est créé, afin de différencier les versions du projet.

## Défis et résolution
- Des bugs ont été identifiés dans le fichier orders.md avant la v1.0. Ceux-ci ont été résolus depuis la branche hotfix.
- Un bug critique a été détecté dans le fichier orders.md après la sortie de la v1.0. Celui-ci a été résolu depuis la branche hotfix.
- Un conflit est apparu dans le fichier index.html après que celui-ci ait été modifié dans 2 branches différentes, chacune fusionnée vers la develop. Le conflit a pu être résolu depuis l'interface de résolution de conflits de VSCode.