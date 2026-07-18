# Règles Visionnariste — Site Agence Pilote

## Polices — RÈGLE ABSOLUE

**Polices autorisées uniquement :**
- Corps / headings : `'Plus Jakarta Sans', 'Inter', sans-serif`
- Variable CSS : `--font: 'Plus Jakarta Sans','Inter',sans-serif`
- Variable CSS : `--serif: 'Plus Jakarta Sans','Inter',sans-serif` (même police, pas de vraie serif)
- Décoratif (rare) : `'Bangers', Impact, cursive` (uniquement pour effets graphiques homepage)

**Google Fonts à charger :**
```
https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800;900&display=swap
```

**INTERDIT :**
- Bodoni Moda
- Playfair Display
- Georgia (sauf fallback natif navigateur, jamais explicitement nommée)
- Toute autre police serif externe

## Couleurs
- `--blue: #1a3ff0`
- `--bg: #fff`
- `--bg2: #f7f6f2`
- `--border: rgba(0,0,0,.08)`
- `--muted: rgba(0,0,0,.45)`
- Dark sections : `#111` ou `#080808`

## Copywriting — RÈGLE LÉGALE
- JAMAIS nommer Rabanne, Dries Van Noten, Jean Paul Gaultier, Publicis
- Formulations safe : "Formée aux standards des plus grandes agences parisiennes", "Méthodes des Grands Comptes luxe et mode"
- JAMAIS d'em dash `—` dans le copywriting visible
- JAMAIS d'emojis (utiliser texte ou SVG)
- Cible : e-commerces en croissance, marques mode/beauté/luxe, budgets 2K-20K€/mois — PAS commerces locaux

## Fichiers
- Source principale : `visionnariste-maquette.html` → copier en `index.html` avant chaque déploiement Vercel
- Pages : index.html, services.html, tarifs.html, blog.html, blog/*.html
- Formspree : remplacer `VOTRE_ID_FORMSPREE` dans le formulaire de contact
