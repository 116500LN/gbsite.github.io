# Patch — liens relatifs (projet GitHub Pages)

Ce patch corrige les liens qui envoyaient vers `https://116500LN.github.io/...` (site *utilisateur*)
au lieu de `https://116500LN.github.io/gbsite.github.io/...` (site *projet*).

**Changements :**
- `menu.*.url` et `profileMode.buttons.url` deviennent **relatifs** (ex.: `posts/`, `personal-projects/`).
- `relativeURLs: true` et `canonifyURLs: false` pour que Hugo génère des liens corrects sous le sous-chemin `/gbsite.github.io/`.

**Installation :**
1. Décompressez ce ZIP à la racine du dépôt et acceptez d'**écraser** `config.yaml`.
2. Commit sur `main` → GitHub Actions reconstruit et déploie.

URL attendue : `https://116500LN.github.io/gbsite.github.io/`.
