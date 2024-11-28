# Analyse des sentiments exprimés dans les avis de films

## Description

Ce projet de science des données a pour objectif de développer un modèle de classification capable de distinguer les avis positifs des avis négatifs sur des films, en utilisant des commentaires utilisateurs. L'analyse se base sur l'utilisation de techniques de prétraitement du texte, telles que la lemmatisation et la suppression des stopwords, et sur plusieurs algorithmes de classification, comme les forêts aléatoires, les machines à vecteurs de support (SVM), la régression logistique et les réseaux de neurones.

## Objectifs

- **Prétraitement des données** : Nettoyage et transformation des commentaires utilisateurs, y compris la suppression des mots inutiles (stopwords) et la lemmatisation des mots.
- **Développement d'un modèle de classification** : Mise en place et expérimentation de plusieurs modèles pour prédire la polarité des avis.
- **Évaluation du modèle** : Mesure des performances du modèle sur un jeu de données de test, avec des métriques de précision et de rappel.

## Méthodologie

1. **Prétraitement des données** : 
   - Nettoyage des textes
   - Suppression des stopwords
   - Lemmatisation des mots

2. **Sélection et entraînement des modèles** :
   - Forêts aléatoires
   - Machines à vecteurs de support (SVM)
   - Régression logistique
   - Réseaux de neurones

3. **Évaluation et optimisation** :
   - Analyse des performances du modèle à l'aide des métriques de précision et de rappel.
   - Analyse des erreurs de classification et ajustements pour améliorer la performance.

## Outils et technologies utilisés

- **Python** : Langage principal de développement.
- **Jupyter Notebook** : Pour l'interactivité et la documentation du processus.
- **Scikit-learn** : Pour l'implémentation des modèles de classification.
- **NLTK** : Pour le prétraitement du texte et le traitement linguistique.
- **Matplotlib** : Pour la visualisation des résultats.

## Installation

### Prérequis

Assurez-vous d'avoir Python 3.x installé sur votre machine. Vous pouvez vérifier votre version de Python en exécutant la commande suivante dans votre terminal :

```bash
python --version
