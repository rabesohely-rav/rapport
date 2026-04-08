# Rapport d'activité annuel – France Services

Ce dépôt est prêt pour **GitHub Pages**.

## Utilisation

À chaque nouveau rapport :

1. Remplace le fichier `data/data.csv` par ton nouveau CSV.
2. Garde exactement ce nom : `data.csv`.
3. Commit + push sur GitHub.
4. Ouvre ton site GitHub Pages.
5. Imprime en PDF depuis le navigateur.

## Structure attendue

```text
.
├── index.html
└── data/
    └── data.csv
```

## Colonnes minimales attendues dans le CSV

Le rapport a besoin au minimum de ces colonnes :

- `date_creation`
- `nom_FS`
- `id_usager`
- `primo_usager`

Et pour les graphiques supplémentaires :

- `thematique`
- `statut_activite`

## Mise en ligne avec GitHub Pages

1. Crée un dépôt GitHub.
2. Envoie le contenu de ce dossier à la racine du dépôt.
3. Va dans **Settings > Pages**.
4. Choisis **Deploy from a branch**.
5. Sélectionne la branche `main` et le dossier `/root`.
6. Sauvegarde.

GitHub te donnera une URL du type :

```text
https://ton-compte.github.io/nom-du-depot/
```

## Ce que fait le rapport

- Nombre de France Services
- Nombre total d’accompagnements
- Nombre total d’usagers uniques
- Moyenne d’accompagnements par jour
- Part de primo-usagers
- Accompagnements par mois
- Accompagnements par site
- Top 10 thématiques
- Répartition par statut d’activité

## Diagnostic en cas de page vide

En général :

- le CSV n’est pas au bon endroit
- le CSV n’est pas nommé `data.csv`
- les colonnes ont changé
- le CSV n’est plus séparé par `;`

Le modèle affiche un message d’erreur dans la page au lieu d’échouer en silence.
