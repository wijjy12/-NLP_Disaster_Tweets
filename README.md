# Natural Language Processing with Disaster Tweets

Ce projet utilise le traitement du langage naturel (NLP) pour analyser des tweets concernant des catastrophes naturelles. L'objectif principal est de prédire si un tweet est lié à une catastrophe ou non, à l'aide de techniques de NLP et de machine learning.

## Étapes du projet

### 1. **Exploration des données**

Dans cette première étape, nous avons examiné les données pour comprendre leur structure et leur contenu. Nous avons chargé les tweets à partir des fichiers CSV et avons exploré les différentes colonnes présentes dans l'ensemble de données. Cette étape permet de mieux saisir les informations disponibles et de définir les étapes suivantes pour préparer les données.

### 2. **Nettoyage et remplissage des données**

Le nettoyage des données est crucial pour garantir la qualité de notre modèle. Dans cette étape, nous avons supprimé les éléments inutiles, tels que les URL, les balises HTML, et les caractères spéciaux. Nous avons également géré les valeurs manquantes en remplissant les informations manquantes là où nécessaire.

### 3. **Pré-traitement et vectorisation**

Avant de passer à la modélisation, il est essentiel de transformer les données textuelles en un format que le modèle puisse comprendre. Nous avons procédé à plusieurs étapes de pré-traitement, telles que la conversion des mots en minuscules, la suppression des mots vides (stopwords), et le stemming (réduction des mots à leur racine). Ensuite, nous avons vectorisé les textes en utilisant des techniques adaptées pour les transformer en données numériques.

### 4. **Division des données**

Après le pré-traitement, nous avons divisé notre ensemble de données en deux parties : une pour l'entraînement du modèle et l'autre pour les tests. Cette division permet de valider la performance du modèle de manière indépendante.

### 5. **Application du modèle de machine learning**

Nous avons utilisé un modèle de régression logistique pour entraîner notre modèle à classer les tweets en fonction de leur lien avec une catastrophe. Nous avons également évalué la performance du modèle en utilisant la matrice de confusion, qui permet de voir combien de prédictions ont été correctes et incorrectes.

### 6. **Conclusion**

À la fin de ce projet, le modèle a montré une capacité à prédire efficacement les tweets liés aux catastrophes naturelles. Cette analyse démontre l'importance de bien préparer et nettoyer les données avant de les utiliser dans des modèles de machine learning.

---

## Comment exécuter le projet

1. Téléchargez le fichier du projet.
2. Remplacez l'URL par `CMD` dans le fichier.
3. Exécutez le fichier Jupyter Notebook pour suivre l'analyse étape par étape.
