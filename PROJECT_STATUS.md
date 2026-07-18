# Visionnariste Marketing — Statut Projet Site Agence

**Dernière mise à jour :** 18 juillet 2026  
**URL de déploiement :** https://visionnariste-site.vercel.app  
**Dossier source :** `/Users/meyghane/PROJECTS_2026/AGENCE_SMMA/VISIONNARISTE/MON SITE AGENCE PILOTE`  
**Règle de déploiement :** `visionnariste-maquette.html` → copier en `index.html` → `vercel --prod`

---

## CE QUI EST FAIT

### Design & UI
- [x] **Versus section** : redesignée (fond crème, colonnes blanc/noir, markers cercles, zero emoji)
- [x] **Portfolio cards** : 9 cartes remplacées (fini les "commerces locaux"), maintenant : Maison Éclat, Bloom Beauty, Auric Paris, Velda Studio, The Roam, Noé Skincare, Kova Paris, Oréa + doublons scroll
- [x] **Logo nav** : `assets/logo-visionnariste-nobg.png` (transparent, fond retiré, 500×500) — sur TOUTES les pages (20 fichiers)
- [x] **Favicon** : `assets/favicon.png` (VM monogramme, 1024×1024) — `<link rel="icon">` sur toutes les pages
- [x] **Bouton "Nos Services"** du hero → redirige vers `services.html`

### Fonts
- [x] **Aileron** (local, 4 weights) dans `assets/fonts/` : regular 400, semibold 600, bold 700, heavy 800-900
- [x] `@font-face` déclaré sur toutes les pages (chemins `assets/fonts/` racine, `../assets/fonts/` pour blog/)
- [x] **Bodoni Moda** et **Playfair Display** ELIMINÉS de tout le site
- [x] Stack CSS : `--font:'Aileron','Plus Jakarta Sans','Inter',sans-serif`

### Contenu Blog
- [x] **blog.html** : Rewrite complet (titre "Paid Ads, Scaling, Performance."), 12 cartes, filtres catégorie, positionnement e-commerce/marques en croissance
- [x] **15 articles** dans `blog/` :
  - `meta-ads-ecommerce-scaling.html`
  - `tiktok-ads-mode-beaute-2026.html`
  - `google-ads-shopping-roas-maximum.html`
  - `snapchat-ads-guide-complet-2026.html`
  - `strategie-multi-plateforme-meta-tiktok-google.html`
  - `meta-ads-marche-americain.html`
  - `creative-brief-publicite-digitale.html`
  - `roas-vs-poas-quelle-metrique.html`
  - `meta-ads-bresil-guide-2026.html`
  - `attribution-multi-touch-ecommerce.html`
  - `scaling-budget-pub-sans-perdre-roas.html`
  - `audit-compte-meta-ads-checklist.html`
  - `tiktok-ads-pme-france.html`
  - `meta-ads-commerce-local.html`
  - `google-business-profile-2026.html`
- [x] Tous les articles ont : Schema.org Article, canonical, OG tags, CTA → `index.html#footer-contact`, nav avec logo PNG, Aileron

### SEO Technique
- [x] `sitemap.xml` : 16 URLs
- [x] Canonical URLs sur toutes les pages
- [x] OG tags sur toutes les pages
- [x] Schema.org Article sur tous les articles

---

## CE QUI RESTE À FAIRE (TO-DO)

### URGENT — Bloquant pour le live
- [x] **Formspree** : ID `mykrwjke` appliqué → `https://formspree.io/f/mykrwjke` ✓
- [x] **SIRET** : `Visionnariste Marketing — Micro-entreprise — SIRET : 88809943900034` ✓ (statut radiation à clarifier avec INPI/URSSAF)
- [x] **Témoignages** : Sofia A. (ROAS 1.8→4.1) + Jérémy L. (cosmétique) insérés avant la FAQ ✓

### Contenu à créer
- [ ] **Image OG** : Créer une image 1200×630px → sauvegarder en `assets/og-image.jpg` (mettre à jour les balises `og:image` dans le HTML)
- [ ] **Photo de profil** : Intégrer dans la section hero (le slot est prévu)
- [ ] **Témoignages** : 2 témoignages clients anonymisés pour la section social proof
- [ ] **Vidéo 60s** : Le script est préparé, il reste à enregistrer et intégrer

### Liens & Intégrations
- [ ] **Numéro WhatsApp** : À ajouter dans footer et sticky CTA (chercher `href="https://wa.me/..."` dans le code)
- [ ] **Calendly** : Créer l'event "Audit Gratuit 30 min" sur calendly.com, remplacer le lien `#footer-contact` sur les CTAs principaux
- [ ] **Google Search Console** : Soumettre `sitemap.xml` après le prochain déploiement Vercel

### Vérifications visuelles
- [ ] **Taille logo nav** : Actuellement `height:34px` — peut nécessiter ajustement visuel selon rendu réel
- [ ] **Articles blog** : Certains (`meta-ads-commerce-local.html`, `tiktok-ads-pme-france.html`, `google-business-profile-2026.html`) ont un positionnement à vérifier (anciens avant le rewrite)

---

## RÈGLES ABSOLUES DU PROJET

### Copywriting — CONTRAINTES LÉGALES
- JAMAIS nommer : Rabanne, Dries Van Noten, Jean Paul Gaultier, Publicis
- JAMAIS écrire : "J'ai géré les campagnes de [marque]"
- Formulations SAFE : "Formée aux standards des plus grandes agences parisiennes", "Méthodes des Grands Comptes luxe et mode"
- JAMAIS d'em dash `—` NULLE PART (ni copywriting, ni titres, ni meta, ni commentaires HTML) — règle or du 17 juil 2026, appliquée sur tout le site ✓
- JAMAIS d'emojis dans le code

### Cible client
- E-commerces en croissance, marques mode/beauté/luxe
- Budget mensuel : 2 000€ à 20 000€/mois
- PAS de commerces locaux, PAS de PME généralistes

### Fonts
- Aileron (local) + Plus Jakarta Sans (Google) UNIQUEMENT
- JAMAIS Bodoni Moda, JAMAIS Playfair Display

### Couleurs
- `--blue: #1a3ff0`
- `--bg: #fff` / `--bg2: #f7f6f2`
- `--muted: rgba(0,0,0,.45)`
- Sections dark : `#111` ou `#080808`

---

## ASSETS DANS LE PROJET

| Fichier | Taille | Usage |
|---|---|---|
| `assets/logo-visionnariste-nobg.png` | 116KB, 500×500 | Logo nav (transparent) |
| `assets/favicon.png` | 52KB, 1024×1024 | Favicon VM monogramme |
| `assets/visionnariste-wordmark.png` | 62KB, 970×335 | Logo wordmark (fond noir) |
| `assets/visionnariste-logo.png` | 77KB, 1024×1024 | Logo carré (fond noir) |
| `assets/fonts/aileron.regular.otf` | — | Aileron 400 |
| `assets/fonts/aileron.semibold.otf` | — | Aileron 600 |
| `assets/fonts/aileron.bold.otf` | — | Aileron 700 |
| `assets/fonts/aileron.heavy.otf` | — | Aileron 800-900 |
| `assets/hermood-thumb.jpg` | — | Portfolio card Hermood |
| `assets/alwasil-thumb.jpg` | — | Portfolio card Al-Wasil |
| `assets/orion-thumb.jpg` | — | Portfolio card Orion |

---

## STRUCTURE DES FICHIERS

```
MON SITE AGENCE PILOTE/
├── visionnariste-maquette.html  ← SOURCE (toujours éditer ici)
├── index.html                   ← copie de la maquette (deploy)
├── services.html
├── tarifs.html
├── blog.html
├── sitemap.xml
├── PROJECT_STATUS.md            ← ce fichier
├── CLAUDE.md                    ← règles pour Claude
├── assets/
│   ├── fonts/ (4 fichiers Aileron .otf)
│   ├── logo-visionnariste-nobg.png
│   ├── favicon.png
│   ├── hermood-thumb.jpg
│   ├── alwasil-thumb.jpg
│   └── orion-thumb.jpg
└── blog/
    └── (15 articles HTML)
```
