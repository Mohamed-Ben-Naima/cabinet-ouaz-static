# Cabinet Dentaire Dr. Sarra Ouaz — site web

Site vitrine statique (HTML/CSS, sans étape de build) pour le cabinet dentaire
du Dr. Sarra Ouaz à Hiboun, Mahdia.

## Structure

- `index.html` — la page unique (en-tête, hero, à propos, services, exemples
  de soins, avis, horaires/localisation, pied de page)
- `assets/styles.css` — feuille de style unique
- `assets/photos/` — photos réelles du cabinet fournies par la cliente
- `assets/logo*.png`, `favicon*.png`, `icon-*.png` — déclinaisons du vrai
  logo du cabinet
- `robots.txt`, `sitemap.xml`, `site.webmanifest` — fichiers techniques

## Informations vérifiées utilisées

Toutes les informations affichées (téléphone, adresse, avis) proviennent de
la fiche Google Maps et de la page Facebook du cabinet. Aucun prix, horaire
fixe, récompense ou historique n'a été inventé — les horaires précis
n'étant pas confirmés, la page invite les patients à appeler le cabinet.

## Déploiement

Ce dossier est un site statique autonome : aucune étape de build n'est
nécessaire. Sur Netlify, le "Publish directory" est la racine du dépôt (`.`).
