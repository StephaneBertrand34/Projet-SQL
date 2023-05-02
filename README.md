# Créez et utilisez une base de données immobilière avec SQL
---

## Compétences acquises à l'issue du projet
* Créer le schéma d'une base de données
* Créer des tables dans une base de données
* Charger des données dans une base de données
* Effectuer des requêtes SQL pour répondre à une problématique métier
* Mettre à jour un catalogue de données

<br>

## Outils utilisés:
<img src="https://github.com/StephaneBertrand34/SQL-Creer_et_utiliser_une_base_de_donnees_immobiliere/blob/main/img/powerQueryLogo_PowerQuery.png" title="Power Query" alt="Power Query" width="100" height="50"/>&nbsp;
<img src="https://github.com/StephaneBertrand34/SQL-Creer_et_utiliser_une_base_de_donnees_immobiliere/blob/main/img/00-postgresql-logo.jpg" title="PostgreSQL" alt="PostgreSQL" width="80" height="50"/>&nbsp;
<img src="https://github.com/StephaneBertrand34/SQL-Creer_et_utiliser_une_base_de_donnees_immobiliere/blob/main/img/looping.jpg" title="Looping" alt="Looping" width="105" height="50"/>&nbsp;
<img src="https://github.com/StephaneBertrand34/SQL-Creer_et_utiliser_une_base_de_donnees_immobiliere/blob/main/img/papyrus_small.png" title="Papyrus" alt="Papyrus" width="88" height="50"/>&nbsp;
<img src="https://github.com/StephaneBertrand34/SQL-Creer_et_utiliser_une_base_de_donnees_immobiliere/blob/main/img/power%20architect.jpg" title="Power Architect" alt="Power Architect" width="67" height="50"/>


<br>

## Mise en situation
Vous êtes Data Analyst chez Laplace Immo, un réseau national d'agences immobilières. Votre mission consiste à créer la base de données permettant de collecter les transactions immobilières et foncières en France. Vous utiliserez ensuite cette base pour analyser le marché et aider les différentes agences à mieux accompagner leurs clients.
Les données brutes utilisées proviennent des "Demandes de Valeurs Foncières" obtenues sur le <a href="https://www.data.gouv.fr">site de données gouvernemental.</a> 

<br>

## Etapes du projet

### Nettoyage et traitement des données brutes
Le fichier initial a été transformé avec Power Query afin d'obtenir 3 tables au format csv.

<br>

### Modèle Conceptuel de Données (MCD)
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/P3_BERTRAND_2.%20MCD.jpg"/>
<br>

### Modèle Physique de Données (MPD)
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/P3_BERTRAND_3.%20MPD.jpg"/>

<br>

### Implémentation de la base de données dans PostgreSQL:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Cr%C3%A9ation%20de%20la%20base%20SQL.jpg"/>

<br>

### Requêtes

#### 1 . Nombre total d ’appartements vendus au 1er semestre 2020:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%201.jpg" width="800"/>

#### 2. Proportion des ventes d’appartements par nombre de pièces:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%202.jpg" width="800"/>

#### 3. Liste des 10 départements où le prix du mètre carré est le plus élevé:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%203.jpg" width="800"/>

#### 4. Prix moyen du mètre carré d’une maison en Île-de-France:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%204.jpg" width="800"/>

#### 5. Liste des 10 appartements les plus chers avec le département et le nombre de mètres carrés:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%205.jpg" width="800"/>

#### 6. Taux d’évolution du nombre de ventes entre le premier et le deuxième trimestre de 2020:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%206.jpg" width="800"/>

#### 7. Communes où le nombre de ventes a augmenté d'au moins 20% entre le premier et le deuxième trimestre de 2020:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%207.jpg" width="1200"/>

#### 8. Différence en pourcentage du prix au mètre carré entre un appartement de 2 pièces et un appartement de 3 pièces:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%208.jpg" width="1000"/>

#### 9. Les moyennes de valeurs foncières pour le top 3 des communes des départements 6, 13, 33, 59 et 69:
<img src="https://github.com/StephaneBertrand34/Projet-SQL/blob/main/Requ%C3%AAtes%20(jpg)/Requ%C3%AAte%209.jpg" width="1000"/>
