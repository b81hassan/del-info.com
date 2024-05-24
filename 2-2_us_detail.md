 # User story 1 : En tant que travailleur, je veux pouvoir soumettre une demande d'information à mon représentant syndical sur un sujet spécifique lié à mes conditions de travail. #

## Scénario : ##

- Le travailleur se connecte à l'application de gestion des demandes d'informations.
- Sur son tableau de bord, il sélectionne l'option pour soumettre une nouvelle demande d'information.
- il doit séléctionner une option qui correspond à sa demande.
- Il remplit un formulaire où il spécifie :
   - Le sujet de la demande.
   - Une description détaillée du problème ou de la question.
   
- Après avoir rempli le formulaire, il soumet la demande.
- Le système enregistre la demande et lui attribue un numéro de suivi unique.
- Le représentant syndical reçoit une notification indiquant qu'une nouvelle demande d'information a été soumise par un travailleur.
- Le représentant syndical examine la demande et prend en charge son traitement.

## Règles métier : ##



- Chaque demande d'information doit contenir au minimum un sujet et une description.
- Les demandes d'information doivent être liées aux conditions de travail ou aux questions syndicales.
- Le système doit garantir la confidentialité des informations.
- Chaque demande d'information doit être attribuée à un représentant syndical pour traitement dans les plus brefs délais.
- Les travailleurs ont le droit de suivre l'état de leur demande d'information et de recevoir des mises à jour sur l'état de son avancement.

# User story 2 :  En tant que représentant syndical, je veux pouvoir consulter toutes les demandes d'information soumises par les travailleurs de mon entreprise. #
 
 ## Scénario : ##

- Le représentant syndical se connecte à l'application  des demandes d'informations.
- Sur son tableau de bord, il accède à la section dédiée aux demandes d'information.
- Il consulte la liste des demandes d'information soumises par les travailleurs de son entreprise, triées par ordre chronologique ou par pertinence.
- Pour chaque demande d'information, il peut visualiser les détails tels que :
    - Le sujet de la demande.
    - La description détaillée du problème ou de la question.
    - Le nom du travailleur qui a fait la demande.
    - La date de soumission de la demande.
    - Le statut actuel de la demande (en attente, en cours de traitement, traitée, etc.).

- Il peut également effectuer des actions telles que :
Attribuer la demande à un membre spécifique de l'équipe pour traitement.
- Marquer la demande comme traitée une fois qu'une réponse appropriée a été fournie.
- Envoyer une notification au travailleur concerné pour le tenir informé de l'état de sa demande.

## Règles métier : ##

- Les représentants syndicaux ont un accès libre aux demandes d'information soumises par les travailleurs de leur entreprise.
- Les demandes d'information doivent être affichées de manière sécurisée, en préservant la confidentialité des informations sensibles.
- Les représentants syndicaux peuvent consulter les demandes d'information à tout moment mais ils doivent les traiter avec professionnalisme.

- En cas de besoin de clarification ou de discussion supplémentaire sur une demande d'information, les représentants syndicaux peuvent communiquer avec les travailleurs via les fonctionnalités de messagerie sécurisée de l'application.

# User Story 3 : En tant que gestionnaire de l'application, je veux pouvoir gérer les autorisations d'accès des utilisateurs et leur attribuer des rôles appropriés (travailleur, représentant syndical, administrateur, etc.) #

## Scénario : ##

- Le gestionnaire de l'application se connecte à l'interface d'administration de l'application.
- Sur son tableau de bord d'administration, il accède à la section de gestion des utilisateurs et des rôles.
- Il peut voir la liste de tous les utilisateurs enregistrés dans le système, y compris leur nom, leur adresse e-mail et leur rôle actuel.
- Le gestionnaire peut rechercher un utilisateur spécifique en utilisant des filtres tels que le numéro d'affiliation ,le numéro de registre national ou le nom.
- Pour chaque utilisateur, le gestionnaire peut modifier les informations de base telles que le statut et l'adresse e-mail, si nécessaire.
- Le gestionnaire peut également attribuer ou modifier le rôle de l'utilisateur en choisissant parmi une liste de rôles prédéfinis, tels que travailleur, représentant syndical, administrateur, etc.
- Lorsqu'un nouveau rôle est attribué à un utilisateur ou qu'un rôle existant est modifié, le système met à jour automatiquement les autorisations d'accès de l'utilisateur en fonction des privilèges associés à ce rôle.
- Le gestionnaire peut également désactiver ou supprimer un utilisateur du système si nécessaire.

## Règles métier : ##

- Seuls les gestionnaires de l'application ont le droit d'accéder à l'interface d'administration et de gérer les utilisateurs et les rôles.
- Chaque utilisateur doit être associé à un rôle spécifique, déterminant les autorisations d'accès et les fonctionnalités disponibles pour cet utilisateur.


- Le système doit garantir que les utilisateurs ont uniquement accès aux fonctionnalités et aux données nécessaires à l'exécution de leurs tâches, en fonction de leur rôle attribué.

# User Story4 : En tant que travailleur, je veux pouvoir consulter, suivre, et gérer les demandes d'informations que j'ai soumises afin de rester informé de leur état et d'interagir avec les représentants syndicaux si nécessaire. #

## Scénario : ##


- Le travailleur clique sur la section "Mes demandes d'info" depuis le menu principal.
- L'application affiche une liste de toutes les demandes d'informations soumises par le travailleur, triées par date de soumission.

Utilisation des Filtres :

- Le travailleur peut filtrer les demandes par :
Statut (en attente, en cours de traitement, traitée).
Date de soumission.
Il sélectionne "en attente" pour voir toutes les demandes qui n'ont pas encore été traitées.

 Recherche d'une Demande Spécifique :

- Le travailleur utilise la barre de recherche pour trouver rapidement une demande spécifique en entrant des mots-clés liés au sujet ou à la description de la demande.

Consultation des Détails d'une Demande :

- Le travailleur clique sur une demande pour en voir les détails.
L'application affiche :

Le sujet de la demande.
La description détaillée.
La date de soumission.
Le type de demande.
Le statut actuel (en attente, en cours de traitement, traitée).

- L'historique des actions (journal des mises à jour de statut, réponses des représentants syndicaux, clarifications demandées).

Réception des Mises à Jour et Notifications :

- Le travailleur reçoit des notifications en temps réel lorsqu'il y a des mises à jour sur ses demandes.
- Il voit une notification indiquant qu'une de ses demandes a changé de statut.
- Il clique sur la notification pour voir les détails de la mise à jour.

Échange de Messages :

- Le travailleur peut envoyer des messages sécurisés aux représentants syndicaux pour fournir des clarifications supplémentaires ou poser des questions.

## Règles Métier :

Confidentialité :

- Les informations sur les demandes d'information doivent être affichées de manière sécurisée.
- a confidentialité des informations sensibles doit être préservée à tout moment.
Accès et Consultation :

- Les travailleurs ont un accès libre et sécurisé à leurs propres demandes d'information.
Ils peuvent consulter les demandes d'information à tout moment.

Mises à Jour :

- Les travailleurs doivent recevoir des notifications en temps réel pour toutes les mises à jour concernant leurs demandes.
- Les notifications doivent inclure des informations pertinentes et claires sur les changements de statut ou les réponses fournies.

Interactions :

- Les travailleurs doivent pouvoir interagir avec les représentants syndicaux via des fonctionnalités de messagerie sécurisée.
Toute communication doit être enregistrée et accessible pour consultation future.

Professionnalisme et Respect des Délais :

- Les représentants syndicaux doivent traiter les demandes d'information avec professionnalisme.
Les travailleurs doivent recevoir des réponses dans les délais les plus brefs.















