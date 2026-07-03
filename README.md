# PROJET 2.3 - Menu de Restaurant Interactif

Niveau : Avancé  
Technologies : HTML5 sémantique uniquement (zéro CSS, zéro JavaScript)

## Description

Site web monopage présentant le menu du restaurant Mama Ngazi, un restaurant traditionnel congolais situé à Brazzaville (Congo-Brazzaville). Le projet met en œuvre une structuration HTML5 rigoureuse, des balises sémantiques et une accessibilité ARIA.

## Installation

1. Cloner le dépôt :
   ```
   git clone https://github.com/babacleven/projet-2.3-restaurant-menu.git
   ```
2. Ouvrir `index.html` dans un navigateur moderne.

Aucune dépendance ni serveur requis.

## Utilisation

La navigation principale permet d'accéder aux sections suivantes :

- Spécial du jour
- Entrées (3 articles)
- Plats principaux (4 articles)
- Desserts (2 articles)
- Boissons (6 articles)
- Tableau comparatif des prix
- Horaires d'ouverture
- Formulaire de réservation

Le formulaire de réservation valide les champs côté client (HTML5 native) avant soumission.

## Structure du projet

```
index.html
images/
    beignets.webp
    bananes.jpg
    boissons.webp
    brochette.webp
    liboke.jpg
    makayabu.png
    mwambe.webp
    oip-2.webp
    pate-darachide.jpg
    pate-darachide.webp
    poulet-mayo.png
    poulet-moambe.jpg
    riz-poulet.webp
    saka-saka.webp
    viande-banane.webp
```

### Architecture du document HTML

- `header` : En-tête avec navigation (7 ancres internes)
- `main` : Contenu principal
  - `section#special` : Spécial du jour
  - `section#entrees` : 3 entrées
  - `section#plats` : 4 plats principaux
  - `section#desserts` : 2 desserts
  - `section#boissons` : 6 boissons
  - `section#prix` : Tableau comparatif des prix
  - `section#horaires` : Liste de définition (dl)
  - `section#reservation` : Formulaire de réservation
- `footer` : Coordonnées et copyright

### Balises HTML5 utilisées

header, nav, main, section, article, table, thead, tbody, caption, dl, dt, dd, form, blockquote, address, footer, span, strong, em, small, h1, h2, h3, p, ul, ol, li, a, img, label, input, select, option, textarea, button, br, meta, link, title (30+ types)

### Accessibilité

- Attributs `aria-labelledby` sur chaque section
- Attributs `alt` descriptifs sur toutes les images
- `scope` sur les en-têtes de tableau
- `aria-label` sur la navigation et le formulaire
- Rôles ARIA natifs (header, nav, main, footer) sans redondance

## Technologies utilisées

- HTML5 (norme W3C)
- Aucune feuille de style CSS
- Aucun script JavaScript

## Conformité PROJET 2.3

- HTML5 strict, zéro CSS et zéro JavaScript
- 30+ types de balises sémantiques HTML5
- 7 ancres de navigation interne
- Images avec attributs alt descriptifs
- Tableau comparatif avec caption, thead, tbody
- Liste de définition (dl) pour les horaires
- Formulaire complet avec validation native HTML5
- Accessibilité ARIA sans attributs redondants
- Contenu authentique congolais
