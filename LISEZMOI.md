# Tally — installation sur iPhone

L'app est un site statique : il faut la mettre en ligne **une seule fois** pour que Safari puisse l'installer. Ensuite elle s'ouvre depuis son icône, en plein écran, **fonctionne hors ligne**, et vos données restent **uniquement sur l'iPhone**.

## 1. Mettre en ligne (gratuit, ~5 min) avec GitHub Pages
1. Créez un compte sur github.com (si besoin).
2. « New repository », nom : `tally`, visibilité **Public**, puis « Create ».
3. « uploading an existing file » → glissez **tous les fichiers de ce dossier** (index.html, sw.js, manifest.webmanifest, les icônes) → « Commit changes ».
4. Settings → Pages → Source : « Deploy from a branch », branche `main`, dossier `/ (root)` → Save.
5. Après 1 à 2 minutes, l'adresse s'affiche : `https://VOTRE-PSEUDO.github.io/tally/`

Le site ne contient aucune donnée personnelle : votre historique ne quitte jamais le téléphone.

## 2. Installer sur l'iPhone
1. Ouvrez l'adresse dans **Safari**.
2. Bouton Partager → **Sur l'écran d'accueil** → Ajouter.
3. L'icône Tally apparaît. Ouvrez l'app au moins une fois avec du réseau pour qu'elle se mette en cache.

## Bon à savoir
- **Sauvegarde** : Réglages → Exporter, enregistrez le fichier dans Fichiers / iCloud Drive. Supprimer l'icône de l'écran d'accueil efface les données.
- **Mettre à jour l'app** : remplacez les fichiers sur GitHub ; l'app prend la nouvelle version au prochain lancement avec du réseau. Vos données ne sont pas touchées.
