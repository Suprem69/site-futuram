# Futuram Coaching

Site vitrine pour une activité de coaching / hypnose ericksonienne.
Le projet présente les prestations, la philosophie du cabinet, les tarifs et les informations de contact.

## Visualier le site en ligne 
https://raw.githack.com/CypMas/site-futuram/main/index.html


## Ce que contient ce dossier

Le dossier contient **deux versions** du site :

- `index.html` : version actuelle, plus moderne, avec le style intégré directement dans la page.
- `index_ancien.html` : version précédente.
- `futuram_coaching.css` : feuille de style de l’ancienne version (`index_ancien.html`).

Images utilisées sur le site :
- `fougere.jpg`
- `Arbre devant le couche du soleil.jpg`
- `Feu d'artifice 4 juillet.jpg`
- `eau.jpg`
- `vue 2 2 2.jpg`
- et d’autres visuels présents dans le dossier.


## Structure de la page (version actuelle)

La version `index.html` est organisée en sections :

1. En-tête (nom + localisation)
2. Navigation ancrée (Accueil, Prestations, À propos, Tarifs, Contact)
3. Hero de présentation
4. Prestations (cartes)
5. Blocs explicatifs avec visuels
6. À propos du thérapeute
7. Tarifs
8. Contact (email + téléphone)

## Personnalisation rapide

### Modifier les textes

Éditer directement le contenu dans `index.html` (titres, paragraphes, prix, coordonnées).

### Changer les images

Dans `index.html`, les visuels sont définis dans les classes CSS (`background-image`) :
- `.hero-image-container`
- `.feature-image.img1`
- `.feature-image.img2`
- `.feature-image.img3`
- `.about-image`

Remplacer le nom des fichiers ou déposer de nouvelles images dans le dossier.

### Adapter les couleurs

Toujours dans `index.html`, les couleurs principales sont regroupées dans `:root` :
- `--primary-dark`
- `--primary-green`
- `--accent-green`
- `--light-bg`

## Remarques

- La version actuelle (`index.html`) est autonome (HTML + CSS dans le même fichier).
- L’ancienne version (`index_ancien.html`) dépend de `futuram_coaching.css`.
- Le dossier contient un répertoire `.git/` : le projet est déjà initialisé avec Git.

---

Projet réalisé pour **Futuram Coaching**.
