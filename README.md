# Mini-projets Machine Learning

Trois mini-projets réalisés en Python avec scikit-learn, conçus pour être ajoutés à un portfolio GitHub.

## Projets

| Projet | Type | Dataset | Compétences démontrées |
|---|---|---|---|
| [01 - House Price Regression](01_house_price_regression) | Régression | California Housing | Préparation des données, pipeline, régression, évaluation |
| [02 - Customer Churn Classification](02_customer_churn_classification) | Classification | Dataset synthétique | Classification, déséquilibre des classes, métriques métier |
| [03 - Sentiment Analysis](03_sentiment_analysis) | NLP | Avis synthétiques | TF-IDF, classification de texte, matrice de confusion |

## Installation

```bash
python -m venv .venv
source .venv/bin/activate  # Windows : .venv\\Scripts\\activate
pip install -r requirements.txt
```

## Exécution

Chaque projet peut être lancé indépendamment depuis son dossier :

```bash
cd 01_house_price_regression
python main.py
```

Les modèles utilisent des données publiques intégrées à scikit-learn ou générées localement. Les scripts créent automatiquement un dossier `outputs/` avec les résultats et visualisations.

## Technologies

Python 3.10+, pandas, NumPy, scikit-learn, Matplotlib et Seaborn.
