# Analyse des Habitudes et Performance Académique des Étudiants

## 📚 Description du Projet
Ce projet, réalisé dans le cadre du module USSI09 "Analyse de données" (2024-2025), étudie les relations entre les habitudes quotidiennes des étudiants et leur performance académique. L'analyse se base sur le dataset [Student Habits and Academic Performance](https://www.kaggle.com/datasets/aryan208/student-habits-and-academic-performance).

## 👥 Équipe
- Alla Mohamed [@Mohamed-A2001](https://github.com/Mohamed-A2001)
- Planche Tom [@TomPlanche](https://github.com/TomPlanche)

## 📊 Dataset
Le dataset comprend :
- 204 observations (étudiants)
- 18 variables incluant :
  - Variables démographiques (âge, genre, localisation)
  - Habitudes d'étude (heures d'étude, sommeil, exercice)
  - Utilisation de la technologie
  - Facteurs psychologiques
  - Performance académique

## 🎯 Objectifs
1. **Analyse Descriptive et Exploratoire**
   - Statistiques univariées
   - Analyse des relations entre variables
   - Analyse en Composantes Principales (ACP)
   - Visualisations des données

2. **Modélisation Prédictive**
   - Régression linéaire pour prédire la performance académique
   - Évaluation des performances du modèle
   - Identification des facteurs clés de réussite

## 🛠 Installation et Configuration

### Prérequis
- Python 3.8+
- pip ou uv (gestionnaire de paquets)

### Installation

1. Cloner le repository :
```bash
git clone [URL_DU_REPO]
cd projet_alla_planche
```

2. Créer et activer un environnement virtuel :
```bash
python -m venv sklearn-env
source sklearn-env/bin/activate  # Pour Unix/macOS
# ou
.\sklearn-env\Scripts\activate  # Pour Windows
```

3. Installer les dépendances :
```bash
uv pip install -r requirements.txt
```

## 📈 Structure du Projet
```
projet_alla_planche/
├── assets/
│   ├── cours/                    # Documents de cours
│   └── enhanced_student_habits_performance_dataset.csv
├── main.ipynb                    # Notebook principal d'analyse
├── notes.md                      # Notes détaillées sur l'analyse
├── pyproject.toml               # Configuration du projet
└── README.md                    # Documentation du projet
```

## 📝 Méthodologie
1. Chargement et nettoyage des données
2. Analyse exploratoire (EDA)
3. Prétraitement des données
4. Analyse en Composantes Principales
5. Modélisation par régression linéaire
6. Interprétation et conclusions

## 🚀 Utilisation
1. Ouvrir le notebook `main.ipynb`
2. Suivre les sections dans l'ordre :
   - Configuration de l'environnement
   - Chargement des données
   - Nettoyage et préparation
   - Analyses statistiques
   - Visualisations
   - Modélisation
   - Interprétation des résultats

## 📊 Variables Analysées

### Variables Qualitatives
- Genre (gender)
- Filière d'études (major)
- Qualité de l'alimentation (diet_quality)
- Environnement d'étude (study_environment)
- Et plus...

### Variables Quantitatives
- Temps d'étude (study_hours_per_day)
- Performance académique (exam_score)
- Temps d'écran (total_screen_time)
- Santé mentale (mental_health_rating)
- Et plus...

## 📜 Licences
- [APACHE](./LICENCE-APACHE)
- [MIT](./LICENCE-MIT)