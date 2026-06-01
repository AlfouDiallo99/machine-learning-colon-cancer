# 🧬 Classification de tissus du côlon (Machine Learning)

Ce projet est une introduction à l'utilisation du Machine Learning pour le diagnostic médical. Nous cherchons à entraîner un ordinateur à distinguer automatiquement des tissus sains de tissus tumoraux à partir de données génétiques.

---

## 🎯 Objectif du projet
Apprendre à manipuler un jeu de données médicales, tester différents algorithmes et comparer leurs performances pour trouver le modèle le plus efficace.

## 📊 Le jeu de données
*   **Total d'échantillons :** 804
*   **Nombre de caractéristiques :** 62 (chaque colonne représente un gène ou une mesure biologique).
*   **Variable cible (`tissue_status`) :** 
    *   `1` : Tissu normal
    *   `0` : Tissu tumoral

## 🛠️ Étapes de travail (Le pipeline)
1.  **Nettoyage & Encodage :** Conversion des labels en chiffres.
2.  **Séparation :** Découpage des données (80% pour l'entraînement, 20% pour le test).
3.  **Normalisation :** Utilisation de `StandardScaler` pour que chaque gène soit sur la même échelle.
4.  **Entraînement :** Test de plusieurs algorithmes (KNN, Arbres de décision, Random Forest, SGD).

## 🏆 Résultats
Le modèle **KNN** a obtenu les meilleurs résultats.

*   **Accuracy : 100%**
*   *Note :* Obtenir 100% est un résultat exceptionnel, mais en Machine Learning, cela peut signifier que les données sont trop "faciles". C'est un excellent point de départ pour apprendre à critiquer ses résultats.

## 🚀 Comment lancer le projet ?

### Prérequis
*   Avoir [Python](https://www.python.org/) installé.

### Installation
1. Cloner le projet :
   ```bash
   git clone <URL_DE_TON_REPO>
