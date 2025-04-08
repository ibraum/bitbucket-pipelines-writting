# 🤺TRAINNING FOR BITBUCKET PIPELINES WRITTING

## 🧩 Exercice 1 — Niveau Débutant : "Mon Premier Pipeline"

#### Objectif : Créer un pipeline qui :

- Utilise l'image officielle node:20.

- Installe les dépendances (npm install).

- Lance les tests (npm test).

#### Contraintes :

- Utiliser un default pipeline.

- Un seul step.

```🎯 Question bonus : Quelle est la structure de ton pipelines ?```

## 🚀 Exercice 2 — Niveau Intermédiaire : "Branche Master vs Develop"

#### Objectif : Construire deux pipelines différents :

- Quand je push sur develop, je fais un build simple (npm run build).

- Quand je push sur master, je fais un build + deploy (npm run deploy).

#### Contraintes :

- Séparer le comportement entre branches:.

- Mettre 2 steps différents.

```🎯 Question bonus : Comment définir un step pour uniquement develop sans toucher aux autres branches ?```