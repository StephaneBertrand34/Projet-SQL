# Créez et utilisez une base de données immobilière avec SQL
---

## Compétences acquises à l'issue du projet
* Créer le schéma d'une base de données
* Créer des tables dans une base de données
* Charger des données dans une base de données
* Effectuer des requêtes SQL pour répondre à une problématique métier
* Mettre à jour un catalogue de données

<br>

## Cadre de la mission
Dans ce projet, il était demandé d'utiliser les données brutes des "Demandes de Valeurs Foncières" obtenues sur le <a href="https://www.data.gouv.fr">site de données gouvernemental</a>  

<br>

## Etapes du projet

### Nettoyage et traitement des données brutes
Le fichier initial a été transformé avec Power Query afin d'obtenir 3 tables au format csv.
<br>

### Modèle Conceptuel de Données (MCD)
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/P3_BERTRAND_2.%20MCD.jpg?raw=true)
<br>

### Modèle Physique de Données (MPD)
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/P3_BERTRAND_3.%20MPD.jpg?raw=true)
<br>

### Création de la base de données dans PostgreSQL:
 
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Cr%C3%A9ation%20de%20la%20base%20SQL.jpg)

<br>

### Requêtes

#### 1 . Nombre total d ’appartements vendus au 1er semestre 2020:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%201.jpg)

#### 2. Proportion des ventes d’appartements par nombre de pièces:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%202.jpg)

#### 3. Liste des 10 départements où le prix du mètre carré est le plus élevé:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%203.jpg)

#### 4. Prix moyen du mètre carré d’une maison en Île-de-France:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%204.jpg)

#### 5. Liste des 10 appartements les plus chers avec le département et le nombre de mètres carrés:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%205.jpg)

#### 6. Taux d’évolution du nombre de ventes entre le premier et le second trimestre de 2020:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%206.jpg)

#### 7. Communes où le nombre de ventes a augmenté d'au moins 20% entre le premier et le second trimestre de 2020:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%207.jpg)

#### 8. Différence en pourcentage du prix au mètre carré entre un appartement de 2 pièces et un appartement de 3 pièces:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%208.jpg)

#### 9. Les moyennes de valeurs foncières pour le top 3 des communes des départements 6, 13, 33, 59 et 69:
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAte%209.jpg)
