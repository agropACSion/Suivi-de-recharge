# Suivi de recharge (PWA)

Appli installable, utilisable hors connexion. Elle contient : `index.html`, `manifest.webmanifest`, `sw.js` et le dossier `icons/`.

## Mettre en ligne sur GitHub Pages
1. Crée un dépôt GitHub (public) ou ouvre le tien.
2. Envoie **tout le contenu de ce dossier à la racine du dépôt**, en gardant le dossier `icons/` (bouton *Add file → Upload files*, ou glisse-dépose).
3. *Settings → Pages* : Source = *Deploy from a branch*, branche `main`, dossier `/ (root)`, puis *Save*.
4. Après une minute, l'appli est sur `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Installer sur le téléphone
- **iPhone (Safari)** : bouton Partager → *Sur l'écran d'accueil*.
- **Android (Chrome)** : menu ⋮ → *Installer l'application*.

## Attention aux données
- Les données sont stockées dans le navigateur, **séparément pour Safari et pour l'appli installée** (sur iPhone surtout). Avant d'installer, exporte en Excel depuis l'ancienne page, puis importe le fichier dans l'appli installée.
- Exporte régulièrement en Excel : c'est ta vraie sauvegarde.

## Mettre à jour l'appli
Remplace `index.html` sur GitHub. Change aussi `VERSION` dans `sw.js` (ex. `v4.2`) pour que les anciens fichiers en cache soient nettoyés. Ferme puis rouvre l'appli pour voir la nouvelle version.
