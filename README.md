# TP - Mini Réseau de Neurones avec NumPy (XOR)

TP du module Python pour l'IA - implémentation d'un réseau de neurones de zéro avec NumPy et Matplotlib (sans framework comme TensorFlow/PyTorch).

## Contenu

- `TP_XOR_NumPy.ipynb` : le notebook avec tout le code (fonctions d'activation, réseau 2→3→1, forward, backprop, entraînement, étude d'influence, dataset bruité, évaluation)
- `rapport.docx` : le rapport du TP
- `info.md` : l'énoncé du TP

## Comment lancer le notebook

```
pip install numpy matplotlib scipy notebook
jupyter notebook TP_XOR_NumPy.ipynb
```

Puis "Run All" pour tout réexécuter.

## Résumé

- Implémentation de ReLU, Sigmoid, Tanh, Leaky ReLU (+ Softplus et ELU en extension)
- Réseau 2 → 3 (tanh) → 1 (sigmoid) entraîné sur XOR
- Backpropagation codée à la main (sans autodiff)
- Étude de l'influence du learning rate, du nombre de neurones cachés et de l'activation
- Évaluation sur un XOR bruité : accuracy, precision, recall, F1, matrice de confusion, courbe ROC/AUC
