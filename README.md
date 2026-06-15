# Cape Town Food Fest – Interactive Ticket Landing Page

An elegant, modern, and fully responsive single-page Vue.js application designed for the annual **Cape Town Food Fest**. This landing page serves as the visual foundation for a future ticketing system, allowing food lovers to explore ticket tiers, compare benefits, and interact with the event's offerings.

Built with **Vue 3** and optimized for a seamless user experience, the project showcases component-driven development, dynamic data rendering, and fluid interactions.

---

## Project Overview

The Cape Town Food Fest landing page brings a vibrant outdoor festival energy to the screen. It aims to drive engagement and help potential attendees evaluate ticket tiers before official sales launch.

### Key Features
* **Dynamic Ticket Grid:** Ticket tiers (Bronze, Silver, Gold) are rendered dynamically from a centralized local data array using reusable Vue components and props.
* **Visual Hierarchy:** The **Gold Tier** is dynamically highlighted as the "Featured" option with enhanced styling to drive conversions.
* **Interactive Engagement:** Users can "favourite" tiers in real-time, simulating a modern e-commerce experience with interactive state changes.
* **Responsive Layout:** A mobile-first CSS grid/flexbox design ensuring the festival looks stunning on smartphones, tablets, and desktops alike.
* **Polished Micro-interactions:** Smooth CSS hover transitions and button animations for an organic, premium feel.

---

## Interface Preview

---

## Technical Architecture

This project strictly adheres to the technical boundaries set by the brief:
* **Framework:** Vue 3 (Composition API / Options API)
* **Tooling:** Vite (for ultra-fast development and bundling)
* **State Management:** Local Vue reactivity (`ref`, `reactive`, and `computed` properties)
* **Component Architecture:**
    * `App.vue`: Handles global layout, header, state initialization, and the main wrapper.
    * `TicketCard.vue`: A highly reusable component leveraging **Props** for data injection and **Slots** for flexible action buttons.

---

## Installation & Setup Instructions

Follow these steps to clone, install, and run the project locally on your machine.

### Prerequisites
Ensure you have [Node.js](https://nodejs.org/) installed (version 16.x or higher recommended).

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/cape-town-food-fest.git](https://github.com/YOUR_USERNAME/cape-town-food-fest.git)
cd cape-town-food-fest
