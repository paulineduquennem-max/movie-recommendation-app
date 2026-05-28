# 🎬 Système de Recommandation de Films — Cinéma Local

![Aperçu de l'application Streamlit](Capture d'écran 2026-05-28 110126.png)

## 📌 Contexte du Projet
Ce projet a été réalisé dans le cadre de ma formation de Data Analyst à la Wild Code School. L'objectif était de concevoir un outil d'aide à la décision et d'optimisation de l'expérience utilisateur pour un cinéma local, en lui permettant de proposer des recommandations de films hautement personnalisées à ses clients.

## 🎯 Objectifs Business & Techniques
* **Analyse du catalogue :** Traitement, exploration et vectorisation des caractéristiques des films (genres, notes, etc.).
* **Modélisation (Machine Learning Non Supervisé) :** Implémentation de l'algorithme des K-Plus Proches Voisins (KNN) pour calculer la similarité entre les œuvres.
* **Moteur de recommandation :** Permettre à l'utilisateur de saisir un film pour obtenir instantanément une recommandation ciblée de 5 films similaires.

## 🛠️ Stack Technique
* **Langage :** Python
* **Analyse & Traitement de données :** Pandas, NumPy
* **Machine Learning :** Scikit-learn (K-Nearest Neighbors / KNN)
* **Interface & Déploiement :** Streamlit

## 📊 Méthodologie & Étapes clés
1. **Collecte et Nettoyage (EDA) :** Traitement des données massives sur les films et les évaluations des utilisateurs, gestion des valeurs manquantes et des doublons avec Pandas.
2. **Ingénierie des features :** Sélection et normalisation des critères pertinents (genres, mot-clés, notes moyennes) pour nourrir l'algorithme.
3. **Entraînement du modèle :** Mise en place du modèle KNN non supervisé pour mesurer la distance (similarité) entre le film recherché et le reste du catalogue.
4. **Restitution :** Développement de l'application Streamlit.

## 🚀 Résultats
L'application fournit instantanément une liste de 5 films recommandés basés sur les choix ou le profil d'un utilisateur, permettant d'optimiser l'engagement de l'audience et de valoriser le catalogue du cinéma.
