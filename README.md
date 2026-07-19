# Documents légaux ContesÉveil Magique

Pages HTML prêtes pour Google Play / App Store (URLs HTTPS publiques).

## Fichiers

| Fichier | Usage Play Console |
|---------|-------------------|
| `privacy-fr.html` | **Politique de confidentialité** (FR) — URL principale recommandée CA/FR |
| `terms-fr.html` | **Conditions d’utilisation** (FR) |
| `privacy-en.html` | Privacy Policy (EN) |
| `terms-en.html` | Terms of Use (EN) |
| `index.html` | Page d’accueil des docs |

Contact : **conteseveil.studio@gmail.com**  
Package : **com.conteseveil.app**  
Version docs : **1.0** (2026-07-19)

## Contenu couvert (aligné produit)

- Compte parental 18+, enfant 3–6 ans sous supervision  
- Histoires / voix / images / coloriages IA  
- Album device-primary, paiements Stripe / Play  
- Pas de caméra obligatoire, pas de pub ciblée enfant  
- RGPD / PIPEDA / Loi 25 / principes COPPA  

## Publier en HTTPS (obligatoire Play)

### Option A — GitHub Pages (simple)

1. Pousser le dossier `legal/` sur GitHub  
2. Settings → Pages → déployer le dossier `/legal` (ou racine `docs/`)  
3. URLs du type :
   - `https://<user>.github.io/<repo>/privacy-fr.html`
   - `https://<user>.github.io/<repo>/terms-fr.html`

### Option B — Render Static Site

1. Nouveau **Static Site** pointant sur `legal/`  
2. Publish directory : `legal`  
3. Coller les URLs dans Play Console  

### Option C — Domaine perso

Copier le dossier `legal/` sur n’importe quel hébergeur statique (Netlify, Cloudflare Pages, etc.).

## Dans Play Console

- **Privacy policy** → URL de `privacy-fr.html` (ou EN si store EN)  
- **Terms** (si demandé) → `terms-fr.html`  

## Avertissement

Modèles adaptés au produit. **Pas un avis d’avocat.** Relire avant lancement commercial large ; ajouter adresse postale / raison sociale exacte si vous en avez une.
