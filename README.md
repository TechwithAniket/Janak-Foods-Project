# Janak Foods: Farm-to-Table Grocery Prototype

A professional, responsive e-commerce front-end for a local grocery service based in Amritsar. This project focuses on a premium user experience, clean UI design, and functional client-side authentication.

## 🚀 Live Demo
[Insert link to your GitHub Pages or Vercel deployment here]

## 🛠 Tech Stack
* **HTML5:** Semantic structure for optimal accessibility.
* **CSS3:** Custom responsive design using Flexbox and CSS Grid.
* **JavaScript (ES6+):** DOM manipulation, event handling, and client-side session management.

## 🔑 Key Features
* **Responsive Architecture:** Fully optimized for desktop and mobile layouts.
* **Client-Side Authentication:** Simulates user sign-up and sign-in flows using `localStorage`.
* **Dynamic Navigation:** Seamless page routing and interaction.
* **Interactive UI:** Price tables, promotional video embeds, and search functionality.

## 🧩 Engineering Challenges & Solutions
* **Challenge: "Unsafe attempt to load URL" errors.** * *Solution:* Implemented a local development server (VS Code Live Server) to bypass browser security restrictions on `file://` protocols and manage relative pathing effectively.
* **Challenge: Redirect Logic.**
    * *Solution:* Managed form submission flows by utilizing `e.preventDefault()` to override default browser behavior, ensuring smooth transition between pages during the authentication cycle.
* **Challenge: CSS Scope & Repetition.**
    * *Solution:* Managed styling through structured CSS blocks, focusing on reusable classes and the parent-child inheritance model to maintain a consistent brand identity across pages.

## 📈 Future Roadmap
This project serves as **Version 1.0 (Vanilla JS)**. The following improvements are planned for the transition to **Next.js (Version 2.0)**:
1.  **Component-Based Architecture:** Migrating the Header/Footer to reusable React components.
2.  **Backend Integration:** Implementing a Node.js/Express backend with MongoDB for real user data persistence.
3.  **State Management:** Replacing `localStorage` with React context/state management for a more robust auth flow.

## 📸 Project Preview
[Add a screenshot of your home page here]
