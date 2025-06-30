# 🐶🐱 Classification d’Images : Dogs vs Cats

Ce projet utilise un modèle de deep learning (CNN avec TensorFlow) pour classifier des images de **chiens** et de **chats** à partir d'un dataset d'entraînement.

---

## 📁 Structure du projet

```
.
├── dogs_vs_cats/     # Dossier contenant les images (non suivi par Git)
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   └── test/
│       ├── cats/
│       └── dogs/
├── Project_7.ipynb   # Notebook principal avec tout le code
├── .gitignore        # Fichier pour ignorer les images
├── requirements.txt  # Librairies nécessaires
└── README.md         # Ce fichier
```

---

## 🚀 Objectifs du projet

- Charger et prétraiter des images
- Créer un modèle CNN avec TensorFlow/Keras
- Entraîner le modèle et suivre ses performances
- Éviter le sur-apprentissage avec `EarlyStopping` et `Dropout`
- Évaluer la précision du modèle sur des données de test

---

## 🧠 Technologies utilisées

- Python 3
- TensorFlow / Keras
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Installation

1. Cloner ce dépôt :
```bash
git clone <URL_DU_DEPOT>
cd CLASSIFICATION_DOG_VS_CAT
```

2. Créer un environnement virtuel :
```bash
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate.bat     # Windows
```

3. Installer les dépendances :
```bash
pip install -r requirements.txt
```

---

## 📊 Résultats

Le modèle atteint une précision d'entraînement supérieure à 95%, et une précision de validation autour de 78-80% avant régularisation.

Des techniques comme l’augmentation de données, `Dropout`, et `EarlyStopping` sont utilisées pour limiter l'**overfitting**.

---

## 📝 À venir

- Test sur image individuelle
- Amélioration avec MobileNetV2
- Export du modèle pour API ou application

---

## 🔒 Remarque

Les dossiers `dogs_vs_cats/`, `train/`, et `test/` sont **ignorés dans le suivi Git** via `.gitignore` pour ne pas surcharger le dépôt.

---

## 📬 Auteur

Projet réalisé par Ephraïm KOSSONOU dans le cadre de l’apprentissage du deep learning.