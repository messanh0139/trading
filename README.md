# trading

# Projet d'Apprentissage par Renforcement pour le Trading

## 1. Description

Ce projet explore l'application de plusieurs algorithmes d'apprentissage par renforcement profond (Deep RL) à un problème de trading algorithmique. L'objectif est de comparer les performances de différents agents :

*   **DQN (Deep Q-Network)**
*   **Double DQN**
*   **Dueling DQN**

Les performances de ces agents sont évaluées en termes de récompenses cumulées et de valeur du portefeuille (`Portfolio Value`). Les résultats sont également comparés à une stratégie de référence simple : **Buy & Hold**.

Le projet est structuré sous forme de notebook Jupyter, permettant une analyse et une visualisation pas à pas des résultats.

## 2. Technologies et Bibliothèques

Le projet utilise les principales bibliothèques Python pour la science des données et l'apprentissage par renforcement :

*   **TensorFlow** et **PyTorch** : Frameworks pour la création des réseaux de neurones.
*   **Stable-Baselines3** : Une bibliothèque de référence pour les implémentations d'algorithmes de RL.
*   **Gymnasium** : La boîte à outils standard pour créer et interagir avec les environnements de RL.
*   **Pandas** : Pour la manipulation et l'analyse des données financières.
*   **NumPy** : Pour les calculs numériques.
*   **Matplotlib** : Pour la visualisation des résultats et des graphiques de performance.

## 3. Installation

Pour exécuter ce projet, suivez les étapes ci-dessous.

1.  **Clonez le dépôt (exemple) :**
    ```bash
    git clone https://github.com/messanh0139/trading.git
    cd KODJO_TP06_TP07_RL
    ```

2.  **Créez un environnement virtuel :**
    Il est fortement recommandé d'utiliser un environnement virtuel pour isoler les dépendances du projet.
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Installez les dépendances :**
    Utilisez le fichier `requirements.txt` fourni pour installer toutes les bibliothèques nécessaires.
    ```bash
    pip install -r requirements.txt
    ```

## 4. Utilisation

1.  Lancez Jupyter Notebook ou JupyterLab depuis votre terminal :
    ```bash
    jupyter notebook
    ```
2.  Ouvrez le fichier de notebook principal du projet.
3.  Pour garantir que toutes les variables sont correctement initialisées, il est conseillé d'exécuter toutes les cellules dans l'ordre. Vous pouvez le faire via le menu **"Kernel" -> "Restart & Run All"**.

Les résultats, y compris les graphiques comparatifs, seront affichés à la fin du notebook.
