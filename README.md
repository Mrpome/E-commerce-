# Projet React E-Commerce JavaScript

Ce projet est un site e-commerce minimaliste en React JS avec :

- Navigation multi-pages avec React Router
- Panier global avec React Context + localStorage
- Ajout/suppression/modification quantité dans panier
- Formulaire de commande avec simulation de paiement
- Design avec Tailwind CSS (optionnel)

---

## Installation

1. Cloner ce projet ou décompresser le zip
2. Installer les dépendances : `npm install`
3. Lancer le serveur dev : `npm run dev` (avec Vite) ou `npm start` (create-react-app)
4. Visiter http://localhost:3000 ou http://localhost:5173

---

## Structure

- src/
  - components/ (Navbar, ProductCard)
  - context/ (CartContext)
  - pages/ (Home, Products, Checkout)
  - data.js
  - App.jsx
  - main.jsx
- public/images/ (images produits)

---

## Notes

- Ajouter vos propres images dans public/images
- Adapter styles dans styles.css
- Nécessite React Router, React 18+, Tailwind CSS (optionnel)
