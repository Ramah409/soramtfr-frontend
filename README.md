Ce dépôt contient la partie frontend du projet Soramfr, une mini-application e-commerce développée avec Angular 17.

Il comprend :
une page d’accueil
un système d’inscription et de connexion
une page produits
un panier
une interface administrateur (gestion des utilisateurs/produits)

L’objectif du projet est de proposer une interface simple, moderne et responsive, qui communique avec une API Spring Boot.

🛠️ Technologies utilisées
Angular 17 (standalone components, Router, Guards) pour protéger les routes
TypeScript
HTML / CSS pour la mise en page et le style
HTTP Interceptor (AuthInterceptor) pour ajouter le token aux requêtes
Services Angular pour appeler l’API
Formulaires (template-driven) pour gérer l’inscription / connexion

API Backend 
Le frontend consomme une API REST développée en Spring Boot (dépôt séparé).
L’URL de l’API sera remplacée en production par l’URL Render.

Déploiement
Le projet sera déployé sur Netlify, qui exécute automatiquement
