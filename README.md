# FITAHIANTSOA — Prototype d'application

Ce dossier contient une version **prête à héberger** de l'application FITAHIANTSOA :

- `index.html` — l'application complète (React + Babel + icônes Lucide chargés depuis un CDN), avec le logo et les vraies photos de matériel intégrés directement dans le fichier. **Aucune installation ni build n'est nécessaire** : ouvrez simplement ce fichier dans un navigateur, ou déployez-le tel quel.
- `FitahiantsoaApp.jsx` — le même composant, au format `.jsx` pur, si votre équipe veut l'intégrer plus tard dans un vrai projet React Native/Expo ou React web avec un build (Vite, Next.js, etc.).

## Ajouter ça à votre dépôt GitHub

Je n'ai pas d'accès direct à votre compte GitHub (aucun connecteur n'est activé dans cette conversation), donc voici la marche à suivre de votre côté — 2 minutes :

### Option A — directement depuis l'interface GitHub (le plus simple)
1. Allez sur votre dépôt (ou créez-en un nouveau sur https://github.com/new si ce n'est pas encore fait).
2. Cliquez sur **Add file → Upload files**.
3. Glissez-déposez `index.html` (et `FitahiantsoaApp.jsx` si vous voulez le garder en référence).
4. Validez le commit.

### Option B — en ligne de commande, depuis votre ordinateur
```bash
git clone https://github.com/sergioolivier/<nom-du-depot>.git
cd <nom-du-depot>
# copiez index.html (et FitahiantsoaApp.jsx) téléchargés depuis cette conversation dans ce dossier
git add index.html FitahiantsoaApp.jsx
git commit -m "Ajout du prototype de l'application FITAHIANTSOA"
git push
```

## Afficher l'application en ligne (GitHub Pages)

Une fois `index.html` poussé sur le dépôt :
1. Dans le dépôt GitHub → **Settings → Pages**.
2. Sous « Build and deployment » → Source : **Deploy from a branch**.
3. Branche : `main` (ou `master`), dossier : `/ (root)`.
4. Enregistrez. Après 1 à 2 minutes, l'application sera visible à une adresse du type :
   `https://sergioolivier.github.io/<nom-du-depot>/`

Vous pourrez alors partager ce lien tel quel — n'importe qui pourra naviguer dans l'app (accueil, catalogue, panier, commande, suivi, et les 5 espaces via « Changer d'espace ») sans rien installer.
