# Innoxel Pvt Ltd — The World Is Our Warehouse | 3D Global Trade

An interactive, cinematic 3D global logistics and commodity export web application built with **Three.js**, **WebGL**, and modern responsive CSS/JavaScript.

---

## 🌟 Key Features

1. **Fixed Three.js WebGL 3D Viewport (`#webgl-viewport-canvas`)**:
   - High-fidelity 3D Earth globe with Blue Marble realistic surface texturing (`assets/earth-blue-marble.jpg`).
   - Atmosphere and animated cloud layer (`assets/earth-clouds.jpg`).
   - Interactive orbit controls (drag to rotate the globe, zoom in/out).
   - Dynamic maritime shipping trade corridors with flowing light particles tracing global routes.
   - Interactive port pins with hover and click telemetry cards showing key commodities and logistics modes.

2. **Scroll-Driven Storytelling Timeline (0% – 100%)**:
   - **0%–20% Hero Scene**: Earth in deep space, typography (*"WE MOVE THE WORLD"*), glowing action button.
   - **20%–40% Interactive Globe & Network**: Trade corridor visualization, interactive port pins.
   - **40%–60% Logistics Network**: Ocean freight fleet, smart reefer cold chain (+4°C), and priority air cargo cards with hover micro-interactions.
   - **60%–80% 3D Products Gallery**: 40ft Reefer Container, Precision Machinery, 1121 Basmati Rice, and Electronics Freight with interactive 3D specs modal dialogs.
   - **80%–100% Cinematic Shipment Simulation**: Origin and destination route selector, real-time telemetry HUD (*Origin Hub*, *Logistics Mode*, *Discharge Port*, *Voyage Status*), and voyage launch animation.
   - **Resources & Export Intelligence**: APEDA AgriExchange, DFPD, IBEF, Agmarknet, and compliance portals.

3. **UI / UX & Animations**:
   - Dark glassmorphism (`backdrop-filter: blur(24px)`), hairline borders (`rgba(255, 255, 255, 0.08)`).
   - Google Fonts: **Outfit** (headings), **Plus Jakarta Sans** (body), and **JetBrains Mono** (HUD & pills).
   - Right-side vertical dot navigation synchronizing with scroll position.
   - Interactive modal sheets for commercial inquiries and cargo specifications.

---

## 📁 Project Structure

```
Ra Export Website/
├── assets/
│   ├── index-BMwJKa5h.css          # Core styles, glassmorphism, responsive grid, animations
│   ├── index-CvxV1eMx.js           # Three.js 3D WebGL engine, camera controller, interactions
│   ├── earth-blue-marble.jpg       # Earth 3D surface texture map
│   └── earth-clouds.jpg            # Earth 3D atmospheric cloud texture map
├── favicon.png                     # Browser favicon
├── innoxel-logo-dark.png           # High-resolution brand logo (dark variant)
├── innoxel-logo-original.jpg       # High-resolution brand logo fallback
├── index.html                      # Main entry HTML document
├── package.json                    # Development and preview server scripts
└── README.md                       # Documentation
```

---

## 🚀 How to Run Locally

Because the project uses **Three.js WebGL textures** and **ES modules** (`<script type="module">`), modern browsers require an HTTP server rather than opening `file:///` directly.

### Option 1: Using npm (recommended)
```bash
npm start
```
Then open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 2: Using Python
```bash
python -m http.server 3000
```
Then open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 3: Using VS Code Live Server
Right-click `index.html` in VS Code and select **"Open with Live Server"**.

---

## 🌐 Deployment

This website is a static WebGL application. You can deploy it instantly to:
- **Netlify**: Drag and drop the folder into the Netlify dashboard or link to your Git repository.
- **Vercel**: Run `vercel` or connect your repository.
- **GitHub Pages**: Push to a repository and enable GitHub Pages in repository settings.

