<div align="center">

# Hey, I'm Haarish S 👋

**Backend Engineer · Product Thinker · Placement-Ready**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-haarish--s-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haarish-s-20937a294/)
[![GitHub](https://img.shields.io/badge/GitHub-haarish009-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/haarish009)
[![Location](https://img.shields.io/badge/Chennai%2C%20India-📍-orange?style=flat-square)](#)

</div>

---

## 🧠 About Me

I'm a Electronics student based in Chennai, building production-grade backend systems with a strong emphasis on **scalability, clean architecture, and real-world trade-offs**.

My approach to engineering goes beyond making things work — I care about *why* certain design choices scale better, cost less, or fail more gracefully. I document these decisions and build with placement in mind, so every project tells a story a recruiter can follow.

Currently deep in **WealthOS**, a full-stack paper trading & AI portfolio advisor platform I'm building from scratch.

---

## 🚀 Featured Project — WealthOS

> *A paper trading platform with an AI-powered multi-agent portfolio advisor*

**WealthOS** simulates real market trading with live stock data, lets users build watchlists, and uses GPT-4o-powered agents to give personalized portfolio advice — complete with human-in-the-loop approval before any trade action.

### Architecture Highlights

- **Multi-Agent System** — Portfolio Guardian, Wishlist Scout, Risk Sentinel, and a Master Orchestrator coordinate together; no trade recommendation goes through without explicit user approval
- **Async AI Processing** — AI calls run asynchronously so the main trading flow is never blocked
- **Redis Caching** — Live stock quotes and AI responses are cached to cut latency and reduce Twelve Data API costs
- **Rate Limiting** — Per-user request throttling to prevent API abuse
- **Correlation IDs** — MDC-based tracing so every log line across services can be traced back to a single request
- **CI/CD Pipeline** — GitHub Actions runs JUnit 5 tests on every push; Docker containerizes the full app

### Tech Stack

| Layer | Technology |
|---|---|
| Language | Java 21 |
| Framework | Spring Boot 3.3, Spring AI |
| Database | PostgreSQL + Flyway migrations |
| Cache | Redis |
| Auth | Firebase Authentication |
| AI | OpenAI GPT-4o via Spring AI |
| Market Data | Twelve Data API |
| Payments | Razorpay |
| DevOps | Docker, GitHub Actions CI |
| Connection Pool | HikariCP (tuned) |
| Testing | JUnit 5, global exception handling |

---

## 🛠️ Tech I Work With

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-FF6F00?style=flat-square)

**Databases & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

---

## 💡 What I'm Focused On Right Now

- Completing end-to-end trading flow on **WealthOS**
- Deploying on **Railway / Render** with a custom minimal frontend
- Nailing the interview narrative around **architectural trade-offs** (why Redis, why async, why HikariCP tuning)
- Preparing to talk about **scalability decisions** — not just what I built, but *why*

---

## 📈 GitHub Stats

<div align="center">

![Haarish's GitHub Stats](https://github-readme-stats.vercel.app/api?username=haarish009&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=haarish009&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9)

</div>

---

## 📫 Let's Connect

I'm actively looking for **backend / full-stack SDE internships and placements**. If you're hiring or just want to talk systems design and trade-offs, reach out!

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haarish-s-20937a294/)

---

<div align="center">
<sub>Built with Java, Spring Boot, and a lot of trade-off decisions. 🔧</sub>
</div>
