# Lucas Paes Januzi

**Tech Lead & Software Architect** · Healthcare integrations

![Profile Views](https://komarev.com/ghpvc/?username=lucaspaesj&color=00d4ff&style=flat-square&label=Profile+Views)

---

Half of what I build exists because the system on the other side has no API.

I work on healthcare integrations. On one side, a clinic requesting authorization for an exam. On the other, an insurance payer portal that only speaks HTML, TISS over SOAP, magnetic-stripe card tokens, patient biometrics. My job is turning that mess into clean data inside the platform a clinic uses every day.

That shaped how I work. I do not build elegant integrations. I build integrations that survive the portal changing its layout on a Friday night.

Today I am Tech Lead and architect of the product: I sit with the client and decide on the spot what is feasible, write the requirement and the technical analysis, build it, review what the team ships, and sign off on the production deploy.

---

### Things I have shipped

- **Facial and fingerprint biometrics SDKs** embedded into partner portals through an iframe with a strict CSP, identifying a patient without them typing anything.
- **Reverse-engineering automation** of manual client routines. Hours became minutes, and it showed up in their revenue.
- **AI in the product** — microservices that read medical orders and return structured, ready-to-consume data.
- **A browser extension published on the Chrome Web Store**, cleared through Google's single-purpose and privacy policy review.
- **Corporate SSO with Microsoft Entra ID** and patient notifications over the WhatsApp Cloud API, with a Meta-approved template.
- **Payer portal crawlers** in Node.js, each with its own authentication rules, layout and creative ways of breaking.
- **The release pipeline** — Bitbucket CI/CD to dev, staging and production; containers on AWS (ECS, ECR, EC2, CloudWatch) and Azure App Service.

---

### Experience

**Tech Lead & Software Architect** — IconCode · Remote
*Apr 2026 – present*

Architecture of the product and technical leadership of the team. Full cycle: client conversations with decision weight, requirements and technical analysis, hands-on building, code review across every front (front end, back end, services and crawlers), and ownership of the production release. Team guidance and technical mentoring.

**Frontend & Crawler Developer** — IconCode · Remote
*Aug 2022 – Apr 2026*

Two fronts for almost four years: the platform's front end in React (UI/UX collaboration, reusable components, testing, deploy, performance) plus a legacy AngularJS codebase, and the crawlers that pull data out of payer portals. Grew into technical leadership of the front end.

**IT Support** — BHS, Samp, Promed · *2017 – 2018*
Where I learned to solve problems under pressure and listen before writing code.

---

### Side project

**Partiu** — an insurance quote-comparison product I built end to end:
[`partiu-corretora`](https://github.com/lucaspaesj/partiu-corretora) (React 19 + Vite + Tailwind) ·
[`partiu-crawler`](https://github.com/lucaspaesj/partiu-crawler) (multi-quote API across partner insurers) ·
[`partiu-admin`](https://github.com/lucaspaesj/partiu-admin) (operational cockpit: health, stats, actions)

---

### On AI

I use it every day and I review it line by line. The hard part was never generating code, it is deciding what gets in. I am the reviewer across every front at work, and I wrote the review standard so the quality bar stays up when I am not in the room.

---

### Stack

| Front end | Back end | Data | Cloud & infra | Domain |
|---|---|---|---|---|
| React · TypeScript | .NET · C# | MySQL · SQL Server | AWS (ECS, ECR, EC2, CloudWatch) | TISS · SOAP |
| JavaScript · AngularJS | Node.js · Express | Oracle · NoSQL | Azure (Entra ID, Blob, App Service) | Patient biometrics |
| HTML · CSS · Redux | REST APIs · SignalR | | Docker · nginx · Bitbucket Pipelines | Web crawlers · Reverse engineering |

**Also:** software architecture · technical leadership · code review · requirements engineering · CI/CD · SOLID · Scrum

---

### Education

- **Technical degree in Computing** — COTEMIG (2015 – 2017)
- **Full-Stack Web Development** — Trybe (2022 – 2023)
- **Law** — Faculdades Milton Campos (2018 – 2021), four years completed, enrollment on hold. Where my ease with contracts, written requirements and holding an argument in a room comes from.

---

### Get in touch

- **LinkedIn:** [linkedin.com/in/lucas-paes-januzi](https://linkedin.com/in/lucas-paes-januzi)
- **Location:** Belo Horizonte, MG, Brazil

Open to Tech Lead, Software Architecture and Senior/Staff Engineering roles. If your problem is making two systems that hate each other talk, I have probably already done it.
