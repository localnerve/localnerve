# 🚀 Full-Stack Web Developer | 20+ Years | Available for Contract & Consulting

[![Availability](https://img.shields.io/badge/Availability-Open%20for%20Contracts-brightgreen)](#)
[![Experience](https://img.shields.io/badge/Experience-20%2B%20Years-blue)](#)
[![Website](https://img.shields.io/badge/Website-localnerve.com-orange)](https://localnerve.com)

## 🎯 What I Do

I help businesses **build and maintain production web applications** — from PWAs and offline-first architectures to backend APIs and CI/CD tooling. Over 20+ years I've worked across scientific R&D, test & measurement, manufacturing, insurance, and e-commerce, so I'm comfortable translating between "what the business needs" and "what the code has to do."

- 🛠️ **Current Focus:** Progressive Web Apps, offline-first architecture, developer tooling, and AI
- 🤖 **I run my own local AI stack** — not just an API key: self-hosted LLM service configuration, an MCP server constellation, custom tool-routing prompts for my dev shop, and a persistent dev-container for secure open-source development. I work *with* agents daily because I operate the infrastructure they run on.
- 🌍 **Location:** USA (Remote)
- 💼 **Services:** Full-stack development, technical auditing, team augmentation, automation, AI-stack setup & agent-workflow design

---

## 🛠️ Specialized Ecosystem

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/github/explore/main/topics/javascript/javascript.png" width="48" height="48" alt="JS" />
      <br />JavaScript
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/github/explore/main/topics/go/go.png" width="48" height="48" alt="Golang" />
      <br />Golang
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/github/explore/main/topics/nodejs/nodejs.png" width="48" height="48" alt="Node" />
      <br />Node.js
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/github/explore/main/topics/react/react.png" width="48" height="48" alt="React" />
      <br />React
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/github/explore/main/topics/docker/docker.png" width="48" height="48" alt="Docker" />
      <br />Docker
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/github/explore/main/topics/mariadb/mariadb.png" width="48" height="48" alt="MariaDB" />
      <br />MariaDB
    </td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/github/explore/main/topics/postgresql/postgresql.png" width="48" height="48" alt="PostgreSQL" />
      <br />PostgreSQL
    </td>
  </tr>
</table>

---

## 🏆 Featured Production Work

### 📌 [jam-build](https://github.com/localnerve/jam-build)
> **Reference architecture for building PWAs with vanilla JS.**
* **What it demonstrates:** Static/dynamic data handling, service-worker-based offline-first design, no framework dependency
* **Stack:** JavaScript, Service Workers, MariaDB (via companion Nodejs propsdb-api service)

### 📌 [jam-build-propsdb](https://github.com/localnerve/jam-build-propsdb)
> **High-performance Go data service, built as a drop-in replacement for the jam-build Node/Express service.**
* **What it demonstrates:** Cross-language service replacement without breaking API compatibility
* **Engineering details:** Multi-database support (MariaDB, MySQL, PostgreSQL, SQLite, SQL Server) via GORM, Authorizer-based auth integration, optimistic locking with version-conflict detection, tested with testcontainers, shipped as a public Docker image
* **Stack:** Go, Fiber, GORM, Docker

### 📌 [agent-skills](https://github.com/localnerve/agent-skills)
> **Deterministic generator that turns a curated, evidence-anchored rule corpus into tiered instructions for coding agents (VS Code Copilot skills and `AGENTS.md`) — with the tooling to keep those rules honest.**
* **What it demonstrates:** Treating agent instructions as compiled data rather than rotting prose — every rule carries an evidence anchor into the reference repo, so drift surfaces as a named rule ID instead of silent staleness; and measuring real skill value (conformance delta vs. a no-skills baseline) using only the AI stack you already run
* **Engineering details:** Pure-Node, zero runtime dependencies; deterministic compilation (same input → byte-identical output, snapshot-testable); anchor-drift verifier with durable/volatile severity classes and CI-ready exit codes; tiered output with a hard 20-line always-resident budget; LLM mining as suggestion-only layer; golden-task conformance evals executed in-chat by subagents of your existing AI stack — no new LLM services, API keys, or AI infrastructure required
* **Stack:** Node.js, **Your AI Stack**

### 📌 [csp-hashes](https://github.com/localnerve/csp-hashes)
> **Build-time library for generating CSP (Content Security Policy) script/style hashes.**
* **What it demonstrates:** Security-conscious tooling — solves a real, easy-to-get-wrong problem (keeping CSP headers in sync with build output)
* **Proof:** 1500+ weekly npm downloads — actively used by other developers
* **Stack:** Node.js, integrates into Gulp/build pipelines, published on npm

---

## 🤝 Let's Build Something Together

I am currently accepting select engineering contracts and technical consultation roles — including AI-stack setup, auditing, and agent-workflow design for teams that want to run their own local AI rather than rent it.

* 📧 **Direct Email:** [alex@localnerve.com](mailto:alex@localnerve.com)
* 💼 **Professional Network:** [Connect on LinkedIn](https://www.linkedin.com/in/alexpaulgrant/)
* 🌐 **Portfolio:** [localnerve.com](https://localnerve.com/about#projects)
* 🐦 **Mastodon:** [@localnerve](https://mastodon.social/@localnerve)
* 🐦 **X / Twitter:** [@localnerve](https://x.com/localnerve)

---

## 📈 Engineering Metrics & Proof

![Alex's GitHub Stats](https://github-stats-extended.vercel.app/api?username=localnerve&show=reviews%2Cdiscussions_started%2Cdiscussions_answered%2Cprs_merged%2Cprs_merged_percentage%2Cprs_commented%2Cprs_reviewed%2Cissues_commented&show_icons=true&include_all_commits=true&theme=react)
![Top Langs](https://github-stats-extended.vercel.app/api/top-langs?username=localnerve&langs_count=8&theme=react)
