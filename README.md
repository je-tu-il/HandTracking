# 🖐️ HandTracking — Air Drawing Canvas with MediaPipe

[![Live Demo](https://img.shields.io/badge/Demo%20en%20Ligne-Essayer%20avec%20sa%20webcam-success?style=for-the-badge&logo=github)](https://je-tu-il.github.io/HandTracking/)
[![HTML5 / JS](https://img.shields.io/badge/Tech-HTML5%20%7C%20Canvas%20%7C%20MediaPipe-blue.svg)](https://developers.google.com/mediapipe)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-0%20(CDN)-brightgreen.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Dessinez dans les airs avec votre webcam !  
> Une application web ultra-légère utilisant l'intelligence artificielle de Google MediaPipe pour détecter votre main et vous permettre d'écrire ou dessiner à l'écran par simple pincement de doigts (*pinch gesture*).

---

## ⚡ Essayer Immédiatement (Sans Installation)

👉 **[Lancer HandTracking en ligne : https://je-tu-il.github.io/HandTracking/](https://je-tu-il.github.io/HandTracking/)**

1. Ouvrez le lien dans un navigateur moderne (Chrome, Edge, Firefox, Safari).
2. Autorisez l'accès à la webcam.
3. Placez votre main devant la caméra :
   - 🤏 **Pincez l'index et le pouce** pour tracer un trait.
   - ✋ **Ouvrez la main** pour déplacer le curseur sans dessiner.
   - 🎨 Utilisez la palette de gauche pour changer la couleur ou basculer sur la gomme.

---

## ✨ Fonctionnalités

- 🤖 **Détection Visuelle par IA (MediaPipe Hands)** : Suivi temps réel des 21 repères de la main sans aucun capteur matériel supplémentaire.
- 🤏 **Geste Naturel de Pincement (Pinch-to-draw)** : Algorithme avec hystérèse pour éviter les faux contacts et tremblements.
- 🪞 **Rendu Miroir Intuitif** : Le squelette de la main et le flux vidéo sont automatiquement mis en miroir pour une écriture naturelle.
- 🎨 **Boîte à Outils Complète** :
  - Nuancier de couleurs
  - Curseur d'épaisseur de trait
  - Gomme
  - Boutons Annuler / Rétablir
  - Export de votre création en image PNG
- 🔒 **100% Respect de la Vie Privée** : Le flux vidéo de votre webcam reste exclusivement dans votre navigateur et n'est jamais transmis à un serveur.

---

## 🛠️ Lancement Local

Aucun outil de build n'est nécessaire. Clonez et ouvrez directement `index.html` :

```bash
git clone https://github.com/je-tu-il/HandTracking.git
cd HandTracking
```
Ouvrez simplement `index.html` dans votre navigateur ou via un serveur local :
```bash
python -m http.server 8000
```

---

## 📄 Licence

Ce projet est sous licence MIT. Libre d'utilisation et d'expérimentation.
