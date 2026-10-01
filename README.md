# Adam Hussein — Creative Developer & Digital Creator Portfolio

> **High-performance, reactive portfolio platform and Content Management System tailored for Adam Hussein.**

A modern portfolio website built with React 19, TypeScript, Vite, Tailwind CSS, and Node.js. Features fluid micro-interactions, dark/light theme switching, full CMS dashboard capabilities, and instant publishing.

---

## ✨ Features

- **Personalized Identity**: Dedicated showcase for **Adam Hussein** (`adamhussein0215@gmail.com` / `01210278246`).
- **Dark Aesthetic & Dynamic Themes**: Rich obsidian color palette with smooth theme switcher (Dark, Light, System) and instant primary color accent controls.
- **Embedded CMS Dashboard**: Client-side and server-backed management of case studies, skills, services, testimonials, and portfolio settings.
- **Social Integration**: Connected profiles for Facebook, GitHub, and direct communication channels.
- **Contact Inquiries**: Interactive contact form with honeypot spam protection and instant dashboard notifications.
- **Modern Performance**: Zero latency initial load with custom vector SVG branding, high-DPI squircle monograms, and optimized static bundling.

---

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS, Lucide Icons, Canvas Confetti
- **Build System**: Vite 6, Esbuild
- **Backend / API**: Node.js, Express, TypeScript (TSX)
- **Data Persistence**: JSON Document Database with in-memory caching and real-time disk persistence

---

## 🚀 Getting Started

### 1. Installation

```bash
git clone https://github.com/omarmhmdfwzi22-hacker/adam-portifilio.git
cd adam-portifilio
npm install
```

### 2. Development Mode

```bash
npm run dev
```

Visit `http://localhost:3000` (or the configured `PORT`).

### 3. Production Build & Test

```bash
# Build the optimized production bundle
npm run build

# Run automated integration tests
npm test

# Start the production server
npm start
```

---

## 📁 Project Structure

```text
├── src/
│   ├── components/       # Reusable UI components & layouts (Navbar, Footer, GlassCard)
│   ├── pages/            # Public showcase & administrative dashboard views
│   ├── services/         # API services, local CMS store, static fallbacks
│   ├── server/           # Database engine & seed data
│   └── types/            # TypeScript type contracts
├── public/               # Static assets, modern SVG & PNG favicons, portrait artwork
├── dist/                 # Compiled production distribution
├── tests/                # Automated platform verification suite
├── server.ts             # Express & Vite backend server
└── index.html            # Main HTML document with pre-hydration brand loader
```

---

## 📄 License

MIT License. Designed and engineered for **Adam Hussein**.
