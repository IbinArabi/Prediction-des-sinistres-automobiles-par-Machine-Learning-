# Prédiction des sinistres automobiles par Machine Learning 🚗📊

## 📝 Description

Ce projet explore l'application de diverses techniques de Machine Learning pour la prédiction des pertes financières et assurantielles. Il couvre à la fois les fondements théoriques (risque financier, actuariat) et une application pratique comparative de différents modèles.

L'objectif est de déterminer les algorithmes les plus performants pour des tâches telles que la prédiction de la fréquence et de la sévérité des sinistres, ainsi que la détection de fraude.

## 🎯 Objectifs du Projet

Revue de la littérature : Concepts fondamentaux du ML et applications en finance/assurance.

Développement de modèles : Prédiction des pertes (fréquence, sévérité, fraude).

Comparaison de performances : Modèles classiques (Régression) vs. Modernes (Forêts Aléatoires, Réseaux de Neurones).

Analyse : Interprétabilité des modèles et implications pour la gestion des risques.

## 🛠️ Méthodologie et Outils

Le projet suit un pipeline complet de science des données :

Analyse Exploratoire (EDA) : Compréhension des distributions de données (asymétrie, valeurs aberrantes).

Prétraitement : Gestion des valeurs manquantes, encodage One-Hot, normalisation.

Modélisation : Implémentation de :

Régression Linéaire

Arbres de Décision

Random Forest (Forêt Aléatoire)

Réseaux de Neurones Artificiels (ANN)

Évaluation : Utilisation de métriques adaptées (RMSE, MAE, Précision, Rappel) avec validation croisée.

## 📊 Résultats Clés

Le modèle Random Forest s'est révélé le plus performant avec un R² de 0.9653 et une excellente capacité à capturer les relations complexes des données d'assurance. Les méthodes d'ensemble confirment leur supériorité pour ce type de problématique.

Les Réseaux de Neurones ont capturé des relations non-linéaires complexes mais ont nécessité plus de données pour éviter le sur-apprentissage.

L'interprétabilité reste un défi majeur pour les modèles complexes dans un cadre réglementé.
