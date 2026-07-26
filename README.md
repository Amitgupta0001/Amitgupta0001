<h1 align="center">Amit Kumar Gupta</h1>

<p align="center">
  <strong>Backend Engineer</strong> · Java / Spring Boot · Python / FastAPI · System Design
</p>

<p align="center">
  Building production-grade backend systems with Java, Spring Boot, PostgreSQL, and FastAPI.<br/>
  Focused on distributed systems, clean architecture, transactional consistency, and scalable software.
</p>

<p align="center">
  <code>Java</code> · <code>Spring Boot</code> · <code>PostgreSQL</code> · <code>FastAPI</code> · <code>Docker</code> · <code>React</code> · <code>Python</code> · <code>JUnit 5</code>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/amitgupta0001/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:amitgupta001503@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://leetcode.com/u/Amitgupta00001/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="https://codeforces.com/profile/Amitgupta1503">
    <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white" alt="Codeforces"/>
  </a>
</p>

---

## About Me

Final-year Computer Science student at DSATM, Bengaluru (CGPA: 8.84/10). I work primarily with **Java/Spring Boot** and **Python/FastAPI** to design backend systems — REST APIs, transactional workflows, authentication layers, and state machine orchestrators.

I care about clean layered architecture, writing tests that catch real bugs, and handling edge cases properly. 250+ competitive programming problems solved across LeetCode and Codeforces.

---

## 🔨 Currently Building

Building [**AmazonScale**](https://github.com/Amitgupta0001/amazon-scale-backend) — a production-inspired e-commerce backend focused on transactional consistency, secure JWT/RBAC authentication, and scalable layered service architecture using Java 21, Spring Boot, and PostgreSQL.

---

## Projects

### [AmazonScale — E-Commerce Backend Platform](https://github.com/Amitgupta0001/amazon-scale-backend)
`Java 21` `Spring Boot 4` `Spring Security` `JWT` `PostgreSQL` `JUnit 5`

Enterprise e-commerce backend with clean layered architecture (Controller → Service → Repository), designed to handle real order and payment transaction flows.

- Implemented JWT-based authentication with Role-Based Access Control (Admin, Seller, Customer) using Spring Security and BCrypt password hashing
- Designed Order lifecycle state machine (`PENDING → CONFIRMED → SHIPPED → DELIVERED`) with automated tax calculation and transactional inventory deduction using `@Transactional`
- Engineered Payment module with state transitions (`PENDING → SUCCESS → REFUNDED`) and idempotent processing
- Wrote 82+ automated tests (JUnit 5 + MockMvc) covering controller, service, and security layers with structured global exception handling across 20+ REST endpoints

### [RESTORE — Transaction Orchestrator](https://github.com/Amitgupta0001/RESTORE)
`Python` `FastAPI` `PostgreSQL` `Docker` `Pytest`

Stateful refund processing engine with exactly-once semantics, concurrent worker safety, and human-in-the-loop approval flows.

- Implemented idempotent request handling using database-level `UNIQUE` constraints on idempotency keys
- Designed concurrent worker processing with PostgreSQL `FOR UPDATE SKIP LOCKED` to prevent duplicate claim of pending transactions
- Built dead letter queue with configurable retry policy (3 retries) and 48-hour auto-timeout for stalled requests
- Containerized with Docker Compose; full unit test coverage for domain state machine logic

### [King Phisher AI — Phishing Detection System](https://github.com/Amitgupta0001/KingPhisher)
`Python` `FastAPI` `scikit-learn` `Chrome Extension (Manifest V3)` `SQLAlchemy`

Full-stack phishing detection platform combining a trained ML classifier with a Chrome extension for real-time email and URL analysis.

- Trained Random Forest classifier on 600K+ labeled samples with 12 engineered features for URL structure and email header analysis
- Developed Manifest V3 Chrome extension with Gmail DOM monitoring via `MutationObserver` for inline threat detection
- Implemented JWT authentication, SQLAlchemy-backed scan history, and ~150ms average API response time

### [Portfolio & Resume Web Application](https://github.com/Amitgupta0001/Resume)
`HTML5` `CSS3` `JavaScript (ES6+)` `SVG Procedural Art` `Glassmorphism`

Fully responsive developer portfolio engineered from scratch — zero frameworks, zero dependencies, modular vanilla JS architecture.

- Architected reusable component system (theme manager, toast notifications, skill filters, resume modal) using IIFE-scoped modules with clean separation of concerns
- Implemented `IntersectionObserver`-driven lazy animations, `HEAD`-request resume download validation with fallback handlers, and accessible keyboard navigation across all interactive elements
- Engineered interactive particle mesh canvas with mouse-repulsion physics and dynamic line connections, plus 3D magnetic tilt hover with `perspective(800px)` transforms
- Built procedural SVG paint splash achievement cards using `feTurbulence` + `feDisplacementMap` filters, multi-layer frosted glass, noise texture overlays, and animated conic-gradient borders
- Dark/light theme persistence via `localStorage`, responsive layouts across desktop/tablet/mobile, and clipboard-copy toast notification system

---

## Achievements

| | |
|:---|:---|
| **LeetCode** | 207+ problems solved · Peak Rating: 1580 |
| **Competitive Programming** | 250+ problems across LeetCode & Codeforces |
| **Academics** | B.E. CSE — CGPA: 8.84/10 · CBSE XII: 90.6% · CBSE X: 97.0% |

---

## Tech Stack

**Languages:** Java, Python, C++, C, JavaScript, SQL

**Backend:** Spring Boot, Spring Security, Spring Data JPA, Hibernate, FastAPI, Node.js

**Frontend:** React, HTML5, CSS3

**Databases:** PostgreSQL, MySQL, MongoDB, SQLite

**DevOps & Tools:** Docker, Git, GitHub Actions, Linux, Postman, Render, Vercel

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Amitgupta0001&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Amitgupta0001&layout=compact&theme=tokyonight&hide_border=true" height="160" alt="Top Languages" />
</p>
