==============================================
Informations générales sur le projet howTo_doc
==============================================

:Auteur:            `Poltergeist42 <https://github.com/poltergeist42>`_
:Projet:             howTo_doc
:Version:            20180919-dev
:dépôt GitHub:       https://github.com/poltergeist42/howto_doc
:doc GitHub:         https://poltergeist42.github.io/howto_doc/
:doc ReadTheDocs:    https://howto-doc.readthedocs.io
:Licence:            CC BY-NC-SA 4.0
:Liens:              https://creativecommons.org/licenses/by-nc-sa/4.0/

####

Description
===========

Ce projet a pour objectif de fournir quelques clefs et idées pour aider à la documentation
d'un projet.

Il ne s'agit pas d'une doctrine qu'il faut respecter absolument, mais simplement de la façon dont
j'envisage la documentation. Tout au long de ce projet, je vais essayer de vous décrire mes petits
trucs ainsi que quelques outils vous permettant de réaliser la documentation.

Ma philosophie étant que : projet et documentation sont indissociables l'un de l'autre, ce document
vous présentera également différents éléments pour la gestion de l'organisation des projets.

####

Comment utiliser ce document
============================

Ce document est construit sous la forme d'un site web. La navigation se fait par le menu sur la
gauche de la fenêtre ou en cliquant sur la rubrique désirée sur la partie centrale de la fenêtre.

Pour revenir sur la page d'accueil, il faut cliquez sur : "Documentation howTo_doc" sur la gauche 
de la fenêtre (en haut et en bas).

Ce document est constitué de quatre éléments :

    * `README <https://poltergeist42.github.io/howto_doc/includeMe.html>`_ : Donne une brève 
      description du projet et donne quelques informations supplémentaires (Auteur, Licence, Version,
      etc. ).

    * `Comment documenter un projet <https://poltergeist42.github.io/howto_doc/howTo_Doc.html>`_ :
      C'est l'élément principale traitant du sujet qui nous intéresse.

    * `Bug et ToDo-list <https://poltergeist42.github.io/howto_doc/Bug_ToDoLst.html>`_ : Cet 
      élément sert à l'élaboration du projet (et à sa correction).

    * `VoLAB <https://poltergeist42.github.io/howto_doc/VoLAB.html>`_ : Cet élément présente le 
      VoLAB, un super FabLab situé à Vauréal dans le Val d'Oise.

####

Arborescence du projet
======================

Pour aider à la compréhension de mon organisation, voici un bref descriptif de l'arborescence de se 
projet. Cette arborescence est à reproduire si vous récupérez ce dépôt depuis GitHub. ::

    ProjectDir_Name        # Dossier racine du projet (non versionner)
    |
    +--project             # (Branch master) contient l'ensemble du projet en lui même
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
    |                      # Implantation, typon, fichier de perçage, etc.
    |
    \--webDoc              # Dossier racine de la documentation qui doit être publiée
       |
       \--html             # (Branch gh-pages) C'est dans ce dossier que Sphinx va
                           # générer la documentation a publié sur internet




