# 👋 About Me

I’m a Full Stack Web Developer specialising in **WordPress engineering and API-driven applications**, building systems that are designed to be maintainable, scalable, and long-lived.

I entered the industry during the lockdown years after a career in gym management, and since then I’ve worked deeply across **PHP**, **JavaScript (React)**, **SQL**, and modern WordPress architecture — from custom themes and Gutenberg blocks to backend systems, integrations, and performance.

I tend to gravitate towards work that improves and evolves existing systems rather than constantly replacing them. That means a lot of time spent on **refactoring, edge cases, standards compliance, and long-term maintainability** — the kind of decisions that make future development faster and safer.

I’m particularly interested in:

- Backend-heavy WordPress development
- Custom plugins and Gutenberg blocks
- API design and system architecture
- Tooling, automation, and developer experience
- Building products alongside client work


---

## 🗺️ Flagship Project — Course Atlas

**Course Atlas** is a full-stack golf course discovery platform built with an API-first architecture.

It's designed to help users explore, filter, and evaluate golf courses through a performant, map-first interface, while maintaining a clean separation between frontend and backend systems.

### 🧠 What it demonstrates

- Designing and building a **production-ready Laravel API**
- Creating a **map-first frontend using Next.js and Leaflet**
- Implementing **geospatial filtering and search (bounds + radius)**
- Structuring and validating **large JSON datasets for ingestion**
- Building **authentication flows (Google SSO + session-based auth)**
- Applying **security and performance considerations** (rate limiting, payload separation, caching strategies)
- Designing for **multi-platform consumption** (web-first, mobile-ready API)
- Modelling **stateful business processes** (claim lifecycle with audit trail)
- Implementing **AI governance policies** at the data layer

---

### ⚙️ Tech Stack

- **Frontend:** Next.js (App Router), React, Tailwind
- **Backend:** Laravel (API-first), Sanctum authentication
- **Database:** PostgreSQL
- **Mapping:** Leaflet / OpenStreetMap
- **Admin:** Filament (internal tooling)
- **Testing:** Playwright (E2E critical-path coverage)

---

### 🚀 Key Features

- Map-based discovery with clustering and dynamic bounds querying
- Advanced filtering (course type, holes, slope range, facilities)
- Structured listing pages across courses, golf shops, and virtual venues
- Course claiming workflow — submission, admin review, approval, and revocation with full audit trail
- User accounts with saved courses and custom lists
- JSON-driven data ingestion pipeline with validation tooling
- Versioned API (`/api/v1`) for long-term stability

---

### 🧩 Architecture Highlights

- API-first design with strict frontend/backend separation
- JSON-canonical + DB-projection pattern — JSON is the source of truth; the database is a runtime projection, with a sync log to reconcile divergence after workflow events
- AI enrichment governance layer — per-listing `ai_automation_level` controls (`unrestricted` / `human_review_required` / `locked`) gate automated data enrichment and PR creation
- Independent endpoints for map data vs list data (performance optimisation)
- Snapshot-based state restoration for map/search UX
- CLI tooling for dataset validation, completeness scoring, enrichment, and sync management
- Secure redirect handling and sanitised external linking

---

### 🔮 Coming Soon

- API key authentication and external developer access
- Course comparison feature
- Affiliate integrations (booking and equipment)
- Public API documentation (auto-generated via Scribe)

---

### 🔗 Link

- Frontend: [*Course Atlas*](https://www.courseatlas.golf/)

---

## 🔌 Featured Project

### HTTP 410 (Gone) Responses

A lightweight WordPress plugin for correctly handling permanently removed URLs using HTTP 410 responses.

- Actively maintained  
- Thousands of active installs  
- Focused on correctness, simplicity, and WordPress standards  

👉 https://github.com/XanderCalvert/410-for-WordPress

[![WordPress Plugin Active Installs](https://img.shields.io/wordpress/plugin/installs/wp-410?logo=wordpress&logoColor=white)](https://wordpress.org/plugins/wp-410/)
[![WordPress Plugin Downloads](https://img.shields.io/wordpress/plugin/dt/wp-410?logo=wordpress&logoColor=white)](https://wordpress.org/plugins/wp-410/)
[![WordPress Plugin Version](https://img.shields.io/wordpress/plugin/v/wp-410?logo=wordpress&logoColor=white)](https://wordpress.org/plugins/wp-410/)
[![WordPress Plugin: Tested WP Version](https://img.shields.io/wordpress/plugin/tested/wp-410?logo=wordpress&logoColor=white)](https://wordpress.org/plugins/wp-410/)
[![License](https://img.shields.io/badge/license-GPLv2-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.html)


---

## 🧪 Current Focus

- Developing Course Atlas into a production-ready platform  
- Building a reusable **WordPress website toolkit** for client projects  
- Improving testing, automation, and deployment workflows  
- Laying the groundwork for a small, product-focused web agency  


---

## 💻 Tech I Work With

![WordPress](https://img.shields.io/badge/WordPress-%2321759B.svg?style=for-the-badge&logo=wordpress&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-%23339933.svg?style=for-the-badge&logo=node.js&logoColor=white)
![Composer](https://img.shields.io/badge/composer-%23885630.svg?style=for-the-badge&logo=composer&logoColor=white)
![WP-CLI](https://img.shields.io/badge/WP--CLI-%2321759B.svg?style=for-the-badge&logo=wordpress&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)


---

## 🌐 Find Me Elsewhere

<div id="badges">
  <a href="https://linkedin.com/in/matt-calvert">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://medium.com/@Calvert_">
    <img src="https://img.shields.io/badge/Medium-white?style=for-the-badge&logo=medium&logoColor=black" alt="Medium Badge"/>
  </a>
</div>


---

## 📊 GitHub Stats

![GitHub Stats](https://gh-readme-profile.vercel.app/api?username=XanderCalvert&theme=dark)
