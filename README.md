# JK_Couverture_28

Site vitrine **J.K COUVERTURE** — couvreur dans l'Eure-et-Loir (28).

Version **statique** (HTML / CSS / JS), sans dépendance serveur, prête à déployer.

## Domaine
https://jk-couvreur-28.fr

## Structure
- `index.html` — page principale
- `style.css` — styles du thème (couleurs de marque intégrées)
- `estimator.css` / `estimator.js` — estimateur de devis
- `attached_assets/`, `photo_jk/` — logo et photos de réalisations
- `manifest.json` — manifeste PWA

## Déploiement
Hébergement statique au choix : GitHub Pages, Netlify, Vercel, ou simple FTP.

> ⚠️ Le formulaire de contact / estimateur appelle `send-email.php` : sans backend PHP,
> l'envoi d'e-mail ne fonctionne pas. Brancher un service (Formspree, Web3Forms…) si besoin.
