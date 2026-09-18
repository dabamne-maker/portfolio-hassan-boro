# Hassan Boro | Portfolio

Portfolio professionnel moderne et premium pour un monteur, designer et artiste 3D.

## Présentation

Ce projet est une landing page / portfolio visuelle qui met en avant :

- l'image de profil,
- le logo,
- les compétences en montage, motion design et 3D,
- des projets sélectionnés,
- une section reel pour l'animation de logo,
- les contacts et le formulaire de contact.

## Structure du projet

```text
portfolio-hassan-boro/
├── index.html
├── styles.css
├── script.js
├── README.md
├── assets/
│   ├── logo.svg
│   ├── profile-placeholder.svg
│   └── logo-animation.mp4
└── .gitignore
```

## Démarrage rapide

1. Ouvrez le projet dans un navigateur, ou lancez un serveur local :

```bash
python -m http.server 8000
```

2. Ensuite ouvrez :

```text
http://localhost:8000
```

## Personnaliser le portfolio

### 1. Ajouter votre photo de profil
Remplacez le fichier :

```text
assets/profile-placeholder.svg
```

par votre vraie photo de profil en format `.jpg` ou `.png`.

### 2. Ajouter votre logo
Remplacez le fichier :

```text
assets/logo.svg
```

par votre logo officiel, vectorisé ou exporté dans un style premium.

### 3. Ajouter votre animation de logo en MP4
Placez votre fichier :

```text
assets/logo-animation.mp4
```

Le site l'utilise automatiquement dans la section `Reel`.

### 4. Modifier les informations de contact
Dans `index.html`, remplacez :

- `hassan@example.com`
- `+00 00 00 00 00`
- le texte de présentation
- les liens des réseaux / projets

## Personnalisation visuelle

Le thème est pensé pour un style élégant, sombre et premium avec des accents cyan, violet et rose.

Vous pouvez ajuster la palette dans `styles.css` via les variables CSS en haut du fichier :

```css
:root {
  --bg: #08090d;
  --primary: #89f7fe;
  --secondary: #7d6cff;
  --accent: #ff5ea8;
}
```

## Déploiement GitHub Pages

1. Pousser le projet sur GitHub.
2. Dans le dépôt, ouvrir les réglages.
3. Section `Pages`.
4. Sélectionner la branche `main` et le dossier racine.

## Auteur

Hassan Boro

## Licence

Ce projet est prêt à être personnalisé et utilisé comme portfolio personnel.
