# Challenge de validation de MDP - CSGames 2023

## Contexte

Le comité universitaire accorde une grande importance à la sécurité. À cette fin, ils ont mis en place de nombreuses politiques concernant la sécurité de l'information pour les nouvelles villes sous-marines. À cette fin, ils ont mandaté que tous les nouveaux services mis en place soient protégés par des mots de passe complexes pour mieux protéger les systèmes et les renseignements personnels des utilisateurs.

## Résumé

Votre équipe a été mandatée par le comité pour créer un validateur de mot de passe. Le premier objet de ce programme est de recevoir un mot de passe au format chaîne et de valider s'il satisfait à une série de règles prédéfinies. Le deuxième objectif est la possibilité de pouvoir changer dynamiquement les règles en règles **plus fortes**. Le troisième objectif est de fournir à l'utilisateur des informations sur la façon de créer un meilleur mot de passe s'il ne passe pas la validation. L'objectif final est de proposer une fonction de génération de mot de passe qui respecte les règles en vigueur.

## Valeur de la compétition

`500 points`

## Tâches

Ce programme doit être créé en **C++**

### Validation du mot de passe

- Un mot de passe doit comporter entre 10 et 24 caractères (10 points)
- Un mot de passe doit contenir deux chiffres **différents** (10 points)
- Un mot de passe doit contenir deux caractères spéciaux **différents** (10 points)
- Un mot de passe ne doit pas contenir trois caractères identiques à la suite (20 points)

### Modifier les règles

- Inclure la possibilité de modifier les règles pour déterminer si un mot de passe est suffisamment complexe (60 points)
- Les nouvelles règles doivent être **plus fortes** que les règles précédentes. Nous ne pouvons pas rétrograder. (60 points)
- Changer les règles doit être le plus simple possible pour l'utilisateur (40 points)

### Fournir une réponse

- Fournir un feedback à l'utilisateur après une validation de mot de passe (10 points)
- Indiquer à l'utilisateur **TOUTES** les raisons pour lesquelles son mot de passe n'est pas valide (40 points)
- Indiquer à l'utilisateur combien de changements sont nécessaires pour que son mot de passe soit valide (30 points)

### Générer un mot de passe fort

- Générer un mot de passe fort aléatoire basé sur les règles prédéfinies (50 points)
- Générer un mot de passe fort aléatoire basé sur les règles après leur modification (30 points)

### Convivialité

- Créer un menu facile à utiliser pour que l'utilisateur puisse interagir avec (40 points)
- Fournir un feedback clair et efficace à l'utilisateur (20 points)

### Générale

- Le projet fonctionne sans modifications (20 points)
- Le code est propre et commenté (20 points)
- Fournissez un README avec des instructions claires sur la façon d'exécuter et d'utiliser votre programme (30 points)
