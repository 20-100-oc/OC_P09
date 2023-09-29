# Projet: Réalisez une application de recommandation de contenu

## Contexte
Construction du premier MVP d'une startup: système de recommandation d'articles et de livres à des particuliers.
Après consultation avec un développeur web, l'architecture de déploiement "serverless" est retenu.
Les données utilisées pour ce projet viennent d'un dataset rendu publique par Globo.com, le plus grand portail d'actualités au Brésil.
Le but est de recommander à un utilisateur donnée des articles qu'il sera susceptible de lire, compte tenu de son historique de lecture.

## Objectifs
- Développer la fonctionnalité critique du produit: "recommander 5 articles à un utilisateur"
  - pré-traîtement des données: calcul de similarité entre les articles (transformés en plongements de mots) 
  - choisir une métrique pour le calcul de similarité entre articles
  - élaborer un modèle "content-based filtering"
- La déployer le système de recommandation sous forme d'Azure Fuctions
- Créer une application d'interaction qui permet de recevoir les articles recommandés pour l'utilisateur choisi

## Livrables
- Notebooks de modélisation et scripts de déploiement
- Système de recommandation serverless et son application d'interaction
- Présentation PowerPoint

## Outils
- Python
- Git / Github
- Jupyter notebook / Python IDE
- PowerPoint
- Streamlit
- Azure web app
- Google Storage

### Python : libraires additionnelles
- numpy
- pandas
- scikit-learn
- scikit-surprise
- azure-functions
- azure-storage-blob
- streamlit
- requests