# AM Project — Automated Brand Content Pipeline

> End-to-end automated visual campaign generation pipeline. Translates brand strategy and aesthetic rules into autonomous creative production.

![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)
![Thesis Score](https://img.shields.io/badge/Bachelor's%20Thesis-90%2F100-gold?style=flat)
![Stack](https://img.shields.io/badge/Stack-n8n%20%7C%20Generative%20AI%20%7C%20Cloudinary-blue?style=flat)

---

## Overview

AM Project is a research artifact developed as a **Bachelor's thesis** that scored **90/100**. It demonstrates how agentic AI systems can fully automate brand content production — from strategy to finished visual assets — without manual creative intervention.

The system ingests brand guidelines and aesthetic rules, then autonomously generates, evaluates, and delivers campaign-ready visual content at scale.

---

## Key Capabilities

- **Brand-aware generation** — encodes brand identity rules (color palette, tone, composition) as system-level constraints fed into the generative pipeline
- **Agentic orchestration** — n8n workflows coordinate multi-step AI tasks: prompt engineering, image generation, quality evaluation, and asset delivery
- **Autonomous quality control** — AI-driven evaluation loop filters outputs against brand standards before delivery
- **Scalable asset management** — Cloudinary handles versioning, transformation, and CDN delivery of all generated assets
- **API-native architecture** — fully headless, driven by API calls and webhooks; no manual UI steps in the production path

---

## System Architecture

```
Brand Strategy Input
        │
        ▼
 Prompt Engineering Layer (n8n)
        │
        ▼
 Generative AI APIs ──► Image / Copy Generation
        │
        ▼
 Quality Evaluation Agent
        │
        ▼
 Cloudinary Asset Pipeline ──► CDN Delivery
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| Orchestration | n8n |
| AI Generation | Generative AI APIs (image + copy) |
| Asset Management | Cloudinary |
| Integration | REST APIs, Webhooks |
| Architecture | Agentic multi-step pipeline |

---

## Research Context

This project was submitted as a **Bachelor's thesis research artifact**, exploring the feasibility of fully autonomous brand content production using agentic AI. The thesis examined:

- The boundary between human creative direction and machine execution
- How brand identity constraints can be programmatically encoded and enforced
- Scalability tradeoffs in generative pipeline design

**Final score: 90 / 100**

---

## Portfolio

Full documentation and case study available in the [Portfolio Drive](https://drive.google.com/drive/folders/16IQsA1VIEQMihnZebqVT_On0AmO6vvXv).

---

*Built by [Aria Irani](https://www.linkedin.com/in/aria-irani-7a9563261) · Berlin*
