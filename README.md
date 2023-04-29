# Compétences acquises à l'issue du projet:
* Mettre à jour un catalogue de données
* Créer des tables dans une base de données
* Effectuer des requêtes SQL pour répondre à une problématique métier
* Créer le schéma d'une base de données
* Charger des données dans une base de données

<br>
---
# Description du projet:
Dans ce projet totalement réalisé en SQL, nous avons utilisé les Demandes de Valeurs Foncières obtenues sur le <a href="https://www.data.gouv.fr">site de données gouvernemental</a>.  
Le fichier initial a été transformé avec Power Query pour obtenir 3 tables au format csv :

* bien.csv est un fichier de 34161 lignes et 8 colonnes : 
  * id_bien : l'identifiant du bien (PK),
  * adresse,
  * surf_carrez,
  * nb_lot,
  * type_local,
  * surf_reelle,
  * nb_piece,
  * idcom, l'identifiant de la commune (FK).
  
* commune.csv est un fichier de 3125 lignes et 3 colonnes :
  * id_commune : l'identifiant de la commune (PK),
  * nom,
  * dep.
  
* vente.csv est un fichier de 34169 lignes et 5 colonnes :
  * id_vente : l'identifiant de la transaction (PK),
  * no_dispo,
  * date_mut,
  * val_fonc,
  * idbien (FK).
