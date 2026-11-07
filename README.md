# Portfolio de KNRF5

Un portfolio en français qui rassemble mes projets : applications Windows,
outils d’intelligence artificielle, montage vidéo, jeux et projets web.

## Voir le site

**[Ouvrir le portfolio](https://knrf5.github.io/ALL-PROJECTS/)**

Si le site n’est pas encore accessible, active GitHub Pages une première fois :

1. Ouvre **Settings → Pages** dans ce dépôt.
2. Dans **Build and deployment**, sélectionne **GitHub Actions** comme source.
3. Vérifie l’exécution du workflow **Publish website** dans l’onglet **Actions**.

Une fois le déploiement terminé, le site sera disponible à l’adresse ci-dessus.

## Contenu

- Une sélection de projets mis en avant.
- Un catalogue de projets avec filtres par catégorie et recherche.
- Une mise en page adaptée aux téléphones et aux ordinateurs.

## Publication

Le site est une page statique : il n’y a ni dépendances ni étape de compilation.
Le workflow défini dans [`.github/workflows/pages.yml`](.github/workflows/pages.yml)
publie le contenu du dépôt sur GitHub Pages à chaque mise à jour de la branche
`main`. Il peut aussi être lancé manuellement depuis l’onglet **Actions**.

Pour mettre à jour le portfolio, modifie [`index.html`](index.html), puis pousse
tes changements sur `main`. Le workflow publiera la nouvelle version.
