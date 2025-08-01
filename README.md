# La Cocotte à Histoire - Archives du Roannais

## Déploiement Internet

Cette application est prête à être déployée sur internet. Voici les étapes :

### 1. Structure des fichiers
```
dist/
├── index.html              # Page principale
├── assets/                 # Fichiers CSS et JS optimisés
│   ├── index-CxHqPkM5.css
│   └── index-c0pCghI6.js
├── PhotoDocuments/         # Images des documents d'archives
│   ├── albertthomas.JPG
│   ├── caisseEpargne*.JPG
│   ├── eglise_*.JPG
│   ├── hoteldeVille_*.JPG
│   ├── promenades_ensemble.JPG
│   ├── rempart_lettre.JPG
│   ├── theatre_*.JPG
│   └── Vacheresse*.JPG
├── cocotte.png            # Image de la cocotte
├── papier.jpg             # Texture de fond
├── haut.png               # Image décorative
├── 2.png                  # Image décorative
├── qrcode-cocotte.png     # QR code
└── vite.svg               # Icône
```

### 2. Déploiement
- **Serveur web** : Uploadez tout le contenu du dossier `dist/` sur votre serveur web
- **GitHub Pages** : Déployez automatiquement depuis le dossier `dist/`
- **Netlify/Vercel** : Connectez le dossier `dist/` comme dossier de build

### 3. Configuration requise
- Serveur web supportant les fichiers statiques
- Pas de configuration serveur spéciale requise
- Compatible avec tous les navigateurs modernes

### 4. Fonctionnalités
- ✅ Jeu interactif de la cocotte en papier
- ✅ 8 questions historiques sur Roanne
- ✅ Carrousel d'images des documents d'archives
- ✅ Design responsive et accessible
- ✅ Animations fluides
- ✅ Modal pour agrandir les images

### 5. Optimisations incluses
- ✅ Fichiers CSS et JS minifiés
- ✅ Images optimisées
- ✅ Métadonnées SEO
- ✅ Configuration pour internet (`base: './'`)

### 6. Test local
Pour tester localement avant déploiement :
```bash
cd dist
python -m http.server 8000
# Ou avec Node.js
npx serve .
```

L'application sera accessible sur `http://localhost:8000`

---

**Archives municipales et communautaires du Roannais**  
*Journées Européennes du Patrimoine* 