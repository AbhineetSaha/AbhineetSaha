# Abhineet Saha

**Software Engineer** — full-stack & backend systems

B.Tech Computer Science & Engineering, VIT-AP (2022–2026) · West Bengal, India

[Portfolio](https://abhineetsaha.vercel.app) · [LinkedIn](https://linkedin.com/in/abhineetsaha/) · [LeetCode](https://leetcode.com/u/AbhineetSaha/) · [PyPI](https://pypi.org/project/pyxtrace/)

## About

I build backend systems and developer tooling, mostly in TypeScript and Python. Most of my
production work has been on multi-tenant platforms — migration engines, query performance, and
the security and test coverage that keep them trustworthy.

Recently I shipped route-binding migrations and API performance work at Profound, and I maintain
[pyxTrace](https://github.com/AbhineetSaha/pyxTrace), an open-source Python runtime tracing
toolkit published on PyPI.

## Experience

### Software Engineer, Independent Contractor

**Cooper Square Technologies Inc. (Profound)** · Remote, India · Jan 2026 – Aug 2026

`PostgreSQL` `tRPC`

- **Route-binding migration engine** — turned destructive URL changes into a confidence-scored, reviewable workflow, preventing broken content bindings.
- **API performance** — eliminated N+1 queries, added indexes and batching, and fixed cross-tenant scans across endpoints with 1.8–6.5s p99 latency.
- **Reliability & security** — authored 34% of the test suite, implemented multi-tenant database scoping, and remediated 2 SSRF vulnerabilities, 1 XSS vector, and 1 CVE.
- **Platform migrations** — rebuilt the Media Library with a blue-green migration and co-led the Sanity-to-ProfoundCMS migration, contributing ~48% of the CMS integration layer.

## Featured Projects

### [pyxTrace](https://github.com/AbhineetSaha/pyxTrace) · [PyPI](https://pypi.org/project/pyxtrace/)

`Python` `Typer` `Streamlit` `GitHub Actions`

Open-source Python runtime tracing and visualization toolkit.

- Combines bytecode tracing, heap profiling, and OS syscall monitoring with real-time visualization
- Pluggable Linux, macOS, Windows, and fallback backends for graceful cross-platform compatibility
- Configurable tracing modes to balance profiling depth against runtime overhead
- Automated PyPI releases via GitHub Actions, plus JSONL session recording with offline replay

### [SafeRoute India](https://github.com/AbhineetSaha/SafeRoute-India)

`FastAPI` `PostGIS` `LightGBM` `Redis` `React` `Docker`

Accident-aware route scoring platform built on Indian government accident datasets.

- Scores routes on a 0–100 safety scale, weighing severity, distance, recency, and time-of-day risk
- PostGIS geospatial engine analyzes accident exposure along route corridors and identifies hotspots
- LightGBM risk pipeline over 24 engineered features spanning severity, causal factors, temporal patterns, weather, and emergency infrastructure
- 13 REST APIs for route scoring, hotspot analysis, departure-time optimization, risk forecasting, SOS context, and community incident reporting

### [DocDrift](https://github.com/AbhineetSaha/DocDrift)

`FastAPI` `Supabase` `Next.js`

Document-grounded chat platform — upload PDFs, curate context, and get Gemini-powered answers.
Split across [backend](https://github.com/AbhineetSaha/Backend) and
[frontend](https://github.com/AbhineetSaha/Frontend) repositories.

### [Scene Text Reading System](https://github.com/AbhineetSaha/End-to-End-text-reading-system-on-natural-scene-images)

`Python` `Computer Vision`

Capstone project: end-to-end text detection and recognition on natural scene images.

## Technical Skills

| Area | Technologies |
| --- | --- |
| Languages | TypeScript · Python · JavaScript · Java · SQL |
| Backend | Node.js · Express.js · FastAPI · tRPC |
| Frontend | React · Next.js · Tailwind CSS |
| Databases | PostgreSQL · PostGIS · Redis · Supabase |
| Tools | Git · GitHub Actions · Docker · Linux · Bun |

## Certifications

- Microsoft Certified: **Azure AI Engineer Associate**
- Oracle Cloud Infrastructure 2025 Certified **AI Foundations Associate**

## Leadership

### Technical Lead — Mozilla Open Source Community, VIT-AP

- Led a cross-functional team of 12+ members
- Contributed to global open-source projects
- Mentored juniors on GitHub workflows and software architecture

### Finalist — Google Dev Sprint '25

- Built and presented a scalable prototype under time constraints
- Judged on technical execution, creativity, and design-led problem solving
