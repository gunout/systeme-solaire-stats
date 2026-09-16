# 🇫🇷 Dashboard Scientifique Multi-Corps · Données Réelles

Dashboard interactif d'analyse scientifique multi-corps célestes avec **données réelles** (NASA, NOAA, SILSO, JPL, ESA) et **exports multi-formats**. Interface tricolore 🇫🇷 sur fond blanc, mode 100% hors ligne, aucune dépendance externe.

[![Licence MIT](https://img.shields.io/badge/Licence-MIT-ED2939?style=for-the-badge)](LICENSE)
[![Made in France](https://img.shields.io/badge/Made_in-France-002395?style=for-the-badge&labelColor=FFFFFF&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgZmlsbD0iIzAwMjM5NSIvPjxyZWN0IHdpZHRoPSI5MDAiIGhlaWdodD0iNDAwIiB5PSIxMDAiIGZpbGw9IiNmZmYiLz48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjIwMCIgeT0iNDAwIiBmaWxsPSIjZWQyOTM5Ii8+PC9zdmc+)](https://github.com/gunout)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://github.com/gunout/systeme-solaire-stats)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://github.com/gunout/systeme-solaire-stats)
[![Canvas](https://img.shields.io/badge/Canvas_Native-000000?style=flat-square&logo=html5&logoColor=white)](https://github.com/gunout/systeme-solaire-stats)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-en_ligne-222?style=flat-square&logo=githubpages&logoColor=white)](https://gunout.github.io/systeme-solaire-stats/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](https://github.com/gunout/systeme-solaire-stats/pulls)
[![Open Data](https://img.shields.io/badge/Open_Data-NASA_·_NOAA_·_SILSO-ff6f00?style=flat-square)](https://data.giss.nasa.gov/gistemp/)
[![Astres](https://img.shields.io/badge/Astres-8_corps_célestes-0055A4?style=flat-square)](#-les-8-corps-célestes)

---

## 📑 Sommaire

- [Aperçu](#-aperçu)
- [Fonctionnalités](#-fonctionnalités)
- [Démo](#-démo)
- [Installation](#-installation)
- [Déploiement GitHub Pages](#-déploiement-github-pages)
- [Les 8 corps célestes](#-les-8-corps-célestes)
- [Données scientifiques réelles](#-données-scientifiques-réelles)
- [Exports multi-formats](#-exports-multi-formats)
- [Interface](#-interface)
- [Raccourcis clavier](#-raccourcis-clavier)
- [Architecture technique](#-architecture-technique)
- [Moteur de graphiques](#-moteur-de-graphiques)
- [Résolution de problèmes](#-résolution-de-problèmes)
- [Personnalisation](#-personnalisation)
- [Compatibilité](#-compatibilité)
- [Accessibilité](#-accessibilité)
- [Limitations](#-limitations)
- [Feuille de route](#-feuille-de-route)
- [Contribuer](#-contribuer)
- [Références](#-références)
- [Licence](#-licence)
- [Remerciements](#-remerciements)

---

## 🔎 Aperçu

Un fichier HTML unique, sans build ni dépendance npm, qui implémente un **dashboard interactif d'analyse scientifique multi-corps célestes**, alimenté par les **données officielles NASA, NOAA, SILSO, JPL et ESA**.

L'outil combine analyse statistique multi-corps, cartographie de données, système d'alertes, export multi-formats et diagnostic intégré. Il est destiné aux analystes en astrophysique, chercheurs en sciences planétaires, étudiants, journalistes scientifiques et curieux.

L'application est **100 % côté client** : aucune donnée n'est envoyée à un serveur, aucun compte n'est requis, aucune clé API n'est nécessaire. Elle **fonctionne entièrement hors ligne**.

> ⚠️ **Outil académique et pédagogique** — Les données réelles sont issues de sources scientifiques officielles. Les autres données sont simulées à des fins de démonstration.

---

## ✨ Fonctionnalités

### 📊 6 modules d'analyse

1. **Dashboard** — Vue d'ensemble avec 6 métriques clés
2. **Corps céleste** — Sélection parmi 8 astres (Terre, Soleil, Lune, Vénus, Mars, Jupiter, Saturne, Mercure)
3. **Type de données** — ~30 métriques scientifiques (température, CO₂, taches solaires, etc.)
4. **Graphiques** — 4 visualisations interactives Canvas
5. **Insights** — Analyse automatique générée dynamiquement
6. **Exports** — 10 formats de téléchargement disponibles

### 🪐 Analyse multi-corps

- **8 corps célestes** : Terre, Soleil, Lune, Vénus, Mars, Jupiter, Saturne, Mercure
- **~30 types de données** : température, CO₂, taches solaires, marsquakes, anneaux, etc.
- **6 métriques par série** : moyenne, maximum, minimum, valeur actuelle, évolution %, amplitude
- **4 graphiques** : série principale, tendance, variations annuelles, comparaison & projection
- **Insights automatiques** générés dynamiquement

### 💾 Exports multi-formats

- 📊 **CSV** (BOM UTF-8, compatible Excel FR)
- 🧾 **JSON** (structuré avec métadonnées)
- 📄 **XML** (hiérarchique échappé)
- 📝 **TXT** (tableau ASCII lisible)
- 📘 **Markdown** (prêt pour GitHub)
- ⚙️ **YAML** (configuration-friendly)
- 📈 **Excel** (.xls via HTML table)
- 📋 **Presse-papier** (TSV)
- 🖨️ **PDF** (impression navigateur)
- 📦 **Tout exporter** (7 formats en cascade)

### 🚨 Analyse et notifications

- **Badges RÉEL / SIMULÉ** sur chaque série
- **Point vert** sur les astres avec données réelles
- **Toasts** empilables avec types (success, error, warning)
- **Statut live** en barre supérieure
- **Comparaison** réel vs simulé

### 🎨 Interface

- **Design sobre** avec bandeau tricolore 🇫🇷 sur fond blanc
- **Thème clair** institutionnel
- **Responsive** — mobile, tablette, desktop, ultra-wide
- **Drawer latéral** sur mobile (< 1000 px)
- **Bottom sheet** pour les modales sur mobile
- **Skeleton loaders** pendant le chargement

### 🛡️ Robustesse

- **100 % hors ligne** — fonctionne sans connexion
- **Aucune dépendance externe** — Canvas natif
- **Aucune clé API** requise
- **Cache localStorage** : thème persistant
- **Partage par URL** : état encodé dans le query string

---

## 🚀 Démo

### 🌐 Application en ligne

👉 [**https://gunout.github.io/systeme-solaire-stats/**](https://gunout.github.io/systeme-solaire-stats/)

Aucune installation, aucune inscription. Ouvrez le lien dans un navigateur moderne.

---

## 📦 Installation

### Utilisation directe (recommandée)

git clone https://github.com/gunout/systeme-solaire-stats.git
cd systeme-solaire-stats
# Ouvrez index.html dans votre navigateur

Aucune dépendance, aucun `npm install`, aucun build.

### Serveur local (optionnel)

Le dashboard fonctionne en `file://`, mais un serveur local est recommandé pour tester en conditions réelles :

# Python 3
python -m http.server 8000

# ou Node.js
npx serve .

# ou PHP
php -S localhost:8000

Puis ouvrez `http://localhost:8000/index.html`.

---

## 🌐 Déploiement GitHub Pages

L'application est **déjà déployée** à l'adresse :

**🔗 [https://gunout.github.io/systeme-solaire-stats/](https://gunout.github.io/systeme-solaire-stats/)**

### Déployer sur votre propre fork

1. **Forkez** le dépôt : [github.com/gunout/systeme-solaire-stats](https://github.com/gunout/systeme-solaire-stats)
2. Le fichier `index.html` doit être **à la racine** du dépôt
3. Allez dans **Settings → Pages**
4. Sous **Build and deployment** :
   - **Source** : `Deploy from a branch`
   - **Branch** : `main` / `(root)`
5. Cliquez sur **Save**
6. Attendez 1-2 minutes

Votre site sera accessible à : `https://<votre-compte>.github.io/<votre-repo>/`

### Ajouter un fichier `.nojekyll`

Pour éviter tout traitement Jekyll inutile et accélérer le déploiement :

touch .nojekyll
git add .nojekyll
git commit -m "chore: add .nojekyll"
git push

---

## 🪐 Les 8 corps célestes

| Astre | Emoji | Période | Données réelles | Description |
|-------|-------|---------|-----------------|-------------|
| **Terre** | 🌍 | 1880-2024 | ✅ Oui | Climat, atmosphère, océans |
| **Soleil** | ☀️ | 1700-2024 | ✅ Oui | Cycles 11 ans, activité magnétique |
| **Lune** | 🌕 | 2000-2024 | ✅ Oui | Éphémérides JPL haute précision |
| **Vénus** | ♀️ | 1960-2024 | ⚠️ Partiel | Enfer vénusien, effet de serre |
| **Mars** | 🔴 | 1976-2024 | ✅ Oui | Exploration in situ (Viking → Perseverance) |
| **Jupiter** | 🟠 | 1610-2024 | ❌ Non | Géante gazeuse, Grande Tache Rouge |
| **Saturne** | 🪐 | 1610-2024 | ❌ Non | Anneaux, hexagone polaire |
| **Mercure** | ☿ | 1974-2024 | ❌ Non | Extrêmes thermiques, noyau de fer |

> Les astres avec un **point vert** dans l'interface contiennent des données réelles.

---

## 📡 Données scientifiques réelles

### Séries embarquées

| Astre | Série | Source | Points | Unité |
|-------|-------|--------|--------|-------|
| 🌍 Terre | Température | **NASA GISS** | 33 | °C (anomalie) |
| 🌍 Terre | CO₂ | **NOAA Mauna Loa** | 20 | ppm |
| 🌍 Terre | Niveau des mers | **NASA Satellite** | 17 | mm |
| ☀️ Soleil | Taches solaires | **SILSO Belgique** | 39 | Nombre de Wolf |
| ☀️ Soleil | Flux F10.7 | **NOAA SWPC** | 20 | SFU |
| 🌕 Lune | Distance Terre-Lune | **NASA JPL Horizons** | 13 | km |
| 🔴 Mars | Température | **NASA PDS** | 17 | °C |
| 🔴 Mars | Marsquakes | **NASA InSight** | 4 | séismes cumulés |

**Total : 8 séries · 163 points réels · 6 institutions**

### Sources officielles

| Source | URL | Domaine |
|--------|-----|---------|
| **NASA GISS** | [data.giss.nasa.gov/gistemp](https://data.giss.nasa.gov/gistemp/) | Température globale |
| **NOAA GML** | [gml.noaa.gov/ccgg/trends](https://gml.noaa.gov/ccgg/trends/) | CO₂ atmosphérique |
| **NASA Sea Level** | [sealevel.nasa.gov](https://sealevel.nasa.gov/) | Altimétrie satellite |
| **SILSO** | [sidc.be/silso](https://www.sidc.be/silso/) | Taches solaires |
| **NOAA SWPC** | [services.swpc.noaa.gov](https://services.swpc.noaa.gov/) | Météo spatiale |
| **NASA JPL** | [ssd.jpl.nasa.gov/horizons](https://ssd.jpl.nasa.gov/horizons/) | Éphémérides |
| **NASA PDS** | [pds.nasa.gov](https://pds.nasa.gov/) | Données planétaires |
| **NASA InSight** | [insight.ethz.ch](https://www.insight.ethz.ch/seismicity/catalog) | Marsquakes |

---

## 💾 Exports multi-formats

### 10 options de téléchargement

| Bouton | Format | Ext. | Contenu |
|--------|--------|------|---------|
| 📦 **Tout exporter** | Multi | — | 7 formats en cascade |
| 📊 **CSV** | CSV | `.csv` | Semicolon, BOM UTF-8 |
| 🧾 **JSON** | JSON | `.json` | Structuré + métadonnées |
| 📄 **XML** | XML | `.xml` | Hiérarchique échappé |
| 📝 **TXT** | Texte | `.txt` | Tableau ASCII |
| 📘 **Markdown** | Markdown | `.md` | Tableau GitHub-ready |
| ⚙️ **YAML** | YAML | `.yaml` | Config-friendly |
| 📈 **Excel** | XLS | `.xls` | HTML table → Excel |
| 📋 **Copier** | Clipboard | — | Format TSV |
| 🖨️ **PDF** | Impression | `.pdf` | Via navigateur |

### Métadonnées incluses dans chaque export

- Astre, emoji, type de données, unité
- Source, URL officielle
- Qualité : `REAL` ou `SIMULATED`
- Période analysée
- Nombre de points
- Horodatage de l'export

### Nom de fichier

Format : `{body}_{type}_{YYYY-MM-DD}.{ext}`

Exemple : `earth_temperature_2026-01-15.csv`

---

## 🎨 Interface

### Thème tricolore 🇫🇷 sur fond blanc

- **Fond** : blanc pur `#FFFFFF`
- **Bleu France** : `#0055A4` (accents principaux)
- **Bleu marine** : `#002395` (profondeur)
- **Rouge France** : `#EF4135` (accents secondaires)
- **Bandeaux** : dégradé bleu → blanc → rouge
- **Section titles** : soulignés mi-bleu mi-rouge
- **Cartes** : blanches avec ombres bleutées

### Layout

- **Sidebar fixe** : 300 px (sticky en haut)
- **Contenu principal** : grille fluide
- **4 graphiques** en grille auto-fit
- **6 métriques** en grille responsive
- **Insights** en liste verticale

---

## ⌨️ Raccourcis clavier

| Raccourci | Action |
|-----------|--------|
| <kbd>/</kbd> | Focus sur le sélecteur de type |
| <kbd>R</kbd> | Régénérer les données |
| <kbd>C</kbd> | Activer/désactiver la comparaison |
| <kbd>E</kbd> | Export multi-formats d'un coup |
| <kbd>1</kbd> – <kbd>8</kbd> | Naviguer entre les corps célestes |
| <kbd>Échap</kbd> | Fermer le drawer / plein écran |

> Les raccourcis sont désactivés lorsque le focus est dans un champ de saisie.

---

## 🏗️ Architecture technique

### Stack

- **HTML5 / CSS3 / JavaScript ES2022** — aucune dépendance build
- **Canvas 2D natif** — moteur de graphiques maison
- **Aucune dépendance externe** — pas de Chart.js, pas de CDN
- **localStorage** — persistance du thème
- **URLSearchParams** — partage par URL

### Structure du projet

```text
.
├── index.html      # Application complète (HTML + CSS + JS inline)
├── README.md       # Ce fichier
├── LICENSE         # MIT
└── .nojekyll       # (optionnel) désactive Jekyll sur GitHub Pages

```

Pipeline de données
```text

Données réelles (constantes JS embarquées)
       │
       ▼
┌──────────────────┐
│ getRealOrSim()   │  → Détecte si série réelle ou simulée
└────────┬─────────┘
         ▼
┌──────────────────┐
│ Transformation   │  → Lissage, tendance, dérivées, projections
└────────┬─────────┘
         ▼
┌──────────────────┐
│ Rendu            │  → Métriques, 4 graphiques Canvas, insights
└────────┬─────────┘
         ▼
┌──────────────────┐
│ Export           │  → 10 formats disponibles
└──────────────────┘
```
Stockage local
Clé localStorage	Contenu
dash_theme	Thème actif (light / dark)
Synchronisation URL

L'état complet est encodé dans le query string :

?body=mars&type=temperature

Rechargez ou partagez le lien : l'état est restauré automatiquement.
🔧 Moteur de graphiques

Ce dashboard utilise un moteur de graphiques maison en Canvas 2D natif — aucune bibliothèque externe.
Fonctions clés

    setupCanvas() — ajuste la résolution DPR (écrans Retina)

    drawAxes() — dessine grille, labels X/Y

    drawLineChart() — courbes avec dégradés et pointillés

    drawBarChart() — barres vertes (hausse) / rouges (baisse)

Avantages

    ✅ Aucun CDN à charger

    ✅ Fonctionne 100 % hors ligne

    ✅ Ultra-rapide (~1 ms par graphique)

    ✅ Léger (~3 Ko de code)

🧪 Résolution de problèmes
Le dashboard n'affiche pas les graphiques

Causes possibles :

    Navigateur trop ancien → Chrome/Edge 90+, Firefox 88+, Safari 14+

        Solution : mettez à jour votre navigateur

    Canvas désactivé → vérifiez vos paramètres navigateur

    Erreur JS dans la console → ouvrez F12 pour diagnostiquer

Les données ne s'affichent pas pour un astre

Causes possibles :

    Astre sans données réelles → Vénus, Jupiter, Saturne, Mercure utilisent des données simulées

        Solution : vérifiez le badge en haut à droite (📡 RÉEL ou 📊 SIMULÉ)

    Type de donnée non sélectionné → vérifiez le menu déroulant "Type de données"

Test manuel rapide

Ouvrez la console développeur (F12) et vérifiez :

    ✅ Si vous voyez 🇫🇷 Boot démarrage → le script s'exécute

    ✅ Si vous voyez ✅ Dashboard prêt → tout est chargé

    ❌ Si erreur → vérifiez le message pour identifier la cause

⚙️ Personnalisation
Modifier la liste des corps célestes

Dans BODIES, ajoutez ou modifiez une entrée :
javascript

BODIES.nouveau_corps = {
  name: 'Nouveau',
  emoji: '🪨',
  start: 2000,
  end: 2024,
  accent: '#0055A4',
  hasReal: false,
  description: 'Description du corps',
  dataTypes: {
    ma_metrique: {
      label: 'Ma métrique',
      base: 100,
      cycle: 5,
      amp: 20,
      trend: 'up',
      unit: 'unités'
    }
  }
};

Ajouter une série réelle
javascript

const MA_SERIE_REELLE = {
  years: [2000, 2005, 2010, 2015, 2020, 2024],
  values: [100, 105, 110, 118, 125, 130],
  unit: 'km',
  source: 'NASA Exemple',
  url: 'https://exemple.nasa.gov',
  real: true
};

Puis dans BODIES.earth.dataTypes, ajoutez :
javascript

ma_metrique: {
  label: 'Ma métrique',
  real: MA_SERIE_REELLE,
  unit: 'km',
  trend: 'up',
  cycle: 1,
  base: 100,
  amp: 20
}

Changer les couleurs

Modifiez les variables CSS dans :root :
css

:root {
  --france-blue: #0055A4;
  --france-blue-deep: #002395;
  --france-red: #EF4135;
  --real: #16A34A;
  --sim: #CA8A04;
  /* ... */
}

🌐 Compatibilité
Navigateur	Version minimale
Chrome / Edge	90+
Firefox	88+
Safari	14+
Opera	76+

Non supporté : Internet Explorer.
Responsive
Breakpoint	Adaptation
> 1900 px	Layout ultra-wide (max 2000 px)
1200 – 1900 px	Desktop standard
1000 – 1200 px	Tablette paysage
768 – 1000 px	Tablette portrait (sidebar en drawer)
640 – 768 px	Mobile paysage
480 – 640 px	Mobile portrait
380 – 480 px	Petits mobiles
< 380 px	Très petits mobiles
♿ Accessibilité

Ce projet vise la conformité WCAG 2.1 niveau AA :

    Structure sémantique HTML5 (<header>, <main>, <nav>, <article>, <aside>)

    Régions aria-live pour les mises à jour dynamiques

    Lien d'évitement « Aller au contenu principal »

    Tous les contrôles accessibles au clavier

    Contraste texte/fond ≥ 4.5:1

    Focus visibles et personnalisés (:focus-visible)

    Rôles ARIA (tablist, tabpanel, dialog, alert, status)

    Support prefers-reduced-motion

    Safe areas iPhone (env(safe-area-inset-*))

Les retours et signalements de problèmes d'accessibilité sont bienvenus via les issues.
⚠️ Limitations

    Données statiques : les séries réelles sont embarquées dans le code

    Pas de mise à jour automatique : pas de connexion API en temps réel

    Mise à jour manuelle requise pour refléter les dernières données

    8 séries réelles uniquement (les autres sont simulées)

    Pas de données Vénus/Jupiter/Saturne/Mercure (données insuffisantes)

    Pas d'index inversé : la recherche est linéaire

🗺️ Feuille de route

    □

    Intégration API temps réel (NASA, NOAA)
    □

    Mise à jour automatique via GitHub Actions
    □

    Ajout de Vénus (Venus Express, Akatsuki)
    □

    Ajout de Jupiter (Juno, Hubble)
    □

    Ajout de Saturne (Cassini archives)
    □

    Ajout de Mercure (MESSENGER)
    □

    Support des données spectrales (JWST/MAST)
    □

    Cartes topographiques (USGS Astrogeology)
    □

    Mode comparaison multi-astres
    □

    Export PDF natif

🤝 Contribuer

Les contributions sont les bienvenues !

    Forkez le dépôt : https://github.com/gunout/systeme-solaire-stats/fork

    Créez une branche : git checkout -b feature/ma-fonctionnalite

    Committez : git commit -m "feat: ajout de X"

    Poussez : git push origin feature/ma-fonctionnalite

    Ouvrez une Pull Request : https://github.com/gunout/systeme-solaire-stats/pulls

Conventions de commit

Ce projet suit Conventional Commits :

    feat: nouvelle fonctionnalité

    fix: correction de bug

    docs: documentation

    style: formatage

    refactor: refactoring

    perf: performance

    test: tests

    chore: maintenance

Signaler un bug

Ouvrez une issue sur https://github.com/gunout/systeme-solaire-stats/issues en précisant :

    Navigateur et version

    Étapes de reproduction

    Comportement attendu vs observé

    Captures d'écran si pertinent

    Sortie de la console (F12) si erreur JS

📚 Références

    NASA GISS (2024), Surface Temperature Analysis (GISTEMP v4), Goddard Institute for Space Studies

    NOAA GML (2024), Trends in Atmospheric Carbon Dioxide, Global Monitoring Laboratory

    NASA Sea Level Change Portal (2024), Satellite Altimetry Data

    SILSO (2024), Sunspot Number, Observatoire Royal de Belgique (WDC)

    NOAA SWPC (2024), Solar Radio Flux F10.7, Space Weather Prediction Center

    NASA JPL (2024), Horizons System, Solar System Dynamics

    NASA PDS (2024), Planetary Data System, Mars missions archives

    NASA InSight (2024), Marsquake Service, ETH Zürich

    IPCC AR6 (2021), Climate Change 2021: The Physical Science Basis

    Gutenberg & Richter (1956), Magnitude and Energy of Earthquakes

📄 Licence

Ce projet est distribué sous licence MIT — voir le fichier LICENSE pour plus de détails.

MIT License

Copyright (c) 2026 gunout

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
🙏 Remerciements

    NASA GISS — Température globale de référence

    NOAA — Données climatiques et météo spatiale

    SILSO — Base historique de taches solaires

    NASA JPL — Éphémérides de haute précision

    NASA PDS — Archives des missions planétaires

    ESA — Missions européennes (Venus Express, Mars Express)

    ETH Zürich — Marsquake Service (InSight)

    Observatoire Royal de Belgique — WDC Sunspot Index

📊 Outil pédagogique scientifique — Non affilié à la NASA ni à l'État français

Données : NASA · NOAA · SILSO · JPL · ESA

Fait pour la communauté scientifique open source.

---

<div align="center">
🇫🇷 Gunout · 2026

https://img.shields.io/badge/Made_in-France-002395?style=flat-square&labelColor=FFFFFF&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgZmlsbD0iIzAwMjM5NSIvPjxyZWN0IHdpZHRoPSI5MDAiIGhlaWdodD0iNDAwIiB5PSIxMDAiIGZpbGw9IiNmZmYiLz48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjIwMCIgeT0iNDAwIiBmaWxsPSIjZWQyOTM5Ii8+PC9zdmc+
https://img.shields.io/badge/GitHub-gunout-181717?style=flat-square&logo=github&logoColor=white
https://img.shields.io/badge/2026-ED2939?style=flat-square&labelColor=FFFFFF

<sub>© 2026 <strong>gunout</strong> — Tous droits réservés.</sub>
</div>
