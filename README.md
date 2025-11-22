📌 Aperçu du Projet

Ce projet vise à automatiser la détection de la pneumonie à partir d’images radiologiques.
La pneumonie est une infection pulmonaire sérieuse, et son détection précoce permet d’améliorer la prise en charge.

Le modèle est entraîné sur le dataset Chest X-Ray Pneumonia Dataset, qui contient des milliers d’images annotées.

📊 Dataset

Le dataset contient deux classes :

Normal : Images de poumons sains

Pneumonia : Pneumonie virale ou bactérienne
🧠 Modèle & Architecture

Le modèle utilisé est un CNN :

Convolution 2D

MaxPooling

Flatten

Fully Connected layers

Dropout

Fonctions d’activation : ReLU, Sigmoid
Fonction de perte : Binary Crossentropy
Optimiseur : Adam

📈 Résultats
Dataset	Accuracy
Train	89%
Validation	75%
Test	75%
Loss finale : 1.62

Des visualisations sont disponibles dans reports/ :

ROC curve

PR curve

Confusion Matrix
👩‍💻 Auteurs

ACOINE Salma
ACHOUKHI Razane
5IIR 11 — 2025–2026
