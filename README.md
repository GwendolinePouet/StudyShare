# StudyShare
Projet Symfony2 IESA Multimédia

Symfony Standard Edition
========================

Welcome to the Symfony Standard Edition - a fully-functional Symfony
application that you can use as the skeleton for your new applications.

For details on how to download and get started with Symfony, see the
[Installation][1] chapter of the Symfony Documentation.

What's inside?
--------------
Installation
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






The Symfony Standard Edition is configured with the following defaults:

  * An AppBundle you can use to start coding;

  * Twig as the only configured template engine;

  * Doctrine ORM/DBAL;

  * Swiftmailer;

  * Annotations enabled for everything.

It comes pre-configured with the following bundles:

  * **FrameworkBundle** - The core Symfony framework bundle

  * [**SensioFrameworkExtraBundle**][6] - Adds several enhancements, including
    template and routing annotation capability

  * [**DoctrineBundle**][7] - Adds support for the Doctrine ORM

  * [**TwigBundle**][8] - Adds support for the Twig templating engine

  * [**SecurityBundle**][9] - Adds security by integrating Symfony's security
    component

  * [**SwiftmailerBundle**][10] - Adds support for Swiftmailer, a library for
    sending emails

  * [**MonologBundle**][11] - Adds support for Monolog, a logging library

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

  * [**SensioGeneratorBundle**][13] (in dev/test env) - Adds code generation
    capabilities

  * **DebugBundle** (in dev/test env) - Adds Debug and VarDumper component
    integration

All libraries and bundles included in the Symfony Standard Edition are
released under the MIT or BSD license.

Enjoy!

[1]:  https://symfony.com/doc/2.8/book/installation.html
[6]:  https://symfony.com/doc/current/bundles/SensioFrameworkExtraBundle/index.html
[7]:  https://symfony.com/doc/2.8/book/doctrine.html
[8]:  https://symfony.com/doc/2.8/book/templating.html
[9]:  https://symfony.com/doc/2.8/book/security.html
[10]: https://symfony.com/doc/2.8/cookbook/email.html
[11]: https://symfony.com/doc/2.8/cookbook/logging/monolog.html
[13]: https://symfony.com/doc/2.8/bundles/SensioGeneratorBundle/index.html
