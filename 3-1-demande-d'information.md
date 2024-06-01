# Le travailleur soumet une demande d'information : #

En tant que travailleur, je veux pouvoir soumettre une demande d'information à mon représentant syndical sur un sujet spécifique lié à mes conditions de travail.

## Scénario : ##

**Préconditions**

L'employé est authentifié.

(Si l'employé, n'est pas authentifié, il est redirigé vers la page d'authentification).

**Scénario**


- Sur son tableau de bord, il sélectionne l'option pour soumettre une nouvelle demande d'information.
- Il doit séléctionner une option qui correspond à sa demande.
- Il remplit un formulaire où il spécifie :
   - Le type de la demande.
   - Une description détaillée du problème ou de la question.
   
- Après avoir rempli le formulaire, il soumet la demande.
- Le système enregistre la demande et lui attribue un numéro de suivi unique.

**Postconditions**

- Un représentant syndical reçoit une notification indiquant qu'une nouvelle demande d'information a été soumise par un travailleur.
- Le représentant syndical examine la demande et prend en charge son traitement.

**Règles métier :**



- Chaque demande d'information doit contenir au minimum un sujet et une description.
- Les demandes d'information doivent être liées aux conditions de travail ou aux questions syndicales.
- Le système doit garantir la confidentialité des informations.
- Chaque demande d'information doit être attribuée à un représentant syndical pour traitement dans les plus brefs délais.
- Les travailleurs ont le droit de suivre l'état de leur demande d'information et de recevoir des mises à jour sur l'état de son avancement.