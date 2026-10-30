# Projet Machine Learning

Mini-projets d'apprentissage automatique et de deep learning réalisés avec Python sur Google Colab.

## TP2 : Reconnaissance de chiffres manuscrits (MNIST)

Entraînement d'un réseau de neurones avec TensorFlow/Keras pour reconnaître des chiffres manuscrits (0 à 9) à partir d'images de 28×28 pixels.

- **Données** : base MNIST (60 000 images d'apprentissage, 10 000 de test), avec 20 % de l'apprentissage réservé à la validation
- **Modèle** : perceptron multicouche (MLP) avec 2 couches cachées (128 et 64 neurones, activation ReLU), Dropout 0,3 et sortie softmax à 10 classes
- **Entraînement** : optimiseur Adam, perte `sparse_categorical_crossentropy`, 5 époques
- **Résultat** : [XX] % de précision sur l'ensemble de test
- **Visualisations** : exemples d'images, courbes de précision et de perte (apprentissage et validation), prédictions sur des exemples, analyse des images mal classées
- **Outils** : Python, TensorFlow/Keras, NumPy, Matplotlib

Notebook : [TP2_Reconnaissance_Chiffres_MNIST.ipynb](TP2_Reconnaissance_Chiffres_MNIST.ipynb)

## Auteure

Cyrine Gasmi, étudiante en systèmes embarqués, IA & IoT (ISI Ariana)
