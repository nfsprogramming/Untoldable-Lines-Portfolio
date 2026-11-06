# Untoldable Lines

*Giving voice to the silence between the lines.*

An evocative, minimalist poetry and creative works showcase web application built with React, Vite, and Framer Motion. Featuring cinematic dark aesthetics, smooth scroll-driven parallax effects, and curated visual poetry cards.

[![Live Demo](https://img.shields.io/badge/Demo-untoldablelines.vercel.app-d4af37?style=flat-square)](https://untoldablelines.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 🌐 Live Website

Experience the live deployment at [untoldablelines.vercel.app](https://untoldablelines.vercel.app).

---

## ✨ Features

- **Cinematic Parallax Hero**: Smooth scroll transformations and subtle entrance animations powered by Framer Motion (`useScroll` & `useTransform`).
- **Poetry & Works Gallery**: Responsive visual grid presenting four selected poetry pieces (*Silent Echoes*, *Fading Light*, *The Unseen*, *Eternal Loop*) with smooth hover zoom effects.
- **Curated Editorial Aesthetics**: Dark palette (`#0a0a0a`), warm gold accents (`#d4af37`), and classic editorial typography (*Playfair Display* & *Lato* via Google Fonts).
- **Responsive Navigation**: Adaptive desktop header and animated full-screen mobile menu drawer with `AnimatePresence`.
- **Direct Engagement**: Direct social connect links for Instagram and WhatsApp.

---

## 🛠️ Tech Stack

- **Framework**: [React](https://react.dev/) 18 (SPA)
- **Build Tool & Dev Server**: [Vite](https://vitejs.dev/) 5
- **Animations & Transitions**: [Framer Motion](https://www.framer.com/motion/) 10
- **Iconography**: [Lucide React](https://lucide.dev/)
- **Styling**: Vanilla CSS3 with custom properties and responsive media queries
- **Code Quality**: [ESLint](https://eslint.org/) 8 with `eslint-plugin-react` and `eslint-plugin-react-hooks`

---

## 📁 Project Structure

```text
Untoldable Lines/
├── public/                  # Static assets served at root
│   ├── logo.jpg             # Hero visual & avatar artwork
│   ├── logo.png             # Site favicon
│   ├── work1.jpg            # "Silent Echoes" artwork
│   ├── work2.jpg            # "Fading Light" artwork
│   ├── work3.jpg            # "The Unseen" artwork
│   └── work4.jpg            # "Eternal Loop" artwork
├── src/
│   ├── App.jsx              # Main application component & sections
│   ├── index.css            # Design tokens, typography & responsive styles
│   └── main.jsx             # React DOM root entry point
├── .eslintrc.cjs            # ESLint rules and plugins configuration
├── .gitignore               # Ignored build outputs, caches, and system files
├── index.html               # HTML5 entry template & Google Fonts preconnect
├── LICENSE                  # MIT License
├── package.json             # Project manifest, dependencies, and scripts
├── package-lock.json        # Deterministic dependency lockfile
└── vite.config.js           # Vite bundler configuration
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18.x or later recommended; verified on Node v20/v22/v26)
- [npm](https://www.npmjs.com/) (bundled with Node.js)

### Installation

Clone the repository and install dependencies using `npm ci`:

```bash
git clone https://github.com/nfsprogramming/Untoldable-Lines-Portfolio.git
cd Untoldable-Lines-Portfolio
npm ci
```

### Running Locally

Start the Vite development server with Hot Module Replacement (HMR):

```bash
npm run dev
```

Open your browser at `http://localhost:5173` (or the port displayed in your terminal).

---

## 📜 Available Scripts

| Command | Description |
| :--- | :--- |
| `npm run dev` | Starts the Vite local development server with HMR. |
| `npm run build` | Bundles and optimizes production-ready assets into the `dist/` directory. |
| `npm run preview` | Locally serves the production `dist/` build for verification. |
| `npm run lint` | Runs ESLint across `.js` and `.jsx` files to enforce code style and syntax rules. |

---

## 🧪 Testing & Code Quality

- **Linting**: Run `npm run lint` to execute ESLint with zero-warning enforcement.
- **Production Verification**: Run `npm run build` to verify module bundling, CSS minification, and chunk integrity.
- **Test Runner**: No automated unit test runner (Vitest/Jest) is currently configured for this UI presentation project.

---

## 📦 Production Builds & Releases

To compile the production build:

```bash
npm run build
```

The output is written to `dist/`, containing minified HTML, CSS, JavaScript chunks, and static assets.

Pre-packaged release archives and source code releases are published on GitHub:
👉 [Download Latest Release](https://github.com/nfsprogramming/Untoldable-Lines-Portfolio/releases)

---

## ⚠️ Known Limitations

- **Static Content**: Works and poetry excerpts are currently defined statically in `src/App.jsx` rather than fetched from a headless CMS or database.
- **Contact Actions**: Instagram and WhatsApp links route directly to active channels; the email button is currently an anchor placeholder (`#`).

---

## 🤝 Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/poetic-enhancement`).
3. Commit your changes (`git commit -m "Add new poetry showcase feature"`).
4. Verify code quality (`npm run lint` and `npm run build`).
5. Push to the branch (`git push origin feature/poetic-enhancement`).
6. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
Copyright (c) 2026 NFS Programming.
