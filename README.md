# Résolution numérique de l'équation de Black–Scholes 📈

Ce projet, réalisé dans le cadre du cours d'EDP à **CentraleSupélec**, propose une étude comparative des méthodes numériques pour la valorisation d'options financières (Européennes et Barrières).

## Fonctionnalités
- **Méthodes de Différences Finies** : Implémentations explicites et implicites pour résoudre l'EDP de Black-Scholes.
- **Options supportées** : 
    - Options européennes (Call & Put).
    - Options barrières (Down-and-Out Call).
- **Modèles de référence** : Comparaison des résultats avec :
    - La formule fermée de Black-Scholes.
    - La méthode des arbres binomiaux.
    - Les simulations de Monte-Carlo.
- **Visualisation** : Graphiques 3D du prix de l'option en fonction du temps et du prix du sous-jacent.

## Installation
Clonez le dépôt et installez les dépendances :
```bash
pip install -r requirements.txt
