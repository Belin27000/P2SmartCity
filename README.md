
# P2SmartCity

Pour ce projet nous allons réaliser une analyse exploratoire avec un jeu de données portant sur les arbres de la ville de Paris, dans le cadre du programme “Végétalisons la ville”.

Les résultats contribueront à une optimisation des tournées pour l’entretien des arbres de la ville. 
## Tech Stack


![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)

![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)

![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)

![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=folium&logoColor=white)


## Installation
Suivre ces étape pour l'installation du projet
1. Clone du projet

```bash
  git clone https://github.com/Belin27000/P2SmartCity.git
```

Se positionner à la racine du projet.


2. création de l'environnement virtuel

 a. installation du package pour la création de l'environnement virtuel
```bash
  pip install virtualenv
```
b. Création de l'environnement virtuel
```bash
  virtualenv P2_env
```
c. Activation de l'environnement virtuel
```bash
  source P2_env/bin/activate
```

### installation du fichier requirement.txt
#### Prérequis
Avoir le fichier requirements.txt à la racine du dossier
```bash
  pip install -r requirements.txt
```

## Rendre accessible l'environnement dans jupyter

- Se positionner à la racine du projet.
- l'environnement virtuel est activé sinon : 
```bash
  source P2_env/bin/activate
```
- install ipykernel qui permet de gérer les environnement virtuel
```bash
  pip install ipykernel
```
- rendre accessible notre environnement virtuel dans jupyter:
```bash
  python -m ipykernel install --user --name=P2_env --display-name "Python (P2_env)"
```
l'environnement est disponible. si il n'apparait pas, actualiser le notebook.

## Telechargement du jeu de données
Si vous ne souhaitez pas modifier le chemin de chargement des données dans le notebook:

- Se positionner à la racine du projet.
- Créer un dossier : "datas"
- Dans ce dossier venir télécharger le jeu de données. Vous le trouverez en suivant ce lien:
https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/AI+Engineer/Project+2+Participez+%C3%A0+un+concours+sur+la+Smart+City/p2-arbres-fr.csv
- Vérifier que le nom du fichier télécharger est le suivant: "p2-arbres-fr.csv"
- Si ce n'est pas le cas, renommer le fichier.
- 
## Authors

- [@yannLecerf](https://github.com/Belin27000)

