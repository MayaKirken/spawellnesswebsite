# Serene Oasis – Luxury Spa Homepage

Serene Oasis is a modern, premium, single-page digital storefront designed for a luxury wellness spa. Built entirely in a local development environment, this project shifts away from tutorial sandboxes to demonstrate clean HTML5 structure, responsive CSS layout architecture, and elegant Vanilla JavaScript user interactions.

## 🚀 Live Demo
[View Live Project on Netlify](https://phenomenal-beijinho-b516ba.netlify.app/)

---

## ✨ Features & Technical Execution

### 1. Single-Page Navigation Architecture
* **UX Decision:** Implemented a streamlined, single-page layout rather than a heavy multi-page system to provide a seamless, high-end user flow.
* **Smooth Scrolling:** Utilized the CSS `scroll-behavior: smooth` property to glide users naturally to content sections when hitting navigation anchors or the main Call-To-Action (CTA) button, avoiding jarring page snaps.

### 2. Live-Mutating Sticky Header (JavaScript)
* Developed an active event listener in Vanilla JavaScript targeting the window's vertical scroll position (`window.scrollY`).
* Dynamically manipulates the document structure using `classList.add()` and `classList.remove()` to anchor the navigation bar once the user scrolls past 50px.
* Delivers an expensive, polished aesthetic by easing a subtle box-shadow and shifting the solid background color to a 95% translucent off-white (`rgba`), keeping text readable while allowing content elements to slide elegantly behind it.

### 3. Bulletproof Layout Alignment
* Built with semantic HTML5 components (`<header>`, `<section>`, `<footer>`) to maximize accessibility and SEO readiness.
* Leveraging advanced layout alignment via Flexbox to cleanly distribute elements across hero, preview grids, and dual-column information blocks.
* Handled complex container boundary issues using `box-sizing: border-box` to prevent layout clipping and preserve padding constraints across varying viewport widths.

---

## 🛠️ Technologies Used
* **Markup:** HTML5 (Semantic Structure)
* **Styling:** CSS3 (Flexbox Layouts, Transitions, Advanced Positioning)
* **Scripting:** Vanilla JavaScript (DOM Manipulation, Scroll Event Listening)
* **Version Control:** Git & GitHub

---

## 🧠 Key Takeaways & Lessons Learned
* **Local Environment Mastery:** Stepping completely away from structured online platforms allowed for hands-on experience debugging real browser rendering behavior, organizing paths, and tackling layout bugs independently.
* **Defensive Engineering:** Learned how to guard code logic by validating element existence before running event listeners, resolving warnings like "element is possibly null."
* **Version Control Discipline:** Maintained strict Git workflows by packaging atomic, feature-specific changes into clean commits under 50 characters.