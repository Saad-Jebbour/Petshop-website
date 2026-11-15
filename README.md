# 🐾 PetShop - Your Pet's Favorite Place

Welcome to **PetShop**, a modern e-commerce platform dedicated to pets (dogs, cats, birds, fish, and rodents). This website offers a comprehensive catalog of pet food, toys, accessories, and healthcare products to ensure the well-being of your companion animals.

---

## 🌟 Features

- **Interactive Homepage**: Dynamic hero banners, pet category navigation, featured products, and an animated preloader.
- **Product Categories by Pet**:
  - 🐶 [Dogs](html/chiens.html)
  - 🐱 [Cats](html/chats.html)
  - 🦜 [Birds](html/oiseaux.html)
  - 🐟 [Fish](html/poissons.html)
  - 🐹 [Rodents](html/rongeurs.html)
- **Shopping Cart Management**:
  - Add and remove items dynamically.
  - Real-time cart total calculation.
  - Persistent state saved via `localStorage`.
- **Checkout Process**:
  - Cart review summary page.
  - Checkout & payment validation page.
- **User Authentication**:
  - Sign In (`login.html`) and Sign Up (`signup.html`) pages with form validation.
- **Dark / Light Mode**: Seamless theme switching with consistent UI styling across pages.
- **Responsive Design**: Fully optimized for mobile phones, tablets, and desktop screens.
- **About Us & Contact Pages**: Team presentation and customer inquiry contact form.

---

## 📁 Project Structure

```text
Pethsop-website/
├── index.html              # Main entry point (redirects to html/index.html)
├── .gitignore              # Files and directories ignored by Git
├── README.md               # Project documentation
│
├── css/                    # Stylesheets
│   ├── apropos.css         # About page styles
│   ├── contactus.css       # Contact page styles
│   ├── loader.css          # Page preloader animation
│   ├── login.css           # Login page styling
│   ├── modesombre.css      # Dark mode styles
│   ├── pages.css           # Global and shared component styles
│   ├── paiement.css        # Checkout and payment styles
│   ├── panier.css          # Shopping cart styles
│   ├── responsive.css      # Mobile and tablet media queries
│   └── signup.css          # Registration page styling
│
├── html/                   # HTML pages
│   ├── index.html          # Homepage
│   ├── apropos.html        # About us / Team presentation
│   ├── contact.html        # Contact page
│   ├── chiens.html         # Dog products
│   ├── chats.html          # Cat products
│   ├── oiseaux.html        # Bird products
│   ├── poissons.html       # Fish products
│   ├── rongeurs.html       # Rodent products
│   ├── panier.html         # Shopping cart
│   ├── paiment.html        # Payment and checkout
│   ├── login.html          # User login
│   └── signup.html         # User registration
│
├── js/                     # JavaScript files
│   ├── card.js             # Product card interactions
│   ├── footerFIX.js        # Reusable footer component
│   ├── header.js           # Header navigation handling
│   ├── headerFIX.js        # Navigation bar logic and state sync
│   ├── homepage.js         # Homepage animations and logic
│   ├── loader.js           # Page preloader controller
│   ├── login.js            # Login form validation
│   ├── plp.js              # Product Listing Page logic (filtering, cart actions)
│   ├── signup.js           # Sign up form validation
│   └── theme.js            # Dark/light theme toggler
│
└── images/                 # Graphical assets (products, banners, icons)
    └── team images/        # Team member photos (ignored by Git)
```

---

## 🛠️ Built With

- **HTML5**: Semantic and accessible page structure.
- **CSS3**: Modern layout using Flexbox, CSS Grid, custom animations, and responsive media queries.
- **Vanilla JavaScript**: DOM manipulation, dynamic cart calculation, `localStorage` persistence, and theme toggling.
- **Ionicons & Google Fonts**: Poppins font family and vector icon sets.

---

## 🚀 Getting Started

This is a static front-end web project, so no backend setup or database installation is required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Petshop-website.git
   cd Petshop-website
   ```

2. **Open the project:**
   - Double-click `index.html` to open it in your default web browser (Chrome, Edge, Firefox, Safari).
   - *(Recommended)* Open the folder in **Visual Studio Code** and use the **Live Server** extension for live reloading.

---

## 👥 Development Team

This project was built by:

- **Meryem Bahoum**
- **Hajar Amzoirou**
- **Hajar Oumessaoud**
- **Saad Jebbour**
- **Oussama Khattou**

---

## 📄 License

This project was developed for educational purposes. All rights reserved.
