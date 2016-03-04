# StudyShare
Projet Symfony2 IESA Multimédia



Installation
--------------

- uploader tout le fichier du dossier sur le serveur de votre choix
- verifier que dans le dossier il y a bien un composer.phar
- une fois le site uploadé, rendez-vous sur le fichier parameters.yml est modifié le avec vous parametre server
        database_host: Votre url
        database_port: Votre port
        database_name: studysharedb
        database_user: Votre nom utilisateur de base de donné
        database_password: Votre mot de passe de base de donné
        mailer_transport: Votre mail server (smtp)
        mailer_host: Votre mail url
        mailer_user: Votre mail utilisateur
        mailer_password: Votre mail mot de passe
        secret: ThisTokenIsNotSoSecretChangeIt
- Créez votre base de données en entrant dans votre terminal la ligne de code suivante
  $ php app/console doctrine:database:create
- Generez toute les table en entrant dans votre terminal
  $ php app/console doctrine:schema:entities
- Metez a jour votre votre base de données
  $ php app/console doctrine:schema:update --force
vous pouvez dsormais cree un compte grace a l'url www.monsite.com/register et utiliser toute les fonctionalité du site



