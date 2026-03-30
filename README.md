# Projet-Wakdo-Mohamed-BELMEHDIWakdo – Borne de commande & Back-office
Présentation du projet
Le projet a été élaboré dans le cadre de fin de formation pour une certification RNCP 37805 – Développeur Web.
Il consistera à la conception d'une solution de digitalisation complète d'un restaurant fast-food (Wakdo), vu du fonctionnement des bornes de commande modernes.
Cette application permetra au client de passer commande sans intervention de l'Homme à l'aide d'une borne tactile électronique et récupérer la commande par la suite au comptoir grâce à un numéro unique.
Le projet comprend également un back-office permettant aux équipes internes de gérer les produits, les menus et les commandes.
Architecture du projet
Le projet est structuré en 3 blocs principales et distinct:
Bloc 1 : Front borne  : interface client (HTML, CSS, JavaScript)
Bloc 2 : Back-office & API (Bloc 2) : gestion des données (Node.js, Express, MySQL)
Bloc 3 : Application React (Bloc 3) : recherche de restaurants sur carte (React + Vite)
Fonctionnalités principales :
Borne de commande
Parcours utilisateur simple et intuitif
Navigation par catégories (menus, burgers, boissons, desserts…)
Composition de menus (burger + accompagnement + boisson + sauce)
Personnalisation des produits
Gestion du panier en temps réel
Validation de la commande avec un numéro
Back-office :
Authentification des utilisateurs
Gestion des rôles (administration, préparation, accueil)
Gestion des produits et menus
Suivi des commandes
Mise à jour des statuts (en préparation, prêt, livré)
 API :
Récupération des produits et menus
Envoi des commandes (POST /api/orders)
Communication entre le front et le back
Application React :
Recherche de ville
Affichage sur carte (react-leaflet)
Sélection d’un restaurant
Interaction utilisateur dynamique
Base de données :
Une base de données MySQL a été mise en place pour gérer :
les utilisateurs
les produits
les menus
les commandes
Initialisation via :
schema.sql
seed.sql
Sécurité
Le projet inclut :
authentification des utilisateurs
gestion des rôles et permissions
validation des données côté serveur
protection des routes API
