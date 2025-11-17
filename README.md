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

---

## Checklist

 One-page portfolio (UX + dev) OK
 Héros avec promesse claire OK
 CTA principal « Demander un devis » OK
 Section Services OK
 Section Projets avec 3 cartes + KPI (+22% conv, etc.) OK
 Section Compétences OK
 Section Contact avec mailto: + formulaire HTML OK
 Accessibilité : skip-link, alt pertinents, focus visible, contraste OK
 SEO : <title>, meta description, Open Graph, lien sitemap.xml OK
 Bootstrap 5 (CDN) + CSS custom OK
 Navbar sticky (.sticky-top) OK
 Carte projet avec badge Nouveau chevauchant l’image OK
 Images avec width/height + loading="lazy" + decoding="async" OK
 CSS unique (minifié ou optimisé) OK
 Git : branche feature/hero, PR, squash, tag v1.0.0 NOK
 Issue « Fix: CTA non cliquable sur mobile » NOK
 GitHub Pages activé NOK

---

## Scores Lighthouse
Tests réalisés en local (Chrome Lighthouse) sur la page index.html :
Performance : 100
Accessibilité : 96
Best Practices : 100
SEO : 100

<img width="707" height="713" alt="ScoresLighthouse" src="https://github.com/user-attachments/assets/987b3f70-506d-4b44-a1e1-cae26c1d524c" />

Tutoriel: Comment faire le Lighthouse et la capture
   ### En local (fichier `index.html` ouvert):
      1. Ouvre `index.html` dans Chrome.
      2. Ouvre les DevTools : `F12` ou clic droit → **Inspecter**.
      3. Onglet **Lighthouse**.
      4. Coche :
         - Mode : *Desktop* (et éventuellement *Mobile* si tu veux),
         - Catégories : Perf, A11y, Best Practices, SEO.
      5. Clique sur **Analyze page load**.
      6. Une fois le rapport généré :
         - prends une capture d’écran des scores,
         - enregistre-la dans `assets/images/lighthouse.png`.
      7. Ajoute l’image dans ton README comme ci-dessus.
   ### Option B – après GitHub Pages
   1. Active GitHub Pages.
   2. Lance Lighthouse sur l’URL publique: https://yasmineattou.github.io/advanced-portfolio-YasmineAttou/.
   3. Même processus : capture, image dans `assets/images/lighthouse.png`.
---
   
