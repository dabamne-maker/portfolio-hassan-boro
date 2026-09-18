# Hassan Boro — Portfolio audiovisuel

Portfolio statique de **Tjigoulo Dabamne Hassan Boro**, monteur vidéo et créateur audiovisuel basé à Ouagadougou, Burkina Faso.

La page utilise une direction artistique sombre, bleu-argent et dorée, avec une navigation façon timeline, un fond vidéo, une photo de profil, une grille de créations filtrable, des modales détaillées et une section outils/compétences.

## Lancer le portfolio

Depuis la racine du projet :

```bash
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## Fichiers importants

```text
index.html                 Page complète et données des projets
assets/photo-hassan.jpg    Photo de profil
assets/fond-video.mp4      Vidéo d'arrière-plan
assets/intro.mp4           Intro / showreel intégré dans les projets
assets/logo-animation.mp4  Animation logo conservée pour une prochaine section
```

## Ajouter une création

Dans `index.html`, ajouter un objet dans `const PROJECTS` :

```js
{
  title: "Nom du projet",
  category: "Publicité",
  role: "Montage vidéo",
  tools: ["Premiere Pro", "After Effects"],
  duration: "01:30",
  media: { type: "video", src: "assets/mon-projet.mp4" },
  link: "https://exemple.com",
  desc: "Courte description du projet."
}
```

`media` accepte une image locale, une vidéo locale ou une vidéo YouTube :

```js
{ type: "image", src: "assets/projet.jpg" }
{ type: "video", src: "assets/projet.mp4" }
{ type: "youtube", id: "ID_YOUTUBE" }
```

## Contacts intégrés

- `hassan_boro@yahoo.com`
- WhatsApp : `+226 76 55 00 68`
- WhatsApp : `+226 71 71 11 25`
- LinkedIn : [Hassan Boro](https://www.linkedin.com/in/hassan-boro)

## Déploiement

Le dépôt est prêt pour GitHub Pages : sélectionner la branche `main` et le dossier racine dans les réglages **Pages** du dépôt GitHub.
