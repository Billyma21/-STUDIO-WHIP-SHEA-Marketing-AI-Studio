# -STUDIO-WHIP-SHEA-Marketing-AI-Studio
L'Art de la Publicité Produit - Générez des visuels et vidéos publicitaires ultra-professionnels pour vos cosmétiques grâce à l'Intelligence Artificielle.

> **L'Art de la Publicité Produit** — Générez des visuels et vidéos publicitaires ultra-professionnels pour vos cosmétiques grâce à l'Intelligence Artificielle.

---

## ✨ Aperçu

**Studio Whip & Shea** est une application desktop Windows propulsée par l'IA (Gemini) dédiée à la création publicitaire premium pour cosmétiques gourmands. Des rendus si onctueux qu'ils déclenchent l'achat immédiat.

> ⚠️ **Application privée — Tous droits réservés à MAAYOUD.B**
> Toute utilisation, modification ou redistribution sans accord préalable est strictement interdite.

---

## 🖥️ Fonctionnalités

| Fonctionnalité | Description |
|---|---|
| 🖼️ **Image Studio** | Génération de 4 visuels marketing cohérents et premium simultanément |
| 🎬 **Video Studio** | Création de concepts vidéo publicitaires |
| 📚 **Bibliothèque** | Historique de toutes vos créations, classées par thématique |
| 🎨 **Thèmes** | Nuage Rose, Gourmandise, Luxe Minimaliste, Éclat Solaire |
| 🔑 **Clé API perso** | Panneau de paramètres pour configurer votre propre clé Gemini |
| 📦 **Multi-produits** | Compatible cosmétiques, food, lifestyle et plus |

---

## 🚀 Installation (Windows)

### Prérequis
- Windows 10 / 11 (x64)
- Node.js v18 ou supérieur
- Une clé API [Google Gemini](https://aistudio.google.com/app/apikey)

### Lancer depuis les sources

```bash
# 1. Cloner le dépôt
git clone https://github.com/VOTRE-USERNAME/studio-whip-shea.git
cd studio-whip-shea

# 2. Installer les dépendances
npm install

# 3. Configurer la clé API
# Renommer .env.example en .env et y ajouter votre clé :
# GEMINI_API_KEY=votre_cle_ici

# 4. Lancer en mode développement
npm run electron:dev
```

### Générer l'installateur Windows `.exe`

```bash
# Depuis un CMD administrateur :
npm run electron:build
```

Les fichiers générés dans `release/` :
- `Studio Whip & Shea Setup 1.0.0.exe` — Installateur avec assistant
- `Studio Whip & Shea 1.0.0.exe` — Version portable (clé USB ready ✅)

---

## 🗂️ Structure du projet

```
studio-whip-shea/
├── electron/          # Main process Electron
│   └── main.cjs
├── src/               # Application React (Vite + Tailwind)
├── build/             # Icônes et ressources du build
├── dist/              # Build compilé (généré)
├── release/           # Installateurs .exe (généré)
├── package.json
└── vite.config.ts
```

---

## 🛠️ Stack Technique

- **Frontend** : React 19 + TypeScript + Tailwind CSS v4
- **Desktop** : Electron 40
- **Build** : Vite 6 + electron-builder
- **IA** : Google Gemini API (`@google/genai`)
- **Animations** : Motion (Framer Motion)

---

## 📸 Screenshots

> *Visuels à venir — Rendus marketing générés par l'application*

---

## 📄 Licence & Droits d'Auteur

```
© 2026 STUDIO WHIP & SHEA — Créé par MAAYOUD.B
Tous droits réservés.

Toute utilisation commerciale ou personnelle est soumise à un accord préalable.
Il est strictement interdit de modifier, copier ou redistribuer ce code
sans l'accord explicite du créateur. Tout abus est passible de poursuites.
```

---

*Propulsé par Gemini AI — Imaginé & créé par **MAAYOUD.B***
