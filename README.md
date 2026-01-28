<div align="center">
 

  <div>
    <img src="https://img.shields.io/badge/-React-58C4DC?style=for-the-badge&logo=React&logoColor=white" />
    <img src="https://img.shields.io/badge/-GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />
    <img src="https://img.shields.io/badge/-Three.js-27136A?style=for-the-badge&logo=three.js&logoColor=white" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
    <img src="https://img.shields.io/badge/-Zustand-433E38?style=for-the-badge&logo=react&logoColor=white" />
  </div>

  <h3 align="center">Apple MacBook Landing Page</h3>

   <div align="center">
     A stunning recreation of Apple's premium product showcase featuring immersive 3D graphics, scroll-driven animations, and interactive experiences built with modern web technologies.
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🎯 [Introduction](#introduction)
2. ⚡ [Tech Stack](#tech-stack)
3. ✨ [Features](#features)
4. 🚀 [Quick Start](#quick-start)
5. 📦 [Project Structure](#structure)
6. 🎨 [Key Implementations](#implementations)
7. 🤝 [Contributing](#contributing)
8. 📄 [License](#license)

## <a name="introduction">🎯 Introduction</a>

This project is a modern, Apple-inspired landing page that showcases the power of combining React, Three.js, and GSAP to create immersive web experiences. Built following best practices for performance and user experience, it demonstrates advanced techniques in 3D rendering, scroll-based animations, and responsive design.

### Why This Project?

- **Learn Advanced Web Technologies**: Master the integration of 3D graphics with modern React patterns
- **Study Premium UI/UX**: Understand how companies like Apple create engaging, scroll-driven experiences
- **Production-Ready Code**: Well-structured, maintainable codebase suitable for real-world projects
- **Performance Optimization**: Techniques for handling complex animations without sacrificing speed

## <a name="tech-stack">⚡ Tech Stack</a>

### Core Technologies

- **[React 18](https://react.dev/)** - Component-based UI library with hooks and modern patterns
- **[Vite](https://vitejs.dev/)** - Lightning-fast build tool with HMR for instant feedback
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework for rapid UI development

### 3D & Animation

- **[Three.js](https://threejs.org/)** - WebGL library for creating and rendering 3D scenes
- **[GSAP](https://gsap.com/)** - Professional-grade animation library with ScrollTrigger
- **[Zustand](https://zustand-demo.pmnd.rs/)** - Lightweight state management for 3D scene control


## <a name="features">✨ Features</a>

### 🎭 3D Product Showcase
Photorealistic 3D MacBook model with dynamic lighting, materials, and camera controls. Explore products from every angle with smooth, intuitive interactions.

### 📜 Scroll-Driven Animations
Advanced GSAP ScrollTrigger implementations that synchronize 3D transformations, section reveals, and content animations with user scroll position.

### 🎬 Pinned Sections
Sophisticated section pinning that keeps content in viewport while animating internal elements, creating cinematic storytelling experiences.

### 🖼️ Image Masking Effects
Creative use of clip-path and mask animations triggered by scroll events for dramatic visual transitions.

### 🎨 Seamless Timelines
Multi-section animation sequences that flow smoothly across different viewport segments, maintaining visual continuity.

### 📱 Responsive Design
Fully adaptive layouts with breakpoint-specific animations ensuring perfect experiences on desktop, tablet, and mobile devices.

### ⚡ Performance Optimized
- Lazy loading for 3D assets
- Efficient render loops with requestAnimationFrame
- Debounced scroll handlers
- Optimized texture compression

### 🎯 Additional Features
- Custom video playback synchronized with scroll
- Interactive carousel with custom controls
- Smooth page transitions
- Accessibility-focused interactions
- SEO-optimized structure

## <a name="quick-start">🚀 Quick Start</a>

### Prerequisites

Ensure you have the following installed:

- **[Git](https://git-scm.com/)** - Version control system
- **[Node.js](https://nodejs.org/en)** (v18 or higher) - JavaScript runtime
- **[npm](https://www.npmjs.com/)** or **[yarn](https://yarnpkg.com/)** - Package manager

### Installation Steps

1. **Clone the repository**

```bash
git clone https://github.com/adrianhajdin/gsap_macbook_landing.git
cd gsap_macbook_landing
```

2. **Install dependencies**

```bash
npm install
# or
yarn install
```

3. **Start the development server**

```bash
npm run dev
# or
yarn dev
```

4. **Open your browser**

Navigate to [http://localhost:5173](http://localhost:5173) to see the project in action.

### Build for Production

```bash
npm run build
# or
yarn build
```

The optimized build will be available in the `dist` directory.

### Preview Production Build

```bash
npm run preview
# or
yarn preview
```

## <a name="structure">📦 Project Structure</a>

```
gsap_macbook_landing/
├── public/
│   ├── readme/           # README assets
│   └── models/          # 3D model files
├── src/
│   ├── components/      # React components
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   ├── store/          # Zustand state management
│   ├── styles/         # Global styles
│   ├── App.jsx         # Main application component
│   └── main.jsx        # Application entry point
├── index.html          # HTML template
├── vite.config.js      # Vite configuration
├── tailwind.config.js  # Tailwind CSS configuration
└── package.json        # Project dependencies
```

## <a name="implementations">🎨 Key Implementations</a>

### 3D Scene Setup with Three.js

The project uses Three.js to create an immersive 3D product showcase:

- **Scene composition** with cameras, lights, and 3D models
- **PBR materials** for photorealistic rendering
- **OrbitControls** for interactive camera movement
- **Responsive canvas** that adapts to viewport changes

### GSAP ScrollTrigger Integration

Advanced scroll-based animations using GSAP:

- **Section pinning** for narrative control
- **Scrub animations** synced to scroll position
- **Timeline orchestration** across multiple elements
- **Marker debugging** for development precision

### State Management with Zustand

Lightweight, efficient state management for:

- 3D model configurations
- Animation states
- User preferences
- Viewport dimensions

### Performance Optimization Techniques

- **Debounced scroll handlers** to reduce computation
- **Intersection Observer** for lazy loading
- **Asset preloading** for smooth initial experience
- **Code splitting** for faster initial load
