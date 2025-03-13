# RNN From Scratch - Prédiction des noms de dinosaures 



![Sans titre](https://github.com/user-attachments/assets/9ed02a0f-e78a-43f9-a95a-1bafb16fd048)

![Sans titre](https://github.com/user-attachments/assets/bb747be8-0009-4729-955f-bf02810f3336)


# Description du projet

Ce projet implémente un Réseau de Neurones Récurrent (RNN) from scratch pour la prédiction de noms de dinosaures à partir de leur première lettre. L’objectif est de modéliser les séquences de caractères et de comprendre comment un RNN peut apprendre à générer du texte.

Plutôt que d'utiliser un framework comme TensorFlow ou PyTorch, l'algorithme est codé entièrement en NumPy, permettant une compréhension approfondie des concepts comme :
Propagation avant dans un RNN
Rétropropagation dans le temps (BPTT - Backpropagation Through Time)
Entraînement sur des séquences de caractères
Génération de texte (noms de dinosaures) caractère par caractère

# Objectifs du projet

Enseigner à un RNN à générer des noms de dinosaures en se basant uniquement sur la première lettre.
Expérimenter l’apprentissage séquentiel avec un jeu de données textuel.
Comprendre comment un RNN apprend les relations entre les caractères pour former des mots réalistes.
Étudier les limites et améliorations possibles, comme l’implémentation de LSTM ou GRU.
Structure du projet

![Sans titre](https://github.com/user-attachments/assets/07071169-c2bc-45ba-ad86-8f18df0c58db)


# Approche et Méthodologie


![Sans titre](https://github.com/user-attachments/assets/dd964312-95ac-4200-9b6d-54300353cfbe)



![Sans titre](https://github.com/user-attachments/assets/e38e4f38-4e3e-4407-9b48-e2dbdf05dbf7)



1 Chargement des données 📂

    Le dataset dinosaurs.txt contient une liste de noms de dinosaures.
    Chaque mot est converti en séquence de caractères.

2 Prétraitement des données 🛠

    Conversion des caractères en vecteurs numériques (one-hot encoding).
    Création de paires (entrée, sortie) où l'entrée est la première lettre et la sortie est le mot entier.

3 Implémentation du RNN 🧠

    Définition de la structure du RNN simple avec NumPy.
    Implémentation de la propagation avant et arrière (BPTT).
    Mise à jour des poids avec descente de gradient.

4 Entraînement du modèle 📊

    L'entraînement se fait sur plusieurs époques en minimisant l'erreur de prédiction.
    La fonction de coût est surveillée pour ajuster les hyperparamètres.

5 Génération de noms de dinosaures 🦕

    À partir d'une lettre donnée, le RNN génère un nom plausible caractère par caractère.
    Comparaison des résultats avec les noms réels.


# Exemple de Prédiction

![image](https://github.com/user-attachments/assets/7cdf1a00-59c9-43dd-a212-082eb55ade87)


Le modèle apprend progressivement à prédire des noms proches des vrais.
La perte diminue au fil des itérations, montrant un bon apprentissage.
Améliorations futures :

    Ajouter un LSTM ou GRU pour mieux gérer les longues séquences.
    Augmenter la taille du dataset pour une meilleure généralisation.
    Ajouter une technique de régularisation pour améliorer la robustesse.

# Installation et Exécution

🔧 Installation et Exécution

1️⃣ Cloner le dépôt GitHub

git clone https://github.com/idrissi-mounadi-doha/RNN_FROM_SCRATCH.git
cd RNN_FROM_SCRATCH

2️⃣ Installer les dépendances

pip install -r requirements.txt

3️⃣ Lancer l’entraînement du modèle

python src/train.py

4️⃣ Générer des noms de dinosaures

python src/generate.py
# Auteur

👨‍💻 IDRISSI MOUNADI DOHA

📧 Email : dohaidrissimou@gmail.com

🔗 LinkedIn : Doha Idrissi Mounadi
