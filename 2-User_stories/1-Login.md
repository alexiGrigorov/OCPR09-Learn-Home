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
