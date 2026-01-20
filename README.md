# Classification CIFAR-10 : Optimisation Précision/Vitesse (Groupe 21)

Ce projet porte sur la conception d'un système de classification performant sur le dataset **CIFAR-10**. 
L'objectif est d'explorer le compromis entre précision et efficacité computationnelle (latence d'inférence).

## 🚀 Performances Obtenues
- **Meilleur Modèle (CNN Custom)** : **83.14%** de précision.
- **Vitesse d'inférence** : **1.21 ms** (GPU T4).

## 🧠 Approches Expérimentées
- **MLP (Baseline)** : Étude d'une structure naïve sans couches de convolution (Précision : ~52%).
- **CNN Custom** : Architecture optimisée (Dropout 0.65, Batch Size 128) pour capturer la topologie 2D.
- **Transfer Learning (MobileNetV3)** : Exploration de l'efficacité mobile.
- **Distillation de connaissances** : Utilisation d'un modèle "Enseignant" pour guider un modèle "Élève".

## 🛠️ Installation & Usage

### Option 1 : Google Colab (Recommandé)
Le projet est prêt à l'emploi sur Google Colab avec accès GPU gratuit :
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11YZkGu3HktJRDzJztYHSYvNaDiCpGh44?usp=sharing)

### Option 2 : Exécution Locale (Linux/Windows)
Pour exécuter le projet localement, clonez le dépôt et installez les dépendances :

1. **Cloner le projet** :
   ```bash git clone https://github.com/JairVasquezT/CIFAR10-Optimization-ENSTA-Group21.git
