# portfolio-EN — Audrey Tichit’s portfolio

English version of Audrey Tichit’s professional portfolio: a single page built with HTML, CSS and vanilla JavaScript. Entirely static, with no external libraries or visitor tracking.

This project is independent of the original French portfolio. The translation preserves the professional information, dates, company names, qualifications and design. Official French institution and qualification names are retained where appropriate.

- Repository: https://github.com/Audrey-Tic/portfolio-EN
- English website: https://audrey-tic.github.io/portfolio-EN/
- Original French website: https://audrey-tic.github.io/portfolio/

## Local preview

Open `index.html` directly in a browser, or use Node.js 20 or later:

```sh
npm run dev
```

Then open http://localhost:4174. The preview server listens only on the local machine. Stop it with Ctrl+C. No installation is needed. The original project uses port 4173, so both versions can run at the same time.

Run `npm run check` to check JavaScript syntax.

## Editing the content

- `index.html`: introduction, employers, education, certifications, interests, contact details and links.
- `experiences.js`: client and volunteer assignments, project groupings, industries and areas of expertise.
- `app.js`: filters, assignment details, navigation and interest cards.
- `styles.css`: layout and responsive styles.
- `theme.css`: colour palette, client cards, logos and typography.
- `assets/audrey.jpg`: portrait provided by Audrey.
- `assets/logos/`: locally served client and organisation logos.

Professional information comes from the supplied CV and Audrey’s additional details. Her volunteering, interests, portrait, LinkedIn profile, CGI responsibilities and workplace first aid qualification were provided by Audrey. No experience or certification dates have been invented for the translation.

The two ANCV assignments and the two most recent Airbus assignments are grouped, retaining the original dates and scope. The Airbus assignment from 2022–2023 remains separate. Industry and expertise filters can be combined and apply only to client assignments. Some assignments ran concurrently. Word documents and CV working files are not included in this repository or website.

The local folder `portfolio-v2` is excluded from the original repository. Its Git remote points only to `portfolio-EN`; changes here do not update the French portfolio.

## GitHub Pages

GitHub Pages uses **GitHub Actions** as its publishing source in **Settings → Pages → Build and deployment**. The workflow `.github/workflows/deploy-pages.yml` checks JavaScript syntax, prepares the static files and deploys the English website on pushes to `main`. It can also be run manually from **Actions**. No additional secrets or dependency installation are required.

Paths are relative so the website works under `/portfolio-EN/`. Only `index.html`, `styles.css`, `theme.css`, `app.js`, `experiences.js`, `.nojekyll` and the `assets/` folder are deployed. Preview tools and this README are not published as part of the site.

## Logos and certification links

The CGI logo comes from the supplied CV. Its SVG wrapper preserves the original image while cropping asymmetric white margins. The green SST logo comes from https://www.lonasante.com/wp-content/uploads/2026/03/logo-sst-vert-HD-niveau-acteur-Source-INRS.png and retains its original colours and proportions.

Certification links were supplied by Audrey. The Product Owner and Scrum Master credentials link to her Scrum.org profile: https://www.scrum.org/user/805818. The Adobe Experience Manager and Adobe Analytics credential titles match the supplied verification pages.

## Search engine indexing

The page retains the `noindex, nofollow, noimageindex` robots directive. There is no `robots.txt` block, so crawlers can read the directive. The published website is publicly accessible by its link; the directive requests exclusion from search results and does not restrict access.

## Interest illustrations

The vector illustrations are from Game-icons.net, licensed under CC BY 3.0 (https://creativecommons.org/licenses/by/3.0/). Attribution is also available under **Illustration credits** in the footer. The images are stored locally and were not generated using AI. Only colours and background transparency have been adapted.

- Badminton: Shuttlecock, Delapouite — https://game-icons.net/1x1/delapouite/shuttlecock.html
- Skiing: Skier, Delapouite — https://game-icons.net/1x1/delapouite/skier.html
- Board games: Rolling dices, Delapouite — https://game-icons.net/1x1/delapouite/rolling-dices.html
- Sewing: Sewing machine, Caro Asercion — https://game-icons.net/1x1/caro-asercion/sewing-machine.html

Interest cards flip on hover, keyboard focus and touch. Reduced-motion preferences are respected.
