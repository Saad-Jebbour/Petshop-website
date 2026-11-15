# 🐾 PetShop - Your Pet's Favorite Place

Bienvenue sur le projet **PetShop**, une plateforme e-commerce moderne dédiée aux animaux de compagnie (chiens, chats, oiseaux, poissons et rongeurs). Ce site web propose une sélection complète de nourriture, jouets, accessoires et soins pour le bien-être de vos compagnons.

---

## 🌟 Fonctionnalités

- **Accueil interactif** : Bannières dynamiques, catégories d'animaux, produits phares et loader personnalisé.
- **Boutiques par catégorie d'animaux** :
  - 🐶 [Chiens](html/chiens.html)
  - 🐱 [Chats](html/chats.html)
  - 🦜 [Oiseaux](html/oiseaux.html)
  - 🐟 [Poissons](html/poissons.html)
  - 🐹 [Rongeurs](html/rongeurs.html)
- **Gestion du panier d'achat** :
  - Ajout et suppression de produits.
  - Calcul dynamique du total.
  - Persistance locale via `localStorage`.
- **Tunnel de commande** :
  - Page de récapitulatif du panier.
  - Page de paiement et validation.
- **Espace utilisateur** :
  - Pages de connexion (`login.html`) et d'inscription (`signup.html`).
- **Thème Sombre / Clair (Dark Mode)** : Changement de thème avec adaptation visuelle globale.
- **Design Responsive** : Optimisé pour ordinateurs, tablettes et smartphones.
- **Page À Propos & Contact** : Présentation de l'équipe et formulaire de contact.

---

## 📁 Structure du Projet

```text
Pethsop-website/
├── index.html              # Point d'entrée principal (redirection vers html/index.html)
├── .gitignore              # Fichiers et dossiers ignorés par Git
├── README.md               # Documentation du projet
│
├── css/                    # Feuilles de styles CSS
│   ├── apropos.css         # Styles de la page À propos
│   ├── contactus.css       # Styles de la page Contact
│   ├── loader.css          # Animation du préchargeur de page
│   ├── login.css           # Styles de la page Connexion
│   ├── modesombre.css      # Thème sombre
│   ├── pages.css           # Styles principaux et communs
│   ├── paiement.css        # Styles de la page de paiement
│   ├── panier.css          # Styles du panier
│   ├── responsive.css      # Règles pour l'affichage mobile/tablette
│   └── signup.css          # Styles de la page d'inscription
│
├── html/                   # Pages du site web
│   ├── index.html          # Page d'accueil
│   ├── apropos.html        # Page À propos / Présentation de l'équipe
│   ├── contact.html        # Page Contact
│   ├── chiens.html         # Produits Chiens
│   ├── chats.html          # Produits Chats
│   ├── oiseaux.html        # Produits Oiseaux
│   ├── poissons.html       # Produits Poissons
│   ├── rongeurs.html       # Produits Rongeurs
│   ├── panier.html         # Panier d'achat
│   ├── paiment.html        # Processus de paiement
│   ├── login.html          # Connexion
│   └── signup.html         # Inscription
│
├── js/                     # Scripts JavaScript
│   ├── card.js             # Gestion des cartes produits
│   ├── footerFIX.js        # Gestion du composant pied de page
│   ├── header.js           # Gestion de la barre de navigation
│   ├── headerFIX.js        # Navigation et synchronisation
│   ├── homepage.js         # Animations et logique de la page d'accueil
│   ├── loader.js           # Gestion du préchargeur
│   ├── login.js            # Validation du formulaire de connexion
│   ├── plp.js              # Logique des listes de produits (filtres, panier)
│   ├── signup.js           # Validation du formulaire d'inscription
│   └── theme.js            # Basculement mode sombre / clair
│
└── images/                 # Ressources graphiques (photos produits, bannières, icônes)
    └── team images/        # Photos de l'équipe (ignoré par Git)
```

---

## 🛠️ Technologies Utilisées

- **HTML5** : Structuration sémantique des pages.
- **CSS3** : Design moderne, Flexbox, CSS Grid, animations et Media Queries pour le responsive.
- **JavaScript (Vanilla)** : Manipulation du DOM, gestion du panier (`localStorage`), animations, gestion des thèmes.
- **Ionicons & Google Fonts** : Typographie Poppins et bibliothèque d'icônes.

---

## 🚀 Installation et Lancement

Ce projet est un site web statique qui ne nécessite aucun serveur applicatif ou base de données complexe pour être visualisé.

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/votre-nom-dutilisateur/Pethsop-website.git
   cd Pethsop-website
   ```

2. **Lancer le site :**
   - Ouvrez simplement `index.html` dans votre navigateur préféré (Chrome, Firefox, Edge, Safari).
   - *Optionnel* : Vous pouvez également utiliser l'extension **Live Server** sur Visual Studio Code pour un rafraîchissement automatique lors des modifications.

---

## 👥 Équipe de Développement

Ce projet a été réalisé par :

- **Meryem Bahoum**
- **Hajar Amzoirou**
- **Hajar Oumessaoud**
- **Saad Jebbour**
- **Oussama Khattou**

---

## 📄 Licence

Ce projet est réalisé dans le cadre d'un projet d'études. Tous droits réservés.

