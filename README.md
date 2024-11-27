# Réparation Automatique de Programmes avec la Programmation Génétique

## Description

Ce projet explore l'utilisation de la **programmation génétique** pour détecter et réparer automatiquement des bugs dans des programmes. La programmation génétique est une méthode d'optimisation inspirée de l'évolution biologique qui utilise des algorithmes génétiques pour générer des solutions. 

L'objectif principal est de concevoir un système capable de produire des correctifs automatiques pour des programmes contenant des erreurs, d'évaluer ces correctifs en termes d'efficacité et de pertinence, puis de les appliquer aux programmes cibles.

---

## Fonctionnalités principales

- Collecte de données : Identification et gestion d'un ensemble de programmes avec leurs bugs et correctifs manuels.
- Génération de correctifs : Application de la programmation génétique pour proposer des correctifs automatiques.
- Évaluation : Analyse des correctifs générés à l'aide de mesures de qualité et de taux de réussite.
- Intégration : Déploiement du système dans un environnement de développement logiciel existant.

---

## Technologies et outils utilisés

### Langages de programmation
- Python
- Java
- C++
- C#
- Ruby

### Frameworks et bibliothèques
- **Programmation génétique** : DEAP, PyGMO, ECJ
- **Analyse de code** : AST (Python), Clang (C++), PMD (Java)
- **Tests automatisés** : pytest (Python), JUnit (Java)

### Environnements et outils
- IDE : PyCharm, Visual Studio Code, Eclipse
- Gestion de version : Git, SVN, Mercurial

---

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/username/reparation-programmes-genetique.git
   cd reparation-programmes-genetique
   ```

2. Installez les dépendances nécessaires en utilisant `pip` (si vous utilisez Python) :
   - Si vous utilisez Python, installez les bibliothèques nécessaires à partir des sources comme `DEAP`, `pytest`, et autres nécessaires à l'exécution du projet.
   ```bash
   pip install deap pytest
   ```

   - Vous pouvez également ajouter toute autre dépendance manuellement, en fonction des bibliothèques que vous utilisez dans le projet.


3. Configurez votre environnement pour les autres langages (Java, C++, etc.).

---

## Structure du projet

```plaintext
├── data/                # Ensemble de données de programmes avec bugs et correctifs
├── src/                 # Code source du projet
│   ├── genetic/         # Implémentation de la programmation génétique
│   ├── analysis/        # Outils d'analyse de code
│   ├── evaluation/      # Méthodes d'évaluation des correctifs
│   └── tests/           # Tests unitaires et automatisés
├── requirements.txt     # Fichier des dépendances Python
├── README.md            # Documentation du projet
```

---

## Utilisation

1. **Collecte de données :** Ajoutez des programmes avec des bugs dans le dossier `data/`.
2. **Exécution du système :**
   - Pour Python :
     ```bash
     python src/genetic/main.py
     ```
   - Pour Java :
     ```bash
     javac src/genetic/Main.java
     java src/genetic.Main
     ```
3. **Analyse des correctifs :** Consultez les résultats dans le dossier `output/`.

---

## Résultats attendus

- Un système fonctionnel de réparation automatique basé sur la programmation génétique.
- Une évaluation détaillée des correctifs générés, avec des rapports sur :
  - Taux de réussite
  - Qualité des correctifs
- Intégration d'un module d'assistance pour IDE.

---

## Screenshots


![Screenshot 5](https://github.com/dinaftc/project_2cs/raw/main/Screenshot%202024-06-10%20024553.png)
![Screenshot 6](https://github.com/dinaftc/project_2cs/raw/main/Screenshot%202024-06-10%20024615.png)
![Screenshot 7](https://github.com/dinaftc/project_2cs/raw/main/Screenshot%202024-06-10%20024722.png)
![Screenshot 8](https://github.com/dinaftc/project_2cs/raw/main/Screenshot%202024-06-10%20024740.png)



