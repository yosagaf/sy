# Guide de Déploiement Gratuit

## Option 1 : GitHub Pages (Recommandé) ⭐

### Étapes :

1. **Créer un repository GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/VOTRE_USERNAME/portfolio.git
   git push -u origin main
   ```

2. **Activer GitHub Pages**
   - Aller sur votre repository GitHub
   - Settings → Pages
   - Source : sélectionner "main" branch
   - Folder : `/ (root)`
   - Save

3. **Votre site sera disponible à :**
   `https://VOTRE_USERNAME.github.io/portfolio/`

---

## Option 2 : Netlify (Très Simple) 🚀

### Méthode Drag & Drop :
1. Aller sur [netlify.com](https://www.netlify.com)
2. Créer un compte gratuit
3. Glisser-déposer le dossier du portfolio dans Netlify
4. Votre site est déployé instantanément !

### Méthode Git :
1. Connecter votre repository GitHub à Netlify
2. Netlify détecte automatiquement le site
3. Déploiement automatique à chaque push

**URL générée :** `https://votre-site.netlify.app`

---

## Option 3 : Vercel (Rapide) ⚡

1. Installer Vercel CLI :
   ```bash
   npm i -g vercel
   ```

2. Déployer :
   ```bash
   cd portfolio
   vercel
   ```

3. Suivre les instructions
4. Votre site est déployé !

**URL générée :** `https://votre-site.vercel.app`

---

## Option 4 : Cloudflare Pages (Gratuit & Rapide) 🌐

1. Aller sur [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connecter votre repository GitHub
3. Build settings :
   - Build command : (laisser vide)
   - Build output directory : `/`
4. Deploy

**URL générée :** `https://votre-site.pages.dev`

---

## Option 5 : Surge.sh (Ultra Simple) 💨

1. Installer Surge :
   ```bash
   npm install -g surge
   ```

2. Déployer :
   ```bash
   cd portfolio
   surge
   ```

3. Choisir un nom de domaine
4. C'est fait !

**URL générée :** `https://votre-nom.surge.sh`

---

## Recommandation

**Pour débuter rapidement :** Netlify (drag & drop)
**Pour intégration Git :** GitHub Pages ou Netlify
**Pour performance :** Cloudflare Pages ou Vercel

Toutes ces options sont **100% gratuites** pour les sites statiques !

