# Squelette de portfolio — mode d'emploi

## Fichiers
- `index.html` — page d'accueil (hero, métriques, index des projets, aperçu veille)
- `projet-exemple.html` — fiche projet type, à dupliquer pour chaque projet
- `veille.html` — page de veille métier et technologique
- `style.css` — feuille de style partagée par toutes les pages

## Pour ajouter un projet
1. Duplique `projet-exemple.html` et renomme-le, ex. `projet-01-nom-du-projet.html`.
2. Remplace tous les textes entre crochets `[...]`.
3. Dans `index.html`, mets à jour le lien `href` correspondant vers ce nouveau fichier,
   et remplace le titre / la description / les tags de la carte ou de la ligne.
4. Répète pour chaque projet (l'objectif est une dizaine de fiches minimum).

## Pour publier
1. Place tous ces fichiers à la racine de ton dépôt `ziedbelhocine.github.io`
   (à côté du fichier `.nojekyll` déjà présent).
2. Commit et push (ou édite/commit directement depuis l'interface GitHub).
3. Le site se met à jour automatiquement sur `https://ziedbelhocine.github.io/`
   en 1-2 minutes.

## Ce qu'il reste à personnaliser
- Toutes les mentions `[Prénom Nom]`, `[URL LinkedIn]`, `[URL GitHub]`, `[URL CV.pdf]`
- Les métriques du bandeau (nombre de projets, durée de formation, outils, date)
- Les 10 entrées de la section Projets sur `index.html`
- Le contenu de `veille.html` (outils, sources, critères)
- Idéalement : un visuel (capture d'écran, graphique) dans chaque fiche projet,
  à la place du bloc en pointillés `.fiche-visual`

## Idées d'amélioration (optionnel, une fois le contenu posé)
- Ajouter une favicon
- Ajouter une image Open Graph pour un aperçu propre quand le lien est partagé
  sur LinkedIn
- Ajouter un `sitemap.xml` si le portfolio grossit beaucoup
