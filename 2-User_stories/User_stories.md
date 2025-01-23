# User Stories

## Page de Connexion

### US1.1 : Connexion utilisateur

- **En tant que** utilisateur, **je veux** me connecter à mon compte **afin de** pouvoir accéder à mon tableau de bord personnalisé.
- **Critères d'acceptation :**
  1. Le système doit avoir des champs pour saisir le nom d'utilisateur et le mot de passe.
  2. Les utilisateurs doivent pouvoir cliquer sur un bouton "Connexion" après avoir entré leurs identifiants.
  3. En cas de connexion réussie, l'utilisateur doit être redirigé vers le tableau de bord avec un message de bienvenue.
  4. Si les identifiants sont incorrects, un message d'erreur doit être affiché : "Nom d'utilisateur ou mot de passe invalide. Veuillez réessayer."

### US1.2 : Réinitialisation de mot de passe oublié

- **En tant que** utilisateur, **je veux** réinitialiser mon mot de passe **afin de** pouvoir retrouver l'accès à mon compte si j'oublie mes identifiants.
- **Critères d'acceptation :**
  1. Un lien "Mot de passe oublié ?" doit être visible sur la page de connexion.
  2. En cliquant sur le lien, l'utilisateur doit être redirigé vers un formulaire de réinitialisation de mot de passe.
  3. Le système doit envoyer un lien de réinitialisation de mot de passe à l'adresse email enregistrée après soumission.

### US1.3 : Lien de création de compte

- **En tant que** utilisateur, **je veux** accéder à la page de création de compte **afin de** pouvoir créer un nouveau compte.
- **Critères d'acceptation :**
  1. La page de connexion doit contenir un lien visible intitulé "Créer un compte".
  2. En cliquant sur ce lien, l'utilisateur doit être redirigé vers le formulaire de création d'un nouveau compte.

### US1.4 : Verrouillage de compte après plusieurs tentatives échouées

- **En tant que** utilisateur, **je veux** que mon compte soit temporairement verrouillé après plusieurs tentatives de connexion échouées **afin de** garantir la sécurité de mon compte.
- **Critères d'acceptation :**
  1. Le système doit verrouiller le compte après un nombre défini de tentatives de connexion échouées.
  2. L'utilisateur doit recevoir un message indiquant que le compte est verrouillé et le système doit envoyer un lien de réinitialisation de mot de passe à l'adresse email enregistrée.

## Page de Chat

### US2.1 : Gérer les contacts

- **En tant que** utilisateur, **je veux** gérer ma liste de contacts **afin de** contrôler ma liste de communication.
- **Critères d'acceptation :**
  1. L'utilisateur doit pouvoir ajouter, retirer, ou bloquer des contacts.
  2. l'ajout/le retrait d'un contact doit mettre à jour la liste des contacts en temps réel.
  3. Les contacts bloqués doivent être visuellement distingués ou cachés de la liste.

### US2.2 : Sélectionner un contact et afficher l'historique du chat

- **En tant que** utilisateur, **je veux** sélectionner un contact dans ma liste de contacts **afin de** voir l'historique complet des messages échangés avec ce contact.
- **Critères d'acceptation :**
  1. La liste des contacts doit afficher tous les contacts avec des photos de profil.
  2. La sélection d'un contact doit charger l'ensemble de l'historique des discussions avec celui-ci.

### US2.3 : Envoyer des messages

- **En tant que** utilisateur, **je veux** envoyer des messages à un contact **afin de** communiquer efficacement.
- **Critères d'acceptation :**
  1. Un champ de saisie de texte et un bouton d'envoi doivent être présents dans la fenêtre de chat.
  2. Les messages doivent apparaître dans l'historique des messages une fois envoyés.
  3. Les messages envoyés doivent afficher un horodatage et une confirmation de lecture.
  4. Si un utilisateur tente d'envoyer un message sans texte, le bouton d'envoi doit être désactivé.

### US2.4 : Signaler des messages

- **En tant que** utilisateur, **je veux** signaler un chat **afin de** notifier la plateforme d’un contenu inapproprié.
- **Critères d'acceptation :**
  1. Chaque chat doit avoir une option de signalement.
  2. Le signalement d'un chat doit notifier les modérateurs de la plateforme.

### US2.5 : Exporter l’historique des chats

- **En tant que** utilisateur, **je veux** exporter mon historique des chats **afin de** conserver une trace de mes conversations.
- **Critères d'acceptation :**
  1. Un bouton d'exportation doit être disponible dans l'interface de chat.
  2. Cliquer sur le bouton doit télécharger toute la conversation dans un format lisible.
  3. Le fichier exporté doit inclure des horodatages et des informations sur l'expéditeur.

## Page du Calendrier

### US3.1 : Afficher le calendrier mensuel

- **En tant que** utilisateur, **je veux** voir mon calendrier mensuel avec tous les événements et rendez-vous prévus pour le mois **afin de** suivre les dates importantes.
- **Critères d'acceptation :**
  1. Le calendrier dans le panneau "Mon Calendrier" doit s'afficher sous forme de grille mensuelle.
  2. Des indicateurs doivent être présents pour les jours contenant des événements et/ou des rendez-vous.
  3. Cliquer sur les boutons flèches doit changer le mois présenté en conséquence.
  4. Cliquer sur le bouton Aujourd'hui doit ramener le calendrier à son affichage par défaut du mois en cours.

### US3.2 : Afficher les événements et les rendez-vous mensuels

- **En tant que** utilisateur, **je veux** voir tous mes événements et rendez-vous prévus pour le mois sélectionné **afin de** suivre les dates importantes.
- **Critères d'acceptation :**
  1. Le panneau "Mes Événements et Rendez-vous" sur la page doit afficher tous les événements et rendez-vous pour le mois sélectionné par défaut.
  2. Cliquer sur un jour dans le calendrier doit surligner le jour et filtrer la liste des événements et rendez-vous pour ce jour.
  3. Cliquer à nouveau sur un jour dans le calendrier doit rétablir la liste des événements et rendez-vous par défaut (tous les événements et rendez-vous du mois).
  4. Le calendrier doit clairement distinguer entre les événements et les rendez-vous.

### US3.3 : Créer un nouvel événement

- **En tant que** utilisateur, **je veux** créer un nouvel événement **afin de** planifier des activités importantes.
- **Critères d'acceptation :**
  1. Un bouton "Créer un Nouvel Événement" doit être disponible sur la page du calendrier.
  2. Cliquer sur le bouton doit ouvrir un formulaire pour entrer les détails de l'événement (nom, date, heure).
  3. Enregistrer l'événement doit l'ajouter à la date sélectionnée dans le calendrier.
  4. Si un utilisateur tente de créer un événement dans le passé, un avertissement doit s'afficher.
  5. Le système doit rejeter les formulaires d'événements incomplets avec un message d'avertissement.

### US3.4 : Modifier et supprimer des événements

- **En tant que** utilisateur, **je veux** modifier ou supprimer un événement **afin de** garder mon calendrier à jour.
- **Critères d'acceptation :**
  1. Les utilisateurs doivent avoir la possibilité de modifier les détails d'un événement.
  2. Les utilisateurs doivent avoir l'option de supprimer un événement, ce qui le retirera du calendrier.
  3. Les modifications et suppressions doivent mettre à jour immédiatement l'affichage du calendrier.

### US3.5 : Les bénévoles sont les seuls à pouvoir gérer les rendez-vous avec leurs élèves

- **En tant que** bénévole, **je veux** créer et gérer des rendez-vous avec mes étudiants **afin de** rester organisé tout tout en les accompagnant dans leur apprentissage.
- **Critères d'acceptation :**
  1. Un bénévole doit avoir la possibilité de filtrer les rendez-vous par étudiant.
  2. Les bénévoles doivent pouvoir planifier des rendez-vous avec ses étudiants.
  3. Les bénévoles peuvent modifier et supprimer les rendez-vous avec les étudiants. Les étudiants peuvent consulter leurs rendez-vous mais ne peuvent pas les modifier.

## Page de Gestion des Tâches

### US4.1 : Afficher la liste des tâches

- **En tant que** utilisateur, **je veux** voir la liste de mes tâches et devoirs **afin de** suivre ma charge de travail.
- **Critères d'acceptation :**
  1. Les listes de tâches et de devoirs devraient clairement indiquer la priorité et la date limite de chaque élément.
  2. Les tâches et devoirs terminées doivent être visuellement distinctes.
  3. La liste des tâches doit être triable par priorité ou par date limite. Les bénévoles doivent pouvoir filtrer la liste des devoirs par étudiant.

### US4.2 : Créer une nouvelle tâche

- **En tant que** utilisateur, **je veux** créer une nouvelle tâche **afin de** planifier mes activités.
- **Critères d'acceptation :**
  1. Un bouton "Créer une Nouvelle Tâche" doit être disponible.
  2. Cliquer sur le bouton doit ouvrir un formulaire avec des champs pour le nom de la tâche, la date limite, la priorité et les détails.
  3. Les tâches avec des informations manquantes doivent générer un message d'erreur empêchant la création de la tâche.

### US4.3 : Terminer une tâche

- **En tant que** utilisateur, **je veux** marquer mes tâches terminées comme telles **afin de** mon progrès et ma charge de travail.
- **Critères d'acceptation :**
  1. Les utilisateurs doivent avoir une case à cocher pour marquer les tâches comme terminées.
  2. Les tâches terminées doivent être visuellement distinctes et triées séparément des tâches en attente.

### US4.4 : Modifier et supprimer des tâches

- **En tant que** utilisateur, **je veux** modifier ou supprimer des tâches **afin de** garder ma liste de tâches à jour.
- **Critères d'acceptation :**
  1. Les utilisateurs doivent pouvoir modifier tous les aspects de leurs tâches, y compris le nom, la priorité et la date limite.
  2. Les utilisateurs doivent avoir une option pour supprimer définitivement des tâches.
  3. La modification ou la suppression d'une tâche doit mettre à jour immédiatement la liste des tâches.

### US4.5 : Gestion des devoirs spécifiques aux bénévoles

- **En tant que** bénévole, **je veux** gérer les devoirs pour mes étudiants **afin de** organiser efficacement leurs activités d'apprentissage.
- **Critères d'acceptation :**
  1. Un bénévole doit avoir la possibilité de filtrer les devoirs par étudiant.
  2. Les bénévoles doivent pouvoir attribuer des devoirs à des étudiants spécifiques.
  3. Les bénévoles peuvent créer, marquer comme terminé, modifier et supprimer des devoirs pour les étudiants. Les étudiants peuvent voir leurs devoirs mais ne peuvent pas les modifier.

## Page du Tableau de Bord

### US5.1 : Accéder à un tableau de bord personnalisé

- **En tant que** utilisateur, **je veux** accéder à un tableau de bord personnalisé **afin de** voir en un coup d'œil mes tâches à venir, le nombre de mes messages non lus et mes événements à venir en un seul endroit.
- **Critères d'acceptation :**
  1. Le tableau de bord doit afficher mes tâches à venir, mes événements à venir et le nombre de mes messages non lus.
  2. Chaque section doit comporter un lien vers sa page correspondante (Gestion des Tâches, Calendrier, Chat).

### US5.2 : Compteur de messages non lus

- **En tant que** utilisateur, **je veux** voir le nombre de messages non lus **afin de** rester informé de mes conversations.
- **Critères d'acceptation :**
  1. Un compteur de messages non lus doit être affiché sur le tableau de bord.
  2. Le compteur doit se mettre à jour en temps réel lors de l'arrivée de nouveaux messages.
  3. Cliquer sur le bouton "Accéder aux messages" doit rediriger l'utilisateur vers la page de chat.

### US5.3 : Voir les événements et rendez-vous à venir

- **En tant que** utilisateur, **je veux** voir mes événements et rendez-vous à venir sur mon tableau de bord **afin de** rester organisé.
- **Critères d'acceptation :**
  1. Le tableau de bord doit afficher une liste des prochains événements et rendez-vous.
  2. Chaque événement ou rendez-vous doit afficher le titre, la date et l'heure.
  3. Cliquer sur le bouton "Accéder au calendrier" doit rediriger l'utilisateur vers la page de calendrier.

### US5.4 : Voir les tâches et devoirs à venir

- **En tant que** utilisateur, **je veux** voir un résumé de mes tâches et devoirs **afin de** organiser ma charge de travail.
- **Critères d'acceptation :**
  1. Le tableau de bord doit afficher une liste de mes tâches et devoirs.
  2. Chaque tâche ou devoir doit afficher le titre, la date limite et la priorité.
  3. Cliquer sur le bouton "Accéder au tâches" doit rediriger l'utilisateur vers la page de gestion des tâches.
