# FITAHIANTSOA — Application Marketplace

<p align="center">
  <img width="1536" height="1024" alt="ChatGPT Image 16 sept  2026, 10_10_49" src="https://github.com/user-attachments/assets/df60162b-5a39-495b-aedb-476f9ff2a427" />

</p>

<p align="center">
  <strong>Une plateforme numérique dédiée au matériel agricole, au commerce et aux services à Madagascar.</strong>
</p>

---

## Présentation

FITAHIANTSOA est un prototype d'application de marketplace développé pour une entreprise malgache spécialisée dans la fourniture et la distribution de matériel agricole.

La plateforme a pour objectif de faciliter la mise en relation entre les clients, les fournisseurs, les employés, les partenaires logistiques et l'administration de l'entreprise.

L'activité principale est centrée sur le matériel agricole, avec une architecture permettant d'étendre progressivement la plateforme à plusieurs secteurs : tourisme, artisanat, électronique, mode, véhicules, santé et autres services.

Le projet est actuellement développé sous forme de prototype frontend et est conçu pour évoluer vers une véritable application mobile connectée à une API backend et à une base de données.

---

## Objectifs du projet

Le projet vise à développer une plateforme permettant de :

- présenter les produits et équipements disponibles ;
- faciliter la recherche et l'achat de matériel ;
- permettre aux fournisseurs de proposer leurs produits ;
- centraliser la gestion des commandes ;
- suivre les livraisons ;
- gérer les utilisateurs selon leurs rôles ;
- faciliter la communication entre les différents acteurs ;
- développer progressivement une marketplace multi-secteurs ;
- préparer l'intégration d'un backend et de services externes.

---

## Contexte de l'entreprise

FITAHIANTSOA importe et distribue différents équipements agricoles à Madagascar, notamment :

- motoculteurs diesel Changfa ;
- tracteurs 4 roues Hong Yuan ;
- motopompes diesel NS-150 ;
- décortiqueuses de riz ;
- moteurs diesel ;
- pièces détachées ;
- kits de charrues à disques.

Les principaux clients peuvent être des agriculteurs individuels, des coopératives agricoles ainsi que des organismes et institutions intervenant dans le développement agricole.

L'application constitue une évolution numérique de cette activité, avec l'objectif de faciliter la commercialisation, la gestion des produits et la coordination des commandes et des livraisons.

---

# Fonctionnalités

## Espace Client

L'espace client permet de :

- consulter la page d'accueil ;
- rechercher des produits ;
- parcourir le catalogue ;
- filtrer les produits ;
- consulter les caractéristiques détaillées ;
- consulter les avis et évaluations ;
- ajouter des produits aux favoris ;
- gérer le panier ;
- passer une commande ;
- sélectionner un moyen de paiement ;
- suivre une commande ;
- consulter l'historique des commandes ;
- gérer son profil et ses adresses ;
- recevoir des notifications ;
- rechercher un produit à l'aide d'un QR code ou d'un code-barres.

### Moyens de paiement prévus

- Mobile Money ;
- carte bancaire ;
- virement bancaire.

---

## Espace Fournisseur

L'espace fournisseur permet de :

- consulter un tableau de bord ;
- ajouter des produits ;
- ajouter des photos ;
- renseigner les caractéristiques des produits ;
- gérer les stocks ;
- consulter les commandes ;
- suivre les ventes ;
- consulter les revenus ;
- suivre l'état de validation des produits.

---

## Espace Employé

L'espace employé permet notamment de :

- consulter les produits soumis par les fournisseurs ;
- vérifier les informations des produits ;
- accepter un produit ;
- demander une modification ;
- refuser un produit ;
- gérer certaines commandes ;
- traiter les réclamations des clients.

---

## Espace Administrateur

L'administrateur dispose d'un tableau de bord global permettant de suivre :

- le chiffre d'affaires ;
- les utilisateurs ;
- les commandes ;
- les commissions ;
- les statistiques de vente ;
- les fournisseurs ;
- les catégories ;
- les campagnes marketing ;
- l'activité générale de la plateforme.

---

## Espace Partenaire Logistique

Le partenaire logistique peut :

- consulter ses missions de livraison ;
- accepter ou refuser une mission ;
- consulter les informations d'une livraison ;
- mettre à jour le statut d'une livraison ;
- suivre les livraisons en cours ;
- utiliser ultérieurement la géolocalisation.

---

# Catégories de la marketplace

La plateforme est principalement orientée vers l'agriculture, tout en permettant une extension vers différents secteurs.

| Catégorie | Exemples |
|---|---|
| Agriculture | Tracteurs, motoculteurs, motopompes, équipements |
| Tourisme | Produits et services touristiques |
| Artisanat | Produits artisanaux locaux |
| Électronique | Matériel et équipements électroniques |
| Mode | Vêtements et accessoires |
| Véhicules | Véhicules et équipements |
| Santé | Matériel médical |
| Autres | Produits et services divers |

---

# Interface utilisateur

L'interface reprend l'identité visuelle de FITAHIANTSOA et s'inspire de l'agriculture, de la nature et de Madagascar.

## Principes de conception

- interface moderne et professionnelle ;
- conception orientée mobile ;
- navigation simple et intuitive ;
- hiérarchie claire des informations ;
- composants cohérents ;
- boutons adaptés aux écrans tactiles ;
- design responsive ;
- expérience utilisateur adaptée aux différents profils.

## Identité visuelle

La palette principale utilise :

- vert forêt profond ;
- vert naturel ;
- ocre et or ;
- terre cuite ;
- vert sauge et crème.

L'objectif est de créer une identité visuelle différente des interfaces SaaS génériques et davantage liée à l'univers agricole et au contexte malgache.

---

# Écrans du prototype

Le prototype comprend actuellement plusieurs interfaces :

1. Écran d'accueil
2. Catalogue
3. Recherche et filtres
4. Fiche produit
5. Panier
6. Tunnel de commande
7. Suivi de commande
8. Tableau de bord fournisseur
9. Tableau de bord employé
10. Tableau de bord administrateur
11. Tableau de bord logistique
12. Sélection et changement d'espace

---

# Technologies utilisées

| Technologie | Utilisation |
|---|---|
| React | Construction de l'interface |
| JavaScript | Logique applicative |
| JSX | Structure des composants |
| CSS | Mise en forme et responsive design |
| Lucide | Icônes de l'interface |

---

# Structure du projet

```text
APPLICATION_FITAHIANTSOA/
│
├── assets/
│   └── fitahiantsoa-app.png
│
├── index.html
│
├── FitahiantsoaApp.jsx
│
└── README.md
