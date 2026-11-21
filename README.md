# portfolio-EN — Portfolio d’Audrey Tichit

Copie de travail indépendante du portfolio actuel, créée le 21 novembre 2026. Le contenu et le design sont initialement identiques ; la traduction anglaise et la refonte pourront être réalisées ici. Dépôt séparé : https://github.com/Audrey-Tic/portfolio-EN. Cette version n’est pas encore publiée comme site web.

Depuis ce dossier, lancer `npm run dev`, puis ouvrir http://localhost:4174. Le portfolio original conserve son port 4173. Le dossier `portfolio-v2` est exclu du suivi du dépôt original.

Le workflow GitHub Pages est conservé pour une future publication séparée, avec déclenchement manuel uniquement. Ne pas connecter cette copie au dépôt GitHub du portfolio original pour la publier.

Portfolio personnel en français, sur une seule page, en HTML, CSS et JavaScript natifs. Entièrement statique, sans bibliothèque externe ni suivi de visiteurs.

## Ouvrir en local

Ouvrir `index.html` directement dans un navigateur, ou, avec Node.js 20 ou supérieur :

```sh
npm run dev
```

Puis ouvrir http://localhost:4174. Le serveur de prévisualisation écoute uniquement sur la machine locale. Arrêter avec Ctrl+C. Aucune installation nécessaire.

## Modifier le contenu

- `index.html` : introduction, bénévolat, formations, certifications, centres d’intérêt et liens.
- `experiences.js` : expériences professionnelles, bénévolat, regroupements de missions, marchés et domaines.
- `styles.css` : présentation et adaptations mobile.
- `theme.css` : palette chaude, cartes clients, logos et taille des textes.
- `app.js` : filtres, affichage des missions et navigation.
- `assets/audrey.jpg` : photographie fournie par Audrey.
- `assets/logos/` : logos des clients et associations extraits du CV fourni, servis localement.

Les informations professionnelles proviennent du CV fourni. Le bénévolat, les centres d’intérêt, la photo et le lien LinkedIn ont été précisés par Audrey. Les deux missions ANCV et les deux missions Airbus les plus récentes sont regroupées, avec leurs dates et leurs interventions distinctes. L’expérience Airbus 2022–2023 reste séparée. Les filtres par domaine et par marché sont combinables et s’appliquent uniquement aux expériences professionnelles. Le document Word n’est pas inclus dans le site. Le numéro de téléphone est affiché dans la rubrique Contact.

## GitHub Pages

Site original (version 1) : https://audrey-tic.github.io/portfolio/

Le workflow `.github/workflows/deploy-pages.yml` se déclenche uniquement manuellement depuis l’onglet **Actions** du nouveau dépôt, après configuration de GitHub Pages. Il vérifie la syntaxe JavaScript, prépare les fichiers statiques, puis les déploie sur GitHub Pages. Pousser du code ne publie pas le site.

GitHub Pages utilise **GitHub Actions** comme source de publication dans **Settings → Pages → Build and deployment**. Aucun secret supplémentaire ni installation de dépendances n’est nécessaire.

Les chemins sont relatifs : le site pourra fonctionner sous `/portfolio-EN/`. Seuls les fichiers de la page et le dossier `assets` sont prévus pour la publication ; les outils de prévisualisation et le README restent dans le dépôt. Le fichier `.nojekyll` permet de servir les fichiers tels quels.

## Précisions sur le parcours et les logos

Les responsabilités transverses chez CGI et la qualification de Sauveteuse secouriste du travail ont été fournies directement par Audrey. Le logo CGI provient du CV. Le logo SST vert provient de https://www.lonasante.com/wp-content/uploads/2026/03/logo-sst-vert-HD-niveau-acteur-Source-INRS.png et est conservé dans ses couleurs et proportions d’origine. Aucune date de certification ni de début chez CGI n’a été ajoutée.

## Indexation

La page contient une balise robots `noindex, nofollow, noimageindex` pour demander aux moteurs de recherche de ne pas l’indexer. Aucun blocage par `robots.txt` n’est ajouté : les moteurs doivent pouvoir lire cette consigne. Le site reste public et accessible par son lien ; une éventuelle désindexation prend effet après un nouveau passage du moteur.

## Illustrations des loisirs

Illustrations vectorielles du projet Game-icons.net, sous licence CC BY 3.0 (https://creativecommons.org/licenses/by/3.0/), avec attribution accessible dans le volet « Crédits des illustrations » en pied de page, y compris pour cet usage personnel et non commercial. Les dessins sont conservés localement, sans génération par IA. Seules la couleur et la transparence du fond sont adaptées.

- Badminton : Shuttlecock, Delapouite - https://game-icons.net/1x1/delapouite/shuttlecock.html
- Ski : Skier, Delapouite - https://game-icons.net/1x1/delapouite/skier.html
- Jeux : Rolling dices, Delapouite - https://game-icons.net/1x1/delapouite/rolling-dices.html
- Couture : Sewing machine, Caro Asercion - https://game-icons.net/1x1/caro-asercion/sewing-machine.html

Les tuiles se retournent au survol, au clavier et au toucher. Les préférences de réduction des animations sont respectées. Le logo CGI centré reprend l’image originale intégrée dans un SVG dont le cadrage retire les marges blanches asymétriques.

Les liens de certification sont fournis par Audrey. Les certifications agiles Product Owner et Scrum Master renvoient vers son profil Scrum.org : https://www.scrum.org/user/805818. Les intitulés Adobe Experience Manager et Adobe Analytics ont été vérifiés sur les pages de validation fournies.
