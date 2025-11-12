# Mon site — Hugo minimal (sans thème)

## Étapes (GitHub Pages, 1 minute)

1. **Téléversez** tout le contenu de ce dossier à la racine de votre dépôt.
2. Ouvrez `hugo.toml` et remplacez la valeur de `baseURL` par votre URL Github Pages :
   `https://<mon-user>.github.io/<mon-site-hugo>/` (gardez le `/` final).
3. Dans **Settings → Pages** de votre repo, mettez **"Build and deployment" → Source = GitHub Actions**.
4. Poussez sur la branche `main`. L'action *Deploy Hugo to GitHub Pages* va construire puis publier.
5. Votre site sera disponible à l'URL `baseURL` après le déploiement.

## Modifier le contenu

- Accueil : `content/_index.md`
- Blog : `content/blog/`
- À propos : `content/about/`

Aucun thème n'est utilisé ; les gabarits HTML sont dans `layouts/`.