# Classification CIFAR-10 : Optimisation Précision/Vitesse

Ce projet porte sur la conception d'un système de classification performant sur le dataset **CIFAR-10**.
L'objectif principal est d'atteindre une précision >85% tout en minimisant le temps d'inférence.

## 🧠 Approches
- **CNN Custom** : Optimisé par ajustement d'hyperparamètres (Dropout 0.65, Batch Size 128).
- **Transfer Learning** : Implémentation via MobileNetV3 Small pour l'efficacité mobile.

## 🛠️ Installation & Usage
Le projet est fourni sous forme de Notebook Jupyter (`https://colab.research.google.com/drive/11YZkGu3HktJRDzJztYHSYvNaDiCpGh44?usp=sharing`) exécutable sur Google Colab ou en local avec `torch` et `torchvision`.
