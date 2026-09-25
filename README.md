# Dmitry Doronin

**Senior Software Engineer @ Postman**

New York, NY · [doronindm@gmail.com](mailto:doronindm@gmail.com) · [LinkedIn](https://linkedin.com/in/ddoronin) · [Medium](https://medium.com/@dmitrydoronin) · [just-call.app](https://just-call.app) · [qcsku.com](https://qcsku.com) · [int-64.com](https://int-64.com)

Full-stack engineer with 15 years of experience building API platforms, developer tooling, and scalable real-time systems. Founder of qcsku.com and int-64.com. Expert in React, TypeScript, Node.js, Scala, Elixir, and .NET/C#, with Rust experience from personal projects. Proven track record of leading high-impact initiatives end-to-end — from architecture design through production — and driving cross-functional teams at Postman, Dataminr, Goldman Sachs, and early-stage startups.

## Experience

### Senior FDE | Cloudflare — New York, NY

**July 2026 – Today**


### Senior Software Engineer | Postman — New York, NY

**Mar 2024 – May 2026**
`React`, `TypeScript`, `Node.js`, `MySQL`, `Kubernetes`, `AWS`, `SQS`, `Kafka`, `Redis`

- Led **Project Atlas**, an agentic data pipeline that autonomously discovers and onboards API publishers at scale — capable of processing up to 500 companies per day — accelerating Postman's AI-first network growth strategy. The crawling algorithm proved generalizable enough to share via API with the API Products initiative.
- Designed and built **Self-Serve Verification**, a fault-tolerant async engine (Photon + MySQL + SQS) with a pluggable rules system that automated publisher verification for 200+ organizations, reducing turnaround from days to minutes. One of the first production Photon deployments at Postman — architectural patterns adopted by 4+ teams across the Public API Network. Built a Support Dashboard that reduced publisher unblocking time by 80%.
- Solo-engineered **Publisher Intel**, a 4-stage AI classification pipeline that filtered 98% noise from 300K+ publisher records, transforming executive analytics accuracy across all PAN dashboards. Delivered in 6 weeks from concept to production with 95%+ accuracy and 70–80% cost reduction via content-hash optimization.
- Designed **Publisher Expert**, an AI agent providing contextual guidance during the verification workflow. Invented a base64 prompt parameter pattern that was adopted platform-wide by Postman's Agent Mode infrastructure.
- Led cross-team RFCs and architecture reviews; presented at Engineering Forums; mentored engineers to independent feature ownership. **Zero major production incidents** across all initiatives.

### Head of Engineering | Factored Quality — New York, NY

**Mar 2023 – Mar 2024**
`Elixir`, `Phoenix`, `LiveView`, `Render`

- Led a team of 4 engineers building a real-time collaboration platform connecting brands, agencies, and factories for supply-chain quality control.
- Integrated AI-powered insights via OpenAI, reducing manual inspection data entry from hours to seconds and improving defect detection accuracy.
- Designed fault-tolerant integrations with Salesforce, NetSuite, and Anvyl, ensuring reliable data synchronization across enterprise systems.
- Defined technical direction and release cadence, translating user feedback into a product roadmap that drove customer retention.

### Senior Software Engineer | Dataminr — New York, NY

**Nov 2021 – Jan 2023**
`Elixir/Erlang`, `TypeScript`, `Node.js`, `React`, `GraphQL`, `AWS`, `ECS`, `Grafana`, `Sentry`

- Led the architecture and development of **Service Junction**, a high-throughput BFF service in Elixir handling up to 100K req/s, aggregating data from dozens of microservices for all user-facing products. Implemented circuit breakers for fault tolerance and libcluster-based node discovery for horizontal scaling on ECS.
- Designed dual **REST** (OpenAPI v3) and **GraphQL** APIs with security-first schema validation, reducing mobile network traffic by 2× via GraphQL and preventing internal data exposure through strict response whitelisting.
- Led critical pre-IPO initiatives — **Cyber Watchlists**, **Travel Security**, and **Regionalization** — enabling Dataminr's expansion into the EU and strengthening its position in the global cyber and travel security markets.
- Introduced Sentry as the organization-wide bug tracking standard, built Grafana monitoring dashboards backed by Prometheus and InfluxDB, and developed a CI/CD pipeline with a custom Chrome extension for transparent multi-region deployments.
- Created and led weekly Elixir training sessions for front-end engineers, authored 10+ engineering design documents, and contributed Playwright-based visual regression testing to the shared UI Design System.

### Founding Engineer | Smartrr — New York, NY

**Dec 2020 – Oct 2021**
`Node.js`, `TypeScript`, `GraphQL`, `React`, `Postgres`, `Kubernetes`, `GCP`

- Joined as the first full-time engineer and designed the core platform architecture for a Shopify subscription service — wrote Helm charts for Kubernetes on GCP, configured CloudFlare CDN, and established trunk-based CI/CD for rapid iteration.
- Architected and built the **billing engine** with idempotent operations to guarantee exactly-once execution across a multi-node Kubernetes cluster, enabling reliable recurring billing at scale.
- Gathered requirements directly from client calls and investor pitches, then designed and shipped advanced subscription features (add-ons, skips, anchor dates, gifts) implemented as composable RRule functions — differentiating Smartrr from competitors and contributing to the company's **$70M Series A** valuation.

### Staff Software Engineer | Reonomy — New York, NY

**Feb 2019 – Dec 2020**
`Scala`, `Spark`, `GraphX`, `Python`, `TypeScript`, `React`, `RxJS`, `ElasticSearch`, `Postgres`, `Airflow`, `AWS`

- Promoted from Senior to Staff within the first year. Created and open-sourced **reactive-hooks**, an RxJS-to-React bridge library that became the foundation of the entire front-end — featured in the company blog "The Road to React."
- Led the **Ownership Portfolios** initiative, building Spark and GraphX data jobs that constructed an in-memory knowledge graph of real estate, people, and companies — reducing portfolio generation from weeks of manual analyst work to 5 hours of automated computation.
- Optimized Scala/Spark data pipelines by rebalancing data partitioning across 20–50 node clusters, accelerating the data release cadence from monthly to weekly and significantly improving data freshness for customers. _Reonomy was acquired by Altus Group for $200M in 2021._

### EPAM Systems — Various Clients

**Feb 2011 – Feb 2019**

#### Lead Software Engineer | Goldman Sachs — New York, NY

**Jan 2016 – Feb 2019**
`Scala`, `Akka`, `Vert.x`, `React`, `MobX`, `TypeScript`, `MongoDB`

- Built performant React components for **Marquee FX Trading**, Goldman Sachs' institutional trading and risk-management platform.
- Developed a scalable real-time back-end with Scala, Akka, and Vert.x for **SIMON**, a structured investment platform that later spun off as an independent company ([simon.io](https://simon.io)). Migrated architecture from RabbitMQ-based microservices to a monolith to better support WebSocket-driven real-time features.

#### Senior Software Engineer | Thomson Reuters — Remote

**Aug 2014 – Dec 2015**
`JavaScript`, `AngularJS`, `Node.js`, `ASP.NET`, `Less`

- Led a team of 4 engineers and 2 QAs building **Eikon Apps** — Portfolio Dashboard, Fundamentals, Aggregate Report — and a high-performance virtualized grid library capable of rendering millions of rows and columns, used across all Thomson Reuters products.
- Achieved significant performance gains by offloading real-time price and analytics computations to Web Workers, with all performance-critical code written in vanilla JavaScript.

#### Software Engineer | Telligent — Remote

**Sep 2011 – Jul 2014**
`ASP.NET`, `C#`, `MSSQL`, `jQuery`, `JavaScript`

- Developed core features, plugins, and scripted widgets for Telligent Evolution (Community Server), a social network CMS platform. Promoted to Senior Software Engineer after two years.

## Personal Projects

> Founded and built while holding full-time senior engineering roles.

**[qcsku.com](https://qcsku.com)** — 2024
`Node.js`, `Rust`, `gRPC`, `GraphQL`, `Kubernetes`, `Postgres`, `Redis`, `RabbitMQ`

- Designed and built a multi-tenant collaboration platform with GraphQL and gRPC APIs, event-driven processing, and real-time messaging — focusing on scalability, reliability, and developer ergonomics.

**[int-64.com](https://int-64.com)** — 2025
`Node.js`, `GraphQL`, `Kubernetes`, `Postgres`, `Redis`

- Designed a no-code AI agent platform with a GraphQL control plane, extensible tool execution model, and multi-tenant infrastructure enabling secure, composable agent workflows.


## Publications & Open Source

- [Building AI Agents on GraphQL: A Comparative Study of Two Architectural Approaches](https://medium.com/itnext/building-ai-agents-on-graphql-a-comparative-study-of-two-architectural-approaches-f58884c10a49) — Medium
- [Dependency Injection in React](https://medium.com/itnext/dependency-injection-in-react-6fcdbd2005e6) — Medium
- [Reactive Hooks](https://www.npmjs.com/package/@reonomy/reactive-hooks) — Open-source RxJS-inspired state management library for React (NPM)

**Academic Publications (IEEE):**

1. A.N. Savin, I.A. Nakrap, D.M. Doronin — _The equivalent circuit parameters calculation of a coupled cavity chain using electrodynamic characteristics_ — IEEE, 2010. [Link](https://ieeexplore.ieee.org/document/5632593)
2. A.N. Savin, I.A. Nakrap, D.M. Doronin — _The high-order optimal design of experiment development on the base of regular simplex for the slow-wave structures characteristics modeling_ — IEEE, 2010. [Link](https://ieeexplore.ieee.org/document/5632591)
3. M.V. Davidovich, A.N. Savin, D.M. Doronin — _Electromagnetic properties of metallic photonic crystals_ — IEEE, 2010. [Link](https://ieeexplore.ieee.org/document/5632577)

## Education

**Ph.D. (ABD)** – Radiophysics and Electronics, Saratov State University, 2010–2013

**Master's Degree** – Radiophysics and Electronics, 2005–2010

Author of 14 publications in electrodynamics, mathematics, and computer science — [ResearchGate](https://www.researchgate.net/scientific-contributions/2013742207_D_M_Doronin) · [eLibrary](https://elibrary.ru/item.asp?id=15117920)
