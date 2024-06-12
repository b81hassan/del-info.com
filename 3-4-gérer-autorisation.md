# Le syndicat gère les autorisations d'accés des utilisateurs. #

 En tant que gestionnaire de l'application, je veux pouvoir gérer les autorisations d'accès des utilisateurs et leur attribuer des rôles appropriés (travailleur, représentant syndical, administrateur, etc.) #

**Scénario :**

**Préconditions**

- Le gestionnaire de l'application se connecte à l'interface d'administration de l'application.

**Scénario**

- Sur son tableau de bord d'administration, il accède à la section de gestion des utilisateurs et des rôles.
- Il peut voir la liste de tous les utilisateurs enregistrés dans le système, y compris leur nom, leur adresse e-mail et leur rôle actuel.
- Le gestionnaire peut rechercher un utilisateur spécifique en utilisant des filtres tels que le numéro d'affiliation ,le numéro de registre national ou le nom.
- Pour chaque utilisateur, le gestionnaire peut modifier les informations de base telles que le statut et l'adresse e-mail, si nécessaire.
- Le gestionnaire peut également attribuer ou modifier le rôle de l'utilisateur en choisissant parmi une liste de rôles prédéfinis, tels que travailleur, représentant syndical, administrateur, etc.
- Lorsqu'un nouveau rôle est attribué à un utilisateur ou qu'un rôle existant est modifié, le système met à jour automatiquement les autorisations d'accès de l'utilisateur en fonction des privilèges associés à ce rôle.
- Le gestionnaire peut également désactiver ou supprimer un utilisateur du système si nécessaire.

**Règles métier :**

- Seuls les gestionnaires de l'application ont le droit d'accéder à l'interface d'administration et de gérer les utilisateurs et les rôles.
- Chaque utilisateur doit être associé à un rôle spécifique, déterminant les autorisations d'accès et les fonctionnalités disponibles pour cet utilisateur.


- Le système doit garantir que les utilisateurs ont uniquement accès aux fonctionnalités et aux données nécessaires à l'exécution de leurs tâches, en fonction de leur rôle attribué.