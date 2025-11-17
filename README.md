# advanced-portfolio-YasmineAttou

Mini-portfolio one-page pour présenter les services de freelance UX & développement web.

---

## Pitch

Je suis freelance UX & développeuse web (front & back) basée en Belgique.  
Ce mini-portfolio sert à présenter :
- ce que je fais (UX, front, back, audits),
- des preuves par des projets avec KPI,
- un moyen simple de me contacter pour **demander un devis**.

---

## Stack & architecture

- **HTML5** (one-page)
- **CSS** custom (`assets/css/styles.css`)
- **Bootstrap 5** (CDN, CSS uniquement)
- **Font Awesome** (icônes, CDN)
- Aucune dépendance JS obligatoire (scroll doux côté CSS possible)
- Images optimisées (`loading="lazy"`, `decoding="async"`, dimensions définies)

Structure :
- `index.html` : page principale
- `assets/css/styles.css` : styles globaux
- `assets/images/` : photos, visuels de projets, capture Lighthouse

---

## Lancer le projet

Pas de build nécessaire.

1. Cloner le repo :

   ```bash
   git clone https://github.com/yasmineattou/advanced-portfolio-YasmineAttou.git
   cd advanced-portfolio-YasmineAttou
2. Ouvrir index.html dans un navigateur :
soit double-clic sur index.html,
soit via un petit serveur local (ex. VS Code Live Server).
