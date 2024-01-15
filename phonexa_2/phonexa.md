# README de l'Application de Chat

## Table des matières
- [Introduction](#introduction)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Base de données](#base-de-données)
- [Contributions](#contributions)
- [Licence](#licence)

## Introduction
Bienvenue dans l'Application de Chat ! Cette application vous permet de communiquer avec d'autres utilisateurs en temps réel. Elle est dotée d'authentification utilisateur, d'une liste d'utilisateurs en ligne, et offre une expérience de messagerie instantanée.

## Prérequis
Avant de commencer, assurez-vous de disposer des éléments suivants :
- PHP 7.3 ou version ultérieure
- [Postgres](https://www.pgadmin.org/) - PgAdmin4 
- [Ngrok](https://ngrok.com/) - Serveur de dév

## Installation
1. Clonez le dépôt depuis GitHub :
2. git clone ``git clone https://github.com/djibril1212/phonexa.git``
2. Créez une base de données PgAdmin4 pour l'application.
3. Importez le schéma de la base de données depuis le fichier `database.sql` dans votre base de données PgAdmin4.

## Utilisation
1. Démarrez votre projet utiliser `` php -S localhost:8000 `` .
2. Accédez à l'application via un navigateur web.
3. Inscrivez-vous ou connectez-vous pour accéder à l'application de chat.
4. Sélectionnez un utilisateur en ligne pour démarrer une conversation.
5. Commencez à envoyer et à recevoir des messages en temps réel.

## Base de données
L'application utilise PgAdmin4 pour la gestion de la base de données, avec deux tables principales :
- `users` : Cette table stocke les informations des utilisateurs, telles que leur nom, adresse e-mail et image de profil.
- `messages` : Cette table conserve les messages du chat, avec des détails sur les expéditeurs et les destinataires.

## Contributions
Les contributions à ce projet sont les bienvenues ! Si vous avez des idées d'amélioration ou si vous avez trouvé des bogues, veuillez ouvrir des problèmes (issues) ou envoyer des demandes de fusion (pull requests).

## Licence
Ce projet est sous licence [MIT](LICENCE), ce qui signifie que vous pouvez l'utiliser, le modifier et le distribuer librement sous réserve du respect de la licence.
