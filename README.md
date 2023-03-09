<p align="center">
   <img src="https://github.com/Cheezy28/wealthbank/blob/images/wealthbank_logo.png"/>
</p>

# Cahier des charges - Projet WealthBank

Cahier de charges - Projet d'ajout de nouvelles fonctionnalités de l'application bancaire WealthBank.

## 1. Contexte

<p align="center">
   <img src="https://github.com/Cheezy28/wealthbank/blob/images/contexte.png" width = 200 height = 200/>
</p>

Ce projet mené par l'entreprise spécialisée dans la finance WealthBank a pour but de développer de nouvelles fonctionnalités pour leur application bancaire actuellement en production.  
Les utilisateurs de l'application disposent pour le moment d'un espace en ligne et effectuer des actions basiques (modifications de leurs informations personnelles).

La société souhaite développer de nouvelles fonctionnalités à savoir le dépôts d'argent, le retrait d'argent ainsi que la consultation de l'historique des transactions effectuées par le client. 

### 1.1 Objectifs 

La but principal de ce projet est d'apporter des évolutions de l'applications bancaire permettant aux utilisateurs d'effectuer davantages d'actions sur leur espace en ligne. 
Les principales évolutions souhaitées sont le dépôt d'argent, le retrait d'argent et la consultation de l'historique des opérations bancaires. 

Par ailleurs, d'autres fonctionnalités envisagées pourront être rajoutées au projet. 

### 1.2. Fonctions générales 

Pour le moment, l'application de la société permet aux utilisateurs d'accéder à leur espace en ligne via leurs identifiants, de créer des comptes bancaires ou d'effectuer des virements bancaires simples (entre proches). 

### 1.3. Règles de gestion générale de l'application 

Plusieurs règles de gestion ont été mises en place pour un accès à l'application. 

Pour l'application : 
- Etre connecté 
- Connaître ses identifiants personnes pour se connecter 
- Avoir un appareil avec une connexion internet tel qu'un smartphone, une tablette ou un ordinateur

Pour les comptes bancaires : 
- Paramétrer les comptes bancaires 
- Visualiser les informations bancaires 
- Afficher l'historique des opérations bancaires effectuées

Pour les virement bancaires : 
- Disposer du RIB du destinataire 
- Disposer des informations personnelles du destinataire (nom, prénom, adresse postale)
- Insérer un motif du virement bancaire 

Pour les utilisateurs : 
- Créer un compte bancaire chez WealthBank 
- Renseigner ses informations personnelles présentes sur sa carte d'identité (CIN)
- Fournir son statut familial et professionnel 

### 1.4. Profils des utilisateurs 

La société dispose de plusieurs profils d'utilisateurs : 
- Particuliers
- Professionnels
- Associations 

## 2. Spécificités techniques 

<p align="center">
   <img src="https://github.com/Cheezy28/wealthbank/blob/images/spec_technique.png" width = 200 height = 200/>
</p>

### 2.1. Fonctionnalité n°1 - Dépôt d'argent 

La première fonctionnalité doit permettre au client d'effectuer des dépôts d'argent via un guichet automatique (ou avec un agent) afin de créditer son compte bancaire. 

Le client devra avoir une carte bancaire et connaître son code secret à 4 chiffres. 

### 2.2. Fonctionnalité n°2 - Retrait d'argent 

La deuxième fonctionnalité doit permettre au client d'effectuer des retraits d'argent via un guichet automatique (ou avec un agent) afin de disposer d'argent liquide. 

Le client devra avoir une carte bancaire et connaître son code secret à 4 chiffres. 

### Fonctionnalité n°3 - Consultation de l'historique des opérations bancaires 

La troisième fonctionnalité doit permettre au client de visualiser (sur son espace en ligne) l'intégralité de l'historique des opérations bancaires effectuées. 

Le client devra connaître ses identifiants de connexion, d'avoir une connexion internet, de disposer d'un appareil connecté à internet. 

### Fonctionnalité n°4 (optionnelle) - Virement bancaires 

La quatrième fonctionnalité doit permettre au client d'effectuer des virements bancaires vers d'autres structures dans le cadre d'achats de produits ou services en ligne. 

Le client devra connaître ses identifiants de connexion, d'avoir une connexion internet, de disposer d'un appareil connecté à internet. 

Cette fonctionnalité optionnelle validée sera à mettre en place en fonction de l'avancement du projet. 

## 3. Exigences techniques 

<p align="center">
   <img src="https://github.com/Cheezy28/wealthbank/blob/images/exigences.png" width = 200 height = 200/>
</p>

### 3.1. Sécurité 

L'application doit être hébergée chez AWS pour une meilleure sécurité.

### 3.2. Performance 

L'application doit être disponible 7j7 et 24h24 et doit être autoscalable afin d'anticiper les potentiels pics d'activité. 

### Technologies à utiliser 

Plusieurs technologies seront à utiliser pour ce projet : 

- pHp
- Docker 
- AWS
- GitLab & HitHub
- Kubernetes 
- phpMySQL
- HTML & CSS

## 4. Planning 

<p align="center">
   <img src="https://github.com/Cheezy28/wealthbank/blob/images/planning.png" width = 200 height = 200/>
</p>

Le projet aura une durée de 1 an et 5 mois. Il se composera de 5 phases d'avancement. 

![Planning Gantt](https://github.com/Cheezy28/wealthbank/blob/images/Wealth%20Bank_Gantt.png) 

## 5. Matrice RACI de l'équipement de développement 

Voici une description détaillée (matrice RACI) de l'équipe projet.

![Mactrice RACI équipe projet](https://github.com/Cheezy28/wealthbank/blob/images/raci.png)

## 6. Description détaillée de formations & support technique 

Lors de la livraison de chaque fonctionnalité (independante des autres), des plans de formation seront envoyées à l'ensemble des utilisateurs leur permettant de se familiariser avec la nouvelle fonctionnalité. 

#### Fonctionnalité n°1 - Dépôt d'argent 

--> Envoi par mail d'une vidéo explicative de la nouvelle fonctionnalité de dépôt d'argent livrée sur l'application après une mise à jour faite du côté de l'utilisateur. 
Durée de la communication : 1 semaine. 

#### Fonctionnalité n°2 - Retrait d'argent 

--> Envoi par mail d'un tuto écrit (avec des schémas) détaillé de la nouvelle fonctionnalité de retrait d'argent après une mise à jour faite du côté de l'utilisateur. 
Durée de la communication : 1 semaine. 

#### Fonctionnalité n°3 - Consultation de l'historique des opérations 

--> Envoi par mail d'une vidéo tuto détaillée de la nouvelle fonctionnalité de consultation de l'historique des opérations bancaires. 
Durée de la communication : 1 semaine. 

#### Fonctionnalité n°4 (optionnelle) - Virements bancaires 

--> Envoi par mail d'une proposition de formation en ligne de la nouvelle fonctionnalité de virements bancaires.
Durée de la communication : 1 semaine. 

## Rédacteurs

Laurent SALESPARA - MSI 5-23 PO

