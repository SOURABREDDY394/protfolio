# Sourab Reddy — Portfolio

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FSOURABREDDY394%2Fprotfolio)
[![GitHub Profile](https://img.shields.io/badge/GitHub-SOURABREDDY394-181717?logo=github)](https://github.com/SOURABREDDY394)
[![LinkedIn Profile](https://img.shields.io/badge/LinkedIn-Sourab%20Reddy-0A66C2?logo=linkedin)](https://www.linkedin.com/in/sourab-reddy-9b0582330)

<p align="center">
  <strong>Autonomous intelligence, engineered clean.</strong><br>
  Interactive 3D WebGL portfolio showcasing autonomous AI systems, dense RAG pipelines, and high-performance full-stack applications.
</p>

[**Explore Live Demo**](https://test-kohl-two-hsyu9gdvv0.vercel.app) · [**Report Bug**](https://github.com/SOURABREDDY394/protfolio/issues) · [**Request Feature**](https://github.com/SOURABREDDY394/protfolio/issues)

</div>

---

## 🏛️ Overview

This repository houses the personal portfolio of **Sourab Reddy**, an **AI Engineer & Full-Stack Developer** based in Hyderabad, India. 

Designed with an architectural minimalist aesthetic, the portfolio combines modern typography, high-performance WebGL 3D graphics, and tactile micro-interactions to demonstrate engineering excellence from first principles.

### 🌟 Key Design & Architectural Features

- **🗿 Monumental 3D WebGL Hero**: Custom Three.js interactive monument featuring extruded 3D stone doors with "SOURAB" and "REDDY" that seamlessly part on scroll to reveal featured engineering work.
- **🎨 Curated Tri-Tone Design System**:
  - `Ink`: Sleek, deep dark mode with vermilion spotlight accent (`#ff4a1c`).
  - `Bone`: Architectural inverted light palette.
  - `Ultra`: High-contrast dark mode with electric ultramarine accent (`#5c78ff`).
- **🎞️ Horizontal Filmstrip Chapters**: Expandable interactive project viewers with drag-to-scroll, keyboard accessibility, and dynamic frame progression tracking.
- **⚡ Zero Heavy Build Chains**: Fast, vanilla web standards with modern ESModules, import maps, custom CSS properties, and GPU-accelerated transforms.
- **🕒 Real-Time Hyderabad (IST) Clock**: Live timezone indicator with dynamic working status indicator reflecting desk availability.
- **♿ High Accessibility & Performance**: Semantic HTML5 landmarks, keyboard navigation support (`Escape` dismiss, arrow tab navigation), reduced motion detection (`prefers-reduced-motion`), and optimized asset delivery.

---

## 🚀 Featured Engineering Systems

The portfolio highlights six core production projects and open-source contributions:

| # | System | Domain | Core Tech Stack | Highlights |
|---|---|---|---|---|
| **01** | [**CareCircle AI**](https://github.com/SOURABREDDY394/Carecircle-ai) | Autonomous Blood Support Network | Python, FastAPI, React, PostgreSQL, AWS | Sub-12s emergency donor matching; Finalist in **AI For Good 2.0**. |
| **02** | [**FastRAG**](https://github.com/SOURABREDDY394/fastrag) | Multi-Document Knowledge Assistant | FastAPI, Supabase, PostgreSQL, pgvector | <180ms vector search latency with source citation and confidence scoring. |
| **03** | [**EventOS**](https://github.com/SOURABREDDY394/eventos) | AI-First Event Operations Platform | React, Supabase, Groq, Vercel, Tailwind CSS | Prompt-to-event schema generator with QR ticketing; **Top 10 Finalist in SummerShip 2026**. |
| **04** | [**RescueCart AI**](https://github.com/SOURABREDDY394/RescueCart) | Surplus Commerce & Reservation Engine | Python, FastAPI, Valkey, Docker, React | Real-time surplus inventory feed with Valkey sorted-set locks and dark Ops Center. |
| **05** | [**LaunchPilot AI**](https://github.com/SOURABREDDY394/launchpilot-ai) | Multi-Agent Founder Platform | React, FastAPI, LangChain, Gemini Pro, RAG | Orchestrates 10+ autonomous agents in a unified reactive decision graph. |
| **06** | [**Memori & Mini Load Balancer**](https://github.com/SOURABREDDY394/Memori) | Agent Infrastructure & Distributed Networking | Python, WebSockets, Redis, FastAPI, Docker | Persistent agent memory layer & custom Python load balancer with 99.99% uptime telemetry. |

### 📦 Notable Open-Source Repositories

- [**awesome-n8n-templates**](https://github.com/SOURABREDDY394/awesome-n8n-templates): 280+ free production-ready n8n workflows for AI agents, RAG chatbots, email pipelines, and DevOps automation.
- [**mini-load-balancer**](https://github.com/SOURABREDDY394/mini-load-balancer): Custom Python load balancer featuring Round Robin / Weighted distribution, active health checks, and WebSocket dashboard.
- [**hood-admin-app**](https://github.com/SOURABREDDY394/hood-admin-app): Multi-category local commerce application unifying groceries, fresh seafood, pharmacy, and essentials with WooCommerce sync.

---

## 🛠️ Tech Stack & Dependencies

- **Structure & Markup**: HTML5 (Semantic, accessible, SEO-optimized with OpenGraph tags)
- **Styling**: Vanilla CSS3 (Custom properties, grid systems, clamped fluid typography, responsive layout)
- **Scripting**: Modern ES6+ JavaScript
- **3D Graphics**: [Three.js r160](https://threejs.org/) via native ES importmap
- **Typography**: [Inter Tight](https://fonts.google.com/specimen/Inter+Tight) & [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif)
- **Hosting & Edge Delivery**: [Vercel](https://vercel.com/)

---

## 📁 Project Structure

```text
protfolio/
├── assets/
│   ├── portrait.jpg                # Sourab Reddy portrait
│   ├── project1-carecircle.jpg     # CareCircle AI previews
│   ├── project2-fastrag.jpg        # FastRAG architecture & benchmarks
│   ├── project3-eventos.jpg        # EventOS platform & QR system
│   ├── project4-hoodcommerce.jpg   # RescueCart AI & Valkey commerce
│   ├── project5-welerix.jpg        # LaunchPilot AI multi-agent graph
│   └── project6-belvo.jpg          # Memori & Load Balancer telemetry
├── .gitignore                      # Git ignore rules for node, vercel, OS
├── index.html                      # Complete standalone portfolio application
├── vercel.json                     # Vercel deployment configuration & asset caching
└── README.md                       # Comprehensive documentation
```

---

## 💻 Local Development

Because this project is built using native web standards with modern ESModules, no bundler installation or build step is required!

### Option 1: Using Python (Built-in)
```bash
# Clone the repository
git clone https://github.com/SOURABREDDY394/protfolio.git

# Navigate into the project folder
cd protfolio

# Start a local static server
python -m http.server 3000
```
Open [http://localhost:3000](http://localhost:3000) in your web browser.

### Option 2: Using Node.js / npx
```bash
# Using npx serve
npx -y serve .
```

### Option 3: VS Code Live Server
Simply install the **Live Server** extension in VS Code and click **"Go Live"** from `index.html`.

---

## 🚀 Deployment to Vercel

This project is pre-configured with `vercel.json` for immediate, zero-configuration deployment on Vercel.

### Method 1: Deploy with Vercel Web Dashboard (Recommended)

1. Push your repository to GitHub: `https://github.com/SOURABREDDY394/protfolio`
2. Go to [Vercel Dashboard](https://vercel.com/new).
3. Click **"Add New..."** -> **"Project"**.
4. Import the **`protfolio`** repository from your GitHub account.
5. Keep default settings:
   - **Framework Preset**: Other
   - **Root Directory**: `./`
   - **Build Command**: None (Static)
   - **Output Directory**: None
6. Click **"Deploy"**. Vercel will build and assign a production URL (e.g., `https://protfolio-sourabreddy.vercel.app`) with automatic SSL and continuous deployment on every git push!

### Method 2: Deploy using Vercel CLI

```bash
# Install and log in to Vercel CLI
npx vercel login

# Deploy to preview
npx vercel

# Deploy directly to production
npx vercel --prod
```

---

## 📬 Contact & Connect

- **Name**: Sourab Reddy
- **Location**: Hyderabad, India (17.38° N, 78.48° E)
- **Email**: [sourabreddimalla@gmail.com](mailto:sourabreddimalla@gmail.com)
- **Phone**: [+91 6303436418](tel:+916303436418)
- **GitHub**: [@SOURABREDDY394](https://github.com/SOURABREDDY394)
- **LinkedIn**: [sourab-reddy-9b0582330](https://www.linkedin.com/in/sourab-reddy-9b0582330)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
