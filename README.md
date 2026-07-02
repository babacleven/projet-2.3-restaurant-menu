# PROJET 2.3 - Menu de Restaurant Interactif

Niveau : Avance  
Technologies : HTML5 semantique uniquement (zero CSS, zero JavaScript)

## Description

Site web monopage presentant le menu complet du Congo Gourmet, un restaurant traditionnel congolais situe a Brazzaville (Congo-Brazzaville). Le projet met en oeuvre une structuration HTML5 rigoureuse, des balises semantiques, une accessibilite ARIA, et un contenu authentique.

## Installation

1. Cloner le depot :
   ```
   git clone https://github.com/babacleven/projet-2.3-restaurant-menu.git
   ```
2. Ouvrir `index.html` dans un navigateur moderne.

Aucune dependance ni serveur requis.

## Utilisation

La navigation principale permet d'acceder aux sections suivantes :

- Entrees (4 articles)
- Plats principaux (6 articles)
- Desserts (4 articles)
- Boissons (6 articles)
- Special du jour
- Tableau comparatif des prix
- Horaires d'ouverture
- Formulaire de reservation

Le formulaire de reservation valide les champs cote client (HTML5 native) avant soumission.

## Structure du projet

```
index.html
images/
    beignets.webp
    boissons.webp
    liboke.jpg
    makayabu.png
    mwambe.webp
    ntaba.webp
    oip.webp
    oip-2.webp
    pate-darachide.jpg
    pate-darachide.webp
    poulet-mayo.png
    poulet-moambe.jpg
    riz-poulet.webp
    saka-saka.webp
```

### Architecture du document HTML

- `header` : En-tete avec navigation (8 ancres internes)
- `main` : Contenu principal
  - `section#entrees` : 4 entrees
  - `section#plats` : 6 plats principaux
  - `section#desserts` : 4 desserts
  - `section#boissons` : 6 boissons
  - `section#special` : Special du jour
  - `section#prix` : Tableau comparatif des prix
  - `section#horaires` : Liste de definition (dl)
  - `aside` : Temoignages clients
  - `section#reservation` : Formulaire de reservation
- `footer` : Coordonnees, horaires, reseaux sociaux, copyright

### Balises HTML5 utilisees

header, nav, main, section, article, figure, figcaption, table, thead, tbody, tfoot, caption, dl, dt, dd, form, fieldset, legend, details, summary, aside, blockquote, footer, abbr, span, strong, em, small (25+ types)

### Accessibilite

- Attributs `aria-label` et `aria-labelledby` sur chaque section et element interactif
- `aria-required="true"` sur les champs obligatoires
- Attributs `alt` descriptifs sur toutes les images
- `scope` sur les en-tetes de tableau
- Roles ARIA : banner, navigation, main, contentinfo

## Technologies utilisees

- HTML5 (norme W3C)
- Aucune feuille de style CSS
- Aucun script JavaScript

## Conformite PROJET 2.3

- HTML5 strict, zero CSS et zero JavaScript
- 25+ types de balises semantiques HTML5
- 8 ancres de navigation interne
- 13 images avec figure + figcaption
- Tableau comparatif avec caption, thead, tbody, tfoot
- Liste de definition (dl) pour les horaires
- Formulaire complet avec validation native
- Footer avec coordonnees completes
- Accessibilite ARIA complete
- 830+ lignes de code
- Contenu authentique congolais
