# Hugo + PaperMod — Starter pour `116500LN/gbsite.github.io`

Ce paquet contient uniquement les fichiers nécessaires pour publier un site Hugo **PaperMod** via GitHub Actions,
avec l'architecture : Accueil (profile mode) + CV / Papers / Personal Projects / Blog.

## Déploiement (2–3 minutes)
1. Uploadez **tous ces fichiers à la racine** du dépôt `116500LN/gbsite.github.io` (remplacez les fichiers existants).  
   > S'il existe `hugo.toml` dans le dépôt, **supprimez-le** pour éviter les conflits (on utilise `config.yaml`).
2. Dans **Settings → Pages → Build and deployment → Source**, sélectionnez **GitHub Actions**.
3. Faites un commit sur `main`. Le workflow build & déploie automatiquement.

URL finale : **https://116500LN.github.io/gbsite.github.io/**

## Personnalisation
- Modifiez `config.yaml` : titre, sous-titre, liens des boutons d'accueil, réseaux sociaux, etc.
- Ajoutez vos pages dans `content/` :
  - Blog : `content/posts/`
  - Projets : `content/personal-projects/`
  - CV : `content/cv/`
  - Papers : `content/papers/`

Bon déploiement !
