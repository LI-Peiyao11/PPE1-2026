# PPE1

# Journal de bord du projet encadré

## ==> 2026-10-04

### Travail effectué
- Création du dépôt GitHub et clonage sur l'ordinateur.
- Configuration de l'authentification SSH.
- Création du journal de bord sur GitHub.
- Synchronisation du dépôt local avec git fetch et git pull.
- Consultation de l'historique avec git log.

#### Pendant le cours


#### Après le cours


### Solutions que je veux partager


### Questions à discuter

## 2026-10-04 — Pipelines

### Travail effectué
- Organisation des données dans le dossier data/ann par année et par mois.
- Comptage des annotations et des lieux pour 2016, 2017 et 2018.
- Classement des 15 lieux les plus cités pour chaque année.
- Classement des 15 lieux les plus cités en mars, toutes années confondues.
- Enregistrement des commandes dans Exercices/pipelines.txt et vérification des résultats.

### Difficultés et solutions
- Exclusion des lignes vides avec grep . avant de compter les annotations.
- Tri des lieux avec sort avant leur comptage avec uniq -c.
