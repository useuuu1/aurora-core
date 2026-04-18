# 🎧 AURORA Core — Landing Page

> **Pureté brute. Son infini.**  
> Site de pré-commande pour les écouteurs sans fil AURORA Core — haut de gamme accessible, pensé pour les technophiles, développeurs et étudiants.

---

## 🌐 Aperçu

![AURORA Core](https://img.shields.io/badge/statut-en%20ligne-00c8b4?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-single%20file-orange?style=for-the-badge&logo=html5)
![Licence](https://img.shields.io/badge/licence-privée-red?style=for-the-badge)

Site statique entièrement contenu dans un seul fichier `index.html`. Aucune dépendance, aucun framework, aucun build requis. Prêt à déployer sur GitHub Pages en moins de 5 minutes.

**🔗 Live :** `https://[votre-username].github.io/aurora-core/`

---

## 📸 Sections du site

| Section | Description |
|---|---|
| **Hero** | Présentation du boîtier avec parallaxe souris et particules animées |
| **Composants** | Fiche technique complète des 6 composants clés |
| **Vue éclatée** | Section anatomie avec les composants internes |
| **Fonctionnalités** | Multipoint, App Connect, SDK Open Source, LED signature |
| **Galerie matériaux** | Photos macro de la finition aluminium brossé / verre trempé |
| **Pré-commande** | Formulaire complet avec envoi vers Discord |

---

## ⚙️ Stack technique

- **HTML5 / CSS3 / JavaScript vanilla** — zéro dépendance externe
- **Google Fonts** — Share Tech Mono + Barlow Condensed
- **Discord Webhook** — réception des pré-commandes en temps réel
- **GitHub Pages** — hébergement statique gratuit

---

## 🚀 Déploiement

### GitHub Pages (recommandé)

1. Forkez ou clonez ce repo
2. Assurez-vous que le fichier principal s'appelle `index.html`
3. Allez dans **Settings → Pages**
4. Sélectionnez la branche `main`, dossier `/ (root)`
5. Cliquez **Save** — le site est en ligne en ~2 minutes

### En local

Aucun serveur requis. Ouvrez simplement `index.html` dans votre navigateur :

```bash
git clone https://github.com/[votre-username]/aurora-core.git
cd aurora-core
open index.html   # macOS
# ou
start index.html  # Windows
```

---

## 📬 Intégration Discord

Les pré-commandes sont envoyées automatiquement vers un canal Discord via webhook.

Chaque soumission génère un embed contenant :
- Nom complet du client
- Adresse courriel
- Ville / Province
- Finition choisie (Gris Sidéral ou Noir Mat)
- Gravure laser personnalisée
- Montant (129 $CAD)
- Horodatage (heure de Montréal)

Pour changer le webhook, modifiez la constante dans `index.html` :

```js
const DISCORD_WEBHOOK = 'https://discord.com/api/webhooks/VOTRE_ID/VOTRE_TOKEN';
```

---

## 🎨 Design

| Élément | Choix |
|---|---|
| **Palette** | `#00c8b4` (teal) · `#0080ff` (bleu) · `#080a0c` (noir) |
| **Typographie** | Share Tech Mono (mono) + Barlow Condensed (display) |
| **Esthétique** | Terminal industriel · Blueprint · Circuit imprimé |
| **Animations** | Particules flottantes · Parallaxe · Scroll reveal · Compteurs |

---

## 📦 Produit — Fiche rapide

| Spec | Valeur |
|---|---|
| Bluetooth | 5.4 · Qualcomm QCC5181 |
| Drivers | 11mm dynamique Titane |
| ANC | Hybride −45 dB |
| Autonomie | 8h (écouteurs) + 32h (boîtier) |
| Micros | 6× MEMS avec IA |
| Étanchéité | IP54 |
| Prix | 129 $CAD |

---

## 📁 Structure

```
aurora-core/
└── index.html      # Site complet (HTML + CSS + JS + images base64)
└── README.md       # Ce fichier
```

---

## 📄 Licence

Projet privé — © 2025 AURORA Core Inc., Montréal, Québec, Canada.  
Tous droits réservés. Ne pas reproduire sans autorisation.

---

*Fait avec ☕ et beaucoup de teal.*
