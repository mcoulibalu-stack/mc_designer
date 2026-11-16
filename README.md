# 📁 L'Informagicien - Portfolio Web | Structure Organisée

## 🎯 Structure du Projet

Votre projet a été réorganisé selon une structure professionnelle et maintenable :

```
new_projet/
├── index.html              # Page d'accueil principale
│
├── css/                    # Feuilles de styles
│   ├── style.css           # Styles principaux
│   └── animation.css       # Animations et effets
│
├── js/                     # Scripts JavaScript
│   └── script.js           # Logique interactive (menu, animations)
│
├── assets/                 # Ressources multimédia
│   ├── images/             # Images et visuels
│   │   ├── favicon.ic
│   │   ├── profile.jpg
│   │   ├── projet1.jpg
│   │   ├── projet2.jpg
│   │   └── ... (autres images)
│   │
│   ├── videos/             # Vidéos et contenus motion
│   │   ├── ECO-LIGHT 3.mp4
│   │   └── ... (autres vidéos)
│   │
│   └── fonts/              # (Réservé) Fonts personnalisées
│
├── pages/                  # Pages HTML secondaires
│   ├── portfolio.html      # Page portfolio détaillée
│   ├── formulaire.html     # Formulaire pour motion design
│   └── projetform.html     # Formulaire de projet
│
├── docs/                   # Documentation et ressources
│   └── cv.pdf              # Curriculum vitae
│
└── README.md              # Ce fichier
```

---

## 📋 Avantages de cette Organisation

✅ **Clarté** - Chaque type de fichier a sa place  
✅ **Scalabilité** - Facile d'ajouter de nouvelles pages ou ressources  
✅ **Maintenance** - Facile à modifier et maintenir  
✅ **Performance** - Structure optimisée pour les navigateurs  
✅ **SEO** - Organisation logique favorise l'indexation  

---

## 🔗 Chemins des Fichiers - Référence

### Depuis `index.html` (racine)
```
<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/animation.css">
<script src="js/script.js"></script>
<img src="assets/images/mon-image.jpg">
<video src="assets/videos/ma-video.mp4"></video>
<a href="docs/cv.pdf">Télécharger CV</a>
<a href="pages/portfolio.html">Portfolio</a>
```

### Depuis `pages/portfolio.html` (sous-dossier)
```
<link rel="stylesheet" href="../css/style.css">
<script src="../js/script.js"></script>
<img src="../assets/images/mon-image.jpg">
<video src="../assets/videos/ma-video.mp4"></video>
<a href="../index.html">Accueil</a>
```

---

## 📝 Prochaines Étapes Recommandées

1. **Ajouter un `index.html` vide dans `pages/`** (optionnel)
2. **Créer `404.html` pour les pages non trouvées**
3. **Ajouter `.gitignore` si vous versionnez avec Git**
4. **Créer des CSS séparés par section** (optionnel pour les grands projets)
   - `css/components/navbar.css`
   - `css/components/hero.css`
   - `css/components/footer.css`

---

## 🎨 Conseils de Maintenance

- ✏️ Placez toujours les images dans `assets/images/`
- 📹 Placez toujours les vidéos dans `assets/videos/`
- 📄 Placez toujours les pages HTML dans `pages/`
- 📚 Placez toujours la documentation dans `docs/`

---

## 📞 Notes de Votre Projet

- **Domaine** : Portfolio Créatif (Design, Motion Design, Développement Web)
- **Langue** : Français
- **Thème** : Dark mode avec accents cyan
- **Responsive** : Optimisé pour mobile et desktop

---

**Dernière mise à jour** : 2026-06-08
