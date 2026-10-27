# OpenClassrooms — Parcours Développeur d'Application Python 🐍

Ce méta-répertoire regroupe l'ensemble des projets réalisés dans le cadre du parcours certifiant **Développeur d'Application — Python** chez [OpenClassrooms](https://openclassrooms.com/).

L'intégralité de l'historique Git d'origine de chaque projet a été préservée via `git subtree`.

---

## 📋 Répertoire des projets

| Projet | Nom | Description | Stack & Compétences |
| :---: | :--- | :--- | :--- |
| **02** | [**p02-bookworm**](./p02-bookworm) | Web scraper de surveillance des prix de livres | `Python`, `BeautifulSoup4`, `Requests`, `ETL / CSV` |
| **03** | [**p03-conception**](./p03-conception-cahier-des-charges) | Analyse des besoins et modélisation technique | `Cahier des charges`, `UML`, `Backlog Agile`, `User Stories` |
| **04** | [**p04-gestionnaire-tournoi**](./p04-gestionnaire-tournoi-echecs) | Gestionnaire de tournois d'échecs en mode console (ronde suisse) | `Python`, `Architecture MVC`, `POO`, `Flake8` |
| **06** | [**p06-juststreamit**](./p06-juststreamit) | Interface web dynamique consommant une API REST de notation de films | `JavaScript vanilla`, `HTML5/CSS3`, `API REST`, `Fetch / Asynchrone` |
| **07** | [**p07-algoinvest**](./p07-algoinvest-trade) | Algorithmes d'optimisation d'investissements financiers | `Python`, `Force brute`, `Programmation dynamique (sac à dos)`, `Algorithmes gloutons` |
| **09** | [**p09-litreview**](./p09-litreview) | Plateforme web communautaire de critique de livres et d'articles | `Python`, `Django (MVT)`, `ORM Django`, `Auth`, `Bootstrap` |
| **10** | [**p10-softdesk**](./p10-softdesk-api) | API REST sécurisée de gestion de tickets de support et d'incidents | `Django REST Framework (DRF)`, `JWT Authentication`, `Permissions CRUD`, `Postman` |
| **11** | [**p11-gudlft**](./p11-gudlft-qa) | Débogage, tests et assurance qualité sur une application de réservation | `Flask`, `Pytest`, `Couverture de code (Coverage)`, `Profiling de performance` |
| **12** | [**p12-epic-events**](./p12-epic-events-crm) | Logiciel CRM sécurisé pour une entreprise d'événementiel | `Python`, `Click (CLI)`, `Peewee / SQLAlchemy`, `Sentry`, `Permissions RBAC` |
| **12b**| [**p12-epic-events-v2**](./p12-epic-events-crm-v2) | Évolution et refactoring du CRM Epic Events | `Python CLI`, `PostgreSQL`, `Clean Architecture` |
| **13** | [**p13-oc-lettings**](./p13-oc-lettings-cicd) | Refactoring, conteneurisation et déploiement continu d'un site immobilier | `Django`, `Docker`, `GitHub Actions (CI/CD)`, `Sentry`, `ReadTheDocs` |

---

## 🛠️ Stack technique globale

* **Langage & Environnement** : Python 3, POO, Typage, PEP8 / Flake8 / Black
* **Frameworks Web & API** : Django, Django REST Framework (DRF), Flask
* **Bases de données & ORM** : PostgreSQL, SQLite, Django ORM, SQLAlchemy, Peewee
* **Qualité & Tests** : Pytest, Unittest, Coverage, TDD
* **DevOps & Déploiement** : Docker, GitHub Actions CI/CD, Sentry (monitoring d'erreurs)
* **Architecture logicielle** : MVC, MVT, Clean Architecture, Algorithmique & Complexité (Big O)

---

## 🚀 Utilisation

Chaque sous-dossier dispose de son propre `README.md`, de son `requirements.txt` et de sa documentation spécifique :

```bash
# Cloner le méta-répertoire complet
git clone https://github.com/0ddbird/openclassrooms-python.git
cd openclassrooms-python

# Explorer un projet spécifique
cd p10-softdesk-api
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
```
