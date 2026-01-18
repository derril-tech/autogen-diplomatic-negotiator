# 🌍 AI Diplomatic Negotiator
**Powered by AutoGen + OpenAI**

> **Simulate complex diplomatic negotiations with AI agents. Define parties, set constraints, and watch as role-based delegates negotiate structured agreements with comprehensive risk assessments—all in real-time.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![AutoGen](https://img.shields.io/badge/AutoGen-Multi_Agent-purple.svg)](https://microsoft.github.io/autogen/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

AI Diplomatic Negotiator is an intelligent negotiation simulation platform that uses **multi-agent AutoGen workflows** to:

1. **Simulate Negotiations** — Role-based AI agents (Diplomats, Mediators, Historians, Risk Analysts) engage in structured negotiations
2. **Real-Time Updates** — Watch negotiations unfold live with WebSocket-powered progress indicators
3. **Generate Agreements** — AI extracts structured agreement outlines with terms, timelines, and verification mechanisms
4. **Assess Risks** — Comprehensive risk analysis with categorized threats and mitigation strategies

All powered by GPT-4.1-mini with optimized prompts for diplomatic accuracy and depth.

---

## 🎯 Core Features

### 🤖 **AI-Powered Negotiation**
- **Multi-Agent System** — AutoGen orchestrates specialized role-based agents
- **Real OpenAI Integration** — GPT-4.1-mini with finely-tuned diplomatic prompts
- **Custom Agent Configs** — Create and configure custom negotiation agents
- **Smart Scenario Suggestions** — AI-generated negotiation scenarios based on current events
- **Live Progress Tracking** — Real-time WebSocket updates as negotiations unfold

### 📊 **Rich Analytics & Insights**
- **Negotiation Analytics** — Statistics, trends, and success rate tracking
- **AI-Powered Insights** — Intelligent recommendations and predictions
- **Comparison View** — Side-by-side analysis of multiple negotiations
- **Interactive Charts** — Visualize negotiation patterns and outcomes
- **Export & Sharing** — JSON/PDF export and shareable links

### 💬 **Interactive AI Assistant**
- **Context-Aware Chat** — Ask questions about negotiation results with full context
- **Intelligent Suggestions** — AI-generated follow-up questions
- **Negotiation Analysis** — Deep insights into agreements, risks, and outcomes
- **Real-Time Responses** — Fast, helpful answers powered by optimized prompts

### 🎨 **Modern UI/UX**
- **State-Driven Architecture** — Smooth transitions with React 19.2 features
- **Dark/Light Mode** — Beautiful theme with system preference support
- **Mobile-First Design** — Responsive with 44px+ touch targets and bottom navigation
- **Glassmorphic Design** — Modern visual effects with backdrop blur
- **Real-Time Indicators** — Live progress bars and status updates

### 📱 **Full Feature Set**
| Feature | Description |
|---------|-------------|
| 🎭 **Multi-Agent Negotiation** | Role-based AI delegates with distinct personalities |
| 📝 **Structured Transcripts** | Timeline view of negotiation turns with timestamps |
| 📋 **Agreement Extraction** | AI-powered structured agreement outlines |
| ⚠️ **Risk Assessment** | Categorized risks with levels and mitigations |
| 🔴 **Real-Time Updates** | WebSocket-powered live negotiation progress |
| 💬 **AI Chat Assistant** | Context-aware help and analysis |
| 📊 **Analytics Dashboard** | Statistics, charts, and trend visualization |
| 🔍 **Comparison View** | Side-by-side negotiation analysis |
| 📤 **Export & Share** | JSON/PDF export and shareable links |
| 🎯 **Smart Suggestions** | AI-generated scenario recommendations |
| 📚 **Template Library** | Save and reuse negotiation templates |
| ⚙️ **Custom Agents** | Create and configure custom negotiation roles |
| 📈 **History & Search** | Full negotiation history with filtering |
| 🎨 **Modern Design** | 2025 UI/UX standards with glassmorphism |

---

## 🏗️ Tech Stack

### **Frontend** ⚛️
| Technology | Purpose |
|------------|---------|
| **Next.js 16** | React 19.2 with App Router |
| **TypeScript** | Type-safe development |
| **Mantine** | Modern component library |
| **React 19.2** | Latest React features (useTransition, useActionState) |
| **Recharts** | Data visualization |
| **WebSockets** | Real-time communication |

### **Backend** 🐍
| Technology | Purpose |
|------------|---------|
| **FastAPI** | High-performance Python API |
| **AutoGen** | Multi-agent AI orchestration |
| **OpenAI GPT-4.1-mini** | Intelligent negotiation and analysis |
| **Pydantic v2** | Data validation |
| **WebSockets** | Real-time event streaming |

### **Data & Cache** 💾
| Technology | Purpose |
|------------|---------|
| **Supabase** | PostgreSQL persistence (RPC-only access) |
| **Upstash Redis** | Job queue, caching, and rate limiting |

### **External APIs** 🔌
| API | Purpose |
|-----|---------|
| **OpenAI** | GPT-4.1-mini for negotiations, chat, insights |
| **WebSocket** | Real-time negotiation updates |

### **Deployment** 🚀
| Platform | Service |
|----------|---------|
| **Vercel** | Frontend hosting |
| **Railway** | Backend API |

---

## 📸 Key Pages

### 🏠 **Landing Page** (`/`)
*Elegant hero section with glassmorphic design, smart scenario suggestions, and conflict setup form*

### 📊 **Dashboard** (`/dashboard`)
*Analytics overview with statistics, charts, recent negotiations, and comparison tools*

### 🎮 **Playground** (`/playground`)
*Interactive negotiation interface with real-time transcript, agreement outline, and risk assessment*

### 🔍 **Comparison** (`/compare`)
*Side-by-side analysis of multiple negotiations with difference highlighting*

### 📈 **Analytics** (`/analytics`)
*Comprehensive analytics with AI-powered insights, recommendations, and predictions*

### 📚 **History** (`/history`)
*Full negotiation history with search, filtering, and pagination*

### 🎯 **Templates** (`/templates`)
*Save and manage negotiation templates for quick reuse*

### ⚙️ **Settings** (`/settings`)
*User preferences, theme settings, and data management*

---


## 📖 User Guide

### Getting Started

1. **Define Scenario** — Enter topic, select parties, set constraints and red lines
2. **Choose Rounds** — Select 3-5 rounds for the negotiation
3. **Start Negotiation** — Watch agents negotiate in real-time
4. **Review Results** — Explore transcript, agreement, and risk assessment
5. **Ask AI Assistant** — Get insights and explanations about the negotiation

### Understanding Your Results

| Section | What It Shows |
|---------|---------------|
| **Transcript** | Timeline of negotiation turns with agent roles and timestamps |
| **Agreement Outline** | Structured agreement with terms, timelines, verification, and contingencies |
| **Risk Assessment** | Categorized risks (Political, Economic, Implementation) with levels and mitigations |
| **Analytics** | Statistics, trends, and AI-powered insights |
| **Comparison** | Side-by-side analysis of multiple negotiations |

### Pro Tips

- **Be specific** with topics and constraints for more realistic negotiations
- **Use smart suggestions** to discover interesting scenarios
- **Compare negotiations** to understand different outcomes
- **Ask the AI assistant** for deeper insights into agreements and risks
- **Export results** for documentation and sharing

---

## 🎨 Design Highlights

### Theme Options
- ☀️ **Light Mode** — Clean, professional interface
- 🌙 **Dark Mode** — Easy on the eyes (default)
- 🖥️ **System** — Follows OS preference

### UI Features
- **Glassmorphic Elements** — Modern backdrop blur effects
- **Smooth Animations** — React 19.2 transitions and state updates
- **Mobile Navigation** — Bottom nav with safe area support
- **Responsive Charts** — Optimized for all screen sizes
- **Touch-Optimized** — 44px+ touch targets for mobile

---

## 📊 Performance

| Metric | Value |
|--------|-------|
| Negotiation Time | ~30-60 seconds (3-5 rounds) |
| Frontend Bundle | Optimized with Next.js 16 |
| Lighthouse Score | 90+ |
| Mobile Ready | ✅ Yes |
| Real-Time Updates | ✅ WebSocket-powered |

---

## 🛡️ Security

- ✅ **RPC-Only Database Access** — No schema exposure, secure Supabase integration
- ✅ **API Rate Limiting** — Redis-powered rate limiting
- ✅ **CORS Protection** — Configured for production domains
- ✅ **Environment Variables** — All secrets in environment config
- ✅ **Input Validation** — Pydantic v2 validation on all endpoints
- ✅ **Error Handling** — Graceful fallbacks and error messages

---

## 🏗️ Architecture Highlights

### Multi-Agent System
- **AutoGen Framework** — Orchestrates role-based agents
- **Specialized Roles** — US Diplomat, EU Diplomat, Mediator, Historian, Risk Analyst
- **Custom Agents** — Create and configure custom negotiation roles
- **Round Management** — Structured 3-5 round negotiations

### Real-Time Communication
- **WebSocket Integration** — Live negotiation progress updates
- **Event-Driven** — Turn started, completed, round completed events
- **Fallback Polling** — Graceful degradation if WebSocket unavailable

### AI Integration
- **Optimized Prompts** — Finely-tuned for diplomatic accuracy
- **Context-Aware** — Full negotiation context in AI responses
- **Multi-Purpose** — Negotiations, chat, suggestions, insights
- **Structured Extraction** — AI-powered agreement and risk extraction

### Data Architecture
- **Supabase RPC** — Secure database access without schema exposure
- **Redis Caching** — Job status, rate limiting, and performance optimization
- **Framework-Agnostic UI** — Adapter layer for future framework swaps

---

## 👨‍💻 Creator

**Derril Filemon**

This project demonstrates proficiency in:
- 🤖 **AI/ML Integration** — AutoGen multi-agent workflows, OpenAI GPT-4.1-mini, optimized prompts
- ⚛️ **Modern React** — Next.js 16, React 19.2, Server Components, WebSockets
- 🐍 **Python Backend** — FastAPI, async/await, Pydantic v2, WebSocket support
- 🎨 **UI/UX Design** — Mantine components, responsive design, glassmorphism, 2025 standards
- ☁️ **Cloud Architecture** — Supabase (RPC-only), Redis, Railway, Vercel
- 🔧 **DevOps** — CI/CD, environment management, monitoring, testing
- 📊 **Data Visualization** — Recharts, analytics dashboards, real-time updates
- 🔒 **Security** — RPC functions, rate limiting, input validation, secure deployments

---

## 🙏 Acknowledgments

- **[AutoGen](https://microsoft.github.io/autogen/)** — Multi-agent conversation framework
- **[OpenAI](https://openai.com/)** — GPT-4.1-mini API
- **[Supabase](https://supabase.com/)** — Database & RPC functions
- **[Upstash](https://upstash.com/)** — Redis caching
- **[Railway](https://railway.app/)** — Backend deployment
- **[Vercel](https://vercel.com/)** — Frontend hosting
- **[Mantine](https://mantine.dev/)** — Beautiful component library
- **[Next.js](https://nextjs.org/)** — React framework
- **[Recharts](https://recharts.org/)** — Chart library

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">


Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
