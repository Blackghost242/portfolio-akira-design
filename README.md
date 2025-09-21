# Portfolio Akira Design

Portfolio professionnel d'infographie et design visuel.

## Hébergement sur GitHub Pages

Ce projet est configuré pour être hébergé sur GitHub Pages. Voici les étapes pour le déployer :

### 1. Configuration GitHub Pages

1. **Poussez votre code sur GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Activez GitHub Pages**
   - Allez sur votre dépôt GitHub
   - Cliquez sur "Settings" (Paramètres)
   - Dans la section "Pages", sélectionnez "Deploy from a branch"
   - Choisissez la branche "main" et le dossier "/ (root)"
   - Cliquez sur "Save"

3. **Accédez à votre site**
   - Votre site sera disponible à l'adresse : `https://[votre-nom-utilisateur].github.io/[nom-du-depot]/`

### 2. Structure du projet

```
/
├── index.html          # Page principale
├── css/                # Feuilles de style
│   ├── style.css
│   └── aos.css
├── js/                 # Scripts JavaScript
│   ├── main.js
│   └── aos.js
├── images/             # Images et médias
│   ├── Akiraméta.png
│   ├── Akilogo.png
│   └── [autres images]
├── .nojekyll          # Configuration GitHub Pages
└── README.md          # Ce fichier
```

### 3. Fonctionnalités

- **Design responsive** : Adapté à tous les écrans
- **Animations** : Effets de défilement avec AOS
- **Portfolio interactif** : Galerie avec lightbox
- **Formulaire de contact** : Intégré avec Formspree
- **Réseaux sociaux** : Liens vers les profils sociaux

### 4. Technologies utilisées

- HTML5 / CSS3
- JavaScript (ES6+)
- GSAP (animations)
- AOS (Animate On Scroll)
- Font Awesome (icônes)
- Google Fonts (typographie)

### 5. Personnalisation

Pour personnaliser le site :

1. **Modifier les informations personnelles** dans `index.html`
2. **Changer les couleurs** dans `css/style.css`
3. **Ajouter vos projets** dans la section portfolio
4. **Mettre à jour les liens** vers vos réseaux sociaux

### 6. Support

Pour toute question ou problème, n'hésitez pas à créer une issue sur GitHub.

---

**Développé avec ❤️ par Akira Design**
