# 🌊 Viz-Tsubuyaki

*A live, interactive mathematical visualization inspired by the art of code-golf creativity*

## ✨ Overview

Viz-Tsubuyaki (つぶやき Processing - "Tweet Processing") is an immersive mathematical art experience that transforms complex equations into flowing, organic visualizations. Inspired by the Japanese Twitter/X challenge where creators craft full p5.js sketches in 280 characters, this project expands on that creative constraint to create an endless dance of mathematical beauty. Built with p5.js, it renders real-time mathematical patterns that respond to user interactions.

## 🎨 Features

- **Real-time Mathematical Rendering**: Live visualization of complex mathematical functions with adaptive resolution
- **Interactive Parameter Control**: Gesture-based control system with drag interactions for real-time parameter adjustment
- **Organic Flow Dynamics**: Natural, fluid mathematical patterns that evolve continuously
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Preset Configurations**: Pre-built parameter sets for different visual styles (Organic, Fluid, Crystalline, Chaotic)
- **Ultra-Transparent UI**: 90% transparent control panels that don't obstruct the visualization
- **Pan & Zoom Navigation**: Explore the mathematical landscape with smooth navigation controls

## 🚀 Live Demo

Visit the live app: **[https://viz-tsubuyaki.vercel.app/](https://viz-tsubuyaki.vercel.app/)**

## 🎛️ Controls

### Desktop
- **Mouse**: Drag to pan the visualization
- **Scroll**: Zoom in/out
- **Control Panel**: Click the settings icon to access parameter controls
- **Keyboard Shortcuts**:
  - Arrow keys: Navigate
  - `+`/`-`: Zoom
  - `R`: Reset position and time
  - `F`: Toggle fullscreen
  - `C`: Toggle control panel

### Mobile
- **Touch & Drag**: Pan the visualization
- **Pinch**: Zoom in/out
- **Control Tray**: Tap the control button to access parameter sections
- **Gesture Controls**: Drag parameter sliders to adjust values in real-time

## 🔧 Parameter Sections

### Flow Dynamics 🌬️
- **Time Speed**: Controls animation speed
- **Flow Direction**: Forward/reverse flow direction
- **Turbulence**: Adds chaotic elements to the flow

### Organic Growth 🌱
- **Growth Amplitude**: Scale of growth patterns
- **Branch Frequency**: Density of branching structures
- **Spreading Factor**: How patterns spread across space

### Resonance & Harmonics 📻
- **Harmonic Strength**: Intensity of harmonic frequencies
- **Resonance Intensity**: Feedback strength in the system
- **Wave Complexity**: Detail level of wave patterns

### Visual Effects ✨
- **Radial Scale**: Size of radial components
- **Vertical Stretch**: Vertical scaling of patterns
- **Center Offset**: Displacement from center point

## 🧮 Mathematical Foundation

The visualization is based on a complex mathematical function that combines:

```javascript
// Core mathematical function
let k = (amplitude + sin(y * 2 - t) * turbulence) * cos(x / frequency);
let e = y / spreading - centerOffset;
let d = sqrt(k * k + e * e);
let c = d - t;

// Enhanced detail calculation
let detailTerm = sin(y / complexity) * k * (9 + 4 * sin(e * 9 - d * 3 + t * 2));
let q = harmonicStrength * sin(k * 2) + resonance / (k + 0.01) + detailTerm;

// Final coordinates
let pointX = q + radialScale * cos(c);
let pointY = q * sin(c) + d * verticalStretch;
```

## 🛠️ Technology Stack

- **p5.js**: Core graphics and animation engine
- **Phosphor Icons**: Modern icon set for UI elements
- **CSS3**: Advanced styling with backdrop-filter effects
- **Vanilla JavaScript**: Pure JS for optimal performance
- **HTML5 Canvas**: Hardware-accelerated rendering

## 📁 Project Structure

```
viz-tsubuyaki/
├── public/
│   └── index.html          # Main application file
├── README.md               # Project documentation
└── .git/                   # Git repository
```

The `public/` folder contains the deployable web application, making it easy to deploy on platforms like Vercel, Netlify, or any static hosting service.

## 🎯 Key Technical Features

- **Adaptive Resolution**: Automatically adjusts point density based on zoom level
- **Multi-layer Rendering**: Different detail passes for enhanced visual quality at high zoom
- **Touch-optimized**: Full gesture support for mobile devices
- **Performance Optimized**: Efficient rendering with up to 50,000 points
- **Responsive UI**: Ultra-transparent controls that don't interfere with the art

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone git@github.com:tanish2k/viz-tsubuyaki.git
   cd viz-tsubuyaki
   ```

2. Open `public/index.html` in your browser or serve locally:
   ```bash
   # Using Python (from project root)
   python -m http.server 8000
   
   # Using Node.js (from project root)  
   npx serve .
   
   # Or serve the public folder directly
   npx serve public
   ```

3. Visit `http://localhost:8000` (or `http://localhost:3000` if serving public folder directly)

## 🚀 Deploy to Vercel

The project is structured for easy deployment on Vercel:

1. **One-Click Deploy**: 
   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/tanish2k/viz-tsubuyaki)

2. **Manual Deploy**:
   ```bash
   npm i -g vercel
   vercel --prod
   ```
   
   Vercel will automatically detect the `public` folder and deploy the static site.

## 🎨 Mathematical Concept Presets

- **Drift** 🌊: Minimal speed, gentle motion - reveals subtle mathematical beauty through slow, contemplative patterns
- **Surge** ⚡: Maximum turbulence + growth amplitude + speed - explosive mathematical energy with chaotic complexity
- **Resonance** 📻: Harmonic strength and wave complexity maximized - structured mathematical beauty through frequency interactions
- **Vortex** 🌀: Polar transformation emphasis - circular/spiral mathematical patterns showcasing radial coordinate systems
- **Default** 🔄: Balanced parameters for general exploration and learning

## 📱 Browser Support

- Chrome/Edge: Full feature support
- Firefox: Full feature support
- Safari: Full feature support (iOS and macOS)
- Mobile browsers: Optimized touch controls

## 🤝 Contributing

Contributions are welcome! Whether it's new mathematical functions, UI improvements, or performance optimizations, feel free to open issues and pull requests.

## 📄 License

MIT License - Feel free to use this code for your own mathematical art projects!

## 🙏 Acknowledgments

- Inspired by the beauty of mathematical visualization
- Built with the powerful p5.js creative coding framework
- UI icons by Phosphor Icons

---

*Where mathematical beauty meets the art of creative constraints* ✨ 