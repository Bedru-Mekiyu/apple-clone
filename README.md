# Apple Homepage Clone

A responsive frontend web application replicating Apple's iconic homepage design, user experience, and visual aesthetics. Built using modern utility-first CSS (Tailwind CSS) alongside Bootstrap 5 components, FontAwesome icons, and custom CSS keyframe animations.

---

## 📌 Project Overview

This project is a pixel-accurate implementation of Apple's official web portal layout. It demonstrates advanced responsive layout design, fluid typography, media queries, interactive carousels, backdrop filters, and smooth CSS animation tracks.

### Key Features

- **Responsive Navigation**: Full desktop navigation bar with blur effect (`backdrop-blur-md`) and responsive collapsible drawer for mobile viewports (`data-bs-toggle="collapse"`).
- **Hero Showcase Sections**: Full-width promotional banners featuring dynamic product highlights (iPhone 17 Pro, iPhone Air, and iPhone 17).
- **Interactive Multi-Column Product Grid**: Two-column responsive card layout showcasing flagship Apple hardware with clean call-to-action buttons.
- **Infinite Logo & Asset Marquee**: Custom CSS continuous keyframe animation track for displaying promotional image banners smoothly.
- **Bootstrap Interactive Carousel**: Auto-rotating feature carousel with custom circular indicators and touch/control options.
- **Structured Legal & Footer Hierarchy**: Multi-column desktop links accordion-style breakdown for mobile screens with standard legal disclaimers.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic document structure and media accessibility attributes.
- **CSS3 / Tailwind CSS (v3)**: Utility-first styling for layout, typography, backdrop filters, and responsive spacing.
- **Bootstrap 5.3**: Modal menu interactions, grid system, and interactive carousel component.
- **FontAwesome 6**: Vector icons for branding, search, shopping bag, and navigation.
- **Custom CSS (`style.css`)**: Custom `@keyframes` animations for marquee tracks and custom scrollbars/indicators.

---

## 📁 Project Structure

```text
apple-clone/
├── index.html        # Main landing page HTML
├── style.css         # Custom animations and styling overrides
└── src/
    └── images/       # High-resolution hero and promotional product image assets
```

---

## 🚀 Getting Started

### Prerequisites

No special backend server or build steps are required. The project uses standard web technologies and browser-native ESM/CDN inclusions for dependencies.

### Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Bedru-Mekiyu/apple-clone.git
   cd apple-clone
   ```

2. **Open in browser**:
   - Double-click `index.html` to open directly in any modern web browser.
   - Or serve using any static server tool (e.g., Live Server extension in VS Code, Python HTTP server, or `npx serve`):
     ```bash
     python3 -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser.

---

## 📜 License

This project is open-source and available for educational and portfolio presentation purposes. Apple trademarked assets and brand images belong strictly to Apple Inc.
