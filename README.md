# Pense-bête — traqueur de tâches

Mini-application Todo en HTML, CSS et JavaScript pur (un seul fichier, aucune dépendance). Conçue avec l'aide d'un assistant IA, déployée via GitHub Pages.


## Fonctionnalités

- Ajouter, cocher et supprimer des tâches
- Filtrer : toutes, à faire, terminées
- Compteur de tâches restantes
- Suppression en un clic des tâches terminées
- Sauvegarde automatique dans le navigateur (`localStorage`)
- Thème clair/sombre automatique, responsive, navigation au clavier

## Lancer en local

Ouvrez simplement `index.html` dans un navigateur.

## Déploiement sur GitHub Pages

1. Poussez le dépôt sur GitHub.
2. Dépôt → **Settings** → **Pages**.
3. Source : branche `main`, dossier `/ (root)`, puis **Save**.
4. L'URL apparaît après environ une minute.

## Spécification du projet

| Élément | Détail |
|---|---|
| Objectif | Aider une personne à suivre ses tâches quotidiennes sans compte ni installation |
| Public | Tout utilisateur, sur mobile ou ordinateur |
| Stack | HTML5, CSS3, JavaScript (ES6), aucun framework |
| Données | Tableau d'objets `{ id, text, done }` stocké dans `localStorage` |
| Hors périmètre | Comptes utilisateurs, synchronisation, rappels |
| Améliorations possibles | Dates d'échéance, catégories, glisser-déposer, export |

## Outils IA utilisés

Claude (Anthropic) pour générer le code, le README et la spécification.

## Licence

MIT