# 📊 Application de suivi des ventes – La Ferme de Demain

Cette application web permet d’enregistrer facilement les **ventes quotidiennes** de fruits et légumes, avec génération de graphiques et export des données.

## 🚀 Fonctionnalités
- 📅 Saisie quotidienne des ventes
- 🍓 Produits inclus par défaut : Fraises, Framboises, Haricots verts, Radis, Petits pois, Pommes de terre
- ➕ Ajout / suppression de produits et clients via l’écran Paramètres
- 📈 Graphiques interactifs :
  - Quantités vendues par produit
  - Ventes totales par période
- 📤 Export des données au format **CSV** ou **Excel**
- 📥 Import des données sauvegardées (JSON)
- 📱 Compatible mobile et installable comme **application PWA**
- ⚡ Fonctionne **hors ligne** grâce au Service Worker

## 🛠 Installation
1. Télécharger tous les fichiers de ce dépôt (`ventes_app.html`, `manifest.webmanifest`, `sw.js`, dossier `icons/`).
2. Héberger sur un service en ligne (GitHub Pages, Netlify, etc.).
3. Ouvrir l’URL sur un navigateur **Chrome** ou **Edge**.
4. Cliquer sur "Ajouter à l’écran d’accueil" pour installer l’application sur mobile.

## 🌐 Hébergement sur GitHub Pages
1. Aller dans **Settings** > **Pages**
2. Sélectionner la branche `main` et le dossier `/root`
3. Cliquer sur **Save**
4. Ouvrir l’URL fournie (exemple : `https://toncompte.github.io/ventes-ferme/ventes_app.html`)

## 📸 Capture d’écran
*(ajouter ici une image de l’application)*

---

💡 **Astuce :** Pour restaurer vos données précédentes, utilisez la fonction **Importer JSON** et sélectionnez le fichier `ventes_import_sans_prix.json`.
