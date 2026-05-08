# Déploiement GitHub Pages

Ce site est prêt pour GitHub Pages.

## Étapes de déploiement

1. Créez un dépôt GitHub.
2. Poussez ce dossier dans le dépôt :

```bash
git init
git add .
git commit -m "Site GitHub Pages"
# ajoutez ensuite l'URL de votre dépôt distant
# git remote add origin https://github.com/VOTRE_COMPTE/VOTRE_DEPOT.git
# git push -u origin main
```

3. Dans GitHub, activez GitHub Pages :
   - Allez dans `Settings` > `Pages`
   - Sélectionnez la branche `main` et le dossier `/ (root)`
   - Enregistrez

4. Votre site sera disponible à l'adresse :
   `https://VOTRE_COMPTE.github.io/VOTRE_DEPOT/`

## Fichiers importants

- `index.html` : page d'accueil du site
- `.nojekyll` : permet d'éviter le traitement Jekyll sur GitHub Pages

## Ajustements recommandés

- Remplacez `VOTRE_PHOTO_ICI.jpg` dans le HTML par une URL de photo accessible en ligne.
- Remplacez `VOTRE_URL_GOOGLE_SCRIPT_ICI` par l'URL de votre Google Apps Script si vous souhaitez collecter les réponses.
