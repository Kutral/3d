# Kutraleeswaran B - 3D Interactive Portfolio

An immersive 3D portfolio experience featuring a retro computer setup with an interactive monitor displaying my professional work and experience.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![Built with Three.js](https://img.shields.io/badge/Built%20with-Three.js-black)
![React](https://img.shields.io/badge/React-17.0.2-blue)

## 🌐 Live Demo

**Visit:** [https://kutral.github.io/3d/](https://kutral.github.io/3d/)

## ✨ Features

- **3D Environment**: Fully interactive 3D scene built with Three.js
- **Retro Computer Model**: Detailed 3D computer model with working monitor
- **OS Interface**: Embedded retro OS-style portfolio interface
- **Smooth Animations**: Camera controls and smooth transitions using GSAP
- **Responsive Design**: Works on desktop and mobile devices
- **Loading Screen**: Custom BIOS-style loading animation

## 👨‍💻 About Me

**Kutraleeswaran B**  
Computer Science & Engineering Graduate

I'm a passionate developer currently working as an Incubation Intern at Zoho School for Graduate Studies. This portfolio showcases my journey in software development, from web applications to automated testing frameworks.

### Quick Stats
- 🎓 B.Tech in CSE (CGPA: 8.18)
- 💼 Incubation Intern at Zoho School for Graduate Studies
- 🏅 6 Professional Certifications (Cisco, NVIDIA, AWS)
- 💻 3 Major Projects (Portfolio, Testing Framework, Voting System)

## 🛠️ Tech Stack

### 3D & Graphics
- **Three.js** - 3D rendering engine
- **React Three Fiber** - React renderer for Three.js
- **GSAP** - High-performance animations
- **Camera Controls** - Interactive 3D navigation

### Frontend
- **React** - UI framework
- **TypeScript** - Type safety
- **Framer Motion** - UI animations
- **Webpack** - Module bundler

### Deployment
- **GitHub Pages** - Hosting
- **gh-pages** - Automated deployment

## 📦 Project Structure

```
portfolio-website-master/
├── src/
│   ├── Application/
│   │   ├── World/          # 3D scene components
│   │   │   ├── MonitorScreen.ts    # Monitor iframe logic
│   │   │   └── ...
│   │   ├── UI/             # React UI components
│   │   └── ...
│   ├── script.ts           # Entry point
│   └── index.html
├── static/                 # 3D models, textures, assets
├── bundler/                # Webpack configuration
└── public/                 # Build output
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

The site will be available at `http://localhost:8081/`

### Building for Production

```bash
# Build the project
npm run build

# Deploy to GitHub Pages
npm run deploy
```

## 🎨 Customization

The 3D monitor loads the OS interface from:
```typescript
// src/Application/World/MonitorScreen.ts
iframe.src = 'https://kutral.github.io/3d-OS/';
```

To customize:
1. Update the iframe URL to point to your OS interface
2. Modify 3D models in `/static/models/`
3. Adjust textures in `/static/textures/`
4. Customize UI components in `/src/Application/UI/`

## 📂 Related Repositories

- **OS Interface:** [github.com/Kutral/3d-OS](https://github.com/Kutral/3d-OS)
- **Live OS Site:** [kutral.github.io/3d-OS](https://kutral.github.io/3d-OS/)

## 🎯 Key Achievements

- ✅ Fully functional 3D interactive portfolio
- ✅ Embedded OS-style interface with routing
- ✅ Smooth camera animations and controls
- ✅ Responsive design for all devices
- ✅ Automated deployment pipeline

## 📞 Contact

- **Email:** kutraleeswaran2003@gmail.com
- **Phone:** +91-9597581629
- **GitHub:** [github.com/kutral](https://github.com/kutral)
- **LinkedIn:** [linkedin.com/in/kutraleeswaranb](https://linkedin.com/in/kutraleeswaranb/)

## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Original design inspiration from Henry Heffernan
- 3D models and textures from open-source libraries
- Community support from Three.js and React communities

---

**Built with ❤️ by Kutraleeswaran B**

*If you like this project, please give it a ⭐!*
