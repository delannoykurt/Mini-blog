# 📝 Mini Blog avec Flask

Ce projet est un **mini blog** développé avec **Python** et **Flask**. Il permet d'afficher une liste d'articles, d'en ajouter de nouveaux via un formulaire, et de voir la page se mettre à jour dynamiquement.

---

## 🚀 Fonctionnalités

- Affichage dynamique des articles
- Formulaire d'ajout de nouveaux articles
- Mise à jour de la page sans base de données (en mémoire pour l'instant)
- Structure professionnelle avec templates Flask (`base.html`, `index.html`, etc.)

---

## 📁 Structure du projet

/mini_blog/
├── app.py
├── static/
│   └── style.css
├── templates/
│   ├── index.html
│   ├── ajouter.html
│   └── base.html
└── data/
    └── articles.txt   ← (facultatif pour sauvegarder)



## ⚙️ Prérequis

- Python 3.x
- Flask

Installe Flask avec :

```bash
python -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate     # (Windows)
# Installation des dépendances
pip install -r requirements.txt

▶️ Lancer le projet
python run.py

Puis ouvre dans ton navigateur :
http://127.0.0.1:5000


✍️ Ajouter un article
Clique sur "Ajouter un article"

Remplis le formulaire avec un titre et un contenu

Clique sur "Publier"

→ L’article s’affiche automatiquement sur la page d’accueil



💡 Améliorations possibles
Sauvegarde des articles dans un fichier .json ou .csv

Ajout d’un identifiant unique (id) par article

Suppression ou édition d’un article

Ajout d’une base de données SQLite

Design plus poussé avec Bootstrap


📚 Ressources utiles
Documentation officielle Flask

Jinja2 Templates

Python.org
