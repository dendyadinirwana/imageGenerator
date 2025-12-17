# 🎨 PortraitGen.AI

AI-powered portrait generator with interactive 3D head pose control and comprehensive camera settings.

![PortraitGen.AI](https://img.shields.io/badge/AI-Portrait%20Generator-8B5CF6?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-3D%20Control-000000?style=for-the-badge&logo=three.js)
![Puter.js](https://img.shields.io/badge/Puter.js-Free%20API-yellow?style=for-the-badge)
![Version](https://img.shields.io/badge/version-0.2-00ffff?style=for-the-badge)

## ✨ Features

### 🎭 3D Head Pose Control
- **Interactive Three.js visualizer** - Drag to rotate the head in real-time
- **3D Grid Floor** - Cyan grid lines for enhanced depth perception
- **Precise degree display** - Shows exact yaw and pitch values
- **Premium particle-based rendering** - Modern glow effect with realistic head model
- **ES6 Module Support** - Upgraded Three.js with proper GLTFLoader implementation

### 📷 Camera Controls
| Control | Range | Description |
|---------|-------|-------------|
| **Rotation (Orbit)** | -180° to +180° | Camera position around the subject |
| **Distance (Zoom)** | 5 levels | Extreme close-up to wide shot |
| **Vertical Angle** | 5 levels | Worm's eye to bird's eye view |
| **Lens Type** | 14mm - 135mm | Ultra wide to telephoto |

### 🎨 Art Styles
Choose from 10 different artistic styles:
- 📷 **Photorealistic** - Hyperrealistic DSLR quality
- 🎌 **Anime** - Studio Ghibli/MAPPA inspired
- ✨ **3D Pixar** - Disney animation style
- 🎨 **Digital Art** - Painterly ArtStation quality
- 🖌️ **Concept Art** - Game/film character design
- 🦸 **Cartoon** - Western animation style
- 👾 **Pixel Art** - Retro 16-bit aesthetic
- 🎬 **Cinematic** - Movie-like dramatic shots
- 🌃 **Cyberpunk** - Neon sci-fi atmosphere
- 🖼️ **Oil Painting** - Classical renaissance style

### 🤖 AI Models
Multiple AI models supported via Puter.js:
- GPT Image 1 (Recommended)
- DALL-E 3
- Gemini Flash
- FLUX.1 Schnell

## 🆕 What's New in v0.2

### Visual Enhancements
- ✅ **3D Grid Background** - Custom LineSegments grid with cyan lines for better depth perception
- ✅ **Deep Sea Twilight Palette** - Cohesive color scheme (#0C1821, #1B2A41, #324A5F, #42E3F5, #00ffff)
- ✅ **Enhanced Generate Button** - Prominent 52px height button with card color (#0C1821) and hover effect (#1B2A41)
- ✅ **Improved Visual Hierarchy** - Better contrast and readability throughout the UI

### Technical Improvements
- ✅ **Three.js ES6 Modules** - Upgraded from deprecated examples/js to modern importmap system
- ✅ **Fixed GLTFLoader** - Proper module-based imports for 3D model loading
- ✅ **Custom Grid Implementation** - LineSegments-based grid with fog disabled for consistent visibility
- ✅ **Better Performance** - Optimized rendering and material updates

## 🚀 Quick Start

### Option 1: Run Locally
```bash
# Clone the repository
git clone https://github.com/dendyadinirwana/imageGenerator.git
cd imageGenerator

# Start a local server
python3 -m http.server 8000

# Open in browser
open http://localhost:8000
```

### Option 2: GitHub Pages
Visit the live demo at: `https://dendyadinirwana.github.io/imageGenerator/`

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Tailwind CSS), Vanilla JavaScript
- **3D Graphics**: Three.js (r160) with ES6 modules
- **AI API**: Puter.js (Free, no API key required)
- **Icons**: Lucide Icons
- **Font**: Inter (Google Fonts)

## 📋 How It Works

1. **Enter Subject** - Describe your character (e.g., "A cyberpunk samurai")
2. **Choose Art Style** - Select from 10 artistic styles
3. **Adjust Head Pose** - Drag the 3D head to set orientation (watch the cyan grid for depth!)
4. **Configure Camera** - Set rotation, distance, angle, and lens
5. **Generate** - Click the prominent button to create your AI portrait

The app generates a detailed prompt combining:
- Subject description
- Head pose & gaze direction (with exact degrees)
- Camera settings (position, framing, angle, lens)
- Art style specifications

## 🎯 Changelog

### Version 0.2 (2025-12-17)
- Added 3D grid lines for enhanced depth perception
- Upgraded Three.js to ES6 module system
- Fixed GLTFLoader compatibility issues
- Enhanced UI with Deep Sea Twilight color palette
- Redesigned Generate button for better visibility
- Improved overall visual hierarchy

### Version 0.1 (Initial Release)
- Interactive 3D head pose control
- 10 art style presets
- Comprehensive camera controls
- Multi-model AI support

## 📄 License

MIT License - Feel free to use and modify!

## 🙏 Credits

- **Puter.js** - Free AI API
- **Three.js** - 3D graphics library
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide Icons** - Beautiful icon set

---

Made with ❤️ by [Dendy Adi Nirwana](https://github.com/dendyadinirwana)
