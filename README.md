<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=4169E1&center=true&vCenter=true&width=700&lines=Multiverse+Quest+Website;Site+vitrine+immersif;Pages+Activit%C3%A9s+%2B+Contact+%2B+Tarifs" alt="Typing SVG" />
</p>

<h1 align="center">🎮 <span style="color:#4169E1;">Multiverse Quest</span></h1>
<p align="center">🌌 Site vitrine statique pour présenter les activités immersives, les pass et le contact client.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Website%20Static-4C6EF5?style=for-the-badge&logo=html5&logoColor=white" alt="Status"/>
  <img src="https://img.shields.io/badge/Frontend-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML"/>
  <img src="https://img.shields.io/badge/Style-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS"/>
  <img src="https://img.shields.io/badge/Type-Sans%20Build%20Tool-2F9E44?style=for-the-badge&logo=vercel&logoColor=white" alt="No Build"/>
</p>

---

### 🎯 À propos du projet

**Multiverse Quest** est un site web statique en français destiné à présenter une expérience de divertissement immersif : activités, pass journée, informations de contact et éléments de preuve sociale (sponsors).

Le projet est organisé autour de **3 pages principales** :
- `CWAD.html` : page d’accueil / présentation du concept.
- `Activités.html` : catalogue d’activités et pass tarifaires.
- `contact.html` : formulaire de contact et informations d’accès.

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Consolas&size=14&duration=2200&pause=700&color=4169E1&center=true&vCenter=true&width=520&lines=Loading+Homepage...;Rendering+Activities...;Opening+Contact+Form...;Website+Ready+%E2%9C%A8" alt="Loading Animation" />
</p>

---

### ❓ Informations manquantes / ambiguës à confirmer (avant version figée)

1. **Traitement du formulaire** : `contact.html` envoie vers `submit_form.php`, mais ce fichier n’est pas présent dans le dépôt. Souhaitez-vous un backend réel, un service tiers (Formspree, EmailJS), ou un mode purement statique ?
2. **Polices locales** : `CWAD.css` référence des fichiers dans `fonts/` (`Athelas`, `Montserrat`, `Open Sans`) mais ce dossier n’existe pas ici. Faut-il ajouter les fichiers de police ou basculer sur Google Fonts / polices système ?
3. **Déploiement cible** : aucune cible de déploiement n’est indiquée (GitHub Pages, Netlify, serveur Apache/Nginx). Quelle plateforme faut-il documenter officiellement ?
4. **Licence** : aucune licence explicite n’est fournie dans le projet. Souhaitez-vous une licence open-source (MIT, Apache-2.0) ou une mention “tous droits réservés” ?
5. **Versionnage et roadmap** : pas de changelog ni plan de versions. Voulez-vous une section roadmap (accessibilité, SEO, responsive avancé, backend formulaire) ?

---

### 🛠️ Stack technique

<div align="center">

**💡 Frontend**

![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Mise_en_forme-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Media_Query-5C7CFA?style=for-the-badge&logo=googlechrome&logoColor=white)

**🎨 Contenu & médias**

![YouTube](https://img.shields.io/badge/Embed-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
![Google Maps](https://img.shields.io/badge/Map-Lien_Maps-34A853?style=for-the-badge&logo=googlemaps&logoColor=white)
![Images](https://img.shields.io/badge/Assets-Images-845EF7?style=for-the-badge&logo=googlephotos&logoColor=white)

</div>

---

### 🚀 Fonctionnalités clés

<div align="center">

### 🏠 **Page d’accueil (CWAD.html)**
> *Présentation du concept Multiverse Quest*

- Header avec logo et navigation inter-pages.
- Sections éditoriales : concept, promesse, accessibilité, appel à la réservation.
- Intégration d’une vidéo YouTube immersive.
- Affichage des logos sponsors.
- Footer avec crédits auteurs et liens vers le rapport (PDF/DOCX).

---

### 🎟️ **Page Activités & Pass (Activités.html)**
> *Catalogue des expériences et offres*

- Description des activités : réalité virtuelle, laser game, paintball, escape game, bowling/arcade, casino.
- Bloc “tarifs et pass journée” avec visuels dédiés.
- Liens directs des pass vers la page contact.

---

### 📩 **Page Contact (contact.html)**
> *Collecte de demandes visiteurs*

- Formulaire : nom, prénom, email, pass, paiement, date de visite.
- Bloc d’informations d’adresse et station de transport.
- Lien vers Google Maps.
- Carte affichée via un `iframe` pointant actuellement vers une image locale.

</div>

---

### 🏗️ Architecture du projet

<div align="center">

```text
cwad/
├── Activités.html
├── contact.html
├── CWAD.css
├── CWAD.html
├── fichier_rapport/
│   ├── Rapport_Projet_CWAD.docx
│   └── Rapport_Projet_CWAD.pdf
└── images/
    ├── bowling.png
    ├── casino.png
    ├── contact.png
    ├── dimensional_key_pass.png
    ├── escape_game.webp
    ├── futur.jpg
    ├── infinity_pass.png
    ├── jeu_d'arcade.png
    ├── laser_game.png
    ├── logo_activités.webp
    ├── logo_maps.png
    ├── logo_multiverse_quest.PNG
    ├── logo_universite.png
    ├── paintball.png
    ├── portal_pass.png
    ├── quantum_pass.png
    ├── réalité_virtuelle.png
    ├── realité_virtuelle.webp
    ├── voyageur_pass.png
    └── ... (autres logos sponsors)
```

</div>

---

### ⚙️ Configuration

Ce projet est **statique** et ne nécessite pas de variables d’environnement pour l’affichage des pages.

#### Variables d’environnement
Aucune variable `.env` obligatoire détectée dans le code actuel.

#### Fichiers de configuration utilisés
- `CWAD.css` : styles globaux, responsive, composants visuels.
- Liens internes relatifs entre les pages HTML.

#### Points de configuration à prévoir (si évolution)
- Endpoint de traitement du formulaire (`submit_form.php` ou alternative).
- Gestion des polices (`fonts/` manquant actuellement).

---

### ⚡ Installation & démarrage

#### 1. Prérequis
- Un navigateur moderne (Chrome, Edge, Firefox).
- Optionnel : un serveur local pour éviter les limitations `file://`.

#### 2. Installation
```bash
# Cloner le dépôt
 git clone <URL_DU_REPO>

# Entrer dans le dossier
 cd cwad
```

#### 3. Lancement (mode simple)
Ouvrir `CWAD.html` directement dans le navigateur.

#### 4. Lancement (recommandé, serveur local)
```bash
# Python 3
python -m http.server 8080

# Puis ouvrir
http://localhost:8080/CWAD.html
```

---

### 🧪 Exemples d’utilisation

- **Découverte** : ouvrir `CWAD.html`, parcourir les sections et la vidéo intégrée.
- **Catalogue** : aller sur `Activités.html`, consulter les activités puis cliquer sur un pass.
- **Contact** : remplir le formulaire de `contact.html` (envoi non fonctionnel tant que `submit_form.php` n’existe pas).

---

### 📸 Aperçus suggérés

| **Accueil** | **Activités** | **Contact** |
| --- | --- | --- |
| Hero + présentation | Cartes activités & pass | Formulaire + accès |

---

### 📄 Licence

Licence non définie dans l’état actuel du projet.

> Suggestion : ajouter un fichier `LICENSE` et préciser les conditions d’utilisation du contenu (textes, images, rapport).

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:4169E1&height=120&section=footer&text=Multiverse%20Quest%20|%202026%20|%20Static%20Website&fontColor=ffffff&fontSize=18&animation=fadeIn" />
</p>
