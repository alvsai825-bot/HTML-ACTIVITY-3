# 🍔 FoodieExpress – Online Food Delivery (Pure HTML5 & CSS3)

A modern, responsive, and visually stunning Food Delivery website built **STRICTLY using ONLY HTML5 and CSS3** (Zero JavaScript) for a college Web Development assignment.

![FoodieExpress Banner](assets/images/hero.jpg)

---

## 📌 Project Overview

**FoodieExpress** is an online food delivery web application crafted exclusively with **HTML5 and CSS3**. It adheres strictly to the fundamental curriculum requirement: **no JavaScript, no React, no backend frameworks, no external APIs, and no complex libraries**.

Despite using only HTML5 and CSS3, the website provides a rich, responsive, and interactive user experience using modern CSS3 techniques:
- **Pure CSS Navigation & Mobile Hamburger Menu** (using the CSS Checkbox hack).
- **Pure CSS Food Category Filtering** (using CSS Radio state selectors).
- **Pure CSS Veg / Non-Veg Filtering** (using CSS Checkbox toggle).
- **Pure CSS Restaurant Filtering** (using CSS Radio tabs).
- **Pure CSS Slide-over Shopping Cart Drawer** (using the CSS `:target` pseudo-class).
- **Pure CSS Interactive Modals** for Checkout and Live Order Tracking (using CSS `:target`).
- **Pure CSS Interactive Favorite Toggles** on restaurant cards.

---

## 🎨 Color Palette & Design System

The design follows a modern culinary theme crafted with warm, appetizing colors:

| Color Role | Hex Code | Visual Application |
| :--- | :--- | :--- |
| **Primary** | `#FF6B35` | Vibrant warm orange for buttons, badges, discount tags, and active tabs |
| **Secondary** | `#2D2424` | Dark espresso brown for headings, card titles, and footer |
| **Background** | `#FFF9F3` | Soft warm cream for comfortable readability and natural warmth |
| **White** | `#FFFFFF` | Clean white for food cards, input fields, and modal containers |
| **Accent Green** | `#2E9D59` | Fresh herb green for ratings, Pure Veg badges, and free delivery highlights |
| **Accent Gold** | `#FFB300` | Golden yellow for star reviews and floating badges |

---

## 🚀 Website Sections & Features

### 1. Navigation Bar
- **Brand Logo**: FoodieExpress icon and typography with smooth hover rotation.
- **Navigation Links**: Home, Categories, Restaurants, Menu, Offers, Contact.
- **Search Bar**: Quick search input with search button.
- **Shopping Cart Button**: Shopping bag icon with active cart count badge (`3`).
- **Mobile Menu Toggle**: 100% pure CSS hamburger animation and slide-down drawer.

### 2. Hero Showcase
- Headline: *"Delicious Food Delivered To Your Door"*
- Subtitle: *"Discover your favourite meals from the best restaurants near you."*
- Cuisine search input box and quick action buttons: **Explore Food** and **Order Now**.
- Trust metrics: **500+ Restaurants**, **30 Min Fast Delivery**, and **4.8★ User Rating**.
- Hero visual banner with floating badges (*Flat 20% OFF*, *30 mins Express*, *4.9 Rating*).

### 3. Food Categories (8 Categories)
- **Pizza**, **Burgers**, **Biryani**, **Chinese**, **Desserts**, **South Indian**, **Healthy Food**, and **Beverages**.
- Beautiful rounded cards with hover elevation and instant jump links to corresponding menu tabs.

### 4. Featured Partner Restaurants
- 6 featured restaurants with complete sample data:
  1. **Spice Garden** – North Indian & Mughlai (4.8★ • 25-30 mins • Min. ₹150)
  2. **Pizza Palace** – Italian & Fast Food (4.7★ • 20-25 mins • Min. ₹200)
  3. **Burger House** – Burgers & Fast Food (4.6★ • 15-20 mins • Min. ₹100)
  4. **South Indian Kitchen** – South Indian Dosa (4.9★ • 20-30 mins • Min. ₹99)
  5. **Chinese Wok** – Asian & Chinese (4.5★ • 25-35 mins • Min. ₹120)
  6. **Sweet Treats** – Bakery & Desserts (4.8★ • 15-25 mins • Min. ₹80)
- **Pure CSS Filter Tabs**: Filter restaurants by *All*, *Top Rated (4.7+)*, and *Fast Delivery (<25m)*.
- Interactive favorite heart toggle on every restaurant card.

### 5. Popular Dishes (Menu Section)
- All 8 requested dishes with prices in Indian Rupees (₹), high-resolution imagery, Veg/Non-Veg indicators, and ratings:
  1. **Chicken Biryani** – ₹199 (Non-Veg)
  2. **Margherita Pizza** – ₹249 (Veg)
  3. **Classic Burger** – ₹149 (Non-Veg)
  4. **Paneer Butter Masala** – ₹179 (Veg)
  5. **Veg Fried Rice** – ₹129 (Veg)
  6. **Chocolate Cake** – ₹99 (Veg)
  7. **Masala Dosa** – ₹89 (Veg)
  8. **French Fries** – ₹79 (Veg)
  *(Plus companion options: Paneer Tikka Pizza, Crispy Chicken Burger, Garden Fresh Salad, Mango Lassi).*
- **Pure CSS Category Filter Pills**: Clicking any tab (*All Dishes*, *Biryani*, *Pizza*, *Burgers*, *North Indian*, *Chinese*, *South Indian*, *Desserts*, *Healthy Food*, *Beverages*) instantly filters the dishes without JavaScript!
- **Pure Veg Toggle**: Filters the menu to show strictly vegetarian items.
- "Add to Cart" button linking directly to the slide-over cart drawer.

### 6. Special Promotional Offers
- 3 attractive promotional banners:
  - **20% OFF on your first order** (Code: `FIRST20`)
  - **Buy 1 Get 1 Free on selected pizzas** (Code: `BOGOPIZZA`)
  - **Free delivery on orders above ₹499** (Code: `FREEDEL`)
- "Claim Offer & Order" CTA buttons leading directly to the shopping cart.

### 7. Shopping Cart Drawer (Pure CSS3 `:target`)
- Slide-over drawer opening via `#cart-drawer`.
- Displays active cart items with thumbnails, titles, unit prices, quantity inputs, and totals.
- **Free Delivery Tracker**: Informs user that orders above ₹499 unlock FREE delivery.
- Active coupon code tag (`FIRST20`).
- Complete bill breakdown: Subtotal (₹527), 20% Discount (-₹105), Delivery Fee (FREE), Taxes & Packaging (₹20), and Grand Total (₹442).
- "Proceed to Checkout" button leading to the checkout modal.

### 8. Checkout Modal & Order Tracking (Pure CSS3 `:target`)
- **Checkout Modal (`#checkout-modal`)**:
  - Delivery address form with Full Name, Phone, Street Address, City, Pincode, Landmark.
  - Payment method selector with visual radio button selection (COD, UPI demo, Card demo).
  - "Confirm Demo Order" button leading to the Order Success Modal.
- **Order Confirmation Modal (`#order-success-modal`)**:
  - Animated celebration checkmark in pure CSS3 (`@keyframes`).
  - Unique order tracking ID: `#FE-94821`.
  - Customer summary and total amount paid.
  - 4-step delivery progress tracker:
    - Step 1: Order Confirmed ✓
    - Step 2: Food Being Prepared 🍳
    - Step 3: Out for Delivery 🛵
    - Step 4: Arrived at Doorstep 🏠
  - "Back to Menu" button returning to the main page.

### 9. Contact & Footer
- 4 Customer Support info cards (Phone, 24/7 Email, Bengaluru Headquarters, Kitchen Hours).
- Semantic contact form with pure CSS submission alert message.
- Newsletter subscription box.
- Social media links, quick links, and copyright notice.

---

## 🛠️ Technologies Used

- **HTML5**: Semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<form>`, `<input>`, `<label>`).
- **CSS3**: Custom CSS variables, Flexbox, CSS Grid layout, responsive media queries, CSS `:target` pseudo-class, Checkbox / Radio state hacks, and keyframe animations.
- **No JavaScript**: 100% free of JavaScript, scripts, external frameworks, or runtimes.

---

## 📂 Project Folder Structure

```
food-delivery-website/
│
├── index.html          # Semantic HTML5 structure (no scripts)
├── style.css           # Pure CSS3 styling, animations, and interactive hacks
├── README.md           # Documentation and run instructions
│
└── assets/
    └── images/
        ├── hero.jpg             # Hero banner showcase
        ├── pizza.jpg            # Margherita Pizza
        ├── burger.jpg           # Classic Burger
        ├── biryani.jpg          # Chicken Biryani
        ├── dosa.jpg             # Masala Dosa
        ├── dessert.jpg          # Chocolate Cake
        ├── chinese.jpg          # Chinese wok
        ├── healthy.jpg          # Fresh salad
        ├── beverages.jpg        # Refreshing drinks
        ├── paneer.jpg           # Paneer Butter Masala
        ├── fried-rice.jpg       # Veg Fried Rice
        ├── fries.jpg            # French Fries
        ├── restaurant-1.jpg     # Spice Garden
        ├── restaurant-2.jpg     # Pizza Palace
        ├── restaurant-3.jpg     # Burger House
        ├── restaurant-4.jpg     # South Indian Kitchen
        ├── restaurant-5.jpg     # Chinese Wok
        └── restaurant-6.jpg     # Sweet Treats bakery
```

---

## 💻 How to Run Locally

1. Open the project folder on your computer.
2. Double-click `index.html` to open it in any web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Apple Safari).
3. The website will render immediately with all styles and interactive CSS features functioning offline or online.

---

## 🌐 How to Deploy on GitHub Pages

1. Create a new public repository on [GitHub](https://github.com).
2. Upload `index.html`, `style.css`, `README.md`, and the `assets/` folder to the root of your repository.
3. In GitHub, go to **Settings** &rarr; **Pages**.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Your pure HTML5 & CSS3 website is live on the web!

---

## 🎓 Academic Assignment Note

This project was built strictly using **HTML5 and CSS3** to satisfy fundamental web design curriculum guidelines without requiring any JavaScript knowledge or dependencies.

---

## 📄 License & Credits

- **Copyright**: © 2026 FoodieExpress. All Rights Reserved.
- **Fonts**: [Google Fonts (Poppins & Plus Jakarta Sans)](https://fonts.google.com/)
- **Icons**: [Font Awesome](https://fontawesome.com/)
