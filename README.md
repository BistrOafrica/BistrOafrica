# 👋 Hi, I’m **Joseph Ndirangu Kangethe**

> **Full‑Stack Engineer** • PHP (Laravel), Go, .NET, React, Flutter • Systems architecture, APIs, microservices, DevOps

[![Profile Views](https://komarev.com/ghpvc/?username=BistrOafrica\&style=flat-square)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin\&style=flat-square)](https://www.linkedin.com/in/joseph-kangethe-056257185/)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?logo=gmail\&style=flat-square)](mailto:benny.gitouw254@gmail.com)

---

## 🧭 Mission

Design & ship **reliable, observable, secure** software that turns complex operations into **delightfully simple** user experiences.

* ⚙️ Backend: **Laravel, Go (Gin/gRPC), .NET**
* 🖥️ Frontend: **React/Next.js, TypeScript, Flutter**
* ☁️ Infra: **Docker, Kubernetes, AWS, CI/CD, Grafana, Sentry, New Relic**
* 📡 Protocols: **REST, gRPC, SOAP/XML, WebRTC, SIP/VoIP**

---

## 🏆 Gamified Progress

**Season:** 2025 • **Role:** Code Alchemist 🧪

* **XP**: `#####-----` 50/100 (next milestone: Ship an OSS utility)
* **Active Quests**

  * [ ] Merge a **performance PR** that cuts P95 latency by 20%
  * [ ] Publish a **Laravel + gRPC starter**
  * [ ] Add **end‑to‑end observability** demo (Grafana + Sentry)
* **Recent Achievements**

  * 🛡️ *Resilience Tuner*: Microservices failover with gRPC retries
  * ⚡ *Speedrunner*: Frontend bundle -35% via code‑split + suspense
  * 🧰 *DX Crafter*: Shared UI kit + Storybook in monorepo

> Claim an achievement by opening an issue/PR on any project below 👇

---

## 🔭 Featured Projects

### 1) **Dial Afrika – Customer Support SaaS**

**Stack:** Go (gRPC) · Laravel · React · VoIP · Grafana/Sentry/New Relic
**Highlights:** Real‑time agent orchestration, multi‑tenant APIs, microservices migration.

* Repo: [https://github.com/BistrOafrica/dialafrika-saas](https://github.com/BistrOafrica/dialafrika-saas) (private/placeholder)

### 2) **Leta Logistics Platform**

**Stack:** React + TS · Go microservices · gRPC
**Highlights:** High‑performance UI supporting scale‑up; contributed to seed round.

* Repo: [https://github.com/BistrOafrica/leta-logistics](https://github.com/BistrOafrica/leta-logistics) (case study)

### 3) **Soofapay – Web POS**

**Stack:** React · Redux · Node
**Highlights:** Responsive POS + admin analytics.

* Repo: [https://github.com/BistrOafrica/soofapay-pos](https://github.com/BistrOafrica/soofapay-pos)

> More at **/projects** in this profile; or ping me for deep‑dives.

---

## 🧰 Tech Stack (Badges)

![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php\&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel\&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go\&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?logo=.net\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=TypeScript\&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react\&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes\&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana\&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?logo=sentry\&logoColor=white)
![New Relic](https://img.shields.io/badge/NewRelic-1CE783?logo=newrelic\&logoColor=white)

---

## 📈 Developer Scoreboard

<a href="https://github-readme-stats.vercel.app/api?username=BistrOafrica&show_icons=true&include_all_commits=true&count_private=true">
  <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=BistrOafrica&show_icons=true&include_all_commits=true&count_private=true" />
</a>

<a href="https://streak-stats.demolab.com?user=BistrOafrica">
  <img alt="Streak" src="https://streak-stats.demolab.com?user=BistrOafrica" />
</a>

<a href="https://github-profile-trophy.vercel.app/?username=BistrOafrica&theme=flat&row=1&column=7">
  <img alt="Trophies" src="https://github-profile-trophy.vercel.app/?username=BistrOafrica&row=1&column=7" />
</a>

---

## 🐍 Snake: Eat My Contributions

Embed updates automatically with a GitHub Action (instructions below). The SVG animates your contribution grid as a snake game.

![snake svg](https://raw.githubusercontent.com/BistrOafrica/BistrOafrica/output/github-contribution-grid-snake.svg)

> If the image 404s initially, give the workflow one run and refresh.
> Replace **BistrOafrica** everywhere.

### Setup: Snake Workflow

Create `.github/workflows/snake.yml` in your **profile repo** (a repo named exactly your username).

```yaml
name: Generate snake

on:
  schedule:
    - cron: "0 0 * * *"  # daily
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Generate snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: BistrOafrica
          outputs: |
            dist/github-contribution-grid-snake.svg

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then embed:

```markdown
![snake svg](https://raw.githubusercontent.com/BistrOafrica/BistrOafrica/output/github-contribution-grid-snake.svg)
```

---

## 📚 Case Studies & Talks

* **Microservices with gRPC in Go** — patterns for auth, retries, and observability
* **Laravel → Go migration** — pragmatism, strangler fig, and data contracts
* **Designing for Reliability** — SLOs, budgets, and golden paths

> Want a deep dive? Open a **Discussion** with the topic you’d like me to cover.

---

## 🤝 Let’s Build

I’m open to **consulting, collaboration, and mentorship**.
**Email:** [benny.gitouw254@gmail.com](mailto:benny.gitouw254@gmail.com) • **LinkedIn:** https://www.linkedin.com/in/joseph-kangethe-056257185/

---
