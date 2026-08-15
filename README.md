# Célime KANON — Portfolio officiel

Site portfolio animé et professionnel de **Richmond BIO alias Célime KANON** — Créateur de contenu AI & Web Entrepreneur.

## Pages

| Page | Rôle |
|------|------|
| `index.html` | Accueil animé : présentation, statistiques, offres, aperçu des projets et articles |
| `portfolio.html` | Compétences & réalisations (filtres par catégorie, photos/vidéos) |
| `about.html` | Biographie avec photo, chiffres clés et parcours |
| `contact.html` | Formulaire de commande (nom, prénom, WhatsApp...) envoyé directement sur WhatsApp |
| `admin.html` | Espace d'administration sans code |

## Interface d'administration (sans toucher au code)

Ouvrez `admin.html` et connectez-vous.

- **Mot de passe par défaut :** `ck2024` (à changer dans l'onglet *Données*)
- Modifiez : offres et prix, portefeuille (photos/vidéos), compétences, biographie, articles, réseaux sociaux, statistiques
- **Thème :** couleurs, mode sombre/clair et police — avec aperçu en direct
- Médias : collez une URL **ou** uploadez une image/vidéo (3 Mo max)

## Comment ça marche

1. Les modifications sont enregistrées **dans le navigateur** (localStorage) et visibles immédiatement.
2. Pour publier sur GitHub : onglet *Données* → **Télécharger content.json** → remplacez le fichier dans votre dépôt.
3. Le site charge automatiquement `content.json` (les visiteurs voient la dernière version).

## Mise en ligne sur GitHub (gratuit)

1. Créez un dépôt sur [github.com](https://github.com) (ex : `mon-portfolio`).
2. Uploadez tout le contenu du dossier `CK` à la racine du dépôt.
3. **Settings → Pages** → source : branche `main`, dossier `/ (root)` → Save.
4. Votre site est en ligne : `https://votre-pseudo.github.io/mon-portfolio/`

## Fichiers clés

- `content.json` — tout le contenu du site (modifiable dans l'admin)
- `js/app.js` — logique du site public
- `js/admin.js` — interface d'administration
- `css/style.css` — thème principal (variables CSS)
- `css/admin.css` — styles du panneau d'administration

## Contact

- Email : richmondbio88@gmail.com
- WhatsApp : +229 01 92 46 32 85
