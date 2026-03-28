# ☦️ Walk With Jesus: The Passion Journey

An immersive, high-fidelity web experience designed for spiritual reflection on the **13 Sufferings of Christ**. This project combines liturgical aesthetics with modern interactive storytelling to guide users through the path to Calvary.

---

## 🌟 Core Features

### 1. Interactive Path Map (S-Curve)
The landing page features a custom-designed **S-Curve SVG path** that visually represents the winding journey of the Passion.
* **Station Nodes:** Nine numbered nodes (1-9) act as direct navigation links.
* **Hover Intelligence:** Nodes glow and expand on hover, providing a tactile feel to the digital map.
* **Responsive Layout:** On mobile devices, the path intelligently transforms into a vertical or grid-based flow for better tap targets.

### 2. Smart Navigation Suite
The interface is built to ensure the user remains focused during their reflection:
* **Global Progress Dots:** A fixed "Station Map" at the top center tracks the user's scroll depth, highlighting the current station in gold.
* **Dynamic FAB (Floating Action Button):** A "Next Station" button that tracks the user's position and calculates the next logical stop.
* **Smart Reset:** Upon reaching the final reflection, the primary button automatically transforms into a **"RESTART ↺"** trigger.
* **Elevated "Back to Top":** A secondary navigation button that fades in only when needed, maintaining a clean UI.

### 3. Parallax Visuals & Typography
* **Layered Depth:** Background images move at a slower speed than the foreground (parallax), creating a sense of 3D space as the user "walks" through the stations.
* **Liturgical Palette:** Uses a curated color scheme of **Deep Gold (#c5a059)** for divinity and **Blood Red (#8b0000)** for sacrifice.
* **Font Pairing:** Utilizes **Cinzel** for a stately, ancient feel and **Lora** for a legible, meditative reading experience.

---

## 🛠️ Technical Specifications

* **Architecture:** Single Page Application (SPA) built with pure **HTML5, CSS3, and Vanilla JavaScript**.
* **Performance:** Zero external dependencies (no jQuery or React) ensures lightning-fast load times even on limited mobile data.
* **CSS Animations:** Uses hardware-accelerated transforms and opacity transitions for the "ZoomEffect" and "Pulse" states.
* **Scroll Logic:** Implements the `window.pageYOffset` API for precise section tracking and `scroll-behavior: smooth` for elegant transitions.

---

## 📂 File Structure

| Component | Responsibility |
| :--- | :--- |
| `header#hero` | Contains the landing title and the SVG S-Curve Map. |
| `section#s1-s9` | Individual stations containing thematic background images and reflection cards. |
| `.slider-container` | Horizontal scroll-snap containers for sub-content within stations. |
| `script` | Handles scroll-spy logic, navigation button updates, and smooth scrolling. |

---

## 🚀 Deployment & Usage

1.  **Direct Access:** Simply open the `index.html` file in any modern web browser.
2.  **Hosting:** This project is "static," meaning it can be hosted for free on **GitHub Pages**, **Netlify**, or **Vercel**.
3.  **Customization:** To change images, replace the `url()` links in the `background-image` style attributes within each section.

---

## 📜 Credits & License

**EOTC | Walk With Jesus 2026** This project was developed to serve the community during the Lenten and Passion Week seasons. 

> *"He was wounded for our transgressions, He was bruised for our iniquities."*