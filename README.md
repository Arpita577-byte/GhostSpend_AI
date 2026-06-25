

# 👻 GhostSpend AI

### Enterprise Profit Recovery Platform · Powered by Groq LLM · Zero-Knowledge Architecture

[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![Groq](https://img.shields.io/badge/Groq-LLM-FF6C37?style=for-the-badge)](https://console.groq.com/)
[![Vercel](https://img.shields.io/badge/Vercel-Deployed-000000?style=for-the-badge&logo=vercel)](https://vercel.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

<br/>

> **Every enterprise leaks money silently.**  
> Zombie subscriptions. Duplicate vendor contracts. Missed SLA penalties. Cloud waste.  
> **GhostSpend AI hunts them all — and claws the money back.**

</div>

---

## 📌 Table of Contents

- [What is GhostSpend AI?](#-what-is-ghostspend-ai)
- [Live Demo](#-live-demo)
- [Key Features](#-key-features)
- [How It Works](#-how-it-works)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Deploy to Vercel](#-deploy-to-vercel)
- [AI Engine Details](#-ai-engine-details)
- [Roadmap](#️-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🚀 What is GhostSpend AI?

**GhostSpend AI** is the world's first **Autonomous Cost-Recovery Platform** built for enterprises. It deploys a 4-Agent LLM swarm powered by Groq to automatically detect and recover hidden financial leaks across your operations — in under 60 seconds.

Simply upload your operational CSV → the AI decodes it instantly → savings surface automatically.

No manual audits. No consultants. No waiting.

---

## 🎯 Live Demo

> 🔗 **[ghostspend-ai.vercel.app](https://vercel.com)** *(replace with your live URL)*

No API key? No problem — the platform runs a **high-fidelity demo simulation** out of the box with realistic audit results across all 4 agent categories.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🤖 **4-Agent AI Swarm** | Spend Intelligence, SLA Prevention, Resource Optimization, and FinOps agents run in parallel |
| 🔒 **Zero-Knowledge Vault** | All PII is scrubbed locally in-browser — your raw data never leaves your device |
| 📉 **OHLC Candlestick Charts** | Stock-market style financial variance visualization powered by Recharts |
| ✉️ **Sentinel Negotiation Mode** | Auto-generates legally-sound vendor penalty deduction letters |
| 🐍 **Offline Local Auditor** | Export a downloadable Python script for air-gapped / on-premise environments |
| ⚡ **Groq-Powered Speed** | Full enterprise audit completed in under 60 seconds via Llama-3 8B |
| 🎨 **Glassmorphic Dark UI** | Obsidian dark theme with Framer Motion animations for a premium experience |
| 🧩 **4-Step Onboarding** | Industry and company setup flow before the audit begins |

---

## 🧠 How It Works

```
┌─────────────┐     ┌─────────────┐     ┌──────────────────────┐     ┌────────────────────┐
│  1. INGEST  │ --> │  2. SCRUB   │ --> │     3. HUNT          │ --> │   4. CLAWBACK      │
│             │     │             │     │                      │     │                    │
│ Upload raw  │     │ PII stripped│     │ 4 Groq AI agents     │     │ Sentinel generates │
│ ops CSVs    │     │ locally in  │     │ cross-reference data │     │ vendor deduction   │
│ (AWS, SaaS, │     │ browser     │     │ against market       │     │ notices &          │
│ vendor SLA) │     │ before AI   │     │ baselines            │     │ cancellation       │
│             │     │ processes   │     │                      │     │ letters            │
└─────────────┘     └─────────────┘     └──────────────────────┘     └────────────────────┘
```

### The 4 AI Agents

| Agent | Responsibility |
|---|---|
| 🔍 **Spend Intelligence Agent** | Detects zombie subscriptions and duplicate vendor billing |
| 📋 **SLA Prevention Agent** | Identifies missed SLA clauses eligible for penalty recovery |
| ☁️ **Resource Optimization Agent** | Surfaces cloud waste and over-provisioned infrastructure |
| 💰 **FinOps Agent** | Benchmarks spend against market rates and flags anomalies |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React 18, TypeScript |
| **Build Tool** | Vite 5 |
| **Styling** | Styled-Components (Glassmorphic Obsidian Dark theme) |
| **Animations** | Framer Motion |
| **Charts** | Recharts (Custom OHLC Candlestick Renderer) |
| **AI Engine** | Groq API — `llama3-8b-8192` model |
| **Security** | In-browser PII scrubbing + cryptographic hashing |
| **Hosting** | Vercel |

---

## 📁 Project Structure

```
GhostSpend_AI/
├── public/                     # Static assets
├── src/
│   ├── components/
│   │   ├── animations/         # IntroScreen with particle effects
│   │   ├── charts/             # ObsidianAnalyticsChart (OHLC candlesticks)
│   │   ├── layout/             # Dashboard, Login, UploadView, SetupIndustry, SetupCompany
│   │   ├── tabs/               # AnalysisTab, SentinelTab
│   │   └── ui/                 # PredictivePulse top bar animation
│   ├── utils/
│   │   ├── aiCore.ts           # 4-Agent orchestration + Groq API client
│   │   ├── security.ts         # PII scrubbing + cryptographic hashing
│   │   └── exportScript.ts     # Python offline auditor generator
│   └── App.tsx                 # 4-step onboarding flow
├── index.html
├── vite.config.ts
├── tsconfig.json
└── package.json
```

---

## 🏁 Getting Started

### Prerequisites

- **Node.js** v18 or higher
- **npm** v9 or higher
- A free [Groq API key](https://console.groq.com) *(optional — demo mode works without one)*

### 1. Clone the Repository

```bash
git clone https://github.com/Arpita577-byte/GhostSpend_AI.git
cd GhostSpend_AI
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root of the project:

```env
VITE_GROQ_API_KEY=your_groq_api_key_here
VITE_GEMINI_API_KEY=your_gemini_api_key_here   # optional
```

> 🔑 Get a free Groq API key at [console.groq.com](https://console.groq.com)

### 4. Start the Development Server

```bash
npm run dev
```

Open **http://localhost:5173** in your browser.

### 5. Build for Production

```bash
npm run build
```

---

## 🔐 Environment Variables

| Variable | Required | Description |
|---|---|---|
| `VITE_GROQ_API_KEY` | Recommended | Groq API key for live AI audit mode |
| `VITE_GEMINI_API_KEY` | Optional | Gemini API key for extended AI features |

> ⚠️ **Never commit your `.env` file.** It is already included in `.gitignore`.

---

## 🌐 Deploy to Vercel

Deploying GhostSpend AI takes under 2 minutes:

1. Push your fork to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project** → Import your repository
3. Add environment variables under **Settings → Environment Variables**:
   - `VITE_GROQ_API_KEY` = `your_groq_api_key_here`
4. Click **Deploy** — Vite is auto-detected, no config needed

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

---

## 🤖 AI Engine Details

### With Groq API Key (Live Mode)

- Your CSV content is passed to `llama3-8b-8192` via the Groq API
- The model acts as a 4-agent orchestrator and returns a structured JSON audit
- KPI cards reflect real AI-detected findings with specific dollar amounts

### Without API Key (Demo Mode)

- A high-fidelity local simulation engine activates automatically
- Generates realistic 5-leak findings across all 4 agent categories
- Full UI experience — perfect for stakeholder demos or offline use

### Security Architecture

- All PII (names, emails, account numbers) is stripped **locally in the browser** via `security.ts` before any data is sent to the AI
- Cryptographic hashing is applied to sensitive identifiers
- No raw operational data is ever transmitted to external servers

---

## 🗺️ Roadmap

- [ ] Multi-ERP Integration (SAP, Oracle NetSuite, QuickBooks)
- [ ] Predictive Leak Forecasting via LSTM time-series model
- [ ] Procurement Autopilot — autonomous vendor renegotiation workflows
- [ ] Slack / WhatsApp / MS Teams anomaly alert integrations
- [ ] Blockchain immutable audit ledger
- [ ] **GhostScore™** — industry benchmarking index for financial hygiene

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature description"

# 4. Push to your branch
git push origin feature/your-feature-name

# 5. Open a Pull Request
```

Please follow the existing code style and include descriptive commit messages.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Built with 👻 by [Arpita577-byte](https://github.com/Arpita577-byte)

⭐ **Star this repo** if GhostSpend AI helped you recover hidden costs!

</div>
