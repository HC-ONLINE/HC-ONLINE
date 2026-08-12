# Hi — I’m Andres Henriquez (HC-ONLINE)

## Software Engineer — Backend, Security & AI Infrastructure

I build backend systems, security-oriented tools, AI infrastructure, and modern web experiences.

My primary focus is **Python and Java backend development**, with a strong interest in **application security, IAM, web security, data security, and LLM infrastructure**.

I also build frontend experiences using **Astro, TypeScript, and Tailwind CSS**, with particular interest in frontend architecture, design systems, responsive interfaces, and interactive web experiences.

My projects tend to explore practical engineering problems around system architecture, security boundaries, resilience, automation, and maintainability.

---

## Areas of Focus

### Backend Engineering

- Python
- FastAPI
- Java
- Spring Boot
- Spring Security
- REST APIs
- API architecture
- Authentication and authorization
- Docker
- Redis
- Observability

### Security

- Web application security
- Security assessment
- Technology fingerprinting
- Vulnerability intelligence
- CVE analysis
- PII detection and data exposure
- IAM
- JWT
- RBAC
- Security testing
- API security

### AI Infrastructure

- LLM provider abstraction
- Multi-provider orchestration
- Streaming
- Automatic fallback
- Rate limiting
- Resilience patterns
- Provider adapters
- Observability

### Frontend Engineering

- Astro
- TypeScript
- Tailwind CSS
- HTML/CSS
- Design systems
- Design tokens
- Responsive interfaces
- Interactive web experiences
- Frontend architecture

---

## Featured Projects

### CiberWebScan

#### Web Security Assessment & Reconnaissance

A Python security toolkit for web application assessment that combines reconnaissance, technology fingerprinting, security analysis, vulnerability intelligence, web scraping, and controlled security testing.

Key capabilities include:

- Technology fingerprinting
- SSL/TLS analysis
- Security headers assessment
- CVE correlation
- Static and dynamic web scraping
- XSS testing
- SQL injection analysis
- Directory enumeration
- Path traversal testing
- Subdomain enumeration
- Command injection testing
- REST API
- CLI automation
- JSON, CSV, JSONL, and HTML exports

CiberWebScan is an active project and represents my main work around **web security automation and attack-surface analysis**.

[Repository](https://github.com/HC-ONLINE/CiberWebScan)

---

### ModelRouter

#### Multi-Provider LLM Gateway — Proof of Concept

An asynchronous HTTP API designed to abstract multiple LLM providers behind a single interface.

The project currently explores integrations with:

- Groq
- OpenRouter
- OpenAI
- Gemini
- Ollama

Its architecture focuses on infrastructure concerns such as:

- Automatic provider fallback
- Server-Sent Events streaming
- Rate limiting
- Temporary provider blocklisting
- Exponential backoff
- Prometheus metrics
- Structured logging
- Redis integration
- Docker deployment

ModelRouter is a **proof of concept** exploring provider-agnostic LLM infrastructure, resilience, and observability.

[Repository](https://github.com/HC-ONLINE/ModelRouter)

---

### LexGuard

#### PII Detection & Risk Correlation — Completed Proof of Concep

A completed proof of concept for deterministic detection of Personally Identifiable Information and contextual risk analysis in files and repositories.

The project explores data exposure from a security perspective using techniques such as:

- Pattern detection
- Prefix and length validation
- Luhn validation
- Entropy analysis
- Contextual validation
- Cross-PII correlation
- Explainable risk classification

Current detection covers:

- Colombian identification numbers
- Colombian mobile numbers
- Email addresses
- Credit card numbers

LexGuard is **no longer under active development**. It remains public as a reference implementation for CLI architecture, deterministic PII detection, and explainable risk analysis.

[Repository](https://github.com/HC-ONLINE/LexGuard)

---

### DemoFactory

#### Frontend Architecture & Web Experience Laboratory

A shared Astro-based environment for building and presenting multiple independent web experiences from a single project.

Each demo can maintain its own:

- Components
- Visual identity
- Content
- Types
- Interaction logic
- Data and helpers

while the platform provides common infrastructure for routing, internationalization, layouts, metadata, and shared styling.

The collection includes experiences such as:

- **Elite Vows** — premium editorial wedding invitation
- **Lumina** — cinematic visual-art portfolio
- **TechNexus Consulting** — B2B corporate landing page
- **Aeterna** — immersive historical timeline
- **LyricFlow** — interactive music experience
- **TypoCraft** — typography-focused Markdown editor
- **ORBIT-UI** — CSS-first design system
- **AuraWeather** — immersive weather interface
- **PixelPress** — gaming publication
- **NF Archive** — immersive music discography experience

DemoFactory represents the frontend side of my work, combining **visual design, interaction, responsive development, content architecture, and reusable frontend foundations**.

[Repository](https://github.com/HC-ONLINE/DemoFactory) · [Live demos](https://hc-online.github.io/DemoFactory/)

---

## Other Projects

### AccessManager

Authentication architecture study focused on Spring Boot and Spring Security, exploring stateless JWT authentication and stateful session-based authentication.

[Repository](https://github.com/HC-ONLINE/AccessManager)

### PermissionManager

Authorization architecture study exploring RBAC, granular permissions, JWT-based authentication, sessions, and policy-based authorization.

[Repository](https://github.com/HC-ONLINE/PermissionManager)

### ORBIT-UI

CSS-first design system built with Astro and Tailwind CSS, focused on semantic design tokens, reusable components, accessibility, and explicit component states.

[Repository](https://github.com/HC-ONLINE/ORBIT-UI)

---

## Technical Stack

### Primary

#### Python

FastAPI · CLI development · automation · web security tooling · data processing

#### Java

Spring Boot · Spring Security · Maven · REST APIs · authentication · authorization

### Frontend

Astro · TypeScript · Tailwind CSS · HTML · CSS · Markdown/MDX

### Infrastructure & Tooling

Docker · Docker Compose · Redis · Prometheus · GitHub Actions · Git

### Security

Web security · IAM · JWT · RBAC · CVE analysis · PII detection · security assessment · API security

### AI Infrastructure

LLM orchestration · provider abstraction · streaming · fallback strategies · rate limiting · observability

---

## Engineering Approach

### Understand the problem before introducing abstractions

I prefer understanding the actual architectural problem before introducing a new pattern, framework, or abstraction.

### Keep security boundaries explicit

Authentication, authorization, data protection, and application security should be treated as distinct concerns with explicit boundaries.

### Prefer reusable foundations

Reusable components and infrastructure should solve an actual recurring problem rather than introduce abstraction for its own sake.

### Design for failure

Backend and infrastructure systems should account for provider failures, rate limits, unavailable dependencies, and degraded states instead of assuming that every external service is always available.

### Build with maintainability in mind

I value explicit behavior, modular architecture, clear interfaces, and systems that can be understood and extended without unnecessary complexity.

---

## Current Areas of Development

- Backend engineering with Python and Java
- Application and web security
- IAM and authorization systems
- LLM infrastructure and multi-provider systems
- Resilient API architecture
- Frontend architecture with Astro and Tailwind CSS
- Design systems and reusable UI foundations

---

## Portfolio

For a complete view of my projects and frontend work:

**[View my complete portfolio](https://hc-online.github.io/es/)**

---

## About This Profile

Not every repository represents a production-ready product.

This profile intentionally distinguishes between **active projects, proofs of concept, architectural studies, and frontend experiments**.

The featured projects are selected to represent the areas I am most interested in professionally:
**Backend · Security · AI Infrastructure · Frontend Engineering**

Additional experiments and completed projects remain available through the repositories and the complete portfolio.
