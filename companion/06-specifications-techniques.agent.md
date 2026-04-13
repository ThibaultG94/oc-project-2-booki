## Spécifications techniques (note officielle)

### Maquettes
- **Trois maquettes** ont été réalisées : **desktop, tablette et mobile**
- Consultez la maquette Figma fournie pour tous les détails visuels

### Breakpoints
Utiliser ces breakpoints exacts :
- **> 1024 px** : écrans d'ordinateurs (desktop)
- **>= 768 px** : tablettes
- **< 768 px** : téléphones portables (mobile)

### Largeur min - max
- **Largeur maximum** : 1440 px
  - Au-delà, une marge blanche doit apparaître sur les côtés
  - Le contenu doit se limiter à 1440 px de large
- **Largeur minimum** : 320 px
  - En-deçà, le comportement n'est pas garanti

### Desktop first
- **Important :** Réaliser l'intégration d'abord pour les ordinateurs (**desktop first**)
- Puis les tablettes
- Enfin les téléphones
- Utiliser les **Media Queries** pour l'intégration des différents supports

### Bibliothèque d'icônes
- Les icônes proviennent de **Font Awesome** (déjà lié dans le starter pack)
- Lien : https://fontawesome.com/
- Icônes principales : location-dot, magnifying-glass, money-bill-wave, person, heart, fire, info, star

### Couleurs
Les couleurs de la charte (déjà dans les variables CSS du starter pack) :
- **Bleu** : `#0065FC` (`--main-color`)
- **Bleu clair** : `#DEEBFF` (`--filter-bg-color`)
- **Gris fond** : `#F2F2F2` (`--main-bg-color`)

### Police
- Police du site : **Raleway**
- Déjà importée via Google Fonts dans le starter pack
- Lien : https://fonts.google.com/specimen/Raleway
- Poids : 400 (normal), 500 (medium), 700 (bold)

### Mise en page
- **Recommandation** : Utiliser **Flexbox**
- Grid est aussi possible selon votre préférence

### Balises sémantiques
**Important :** Utiliser des balises sémantiques, au minimum :
- `<header>` : en-tête de page
- `<nav>` : navigation
- `<h1>`, `<h2>`, `<h3>` : hiérarchie des titres
- `<main>` : contenu principal
- `<section>` : sections thématiques
- `<article>` : contenu autonome (cartes)
- `<footer>` : pied de page

### Validité du code
**Règles strictes :**
- Aucun IDE particulier n'est imposé (vous utilisez VS Code)
- Le code doit être **valide aux validateurs W3C** HTML et CSS
- Le code HTML **ne doit pas contenir de propriété CSS** (séparation HTML/CSS)
- **Ne pas dupliquer le code HTML** lors du passage desktop → mobile/tablette
  - Exception : formulaire avec le mot "Rechercher" et l'icône loupe
- **Privilégier les classes CSS** pour cibler un élément (plutôt que le nom de l'élément)
- **Ne pas dupliquer des classes CSS inutilement**
  - Si 4 éléments sont identiques, utiliser une seule classe CSS, pas 4
- HTML sémantique obligatoire
- Responsive (3 breakpoints)
- Aucun framework CSS (Bootstrap, Tailwind, etc.)
- Pas de JavaScript
- Images avec attributs alt

### Compatibilité navigateurs
- La maquette doit être compatible avec les **dernières versions** de :
  - **Google Chrome**
  - **Mozilla Firefox**
- Tester la page web sur ces deux navigateurs

### Restrictions
**Interdictions strictes :**
- ❌ Aucun framework CSS (Bootstrap, Tailwind CSS)
- ❌ Aucun préprocesseur CSS (Sass, Less)
- ❌ Aucun autre langage (JavaScript, etc.)
- ✅ Uniquement HTML et CSS purs

### Contraintes techniques
- Code HTML et CSS valide W3C
- HTML sémantique obligatoire
- Responsive (3 breakpoints)
- Aucun framework CSS (Bootstrap, Tailwind, etc.)
- Pas de JavaScript
- Images avec attributs alt
