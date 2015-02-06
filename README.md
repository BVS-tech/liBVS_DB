# liBVS_DB

**Tout en anglais**

## General
### Lib Base de Données
* constructeur : connection à la base de données
    * args : nom, mot de passe, adresse ip, user, nom de la base
    * connecte MySQL
    * connecte à la base
* requette
    * args : texte 
    * retour selection/erreur
* destructeur : fermeture de la base

## Test Lampes
### programme de test (main)
### Lampe
Classe avec
* id
* state
* pair
* power
* xmin
* xmax
* ymin
* ymax

### Lib Base de donnée application test
* constructeur : ouverture de la base de test

### Lib Base de donnée application test lampe
* ajouter lampe (appairée)
    * args : Lampe
* *supprimer lampe* NE PAS FAIRE
    * args : id
* modifier lampe puissance
    * args : id, puissance
* modifier lampe etat
    * args : id, etat
* modifier lampe (proprement)
    * args : Lampe

### Lib Base de donnée application test consomation
