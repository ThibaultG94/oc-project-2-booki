## Spécifications fonctionnelles (note officielle)

### Fonction recherche
- Les usagers pourront rechercher des hébergements dans la ville de leur choix
- Le champ de recherche est un **champ de saisie**, le texte doit pouvoir être édité par l'utilisateur
- **Important :** Il faut englober ce champ dans un formulaire (`<form>`)
- **Note :** La partie Recherche ne doit pas être fonctionnelle - il s'agit d'une première version pour valider l'interface

### Liens "Hébergements" et "Activités"
- Les textes "Hébergements" et "Activités" dans l'en-tête sont des **liens**
- Ils doivent mener respectivement vers :
  - Section "Hébergements à Marseille" (avec `id="hebergements"`)
  - Section "Activités à Marseille" (avec `id="activites"`)
- Utiliser les ancres HTML : `<a href="#hebergements">Hébergements</a>`

### Cartes hébergements et activités
- **Chaque carte** d'hébergement ou d'activité devra être **cliquable dans son intégralité** (pas uniquement le titre)
- Pour l'instant, les liens sont vides : utiliser `href="#"` pour simuler la présence d'un lien
- Structure : `<a href="#">` doit entourer tout l'`<article>`

### Filtres de recherche
- Les hébergements peuvent être filtrés par thématique (budget, ambiance)
- Les filtres doivent **changer de couleur au survol** de la souris (`:hover`)
- **Note :** Les filtres ne doivent pas être fonctionnels - il s'agit d'une première version pour valider l'interface
