# Analyse Statistique Univariée - Notes d'Observation

## Glossaire des Termes Statistiques

### Termes Généraux
- **Distribution** : La "forme" que prennent nos données quand on les visualise. Comme la répartition des tailles dans une classe : certaines plus fréquentes que d'autres
- **Moyenne** : La valeur "typique". Par exemple, si 3 étudiants étudient respectivement 2h, 4h et 6h, la moyenne est 4h
- **Médiane** : La valeur du milieu quand on ordonne toutes les données. Moins sensible aux valeurs extrêmes que la moyenne
- **Mode** : La valeur qu'on retrouve le plus souvent. Par exemple, si beaucoup d'étudiants dorment 7h, c'est le mode
- **Outliers (valeurs aberrantes)** : Les cas "exceptionnels". Par exemple, un étudiant qui étudie 15h par jour quand la plupart étudient entre 2h et 6h

### Mesures de Forme et Leur Signification Pratique

#### Skewness (asymétrie)
**Définition simple** : Indique si les données sont "tirées" vers la gauche ou la droite

**Exemples concrets** :
1. **Skewness positif (tiré vers la droite)**
   - Pour le temps d'écran : beaucoup d'étudiants passent peu de temps, mais quelques-uns passent énormément de temps
   - Pour les notes : beaucoup d'étudiants ont des notes moyennes à faibles, mais quelques-uns excellent
   - ➡️ Ressemble à : 📊 (beaucoup à gauche, queue à droite)

2. **Skewness négatif (tiré vers la gauche)**
   - Pour l'assiduité : beaucoup d'étudiants ont une présence élevée, quelques-uns sont souvent absents
   - Pour la préparation aux examens : majorité bien préparée, quelques-uns très peu
   - ➡️ Ressemble à : 📊 (beaucoup à droite, queue à gauche)

**Implications pratiques** :
- Un skewness fort peut indiquer des groupes qui nécessitent une attention particulière
- Aide à identifier si des mesures spéciales sont nécessaires pour certains groupes

#### Kurtosis (pointicité)
**Définition simple** : Indique si les données sont concentrées ou dispersées

**Exemples concrets** :
1. **Kurtosis élevé (distribution pointue)**
   - Pour les notes d'examen : beaucoup d'étudiants ont des notes très similaires
   - Pour les horaires de sommeil : majorité dort presque exactement le même nombre d'heures
   - ➡️ Ressemble à : 📈 (pic prononcé)

2. **Kurtosis faible (distribution aplatie)**
   - Pour le temps d'étude : grande variété dans les habitudes d'étude
   - Pour les activités extrascolaires : pas de tendance dominante
   - ➡️ Ressemble à : 📉 (forme plus plate)

**Implications pratiques** :
- Kurtosis élevé : peut indiquer des normes fortes ou des contraintes communes
- Kurtosis faible : suggère une grande diversité dans les comportements

### Comment Utiliser Ces Informations ?

1. **Pour l'enseignement**
   - Distribution asymétrique des notes → Peut indiquer besoin de soutien supplémentaire
   - Forte concentration des temps d'étude → Peut suggérer des habitudes de travail communes

2. **Pour l'administration**
   - Grande dispersion des temps d'écran → Besoin de guidelines plus claires ?
   - Concentration des horaires de sommeil → Impact des horaires de cours ?

3. **Pour les étudiants**
   - Comprendre où ils se situent par rapport aux autres
   - Identifier les domaines où ils diffèrent de la "norme"

### Types de Distributions
- **Distribution normale** : Distribution en forme de cloche, symétrique autour de la moyenne
- **Distribution bimodale** : Distribution présentant deux pics distincts
- **Distribution asymétrique** : Distribution plus étalée d'un côté que de l'autre

### Visualisations
- **Histogramme** : Graphique en barres montrant la distribution des données numériques
- **Boîte à moustaches (Box plot)** : 
  - Visualisation montrant :
    - La médiane (ligne centrale)
    - Les quartiles (boîte)
    - Les valeurs extrêmes (moustaches)
    - Les outliers (points individuels)
- **Diagramme en barres** : Graphique comparant des fréquences entre différentes catégories

### Types de Variables
- **Variables qualitatives** : Décrivent des caractéristiques non numériques (ex: genre, filière)
- **Variables quantitatives** : Représentent des mesures numériques
  - **Continues** : Peuvent prendre n'importe quelle valeur (ex: temps d'étude)
  - **Discrètes** : Prennent des valeurs entières (ex: nombre d'exercices)
- **Variables binaires** : N'ont que deux valeurs possibles (ex: oui/non, 0/1)

## 1. Variables Qualitatives

### Genre (gender)
- Distribution déséquilibrée
- Majorité d'étudiants masculins
- Faible représentation de la catégorie "Other"

### Filière d'études (major)
- Grande diversité des domaines d'étude
- Dominance des filières Computer Science et Business
- Représentation plus faible des filières artistiques

### Qualité de l'alimentation (diet_quality)
- Trois niveaux : Poor, Fair, Good
- Majorité des étudiants rapportent une qualité "Good"
- Minorité significative en "Poor"

### Environnement d'étude (study_environment)
- Préférence marquée pour les espaces "Co-Learning Group"
- Usage modéré de la bibliothèque
- Certains étudiants privilégient les "Quiet Room"

## 2. Variables Quantitatives Continues

### Temps d'étude (study_hours_per_day)
- Moyenne : ~5 heures par jour
- Distribution légèrement asymétrique à droite
- Présence de quelques valeurs extrêmes (>10 heures)

### Performance académique (exam_score)
- Moyenne élevée (~85-90)
- Distribution relativement normale
- Faible dispersion autour de la moyenne

### Temps d'écran (total_screen_time)
- Grande variabilité
- Distribution asymétrique à droite
- Quelques utilisateurs intensifs (outliers)

### Santé mentale (mental_health_rating)
- Distribution relativement normale
- Moyenne autour de 6-7/10
- Présence de cas extrêmes bas (<3) et hauts (>9)

## 3. Variables Quantitatives Discrètes

### Âge (age)
- Concentration autour de 20-25 ans
- Quelques étudiants plus âgés
- Distribution asymétrique à droite

### Fréquence d'exercice (exercise_frequency)
- Mode autour de 3-4 fois par semaine
- Distribution relativement uniforme
- Peu d'extrêmes (très peu ou très fréquent)

### Niveau de stress (stress_level)
- Distribution bimodale
- Pics autour de 4-5 et 7-8
- Suggère deux groupes distincts d'étudiants

## 4. Variables Binaires

### Emploi à temps partiel (part_time_job)
- ~40% des étudiants travaillent
- Impact potentiel sur le temps d'étude

### Participation aux activités extrascolaires (extracurricular_participation)
- Taux de participation élevé (~60%)
- Suggère une population étudiante active

### Risque d'abandon (dropout_risk)
- Faible pourcentage (~15%)
- Corrélation possible avec d'autres facteurs

## 5. Points Clés à Approfondir

1. **Gestion du temps**
   - Équilibre entre études et travail
   - Impact du temps d'écran sur les performances

2. **Bien-être étudiant**
   - Relation stress/performance
   - Impact de l'exercice et de l'alimentation

3. **Environnement d'apprentissage**
   - Efficacité des différents environnements d'étude
   - Rôle du support parental et du tutorat

4. **Performance académique**
   - Facteurs contribuant aux scores élevés
   - Identification des risques d'échec

## 6. Recommandations pour l'Analyse Bivariée

1. Examiner les relations entre :
   - Temps d'étude et performance
   - Stress et santé mentale
   - Environnement d'étude et scores
   - Temps d'écran et performance

2. Analyser l'impact des variables binaires sur :
   - Les scores aux examens
   - Le niveau de stress
   - La gestion du temps

3. Explorer les patterns de :
   - Habitudes d'étude par filière
   - Bien-être selon l'environnement d'étude
   - Performance selon le profil démographique

## Guide d'Interprétation des Statistiques

### Comment Lire les Résultats ?

1. **Pour les moyennes et pourcentages**
   - Une moyenne de 7/10 signifie que la "note typique" est de 7
   - Un pourcentage de 60% signifie que 6 étudiants sur 10 sont concernés

2. **Pour les distributions**
   - Une distribution "normale" ressemble à une cloche : la plupart des valeurs sont au milieu
   - Une distribution "asymétrique" a plus de valeurs d'un côté que de l'autre
   - Une distribution "bimodale" suggère deux groupes distincts dans les données

3. **Pour les valeurs aberrantes (outliers)**
   - Ce sont des cas "exceptionnels" qui s'écartent beaucoup de la moyenne
   - Exemple : Un temps d'étude de 12h/jour quand la moyenne est de 5h
   - Important de les identifier car peuvent influencer les résultats

### Que Chercher Dans l'Analyse ?

1. **Tendances générales**
   - Où se trouve la majorité des étudiants ?
   - Y a-t-il des groupes qui se distinguent ?

2. **Points d'attention**
   - Valeurs extrêmement hautes ou basses
   - Distributions inhabituelles
   - Groupes sous-représentés

3. **Questions pratiques**
   - Les résultats sont-ils logiques ?
   - Correspondent-ils à ce qu'on observe sur le terrain ?
   - Que peut-on faire avec cette information ? 