# 🧠 HackSamAI – Votre Cerveau Numérique Augmenté

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![IndexedDB](https://img.shields.io/badge/IndexedDB-2D3748?logo=databricks&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
[![Mistral AI](https://img.shields.io/badge/Mistral%20AI-API-00e5ff)](https://mistral.ai)

> **HackSamAI** est une plateforme d'intelligence artificielle conversationnelle **100% côté client**, sans serveur, connectée à l'API Mistral AI.  
> Interface cyberpunk immersive, agents personnalisables, mémoire persistante, streaming, markdown, et bien plus.

---

## 🌟 Fonctionnalités

- **💬 Chat streaming** : réponses en temps réel, rendu **Markdown** + **coloration syntaxique** (code).
- **🤖 Agents IA personnalisables** : créez, éditez, dupliquez, exportez/importez vos agents (modèle, température, instructions, etc.).
- **🧠 Mémoire globale** : sauvegarde d'informations persistantes injectées dans les prompts pour des réponses contextuelles.
- **📂 Archives** : historique des conversations, recherche, favoris, suppression.
- **🔒 Sécurité** : clé API chiffrée en local avec **AES-GCM** (Web Crypto). Aucune donnée ne quitte votre navigateur.
- **📤📥 Import/Export** : sauvegardez/restaurez toutes vos données (conversations, agents, mémoire) en un clic.
- **📎 Multimodal** : analyse d'images (Pixtral Vision) et transcription audio (Voxtral).
- **🎤 Dictée vocale** via l'API Web Speech.
- **🎨 Thèmes** : Cyber (défaut), Midnight, Light – responsive mobile/desktop.
- **📊 Compteur de tokens** et barre de contexte.

---

## 🚀 Démo en ligne

Essayez HackSamAI directement depuis votre navigateur, **sans rien installer** :

👉 **[https://samymichel-bit.github.io/hacksamAI/](https://samymichel-bit.github.io/hacksamAI/)**

*(Assurez-vous que GitHub Pages est activé dans les paramètres du dépôt)*

---

## ⚙️ Installation locale

1. Téléchargez le fichier `index.html` (ou clonez le dépôt).
2. Ouvrez-le avec n'importe quel navigateur moderne (Chrome, Edge, Firefox).
3. Aucun serveur, aucune dépendance supplémentaire.

```bash
git clone https://github.com/samymichel-bit/hacksamAI.git
cd hacksamAI
# Ouvrez index.html
```

---

## 🔑 Obtenir une clé API (gratuit)

1. Rendez-vous sur [console.mistral.ai](https://console.mistral.ai)
2. Créez un compte (email ou OAuth Google).
3. Allez dans **API Keys** → **Create new key**.
4. Collez la clé dans HackSamAI via le bouton **⬡ API KEY**.

---

## 🛠️ Technologies utilisées

- **Frontend** : HTML5, CSS3, JavaScript vanilla (ES6+)
- **Stockage** : IndexedDB + Web Crypto pour le chiffrement
- **API externe** : [Mistral AI](https://docs.mistral.ai) (chat completions, streaming)
- **Librairies CDN** :
  - [marked.js](https://marked.js.org/) – rendu Markdown
  - [highlight.js](https://highlightjs.org/) – coloration syntaxique
  - [gpt-tokenizer](https://github.com/niieani/gpt-tokenizer) – comptage de tokens

---

## 📁 Structure du projet

```
hacksamAI/
├── index.html          # Application complète (SPA)
└── README.md
```

Tout est dans un seul fichier HTML pour une portabilité maximale.

---

## 🚢 Déploiement sur GitHub Pages

1. Sur votre dépôt GitHub, allez dans **Settings > Pages**.
2. Sélectionnez la branche `main`, dossier `/ (root)`, puis **Save**.
3. Votre application sera disponible sur `https://samymichel-bit.github.io/hacksamAI/`.

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! Ouvrez une **issue** pour signaler un bug ou proposer une amélioration, ou soumettez directement une **pull request**.

---

## 📄 Licence

Ce projet est sous licence **MIT**. Vous pouvez l'utiliser, le modifier et le distribuer librement, y compris pour un usage commercial.

---

## 📧 Contact

Créé et maintenu par **HackSam** (samymichel-bit).  
Pour toute question ou collaboration, ouvrez une discussion dans l'onglet GitHub.

---

**HackSamAI** – Libérez votre intelligence artificielle. 🧠
