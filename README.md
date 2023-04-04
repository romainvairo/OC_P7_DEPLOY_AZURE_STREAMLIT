# OC_P7_DEPLOY_AZURE

Problématique : détecter grâce à des algorithmes de Deep Learning si un tweet a un sentiment positif ou négatif, ce qui pourra servir par la suite à aider les entreprises à atténuer les bad buzz sur les réseaux sociaux

Application streamlit sur Heroku qui appelle l'API sur azure qui permet de réaliser des prédictions grâce au modèle de regression logistique TFIDF avec lemmatisation.

Organisation des fichiers : 
app.py : 
- une case de texte pour que l'utilisateur entre une phrase dont il souhaite savoir le sentiment prédit
- un tableau qui affiche le retour de l'api d'azure en fonction de la phrase saisie

Requirements.txt :
Il est appelé lors de la mise en production pour installer les packages nécessaires.

Procfile : 
Fichier utilisé par heroku pour pouvoir lancer l'application streamlit

setup.sh :
Fichier de configuration heroku (cf. documentation)

nltk.txt :
fichier de configuration heroku


