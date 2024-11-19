# Credit Scoring System for Banking

## Description
Ce projet implémente un système de scoring de crédit destiné aux institutions financières. À l'aide de modèles de machine learning, le système évalue le profil des clients pour prédire leur éligibilité au crédit. Une interface utilisateur basée sur Flask permet de saisir les données et d'obtenir des prédictions en temps réel.

### Objectifs :
- Aider les banques à prendre des décisions éclairées concernant l'octroi de crédits.
- Offrir une interface conviviale pour interagir avec le modèle prédictif.

---

## Structure du projet
Le projet contient les fichiers suivants :
1. **app.py :** Script Flask pour exécuter l'application et connecter le modèle de scoring.
2. **model.joblib :** Modèle de machine learning pré-entraîné pour effectuer les prédictions.
3. **templates/index.html :** Fichier HTML pour l'interface utilisateur (non inclus ici, mais peut être ajouté).

---

## Installation
Pour exécuter ce projet localement, suivez ces étapes :

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/YassineJada/Credit-Scoring-System.git
   cd Credit-Scoring-System

2. Installer les dépendances requises :
   ```bash
   pip install -r requirements.txt

Si le fichier requirements.txt n'est pas présent, installez ces bibliothèques :
   ```bash
   pip install flask numpy joblib
