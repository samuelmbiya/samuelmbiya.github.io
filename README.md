# Point8 Ventures website (static)

Plain HTML and CSS. No build step, no server code. Fonts (Montserrat, Inter) are bundled in `assets/fonts` under the SIL Open Font License (licence and notice files included).

## Structure
- `index.html`, `cto.html`, `blog.html`: English home, Point8 CTO page and blog
- `fr/index.html`, `fr/cto.html`, `fr/blog.html`: French versions
- `assets/`: stylesheet, fonts, logos, favicon, social preview image

## Publish on GitHub Pages
1. Create a repository and upload the contents of this folder to its root (the `index.html` must be at the top level).
2. In the repository: Settings, Pages, Build and deployment, Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
3. Wait a minute or two. The site appears at `https://<username>.github.io/<repo>/`.
   Note: the 404 page uses root-relative links, which only work when the site is served from a domain root (a custom domain, or a repo named `<username>.github.io`).

## Custom domain
1. Settings, Pages, Custom domain: enter your domain.
2. At your registrar add a CNAME record pointing `www` to `<username>.github.io` (and A records for the apex domain; see GitHub's docs).
3. Tick "Enforce HTTPS" once the certificate is issued.

## Before going live
- Replace every bracketed placeholder (list below).
- Set a real booking or email link on the "Book an intro call" buttons (currently they stay on the page).
- Blog: "Read post" links and the Subscribe button are not wired up yet (no post pages or mailing service). Add post pages and a subscribe link or form.
- In each page's `<head>`, make `og:image` an absolute URL (https://yourdomain/assets/og-image.png) so social previews work, and add a sitemap once the domain is known.
- Replace the PNG logos with SVGs if you have them: the 500px PNG looks soft on large screens.
- Have a native French speaker review the French copy.

## Placeholders still in the pages
- [DATE]
- [DESCRIBE WHEN READY]
- [DEUX OU TROIS PHRASES : votre parcours technique, les types de produits que vous avez construits ou dirigés, et pourquoi vous travaillez avec des fondateurs en phase de démarrage.]
- [FEATURED IMAGE]
- [FEATURED POST TITLE]
- [FIXED FEE]
- [FORFAIT]
- [IMAGE À LA UNE]
- [LIEN OU FORMULAIRE D’ABONNEMENT]
- [LINKEDIN URL]
- [ONE SENTENCE: your specialist depth, and the sectors or regions you know best.]
- [ONE-SENTENCE SUMMARY]
- [PHOTO DE PORTRAIT]
- [PORTRAIT PHOTO]
- [POST TITLE]
- [RAISON SOCIALE ET NUMÉRO]
- [RATE]
- [REGISTERED NAME AND NUMBER]
- [RÉSUMÉ DE L’ARTICLE EN DEUX PHRASES.]
- [RÉSUMÉ EN UNE PHRASE]
- [SUBSCRIBE LINK OR FORM]
- [TARIF]
- [TITRE DE L’ARTICLE À LA UNE]
- [TITRE DE L’ARTICLE]
- [TWO OR THREE SENTENCES: your technical background, the kinds of products you have built or led, and why you work with early-stage founders.]
- [TWO-SENTENCE SUMMARY OF THE POST.]
- [UNE PHRASE : votre expertise de pointe, et les secteurs ou régions que vous connaissez le mieux.]
- [URL LINKEDIN]
- [VOTRE ADRESSE E-MAIL]
- [VOTRE NOM]
- [VOTRE VILLE]
- [YOUR CITY]
- [YOUR EMAIL ADDRESS]
- [YOUR NAME]
- [À DÉCRIRE QUAND LE CONCEPT SERA PRÊT]
