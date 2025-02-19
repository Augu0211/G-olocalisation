# Géolocalisation
📌 Projet de Géolocalisation par Réseaux de Neurones

Ce projet vise à prédire la position d’un utilisateur en fonction de mesures de signaux RSSI (Received Signal Strength Indicator) à l’aide d’un réseau de neurones artificiels. L’objectif est d’exploiter des données de réception de signal pour estimer une position avec une précision optimisée.
🚀 Travail réalisé

1️⃣ Importation et préparation des données

    Lecture des fichiers RSSI et fusion des différentes sources d’information.
    Nettoyage des données pour éliminer les valeurs aberrantes et standardisation des variables.

2️⃣ Exploration et analyse des données

    Étude de la distribution des signaux RSSI et de leur relation avec la position.
    Visualisation des données pour mieux comprendre les patterns exploitables.

3️⃣ Construction du modèle de prédiction

    Définition d’un réseau de neurones adapté à la tâche de régression ou classification selon la nature du problème.
    Sélection des hyperparamètres (nombre de couches, neurones, fonction d’activation, etc.).
    Implémentation avec TensorFlow/Keras.

4️⃣ Entraînement et optimisation du modèle

    Division des données en ensemble d’entraînement et de test.
    Ajustement du modèle avec des techniques de régularisation pour éviter l’overfitting.
    Évaluation des performances à l’aide de métriques adaptées (ex. erreur moyenne en régression, accuracy en classification).

5️⃣ Interprétation et visualisation des résultats

    Analyse des erreurs et de la précision des prédictions.
    Comparaison avec d’autres méthodes de localisation (ex. moyenne des signaux, modèles classiques).

🛠️ Technologies utilisées

    Python (Pandas, NumPy) pour la gestion et le traitement des données.
    TensorFlow/Keras pour la construction et l’entraînement du réseau de neurones.
    Matplotlib, Seaborn pour la visualisation des résultats.

🎯 Résultats obtenus

📌 Le modèle a permis d’obtenir une estimation de position basée sur les signaux RSSI, avec une erreur moyenne raisonnable, démontrant la pertinence des réseaux de neurones pour ce type de problème.
