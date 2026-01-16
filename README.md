# Moniteo by Umbrella

**Moniteo** est un tableau de bord premium pour la gestion des ventes, inventaire, dépenses et staff, conçu pour les entreprises souhaitant suivre leur business en temps réel de manière sécurisée.

---

## Table des matières

- [Fonctionnalités](#fonctionnalités)
- [Technologies utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Configuration Email OTP](#configuration-email-otp)
- [Structure des fichiers](#structure-des-fichiers)
- [Aperçu](#aperçu)
- [Mentions légales](#mentions-légales)

---

## Fonctionnalités

- **Connexion sécurisée par OTP** : L’utilisateur reçoit un code unique sur son email pour se connecter.  
- **Vérification Admin** : Les sections sensibles sont accessibles uniquement après saisie d’un ID admin.  
- **Dashboard interactif** :
  - KPI cards : CA total, bénéfice net, quantité vendue, produits en stock, dépenses totales.
  - Graphiques dynamiques : ventes par produit, ventes par jour, dépenses par catégorie.
- **Alertes automatiques** : Stock faible, rupture, dépenses élevées, top ventes du jour.  
- **Gestion Staff** : Affichage du nombre d’employés.  
- **Export PDF** : Génération du dashboard au format PDF directement depuis le navigateur.  
- **Espace compte utilisateur** : Nom, date de naissance et photo de profil (modifiables lors de la première saisie).  
- **Responsive design** : Compatible desktop et mobile.  
- **Favicon et branding** : Logo Moniteo visible sur toutes les pages.

---

## Technologies utilisées

- HTML5 / CSS3
- JavaScript (Vanilla JS)
- [EmailJS](https://www.emailjs.com/) pour l’envoi OTP
- [Chart.js](https://www.chartjs.org/) pour les graphiques
- [jsPDF](https://github.com/parallax/jsPDF) et [html2canvas](https://html2canvas.hertzen.com/) pour l’export PDF
- LocalStorage pour les données mock (ventes, inventaire, dépenses, staff)

---

## Installation

1. Cloner le dépôt :  
```bash
git clone https://github.com/toncompte/moniteo.git

Mentions légales
Logiciel développé par Umbrella.
Tous droits réservés © 2026 Moniteo.
Conditions d’utilisation et politique de confidentialité incluses dans le footer du dashboard.