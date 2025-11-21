# Ulmy AI S.R.L. - Corporate Website

This repository contains the source code for the official website of **Ulmy AI S.R.L.**, an AI transformation partner helping organizations turn generative artificial intelligence into competitive advantage.

## 🌐 Live Site
[Ulmy.AI](https://ulmy.ai/)

## 🚀 Project Overview
The website is designed to be fast, responsive, and visually engaging, utilizing modern web technologies to present Ulmy AI's services, frameworks, and mission.

### Key Features
- **Modern Aesthetic**: Glassmorphism effects, gradients, and smooth animations.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices.
- **Interactive Elements**: SVG animations and hover effects.
- **Fast Loading**: Static HTML/CSS implementation for optimal performance.

## 🛠 Technology Stack
- **HTML5**: Semantic structure.
- **Tailwind CSS**: Utility-first CSS framework (loaded via CDN for simplicity).
- **JavaScript (Vanilla)**: Lightweight interactivity (mobile menu, dynamic year).
- **SVG**: Scalable vector graphics for diagrams and icons.

## 📂 Project Structure
```
ulmy-ai.github.io/
├── index.html          # Home page
├── about.html          # About Us page
├── framework.html      # End-to-End Frameworks page
├── contact.html        # Contact page
├── styles.css          # Custom CSS overrides and animations
├── logos/              # Directory for logo assets
│   └── logo.svg
└── README.md           # Project documentation
```

## 💻 Getting Started

### Prerequisites
You don't need any complex build tools (like Node.js or Webpack) to run this project, as it uses Tailwind CSS via CDN. You just need a simple local HTTP server.

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ulmy-ai/ulmy-ai.github.io.git
   cd ulmy-ai.github.io
   ```

2. **Start a local server:**
   
   If you have Python installed (Mac/Linux/Windows):
   ```bash
   # Python 3
   python3 -m http.server 8000
   ```

   Or if you use Node.js:
   ```bash
   npx serve .
   ```

3. **View the site:**
   Open your browser and navigate to `http://localhost:8000`.

## 🎨 Design System
- **Colors**:
  - Primary Blue: `#2563EB` (Tailwind `blue-600`)
  - Dark Background: `#0F172A` (Tailwind `slate-900`)
  - Accents: Cyan, Indigo, Pink gradients.
- **Typography**:
  - Headings: `Outfit` (Google Fonts)
  - Body: `Inter` (Google Fonts)

## 📄 License
© 2024 Ulmy AI S.R.L. All rights reserved.