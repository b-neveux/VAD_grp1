# 📘 Projet VAD – Groupe 1

**Analyse et modélisation aérodynamique d’un aéronef**

Ce dépôt contient le travail du Groupe 1 dans le cadre du projet de **Vol, Aéronautique et Dynamique (VAD)**.
Il centralise le code Python, les modèles aérodynamiques, les données et la documentation technique.

---

## 🔧 Objectifs du projet (rapport intermédiaire)

- Définir les caractéristiques géométriques et massiques d’un aéronef.
- Construire un modèle aérodynamique (coefficients, polaires…).
- Réaliser des analyses via **XFLR5**.
- Mettre en place des scripts Python pour :
  - traiter les données,
  - calculer des coefficients,
  - modéliser le comportement dynamique.

-> **Le rapport intermédiaire est disponible dans VAD_grp1/docs**

---

## 📁 Organisation du dépôt

```text
VAD_grp1/
│
├── src/                         # Scripts Python du projet
│   ├── aircraft_details.py      # Paramètres de l’aéronef
│   ├── structure.py             # Structure générale et gestion des données
│   └── data/
│       ├── Data_k_bh.py         # Fichier de coefficients k,bh
│       └── Aircraft_Data.xlsx
│
├── models/
│   └── XFLR5_tests.xfl          # Modèle XFLR5 de l’aéronef
│
├── docs/
│   ├── VAD_rapport_intermediaire.pdf
│   └── cours/                   # Matériel pédagogique (optionnel)
│
├── requirements.txt             # Dépendances Python
└── README.md                    # Documentation du projet