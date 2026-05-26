<div align="center">

```
██████╗  █████╗ ██╗  ██╗██╗   ██╗██╗
██╔══██╗██╔══██╗██║  ██║██║   ██║██║
██████╔╝███████║███████║██║   ██║██║
██╔══██╗██╔══██║██╔══██║██║   ██║██║
     ██║  ██║██║  ██║██║  ██║╚██████╔╝███████╗
     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝
```

### Full Stack Developer · DSA Enthusiast · Builder

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=Building+full-stack+apps+from+scratch;Tracking+DSA+progress+with+AI+insights;Turning+ideas+into+deployed+products)](https://git.io/typing-svg)

</div>

---

## 👨‍💻 About Me

Hey! I'm **Rahul** — a full-stack developer who loves building real, production-ready applications. I work across the entire stack from React frontends to Node.js backends with MongoDB, Redis, and RabbitMQ. When I'm not coding, I'm grinding DSA problems and tracking my progress with tools I built myself.

- 🔭 Currently working on **CodeVault** — a DSA submission tracker with AI-powered mentoring
- 🌱 Exploring distributed systems, async job queues, and AI integrations
- ⚡ I build tools I actually want to use
- 📫 Reach me at: **rahulyad62005@gmail.com**

---

## 🛠️ Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Tools & Infra**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![GitHub OAuth](https://img.shields.io/badge/GitHub_OAuth-181717?style=for-the-badge&logo=github&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

---

## 🚀 Featured Projects

### 🗄️ [CodeVault — DSA Submission Tracker](https://github.com/Rahulbaliar/codevault)

> *Track your DSA journey. Organize your progress. Master algorithms.*

A full-stack platform to sync, track, and analyze coding practice across platforms with **AI-powered mentoring** and progress visualization.

```
React 19 + Node.js + MongoDB + Redis + RabbitMQ + Gemini AI + Prometheus
```

**Highlights:**
- 🔐 GitHub OAuth 2.0 with encrypted token storage
- ⚡ Chrome extension for automatic LeetCode submission capture
- 🤖 Gemini AI generates per-solution insights: intuition, complexity, follow-ups
- 📊 Interactive heatmaps and progress dashboard
- 🔁 Dead-Letter Exchange pattern for resilient async job processing
- 📈 Prometheus metrics with request latency observability

---

### 📋 [CodeBin — Code Snippet Sharing Platform](https://github.com/Rahulbaliar/codebin)

> *A modern Pastebin — but built properly.*

A full-stack code snippet platform with syntax highlighting, auth, and auto-expiration.

```
React 19 + Node.js + MongoDB + JWT + CodeMirror + TailwindCSS
```

**Highlights:**
- 🔑 JWT-based authentication with secure signup/signin
- 🎨 Syntax highlighting via CodeMirror for 10+ languages
- ⏱️ Flexible expiration: 10m, 30m, 1h, 1d, 1w, or never
- 🔗 Short URL generation for easy sharing
- 📱 Fully responsive UI with toast notifications

---

### 🌊 [OceanGuard — Ocean Hazard Monitoring Platform](https://github.com/Rahulbaliar/ocean)

> *Protecting Our Oceans Through Real-Time Hazard Monitoring & Community-Driven Reporting.*

A full-stack civic-tech platform for citizens and authorities to collaboratively monitor, report, and respond to ocean hazards in real-time.

```
React 19 + TypeScript + Node.js + MongoDB + Socket.io + Leaflet + OpenWeather API
```

**Highlights:**
- 🗺️ Interactive live map with real-time hazard markers via Leaflet
- ⚡ WebSocket notifications for instant hazard alerts using Socket.io
- 📋 Multi-step report wizard with image upload and severity classification
- 🎛️ Admin dashboard with verification system, user management & analytics
- 📰 RSS feed aggregation + Reddit API integration + AI sentiment analysis
- 🌤️ Marine weather data — wave height, wind speed via OpenWeather API
- 🔐 JWT auth with RBAC (user/admin roles) and bcrypt password hashing

---

## 📊 GitHub Stats

<div align="center">


![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Rahulbaliar&theme=github-dark-blue&hide_border=true)

</div>

---

## 🏗️ Architecture I Think About

```
Client (React)  →  Express API  →  MongoDB
                        ↓
                    RabbitMQ
                   ↙         ↘
            Gemini AI      GitHub API
            Worker          Worker
                        ↓
                  Redis Cache
                  (token blacklist, sessions)
```

I enjoy designing systems that are fault-tolerant, observable, and scalable — not just CRUD apps.

---

## 📫 Let's Connect

[![GitHub](https://img.shields.io/badge/GitHub-Rahulbaliar-181717?style=for-the-badge&logo=github)](https://github.com/Rahulbaliar)
[![Email](https://img.shields.io/badge/Email-rahulyad62005@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulyad62005@gmail.com)

---

<div align="center">

*"Track your DSA journey. Organize your progress. Master algorithms."*

![Profile Views](https://komarev.com/ghpvc/?username=Rahulbaliar&color=58A6FF&style=flat-square)

</div>
