# Créez et utilisez une base de données immobilière avec SQL
---
<br>

## Compétences acquises à l'issue du projet
* Mettre à jour un catalogue de données
* Créer des tables dans une base de données
* Effectuer des requêtes SQL pour répondre à une problématique métier
* Créer le schéma d'une base de données
* Charger des données dans une base de données

<br>

## Cadre de la mission
Dans ce projet, il était demandé d'utiliser les données brutes des "Demandes de Valeurs Foncières" obtenues sur le <a href="https://www.data.gouv.fr">site de données gouvernemental</a>  

<br>

## Etapes du projet

### Modèle Conceptuel de Données (MCD)
![alt text](https://github.com/StephaneBertrand34/Projet-SQL/blob/main/P3_BERTRAND_2.%20MCD.jpg?raw=true)
<br>

### Modèle Physique de Données (MPD)
![P3_BERTRAND_3. MPD.jpg](attachment:2a58c411-a0de-4f2f-94e9-c2b987c6a232.jpg)
<br>

### Création de la base de données avec PostgreSQL:

Le fichier initial a été transformé avec Power Query afin d'obtenir 3 tables au format csv :

* bien.csv est un fichier de 34161 lignes et 8 colonnes 
    
* commune.csv est un fichier de 3125 lignes et 3 colonnes
  
* vente.csv est un fichier de 34169 lignes et 5 colonnes
 
![Création de la base SQL.jpg](attachment:1212e0d4-c063-4cf8-a9ee-54f46c4a37d7.jpg)

<br>

### Requêtes

#### 1 . Nombre total d ’appartements vendus au 1er semestre 2020:
![Requête 1.jpg](attachment:46a0bced-23ef-403c-8a3b-883f174dcff3.jpg)

#### 2. Proportion des ventes d’appartements par nombre de pièces:
![Requête 2.jpg](attachment:5614bfeb-4aa9-44a8-8afc-4ad5fff43c8c.jpg)

#### 3. Liste des 10 départements où le prix du mètre carré est le plus élevé:
![Requête 3.jpg](attachment:7e08f723-56c1-4edb-b6e6-5492bf20775b.jpg)

#### 4. Prix moyen du mètre carré d’une maison en Île-de-France:
![Requête 4.jpg](attachment:d34f38a0-684a-467c-9c2e-ddabacf574d9.jpg)

#### 5. Liste des 10 appartements les plus chers avec le département et le nombre de mètres carrés:
![Requête 5.jpg](attachment:8ededa63-b9dc-4de1-b54e-b64dff8c4ac2.jpg)

#### 6. Taux d’évolution du nombre de ventes entre le premier et le second trimestre de 2020:
![Requête 6.jpg](attachment:8117d5f8-0dc8-4613-965b-fd3419e33450.jpg)

#### 7. Communes où le nombre de ventes a augmenté d'au moins 20% entre le premier et le second trimestre de 2020:
![Requête 7.jpg](attachment:7b0a4e9e-f02b-490f-9225-af88f1f2f3ed.jpg)

#### 8. Différence en pourcentage du prix au mètre carré entre un appartement de 2 pièces et un appartement de 3 pièces:
![Requête 8.jpg](attachment:7dfd8c71-0395-4d1a-954b-58e6b534405c.jpg)

#### 9. Les moyennes de valeurs foncières pour le top 3 des communes des départements 6, 13, 33, 59 et 69:
![Requête 9.jpg](attachment:10cb0426-aea0-45c8-a905-5cdb00cfdc27.jpg)
