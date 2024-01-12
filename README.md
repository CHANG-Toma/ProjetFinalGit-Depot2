# Projet Final Git
Ce projet Git est conçu pour évaluer la compréhension et l'application pratique des concepts de Git et GitHub dans le cadre d'une collaboration en équipe. 
Le projet est réalisé par des groupes de trois membres maximum et comprend une soutenance de 15 minutes pour présenter les travaux réalisés.

## Membres du Groupe
- CHANG Toma
- BURNAY Robin

## Prérequis
- 15 issues créées.
- 15 branches créées.
- 15 Merge Requests (MR) minimum réalisé.

## Structure du Projet
Ce projet suit le modèle Git flow avec des branches dédiées pour les fonctionnalités, les corrections de bugs, et les releases. Des protections de branches sont mises en place pour assurer l'intégrité du code.

## Fonctionnalités
- **Commits Signés** : Chaque commit est signé pour garantir l'authenticité.
- **Gestion des Issues** : Des templates d'issues sont utilisés pour une meilleure organisation.
- **Merge Requests avec Templates** : Chaque MR suit un template pour maintenir la cohérence.
- **Utilisation de GitHub Project** : Pour le suivi des tâches et l'organisation du projet.
- **Documentation Complète** : Inclut les fichiers README, CONTRIBUTING, et Code of Conduct.
- **Fichier .gitignore** : Pour exclure les fichiers non nécessaires du dépôt.
- **Hooks Git** : Un hook de pré-commit pour le linting des fichiers JavaScript.

## Bonus
- **Intégration Continue avec GitHub Actions** : Pour automatiser le linting et d'autres vérifications.
- **Configuration pour Push sur Deux Remote** : Permet de pousser les changements sur deux dépôts distants.

## Installation et Utilisation
- **Hook de Linting JavaScript** : Le hook qui vérifie les fichiers JavaScript se trouve dans le fichier `hooksLinter.txt`. Pour l'utiliser, copiez et collez son contenu dans votre fichier `.git/hooks/pre-commit`.

## Contribuer
Pour contribuer à ce projet, veuillez lire [CONTRIBUTING.md](./CONTRIBUTING.md) pour connaître les détails de notre code de conduite et le processus de soumission des pulls requests.

