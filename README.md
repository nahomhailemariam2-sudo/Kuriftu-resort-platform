# Kuriftu Resort & Spa | Luxury Digital Platform

A high-performance, responsive luxury web interface built for **Kuriftu Resort & Spa**, featuring immersive glassmorphism modals, spring-physics UI animations, dynamic multi-language indexing, and accessible keyboard navigation controllers.

---

## 🌟 Key Features

* **Advanced Glassmorphism Modal:** Features hardware-accelerated backdrop filters, custom cubic-bezier spring animations (`cubic-bezier(0.16, 1, 0.3, 1)`), and automated staggered child entrances.
* **Accessibility (a11y) First:** Implements robust keyboard focus trapping (`Tab` / `Shift + Tab`), `ESC` key dismissals, ARIA state management, and background scroll locks.
* **Centralized Image Indexing:** A structured ES6 manifest (`images.js`) that handles high-res resort assets, room previews, categories, and dynamic gallery rendering.
* **Modular Code Architecture:** Clean separation of concerns with dedicated directories for components, design tokens, styles, and automated GitHub workflows.

---

## 📂 Project Structure

```text
kuriftu-resort-platform/
│
├── .github/
│   └── workflows/
│       └── deploy.yml          # Automated CI/CD pipeline (GitHub Actions)
├── src/
│   ├── assets/
│   │   └── images.js           # Centralized image index manifest
│   ├── components/
│   │   ├── modal/
│   │   │   ├── modal.js        # Focus trap & lifecycle controller
│   │   │   └── modal.scss      # Glassmorphism & spring animations
│   │   └── gallery/
│   │       ├── gallery.js      # Dynamic DOM grid injector
│   │       └── gallery.scss    # Responsive CSS grid layouts
│   ├── scss/
│   │   ├── variables.scss      # Global design tokens (colors, typography)
│   │   └── main.scss           # Main aggregator stylesheet
│   └── index.html              # Semantic entry markup
├── package.json
└── README.md
