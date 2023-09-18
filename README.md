# Projet Spectre 

### But du projet

*Projet Spectre* a pour but de concevoir un programme capable d’identifier le type d’instrument de musique enregistré dans un fichier audio, quelle que soit la note jouée. Il s'appuie sur une base de données constituée d’environ trois mille fichiers audios dont sont extraits les spectres harmoniques.

## Projet 1 : Base de données non-structurées MongoDB

### Objectifs :

- Constituer une base de données de fichiers audio non structurés.

- Effectuer des pré-traitements sur ces données pour extraire les spectres harmoniques.

- Stocker et analyser ces données en utilisant MongoDB.

- Créer une interface utilisateur graphique avec Tkinter pour interagir avec la base de données.

Cette première phase consiste à construire une base de données robuste pour stocker les fichiers audio et les spectres harmoniques extraits. MongoDB est utilisé pour sa flexibilité en matière de données non structurées. L'interface utilisateur permettra aux utilisateurs d'effectuer des recherches et d'explorer la base de données.

## Projet 2 : Analyse en temps réel d’un stream de données et stockage Big Data

### Objectifs :

- Mettre en place une architecture Big Data pour gérer un flux continu de données audio en temps réel.

- Utiliser HBase pour le stockage des données en streaming.

- Implémenter une solution de Data Visualization avec ElasticSearch pour analyser les données en temps réel.

Cette deuxième phase se concentre sur la gestion des données en temps réel en utilisant des technologies Big Data comme HBase pour stocker et gérer le flux continu de données audio. ElasticSearch est utilisé pour la visualisation et l'analyse des données en temps réel, ce qui peut être précieux pour la détection en temps réel des instruments de musique.

## Projet 3 : Prédiction d’instruments de musique avec le Machine Learning

### Objectifs :

- Étendre la base de données en ajoutant plus de données pour améliorer la précision du modèle.

- Concevoir un modèle de Machine Learning capable de prédire le type d'instrument de musique à partir des spectres harmoniques.

- Développer une application Web pour interagir avec le modèle de Machine Learning. 

Dans cette phase finale, vous étendez votre base de données avec plus de données pour améliorer la qualité de votre modèle de Machine Learning. Le modèle est conçu pour prédire le type d'instrument de musique à partir des spectres harmoniques extraits. Une application Web est développée pour permettre aux utilisateurs de télécharger un fichier audio et d'obtenir la prédiction du modèle.

## Conclusion

Ce projet est une combinaison passionnante de traitement de données, de Big Data et de Machine Learning, avec une application finale qui pourrait être utile pour l'identification d'instruments de musique à partir d'enregistrements audio. Bonne chance avec votre projet Spectre !

