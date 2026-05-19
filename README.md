# 🔧 Liste By Cisepz — Déploiement

## Fichiers inclus
- `index.html` — L'application complète
- `manifest.json` — Config PWA (installation mobile)
- `sw.js` — Service Worker (mode hors-ligne)
- `icon-192.png` / `icon-512.png` — À ajouter (icônes de l'app)

---

## 🚀 Option 1 : Netlify (le plus simple — 2 minutes)

1. Allez sur **https://netlify.com** → créez un compte gratuit
2. Cliquez **"Add new site" → "Deploy manually"**
3. **Glissez-déposez ce dossier** `liste-cisepz/` dans la zone de dépôt
4. Votre app est en ligne ! Netlify vous donne un lien du type :
   `https://liste-cisepz.netlify.app`
5. (Optionnel) Allez dans Site Settings → Domain → pour personnaliser l'URL

---

## 🚀 Option 2 : GitHub Pages

1. Créez un compte sur **https://github.com**
2. Cliquez **"New repository"** → nommez-le `liste-cisepz` → Public → Create
3. Uploadez les 3 fichiers (`index.html`, `manifest.json`, `sw.js`)
4. Allez dans **Settings → Pages → Source : main branch**
5. Votre app est disponible sur :
   `https://votre-pseudo.github.io/liste-cisepz`

---

## 📱 Installer comme app mobile

### iPhone (Safari)
1. Ouvrez le lien dans Safari
2. Appuyez sur le bouton **Partager** (carré avec flèche)
3. Sélectionnez **"Sur l'écran d'accueil"**
4. L'app apparaît comme une vraie application !

### Android (Chrome)
1. Ouvrez le lien dans Chrome
2. Une bannière "Installer l'app" apparaît automatiquement
3. Ou : menu ⋮ → **"Ajouter à l'écran d'accueil"**

---

## 🖼️ Icônes (optionnel mais recommandé)

Pour avoir une belle icône sur l'écran d'accueil :
- Créez deux images PNG du logo CISEPZ :
  - `icon-192.png` (192×192 pixels)
  - `icon-512.png` (512×512 pixels)
- Placez-les dans le même dossier que `index.html`

Sans les icônes, l'app fonctionne quand même (icône par défaut).

---

## ✅ Fonctionnalités

- ✓ Fonctionne **hors-ligne** (Service Worker)
- ✓ **Données sauvegardées** localement sur l'appareil
- ✓ Installable comme **app native** iPhone & Android
- ✓ Envoi par **Email** et **WhatsApp**
- ✓ 11 types de réseaux, base matériaux complète
