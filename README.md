# But
Prédire la qualité du vin en fonction de sa composition.

# Bonnes pratiques
- environnement virtuel
- requirements.txt
- README.md
- dossier `modules`
  - ia_data.py (préparation des données)
  - ia_models.py (création des modèles)
- dossier `models`
  - fichier `pkl` des modèles entrainés

# Installation
`python -m venv.venv`

`activation du venv`

`python.exe -m pip install --upgrade pip`

`pip install numpy plotly pandas ipykernel seaborn`

`pip install --upgrade nbformat`

`Et les autres librairies`

# Data Analyse
Terminer l'analyse

# Normalisation
Analyser les features après normalisation. 
- Est ce que les vins rouge et les vins blanc se ressemble?
- Peut on merger les datasets pour faire un algorithme commun aux deux?

# Merge Dataset
Créer un merge des datasets sans écraser les anciens.

# Class count
Comment équilibrer les classes? 
- oversampling
- undersampling

# Model simple
Faire un modèle simple (ML, petit NN) pour:
- les vins rouge
- les vins blanc
- tous les vins

# Results
Comparer les métriques pour les trois modèles et argumenter. 

# Improvement
Maintenant que vous avez de la visibilité et de la compréhension sur les données et les modèles, améliorez vos résultats. 

# option
Faire un petit front streamlit pour utiliser votre modèle
Analyser une bouteille à la maison :D 

# Conclusion
Conclure