# Cooking Masterclass - Dynamic Catalogue Interface

An interactive, responsive single-page catalogue prototype showcasing curated culinary workshops hosted by expert chefs. Built with a modular, component-driven architecture using **Vue 3** and **Vite**.

This project serves as the interactive frontend layout foundation for the platform's future e-commerce system.

---

## 🚀 Key Features Built

* **Dynamic Component Architecture:** Renders workshop profiles (Chef names, skill level badges, prices) dynamically via Vue components with zero hardcoded duplication.
* **Reactive Wishlist Pipeline:** Clicking "Save to Wishlist" tracks saved courses, updates individual card states, and instantly increments the counter badge in the page header.
* **Clear "Sold Out" Statuses:** Unavailable courses clearly display a bold "Sold Out" badge, drop in opacity, and automatically lock/disable their wishlist selection buttons.
* **Responsive Layout Design:** Adapts smoothly across mobile devices, tablets, and desktop monitors using CSS Grid and clean layout breakpoints.
* **Bonus Stretch Integrations:** * Includes local price formatting using localized currency notation (ZAR).
  * Includes an interactive filter toggle to instantly switch between "All Classes" and "Available Only".
  * Features subtle hover lifting animations on cards and a micro-pulse warning transition on the header wishlist badge.

---

## 🛠️ Technical Scope & Setup

* **Framework:** Vue 3 (Options API configuration)
* **Build Tool:** Vite
* **Data Layer:** Local data arrays (No external API or database dependencies)
* **Routing:** Single-page app workflow (No Vue Router)

---

## ⚙️ Installation & Running the Project Local Engine

Make sure you have [Node.js](https://nodejs.org/) installed on your computer before setting up.

### 1. Clone the Project Repository
```bash
git clone <your-github-repository-url-here>
cd cooking-masterclass
