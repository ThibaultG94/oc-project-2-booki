# Booki : intégration HTML & CSS

Intégration de la page d'accueil de **Booki**, une agence de voyage en ligne, à partir d'une maquette Figma — projet réalisé dans le cadre de la formation **Développeur Web** d'OpenClassrooms.

L'intégration suit une approche **desktop first** : le CSS global cible les écrans d'ordinateur, et les versions tablette et mobile sont construites en surcharge via des media queries.

---

## 📋 Le projet

Booki permet aux usagers de trouver des hébergements et des activités dans la ville de leur choix. L'objectif de cette mission était d'intégrer la page d'accueil en **HTML5 et CSS3 purs**, en respectant la maquette desktop, tablette et mobile ainsi que les spécifications techniques fournies par la CTO.

### Ce qui a été réalisé

- **Header** : logo et navigation avec indication visuelle au survol et sur la page active
- **Barre de recherche** : formulaire avec champ éditable et bouton (texte « Rechercher » sur desktop, icône loupe sur mobile)
- **Filtres** : boutons thématiques avec changement d'état au survol et au focus
- **Section Hébergements** : grille de 6 cartes + encart _Les plus populaires_
- **Section Activités** : 4 cartes en colonnes
- **Footer** : 3 colonnes de liens
- **Responsive complet** : desktop → tablette → mobile, avec réorganisation et inversion de certaines sections selon le breakpoint

---

## 🛠 Contraintes techniques respectées

| Règle        | Détail                                                                           |
| ------------ | -------------------------------------------------------------------------------- |
| Langages     | HTML5 et CSS3 **uniquement** (pas de JS, pas de framework, pas de préprocesseur) |
| Mise en page | Flexbox + CSS Grid                                                               |
| Approche     | **Desktop first**                                                                |
| Breakpoints  | `>1024px` desktop · `≤1024px` tablette · `<768px` mobile                         |
| Largeur      | min 320px — max 1440px                                                           |
| Sémantique   | `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`              |
| Ciblage CSS  | Classes privilégiées, pas de duplication, kebab-case                             |
| Validité     | W3C HTML + CSS — 0 erreur                                                        |
| Navigateurs  | Chrome et Firefox (dernières versions)                                           |

---

## 📁 Structure du projet

```
Booki/
├── index.html
├── README.md
├── css/
│   └── style.css
└── images/        (toutes les images du site : hébergements, activités, logo)
```

---

## ▶️ Visualiser le projet

Cloner le dépôt et ouvrir `index.html` dans un navigateur :

```bash
git clone https://github.com/ThibaultG94/oc-project-2-booki
cd booki
```

---

## 🎨 Ressources du projet

- **Police** : [Raleway](https://fonts.google.com/specimen/Raleway) (Google Fonts)
- **Icônes** : [Font Awesome](https://fontawesome.com/)
- **Charte couleurs** : `#0065FC` (bleu principal), `#DEEBFF` (bleu clair), `#F2F2F2` (gris de fond)

---

## ✅ Validation

Le code a été validé sans erreur par les outils officiels :

- [Validateur HTML W3C](https://validator.w3.org/)
- [Validateur CSS W3C](https://jigsaw.w3.org/css-validator/)

---

_Projet réalisé par **Thibault Guilhem** — formation OpenClassrooms Développeur Web._
