================================
Informations générales howTo_doc
================================

:Autheur:            `Poltergeist42 <https://github.com/poltergeist42>`_
:Projet:             howTo_doc
:dépôt GitHub:       https://github.com/poltergeist42/howto_doc
:documentation:      https://poltergeist42.github.io/howto_doc/
:Licence:            CC BY-NC-SA 4.0
:Liens:              https://creativecommons.org/licenses/by-nc-sa/4.0/

Déscription
===========

Ce projet a pour objectif de fournir quelques clefs et idée pour aider à la documentation
d'un projet.

Il ne s'agit pas d'une doctrine qu'il faut respecter absolument, mais simplement de la façon dont
j'envisage la documentation. tout au long de ce projet, je vais essayer de vous décrire mes petits
trucs ainsi que quelques outils vous permettant de réaliser la documentation.

Arborescence du projet
======================

Pour aider à la compréhension de mon organisation, voici un bref descriptif de l'arborescence de se 
projet.Cette arborescence est à reproduire si vous récupérez ce dépôt depuis GitHub. ::

    ProjectDir_Name        # Dossier racine du projet (non versionner)
    |
    +--project             # (branch master) contient l'ensemble du projet en lui même
    |  |
    |  +--_1_userDoc       # Contiens toute la documentation relative au projet
    |  |   |
    |  |   \--source       # Dossier réunissant les sources utilisées par Sphinx
    |  |
    |  +--_2_modelisation  # Contiens tous les plans et toutes les modélisations du projet
    |  |
    |  +--_3_software      # Contiens toute la partie programmation du projet
    |  |
    |  \--_4_PCB           # Contient toutes les parties des circuits imprimés (routage,
    |                      # implantation, typon, fichier de perçage, etc
    |
    \--webDoc              # Dossier racine de la documentation qui doit être publiée
       |
       \--html             # (branch gh-pages) C'est dans se dossier que Sphinx va
                           # générer la documentation à publié sur internet

