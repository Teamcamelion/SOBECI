# Site Vitrine SOBECI

Site vitrine multi-page optimisé pour le référencement (SEO) pour SOBECI - Société de Construction Générale.

## Structure du Projet

```
SOBECI/
├── index.html          # Page d'accueil
├── about.html          # À propos
├── services.html       # Nos services
├── projets.html        # Réalisations
├── contact.html        # Contact
├── css/
│   ├── style.css       # Styles principaux
│   └── responsive.css  # Media queries responsive
├── js/
│   ├── main.js         # JavaScript principal
│   └── animations.js    # Animations et interactions
├── images/             # Dossier pour les images (à créer)
├── sitemap.xml         # Sitemap pour le référencement
├── robots.txt          # Robots.txt pour le référencement
└── README.md           # Ce fichier
```

## Optimisations SEO Incluses

- ✅ Balises meta optimisées (title, description, keywords)
- ✅ Structure HTML sémantique (header, nav, main, section, footer)
- ✅ Attributs alt sur toutes les images (à ajouter)
- ✅ Sitemap.xml
- ✅ Robots.txt
- ✅ URLs propres et descriptives
- ✅ Meta tags Open Graph pour les réseaux sociaux
- ✅ Meta tags Twitter Card
- ✅ Navigation structurée
- ✅ Contenu optimisé pour les mots-clés

## Caractéristiques

- **Design moderne et professionnel**
- **Entièrement responsive** (mobile, tablette, desktop)
- **Animations fluides** au scroll
- **Formulaire de contact** avec validation
- **Menu mobile** responsive
- **Performance optimisée**

## Personnalisation

### Modifier les informations de contact

Éditez les fichiers HTML pour mettre à jour :
- Numéro de téléphone
- Adresse email
- Adresse physique
- Horaires d'ouverture

### Ajouter des images

1. Placez vos images dans le dossier `images/`
2. Remplacez les emojis dans les sections `.project-image` et `.service-icon` par des balises `<img>` avec les attributs `src` et `alt` appropriés

### Modifier les couleurs

Éditez `css/style.css` et modifiez les variables CSS dans `:root` :
- `--primary-color` : Couleur principale
- `--secondary-color` : Couleur secondaire
- `--accent-color` : Couleur d'accentuation

## Utilisation

1. Ouvrez `index.html` dans un navigateur web
2. Tous les fichiers sont statiques, aucun serveur n'est nécessaire pour le développement
3. Pour la mise en production, hébergez tous les fichiers sur votre serveur web

## Notes

- Le formulaire de contact affiche actuellement une alerte JavaScript. Pour un fonctionnement réel, connectez-le à un backend ou un service de formulaire (comme Formspree, Netlify Forms, etc.).
- N'oubliez pas de remplacer `https://www.sobeci.fr` dans `sitemap.xml` par votre véritable URL de domaine.
- Ajoutez vos propres images dans le dossier `images/` et mettez à jour les références dans le HTML.

## Support

Pour toute question ou personnalisation supplémentaire, contactez votre développeur.

