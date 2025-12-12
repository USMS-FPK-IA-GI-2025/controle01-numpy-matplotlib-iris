# Contrôle 01 — Data Science avec NumPy et Matplotlib  
**Master 1 — Intelligence Artificielle & Génie Informatique (FPK / USMS)**

---

## 1. Contexte et présentation du projet

Ce contrôle prend la forme d’un **mini-projet de data science** à réaliser individuellement.
L’objectif est de manipuler un dataset réel au format CSV et de produire une **analyse exploratoire complète** en utilisant uniquement les bibliothèques **NumPy** et **Matplotlib**.

Le travail demandé doit être réalisé de manière autonome, structurée et progressive, comme dans un contexte académique ou professionnel réel.

---

## 2. Dataset utilisé

Le dataset utilisé est le célèbre dataset **Iris**, fourni dans le dossier `data/` sous le nom : data/iris.csv


Il contient **150 observations** et **5 colonnes** :

- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `variety` (classe : Setosa, Versicolor, Virginica)

Toutes les colonnes sont numériques sauf `variety`, qui est catégorielle.

---

## 3. Objectifs pédagogiques

À travers ce mini-projet, l’étudiant doit démontrer sa capacité à :

- Charger et manipuler un fichier CSV avec **NumPy**
- Comprendre et exploiter la structure des **arrays**
- Utiliser le **slicing**, l’**indexing** et les masques booléens
- Effectuer des opérations mathématiques et statistiques vectorisées
- Réaliser des transformations de données (`reshape`, `concatenate`, etc.)
- Effectuer un nettoyage de données basique avec NumPy
- Produire des visualisations claires et pertinentes avec **Matplotlib**
- Présenter une analyse structurée et interprétée

---

## 4. Règles et contraintes techniques

**Règles strictes à respecter** :

- Bibliothèques autorisées :
  - `numpy`
  - `matplotlib`
- Toute autre bibliothèque est interdite :
  - pandas, seaborn, sklearn, scipy, etc.
- Le travail doit être réalisé dans un **Jupyter Notebook**
- Le code doit être :
  - clair
  - commenté
  - structuré par sections
- Chaque résultat doit être accompagné d’une **courte interprétation en français**

Tout non-respect de ces règles sera pénalisé.

---

## 5. Instructions de travail (GitHub & Google Colab)

- Ce dépôt est un **dépôt personnel privé**, généré automatiquement via GitHub Classroom.
- Vous pouvez travailler :
  - soit directement dans GitHub
  - soit dans **Google Colab** (recommandé), puis pousser le notebook final sur GitHub.
- Le fichier `iris.csv` doit être chargé depuis le dossier `data/`.

---

## 6. Travail demandé

Le travail demandé est organisé en plusieurs parties progressives :

- **Partie A** : Importation du dataset et premières manipulations avec NumPy
- **Partie B** : Statistiques descriptives et opérations mathématiques
- **Partie C** : Transformations avancées et nettoyage basique des données
- **Partie D** : Visualisations simples avec Matplotlib
- **Partie E** : Visualisations avancées (subplots, comparaisons)
- **Partie F** : Mini-analyse finale combinant NumPy et Matplotlib

**NB :** Les questions détaillées sont à traiter **directement dans le notebook** fourni.

---

## 7. Structure attendue du rendu

Votre dépôt final doit contenir :

controle01-numpy-matplotlib-iris/
│
├── README.md
├── notebooks/
│ └── controle_numpy_matplotlib_iris.ipynb
│
├── data/
│ └── iris.csv
│
└── figures/ (optionnel)


Le notebook doit être **exécutable du début à la fin sans erreur**.

---

## 8. Modalités d’évaluation

L’évaluation portera sur :

- La maîtrise de **NumPy** (arrays, opérations, transformations)
- La qualité des **visualisations Matplotlib**
- La clarté du code et des commentaires
- La pertinence des interprétations
- Le respect strict des consignes techniques

---

## 9. Date de remise

**Délai de remise : 1 semaine après la date de distribution du sujet**  
Toute remise en retard sera pénalisée selon le règlement pédagogique.

---

Bon travail et bon courage.
