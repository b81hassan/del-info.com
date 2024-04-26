# database #

 Le modèle suivant décrit le schéma de la base de données utilisée pour l'application :

![ERD](./images/BD.png)


1- La table **employe** contient la liste des employés.

Le délégué est un employé aussi

2- La table **delegate** contient la liste des délégués ainsi que leurs compétences

La relation entre delegate et type-request :

- Un délégué peut avoir une ou plusieurs compétences.
 
- Un délégué recoit les types de demande selon ses compétences.
- Un délégué peut recevoir plusieurs demandes d'informations.



3- La table **request** contient les demandes d'informations:

La relation request et employe:

- Un employé peut faire plusieurs demandes d'informations.
- Une demande ne concerne qu'un seul employe
  


4-La table **type-request** contient les différents types de demandes d'informations :

1. Salaire et avantages
2. Bien etre et prévention
3. Condition de travail
4. Congés et absences
5. Prime syndicale et cotisations


5-La table **syndicat** contient le nom du sécretaire syndicale en lien direct avec les délégués.

La relation entre syndicat et delegate :

- Chaque délégué a un seul secretaire syndicale
- Le secrétaire est en relation avec tous les délégués

la relation entre syndicat et type-request :

-  Un secretaire peut traiter plusieurs demandes d'informations
-  Un secretaire ne peut recevoir qu'un seul type de demande.

La relation entre syndicat et employe :

- Un employe peut avoir qu'un seul syndicat
- Un syndicat peut avoir plusieurs affiliés (les employes)

