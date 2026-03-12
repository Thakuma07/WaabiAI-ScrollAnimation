# Waabi AI - Image Scroll Animation

A premium, high-performance scroll animation project inspired by Waabi AI. This project uses **Vite** for the build tool, **GSAP** for sophisticated animations, and **Lenis** for ultra-smooth scrolling.

## ✨ Features

- **Smooth Scrolling**: Powered by [Lenis](https://github.com/darkroomengineering/lenis) for a buttery-smooth user experience.
- **Scroll-Driven Hero Transition**: The hero image dynamically resizes and transitions as the user scrolls.
- **Progressive Text Reveal**: Text elements fade in word-by-word based on scroll progress (using a custom lightweight `splitText` implementation).
- **Parallax Gallery**: Multi-column image layout with drifting parallax effects in the "About" section.
- **Responsive Design**: Fully optimized for desktop and mobile devices.

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- npm or yarn

### Installation

1. Clone or download the project.
2. Open your terminal in the project directory.
3. Install dependencies:
   ```bash
   npm install
   ```

### Development

Run the development server:
```bash
npm run dev
```
Open your browser and navigate to the local server address (usually `http://localhost:5173`).

### Production

To build for production:
```bash
npm run build
```
The optimized files will be generated in the `dist` folder.

## 🛠️ Built With

- **HTML5/CSS3**: Semantic structure and modern styling.
- **GSAP**: The GreenSock Animation Platform for core animation logic.
- **Lenis**: Smooth scroll library.
- **Vite**: Modern frontend tooling for rapid development.

## 📝 Note on SplitText
This project uses a custom `splitText` helper in `script.js` to avoid dependency on the paid GSAP SplitText plugin while maintaining a similar word-reveal effect.

---
Built with ❤️ by [thakuma.dev](https://thakuma.dev)
