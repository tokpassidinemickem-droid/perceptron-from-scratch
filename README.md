# Perceptron From Scratch

## Description

Ce projet a été réalisé dans le cadre d'un stage académique de Licence 3 en Mathématiques-Informatique.

Il consiste à développer un **perceptron from scratch** en Python, sans utiliser l'implémentation du perceptron proposée par les bibliothèques de Machine Learning.

Le modèle est appliqué au **Wisconsin Breast Cancer Dataset** afin de classifier les tumeurs en deux catégories :
- Tumeur bénigne (Benign)
- Tumeur maligne (Malignant)

---

## Objectifs

- Comprendre le fonctionnement du perceptron
- Implémenter l'algorithme à partir des équations mathématiques
- Préparer et normaliser un jeu de données réel
- Évaluer les performances du modèle
- Visualiser les résultats obtenus

---

## Technologies utilisées

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (uniquement pour `train_test_split` et `PCA`)

---

## Jeu de données

Le projet utilise le **Wisconsin Breast Cancer Dataset** (`breast.csv`).

---

## Résultats obtenus

Le perceptron développé atteint une précision d'environ :

**Accuracy : 95,33 %**

Les visualisations générées comprennent :

- Courbe d'apprentissage
- Matrice de confusion
- Frontière de décision (PCA)
- Visualisation d'un nouveau patient

---

## Structure du projet

```
perceptron-from-scratch/
│
├── breast.csv
├── perceptron.py (ou projet_de_stage.ipynb)
├── courbe_apprentissage.png
├── matrice_confusion.png
├── frontiere_decision.png
├── nouveau_patient.png
├── README.md
```

---

## Auteur

**TOKPASSI Dine Mickem**

Licence 3 Mathématiques-Informatique

UNSTIM – FAST Natitingou

Année académique : 2025–2026

---

## Encadrement

Projet réalisé dans le cadre d'un stage académique au :

**CAEB Natitingou – Fondation Vallet**
