# Portfolio — Nohon Serge Toussaint GNEPA

Site statique (HTML/CSS/JS), sans serveur ni installation.

## Contenu

| Fichier      | Rôle                                                   |
|--------------|--------------------------------------------------------|
| `index.html` | Page principale (styles et script inclus)              |
| `photo.jpg`  | Photo de profil                                        |
| `.nojekyll`  | Indique à GitHub Pages de servir les fichiers tels quels |

## Publier sur GitHub Pages

1. Créez un compte sur https://github.com si vous n'en avez pas.
2. Cliquez sur **New repository**.
   - Pour l'adresse `https://VOTRE-PSEUDO.github.io`, nommez le dépôt exactement `VOTRE-PSEUDO.github.io`.
   - Sinon, donnez-lui un nom comme `portfolio` : l'adresse sera `https://VOTRE-PSEUDO.github.io/portfolio`.
   - Cochez **Public**, puis **Create repository**.
3. Sur la page du dépôt, cliquez sur **uploading an existing file** (ou **Add file > Upload files**).
4. Glissez `index.html`, `photo.jpg` et `README.md` (pas le dossier lui‑même, son contenu), puis **Commit changes**.
5. Allez dans **Settings > Pages**.
   - **Source** : *Deploy from a branch*
   - **Branch** : `main` et dossier `/ (root)`, puis **Save**.
6. Patientez 1 à 2 minutes, puis rafraîchissez la page **Settings > Pages** : l'adresse du site s'affiche en haut.

Le fichier `.nojekyll` est caché sous Windows et facultatif : le site fonctionne sans lui.

## Modifier le site

Ouvrez `index.html` dans un éditeur (VS Code par exemple), modifiez le texte, puis renvoyez le fichier sur GitHub (**Add file > Upload files**). Pour changer la photo, remplacez `photo.jpg` par une autre image du même nom.

Pour voir le site en local, double‑cliquez simplement sur `index.html`.
