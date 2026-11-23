# Group 4 — Data Scraping & Market Exploration

> **FR :** Application Streamlit de collecte, d'exploration et de visualisation d'annonces de véhicules, motos et équipements au Sénégal.  
> **EN:** Streamlit application for collecting, exploring and visualizing vehicle, motorcycle and equipment listings in Senegal.

## 🇬🇧 English

### Overview
This academic team project provides a Streamlit interface around web scraping and exploratory data analysis. The scraper uses **Requests** and **BeautifulSoup** to collect listing attributes such as condition, brand, year, location, price and image URL from Expat-Dakar listing pages.

### Features
- Scrape vehicle and motorcycle listings.
- Collect equipment and spare-parts listings.
- Inspect datasets in the Streamlit interface.
- Load locally stored CSV datasets.
- Explore brand counts and price-related trends with Matplotlib and Seaborn.
- Open an embedded KoboToolbox form.

### Tech stack
Python · Streamlit · Requests · BeautifulSoup · Pandas · NumPy · Matplotlib · Seaborn

### Run locally
```bash
git clone https://github.com/Slymanidiallo/group_4_app.git
cd group_4_app
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
streamlit run Group4.py
```

The application expects the local image `image.jpg` and, for the CSV/dashboard options, datasets under a `datas/` directory. Check that these paths match the files in your checkout before launching those options.

### Team
- Rokhaya Diop
- Anna Niane
- Thierno Souleymane Diallo

### Notes
The scraper depends on the target website's HTML structure and may need maintenance if that structure changes. Use responsible scraping practices and respect the website's terms and access rules. This repository contains collected CSV files; review their provenance and usage rights before redistribution.

## 🇫🇷 Français

### Présentation
Ce projet académique en équipe propose une interface Streamlit pour collecter, explorer et visualiser des annonces publiées sur Expat-Dakar. Les scripts utilisent **Requests** et **BeautifulSoup** pour extraire notamment l'état, la marque, l'année, la localisation, le prix et l'URL de l'image.

### Fonctionnalités
- Collecte d'annonces de voitures et de motos.
- Collecte d'annonces d'équipements et de pièces détachées.
- Consultation des jeux de données dans Streamlit.
- Chargement de fichiers CSV locaux.
- Visualisations exploratoires avec Matplotlib et Seaborn.
- Intégration d'un formulaire KoboToolbox.

### Installation
```bash
git clone https://github.com/Slymanidiallo/group_4_app.git
cd group_4_app
python -m venv .venv
# Windows : .venv\Scripts\activate
# macOS/Linux : source .venv/bin/activate
pip install -r requirements.txt
streamlit run Group4.py
```

L'application attend le fichier local `image.jpg` et, pour certaines options, des fichiers CSV dans un dossier `datas/`. Vérifiez ces chemins dans votre copie du dépôt.

### Équipe
- Rokhaya Diop
- Anna Niane
- Thierno Souleymane Diallo

### Limites et précautions
Le scraping dépend de la structure HTML du site cible et peut nécessiter des adaptations. Respectez les conditions d'utilisation du site et vérifiez les droits d'utilisation des données avant toute redistribution.
