# Hi, I'm Tú (Uông Thanh Tú) 👋

**Backend developer who ships and runs a real product.**
I built **[Tượng Kỳ Đại Sư](https://tuongkydaisu.com)** — an online Chinese chess (xiangqi) platform for Android and the web — and I operate it end to end: backend, app, servers, releases, SEO and content.

📍 Vietnam · 🎓 Software Engineering, FPT University · 🌐 [tusry.my](https://www.tusry.my) · 💼 [LinkedIn](https://www.linkedin.com/in/uongthanhtu/)

---

## 🏁 Tượng Kỳ Đại Sư — live in production

[![Get it on Google Play](https://img.shields.io/badge/Google_Play-Tượng_Kỳ_Đại_Sư-34A853?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.tusry.xiangqi)
[![Web](https://img.shields.io/badge/Web-tuongkydaisu.com-8a4b1f)](https://tuongkydaisu.com)
[![YouTube](https://img.shields.io/badge/YouTube-@apptuongkydaisu-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@apptuongkydaisu)

*Numbers as of 20 Nov 2026:*

| | |
|---|---|
| **1K+** installs on Google Play · **4.3★** rating | **3,700+** player accounts (Android + web) |
| **22,000+** games played | **100+** players and **500+** games on peak days |

**What I built (solo):**
- **Real-time play** — STOMP/WebSocket game loop, matchmaking queues, server-side clocks and rule enforcement (perpetual-check / chase rules), ranked Elo, blitz mode.
- **Game analysis** — move-by-move post-game analysis backed by a shared pool of chess-engine processes with priority lanes, CPU isolation and back-pressure, so it stays fast at peak hours.
- **Learning content** — a tournament database of **25,000+ master games** (as of Nov 2026; imported and verified), lessons, and — in progress — a leveled puzzle mode (410 classic-book puzzles in 13 levels, every solution engine-verified).
- **Security & reliability** — JWT auth, permission-based access, hardening after a pentest (fail2ban, rate limits, Redis auth), silent auto-recovery UX for older players, rollback-ready deploys.
- **Ops** — Docker Compose on a small VPS behind Nginx + Cloudflare, Postgres 16, Redis 7, a relay for slow networks, CI with SonarCloud, manual migration runbooks, quiet-hour deploy checks.
- **Mobile** — React 19 + Capacitor app, Play Store releases (AAB), AdMob.
- **Growth** — pre-rendered SEO pages for tournaments and players, structured data, Search Console; an automated content pipeline (Telegram-driven YouTube/Facebook publishing, video rendering with Remotion/FFmpeg and Vietnamese TTS).

**Stack:** Java 21 · Spring Boot 3 · Spring Security · PostgreSQL 16 · Redis 7 · WebSocket (STOMP) · React 19 · TypeScript · Capacitor 8 · Nginx · Docker · Python · Node.js

---

## 🧩 Other projects

| Project | What it is | Stack |
|---|---|---|
| [Movie-Recommendation-Hybrid-Engine](https://github.com/uongthanhtu/Movie-Recommendation-Hybrid-Engine) | Multi-engine recommender: Social-LightGCN (graph neural CF with social contrastive learning), SASRec, TrustSVD, content-based + MMR diversification, benchmarked on 5 datasets | Python · PyTorch · FastAPI · Redis |
| [spring-security-toolkit](https://github.com/uongthanhtu/spring-security-toolkit) | Plug-and-play security starter for Spring Boot 3: JWT, rate limiting, audit logging, method security | Java · Spring Security 6 |
| [hiv-and-medical-system-backend](https://github.com/uongthanhtu/hiv-and-medical-system-backend) | Healthcare backend: appointments, ARV regimens, anonymous consultations, reminders, admin reporting | Java · Spring Boot · JWT · JPA |

## 💼 Experience

**Full-stack Developer — Binh Furniture Company** (Jun 2026 – Present)
In-house ERP for an export furniture manufacturer, covering the product lifecycle from design to export.

**Backend Developer Intern — FPT Software** (Sep–Dec 2025)
ERP for a major Japanese steel-trading company: designed a DB-driven dynamic permission system and a multi-layer security chain (interceptors) for fine-grained access control; integration-tested security modules with QC through UAT.

## 🛠️ What I'm good at

- Designing APIs and data models that stay fast under real traffic
- Real-time systems (WebSocket, queues, schedulers, locking)
- Security: authN/authZ, permission models, hardening
- Running production: monitoring, safe deploys, rollbacks, incident fixes
- Shipping end to end — from database to Play Store listing

---

<sub>Open to backend / full-stack roles. Reach me via [LinkedIn](https://www.linkedin.com/in/uongthanhtu/) or [tusry.my](https://www.tusry.my). · Last updated: 20 Nov 2026</sub>
