RNN From Scratch 
Description 

Ce projet implémente un Réseau de Neurones Récurrent (RNN) à partir de zéro, sans utiliser de frameworks avancés comme TensorFlow ou PyTorch. L'objectif est d'explorer et de comprendre en profondeur les concepts fondamentaux des RNN, notamment la propagation avant, la rétropropagation dans le temps (BPTT) et l'apprentissage séquentiel.
Objectifs du projet 

L'objectif principal de ce projet est de comprendre et d'implémenter un RNN de base, en mettant en pratique les concepts fondamentaux des réseaux de neurones récurrents. Plus précisément, ce projet vise à :

Comprendre la théorie des RNN :
Étudier la structure des RNN et leur utilité.
Apprendre les concepts de mémoire et de dépendances temporelles.

Implémenter un RNN from scratch :
Construire un modèle RNN sans utiliser de frameworks préconçus comme TensorFlow ou PyTorch.
Gérer la propagation avant et arrière dans le temps (BPTT).

Expérimenter sur des données séquentielles :
Tester le modèle sur des séries temporelles ou du texte.
Observer l’évolution de la perte et ajuster les hyperparamètres.

Analyser les performances et explorer les améliorations possibles :
Visualiser les résultats et identifier les limites du modèle.
Comparer avec d'autres architectures comme LSTM et GRU.

Contenu du Notebook 

Le notebook RNN_FROM_SCRATCH.ipynb couvre les aspects suivants :
Introduction aux RNN : pourquoi les utiliser et comment ils fonctionnent ?
Implémentation des fonctions fondamentales :
Initialisation des poids et biais
Fonction d'activation (tanh, softmax)
Propagation avant
Propagation arrière avec BPTT
Mise à jour des paramètres avec descente de gradient
Entraînement du modèle sur un dataset simple.
Analyse des performances et discussion des limites.

Prérequis 🛠

Avant d'exécuter ce projet, assure-toi d'avoir installé les dépendances suivantes :

pip install numpy matplotlib

Utilisation 

Pour exécuter le projet :

    Clone le dépôt :

git clone https://github.com/idrissi-mounadi-doha/RNN_FROM_SCRATCH.git
cd RNN_FROM_SCRATCH

Ouvre le notebook avec Jupyter :

    jupyter notebook RNN_FROM_SCRATCH.ipynb

Résultats 📊

Des visualisations des pertes d'entraînement ainsi que des prédictions du modèle seront générées pour mieux comprendre son comportement.
Améliorations possibles 🚀

    Ajouter LSTM et GRU pour comparaison.
    Expérimenter avec des datasets plus complexes.
    Implémenter une version PyTorch ou TensorFlow pour vérifier les performances.

Auteur 

    IDRISSI MOUNADI DOHA
    📧 Email : dohaidrissimou@gmail.com
    🔗 LinkedIn : Doha Idrissi Mounadi
