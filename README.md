# Mini-Projet : Apprentissage par Renforcement et Analyse Comparative

Cours 8INF867 - Fondamentaux de l'Apprentissage Automatique

UQAC - Automne 2025

Léon MORALES, Léonard ZIPPER

## Description

Ce projet compare deux approches d'apprentissage automatique appliquées au marché du Bitcoin :
- Deep Q-Network (DQN) pour le trading algorithmique
- Réseau de neurones supervisé pour la classification directionnelle
- Adaptation du DQN pour la classification

## Notebooks

- `train_dqn.ipynb` : Agent DQN pour le trading avec gestion de portefeuille
- `train_supervised.ipynb` : Réseau supervisé pour la prédiction de direction
- `train_dqn_classification.ipynb` : DQN adapté pour la classification

## Installation

```bash
pip install torch numpy pandas yfinance ta matplotlib seaborn scikit-learn
```

## Exécution

Les notebooks sont autonomes et peuvent être exécutés dans n'importe quel ordre. Chaque notebook génère ses propres graphiques de résultats.

## Données

Les données Bitcoin (2018-2024) sont téléchargées automatiquement via l'API yfinance lors de l'exécution des notebooks.