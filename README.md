# NDF APP 

**Gestionnaire de notes de frais.**  
Compte-rendu des réunions avec M.Galli et récapitulatif du travail effectué chaque semaine.  
Pour des informations sur les applications développées. Se référer aux readme dans les sous-dossiers.  

## Membres du groupe
* AGREBI Jihenne
* AHMED Saad El Din
* BEN EL BEY Yessine
* NORTIER Hugo

## Contexte projet et travail attendu
Les gestionnaires de l’université doivent effectuer des notes de frais (NDF) à la main chaque mois à partir des factures de chaque collaborateur.  
L’objectif est de les aider et alléger leur travail en mettant en place un outil de gestion de NDF.  
L’outil possédera un backoffice web utilisé par les gestionnaires (admin) qui leur permettra de gérer les utilisateurs et leurs factures ainsi que générer des NDF. Ces données seront stockées par une BD que l’on accèdera par une API REST.  
On aura aussi une app mobile qui permettra aux collaborateurs (user) de scanner leurs factures.  
Les factures seront ensuite passées à travers un OCR qui sera en charge de retrouver les infos clés telles que : date facture, € HT, € TTC, TVA totale (5.5, 10, 20), catégorie (ex : restauration).  
On pourrait envisager de donner la possibilité aux gestionnaires de modifier les infos retrouvées par l’OCR si celles-ci se révèlent erronées.  
Il faudra enfin prévoir un mode admin pour l’appli mobile qui permet aux gestionnaires de scanner une facture pour n’importe quel collaborateur.  