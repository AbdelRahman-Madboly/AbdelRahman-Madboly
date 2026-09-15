<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&height=220&color=0:071A2B,45:0B7285,100:22B8CF&text=Abdel%20Rahman%20Madboly&fontColor=FFFFFF&fontSize=42&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20Applied%20AI%20%E2%80%A2%20Production%20Systems&descAlignY=60&descSize=18&animation=twinkling)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2600&pause=900&color=22B8CF&center=true&vCenter=true&width=860&lines=Software+Engineer+at+VOTECHX.+Building+VINEX.;Arabic-first+products+that+run+for+real+businesses.;Specs+before+code.+Tests+before+deploy.;Deepfake+detection+and+Arabic+tokenization+research+on+the+side.)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdllrhmh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdllrhmh)
[![Email](https://img.shields.io/badge/Email-abdllrhmh24%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdllrhmh24@gmail.com)
[![Location](https://img.shields.io/badge/Cairo-Egypt-0B7285?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
<br>
[![VOTECHX](https://img.shields.io/badge/VOTECHX-votechx.com-071A2B?style=for-the-badge&logoColor=white)](https://votechx.com)
[![VINEX](https://img.shields.io/badge/VINEX-GitHub%20org-22B8CF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VINEX-Tech)
[![Profile views](https://komarev.com/ghpvc/?username=AbdelRahman-Madboly&style=for-the-badge&color=0B7285&label=Views)](https://github.com/AbdelRahman-Madboly)

</div>

## About

Software Engineer at **[VOTECHX](https://votechx.com)**, Ismailia, Egypt, where I build and operate the company's products end to end: a clinic-management SaaS, an AI outreach CRM, a WhatsApp reservation assistant, an inventory system, and the shared infrastructure they run on. Alongside that I am building **[VINEX](https://github.com/VINEX-Tech)**, a product and engineering studio for Egyptian businesses, and doing a Master's at Suez Canal University. My own research runs on the side: deepfake detection and Arabic tokenization.

Most of what I ship is Arabic and right-to-left from the first screen, private by default, and delivered with tests, CI, and a deploy pipeline. Below is a selection, not the full list. Several repositories are private because they hold client and patient data.

**Now:** building the SIS platform at VOTECHX, cardscan at VINEX, and running the AraFT experiments.

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:071A2B,50:0B7285,100:22B8CF" width="100%" alt="">

## Production systems at VOTECHX

| Project | What it does | Stack | Where |
|---|---|---|---|
| **Smile Island** | Multi-workspace clinic-management SaaS for Egyptian dental clinics: reception, patients, doctors, finance, stock, and HR in one Arabic-RTL workspace. | <img src="https://skillicons.dev/icons?i=nextjs,nestjs,ts,prisma,postgres,docker,githubactions&perline=7" height="26" alt="Next.js, NestJS, TypeScript, Prisma, PostgreSQL, Docker, GitHub Actions"><br><sub>Next.js · NestJS · Prisma · PostgreSQL · Docker · GitHub Actions</sub> | [Live](https://app.votechx.com) · private repo |
| **Clinic Assistant** | AI reservation assistant for clinics on WhatsApp and web, with an operator console for the clinic's staff. | <img src="https://skillicons.dev/icons?i=nestjs,react,ts,postgres,docker&perline=5" height="26" alt="NestJS, React, TypeScript, PostgreSQL, Docker"><br><sub>NestJS · React · PostgreSQL + pgvector · WhatsApp API</sub> | [Live](https://chatbot.votechx.com) · private repo |
| **si-reach** | Multi-tenant B2B lead-generation and outreach CRM. Scrapes Google Maps across Egypt's 27 governorates, scores leads, sends personalised Arabic WhatsApp outreach, answers replies with an AI agent, and escalates to a human operator. | <img src="https://skillicons.dev/icons?i=fastapi,py,postgres,react,docker&perline=5" height="26" alt="FastAPI, Python, PostgreSQL, React, Docker"><br><sub>FastAPI · n8n · PostgreSQL · React · LLM classification and routing</sub> | Private repo · feeds the Smile Island trial funnel |
| **Inventory** | Warehouse management for one administrator running several independent inventories. Workers file daily stock and cash reports from an offline-first Arabic-RTL mobile app; the API derives sales, shortfall, and balance, and an administrator approves before anything applies. | <img src="https://skillicons.dev/icons?i=nestjs,prisma,postgres,flutter,dart&perline=5" height="26" alt="NestJS, Prisma, PostgreSQL, Flutter, Dart"><br><sub>NestJS · Prisma · PostgreSQL · Flutter</sub> | Private repos (backend + mobile) |
| **SIS platform** | Student information system for Egyptian public universities: one deployment serving sixteen faculties by configuration, twenty applications specified rule by rule before any code. | <img src="https://skillicons.dev/icons?i=dotnet,cs,docker,githubactions&perline=4" height="26" alt=".NET, C#, Docker, GitHub Actions"><br><sub>ASP.NET Core · SQL Server · modular monolith</sub> | In build (verified skeleton, Sep 2026) · private repo |
| **VOTECHX website** | The bilingual company site, statically built, English at the root and Arabic under `/ar/`. | <img src="https://skillicons.dev/icons?i=astro,ts,html,css,nginx&perline=5" height="26" alt="Astro, TypeScript, HTML, CSS, nginx"><br><sub>Astro · static output · nginx</sub> | [Live](https://votechx.com) · private repo |

## Founder work at VINEX

| Project | What it does | Stack | Status |
|---|---|---|---|
| **Abaad ERP** | Self-hosted ERP for 3D-printing shops: quote-to-delivery orders with per-gram pricing and PDFs, filament inventory, printer depreciation and wear, expenses, and a live finance dashboard. | <img src="https://skillicons.dev/icons?i=py,fastapi,sqlite,react,ts,vite,tailwind&perline=7" height="26" alt="Python, FastAPI, SQLite, React, TypeScript, Vite, Tailwind"><br><sub>Python · FastAPI · SQLite (WAL) · React · Vite · shadcn/ui</sub> | v6.0.0 · private |
| **Abaad Platform** | Public website and ordering platform for Abaad. The quoted price is the maximum the customer pays, enforced by a versioned pricing function and database check constraints rather than by policy. | <img src="https://skillicons.dev/icons?i=nextjs,ts,py,docker&perline=4" height="26" alt="Next.js, TypeScript, Python, Docker"><br><sub>Next.js 15 · Drizzle · Python slicing worker · Caddy</sub> | Private |
| **EWIMS** | Encrypted, offline-first workforce insurance records for a controlled three-PC Windows pilot: per-device SQLCipher stores, one-use provisioning, authenticated HTTPS sync, no public cloud. | <img src="https://skillicons.dev/icons?i=py,sqlite,windows&perline=3" height="26" alt="Python, SQLite, Windows"><br><sub>Python · SQLCipher · Windows</sub> | Pilot v0.4.0 · private |
| **cardscan** | Captures business cards at trade fairs, extracts and verifies the contact details, and stores them in a CRM that keeps working when the hall has no signal. | <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,ts,nodejs&perline=4" height="26" alt="Kotlin, Android Studio, TypeScript, Node.js"><br><sub>Kotlin · TypeScript · shared contact schema</sub> | In build · private |
| **Monion** | Offline-first university bus platform: driver identity, passenger attendance, live fleet operations, device qualification, and safety monitoring. | <img src="https://skillicons.dev/icons?i=flutter,dart,nestjs,prisma,react,postgres,docker&perline=7" height="26" alt="Flutter, Dart, NestJS, Prisma, React, PostgreSQL, Docker"><br><sub>Flutter · NestJS · Prisma · React · PostgreSQL · MinIO</sub> | Private |
| **ORIVEX** | Pharmacy operations product. Domain rules, safety classification, and data contracts are written and tested; the application layer is still planned. | <img src="https://skillicons.dev/icons?i=nodejs,prisma,md&perline=3" height="26" alt="Node.js, Prisma, Markdown"><br><sub>Node.js · Prisma · documented decisions</sub> | Design stage · [public docs](https://github.com/AbdelRahman-Madboly/PharmBot-docs) |

## Research

| Project | Question | Stack | Status |
|---|---|---|---|
| **WaveGate** | Can a wavelet boundary gate, trained on real faces only with self-blended pseudo-fakes, generalise deepfake detection to manipulation methods it has never seen? | <img src="https://skillicons.dev/icons?i=pytorch,py&perline=2" height="26" alt="PyTorch, Python"><br><sub>PyTorch · EfficientNet-B5 · 2-level DWT · optional temporal state-space head</sub> | Reproducible baseline committed · results not yet published |
| **AraFT** | How much of an LLM's Arabic weakness is tokenizer fertility, and how much is data? A compute-matched, byte-matched, dose-controlled intervention study. | <img src="https://skillicons.dev/icons?i=pytorch,py,bash&perline=3" height="26" alt="PyTorch, Python, Bash"><br><sub>PyTorch · Hugging Face · Qwen 3.5 substrates</sub> | In progress · targeting a Q1 journal |
| **USV link manager** | Which link should a maritime robot use right now: cellular, satellite, both, or store and forward? A mission-aware classifier with a physics-based safety guard. | <img src="https://skillicons.dev/icons?i=py&perline=1" height="26" alt="Python"><br><sub>Pure-NumPy MLP · early stopping · guarded inference</sub> | 97% held-out test accuracy · private |

## Edge and IoT

| Project | What it does | Stack | Where |
|---|---|---|---|
| **FarmLens** | Solar-powered edge-AI field node for crop health: camera-based disease detection fused with soil sensor readings into one risk score, plus a Flutter companion app. Software validated end to end against a mock node; field hardware not yet built. | <img src="https://skillicons.dev/icons?i=raspberrypi,fastapi,py,cpp,flutter&perline=5" height="26" alt="Raspberry Pi, FastAPI, Python, C++, Flutter"><br><sub>Raspberry Pi · FastAPI · YOLOv11n INT8 · ESP32 · Flutter</sub> | [node](https://github.com/AbdelRahman-Madboly/FarmLens-node) · [app](https://github.com/AbdelRahman-Madboly/FarmLens-app) |
| **Nazer** | Vehicle-mounted box that detects speeding violations and reports them to a cloud backend, with a driver app and an admin site. | <img src="https://skillicons.dev/icons?i=cpp,fastapi,py,flutter,react&perline=5" height="26" alt="C++, FastAPI, Python, Flutter, React"><br><sub>ESP32 · GPS + IMU · C++ · FastAPI · Flutter · React</sub> | Private |

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:071A2B,50:0B7285,100:22B8CF" width="100%" alt="">

## How I work

- **Specs and decisions before code.** Architecture decision records, acceptance criteria, and a task board per product, kept in a companion repo the code must answer to.
- **Private by default, sanitised proof only.** Client and patient data never leave the product. Public repos get a secret scan in CI.
- **Arabic and right-to-left from the first page,** not as a translation layer added later.
- **Every product ships with a pipeline:** tests against a real database in CI, images built once and pulled by the server, backups, and a rollback path.
- **Numbers are measured or version-tagged.** Targets stay labelled as targets.

## Toolkit

<table align="center">
  <tr>
    <th align="left">Area</th>
    <th align="left">Icons</th>
    <th align="left">Tools</th>
  </tr>
  <tr>
    <td><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,ts,cs,cpp,kotlin,dart,bash&perline=7" height="34" alt="Python, TypeScript, C#, C++, Kotlin, Dart, Bash"></td>
    <td>Python · TypeScript · C# · C++ · Kotlin · Dart · Bash · SQL</td>
  </tr>
  <tr>
    <td><b>AI and ML</b></td>
    <td><img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv,tensorflow&perline=4" height="34" alt="PyTorch, scikit-learn, OpenCV, TensorFlow"></td>
    <td>PyTorch · YOLO · OpenCV · scikit-learn · RAG and agent workflows · LLM classification and routing · tokenizer research</td>
  </tr>
  <tr>
    <td><b>Backend and web</b></td>
    <td><img src="https://skillicons.dev/icons?i=fastapi,nestjs,nextjs,react,dotnet,nodejs,astro&perline=7" height="34" alt="FastAPI, NestJS, Next.js, React, .NET, Node.js, Astro"></td>
    <td>FastAPI · NestJS · Next.js · React · ASP.NET Core · Node.js · Astro · n8n</td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,sqlite,prisma&perline=3" height="34" alt="PostgreSQL, SQLite, Prisma"></td>
    <td>PostgreSQL · pgvector · SQLite · SQLCipher · SQL Server · Prisma · Drizzle</td>
  </tr>
  <tr>
    <td><b>Operations</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,linux,ubuntu,nginx,githubactions,git,cloudflare&perline=7" height="34" alt="Docker, Linux, Ubuntu, nginx, GitHub Actions, Git, Cloudflare"></td>
    <td>Docker Compose · nginx · Caddy · GitHub Actions · Linux VPS · Cloudflare · backups and rollback</td>
  </tr>
  <tr>
    <td><b>Edge and mobile</b></td>
    <td><img src="https://skillicons.dev/icons?i=raspberrypi,arduino,cpp,flutter,kotlin,androidstudio&perline=6" height="34" alt="Raspberry Pi, Arduino, C++, Flutter, Kotlin, Android Studio"></td>
    <td>ESP32 · Raspberry Pi · C++ · PlatformIO · Flutter · Kotlin</td>
  </tr>
</table>

I also keep a public notebook of the fundamentals: [codebricks-linux](https://github.com/AbdelRahman-Madboly/codebricks-linux) is a 19-chapter hands-on Linux course written by hand in the terminal, currently in progress.

## GitHub activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=AbdelRahman-Madboly&theme=transparent&hide_border=true&stroke=22B8CF&ring=22B8CF&fire=FF922B&currStreakLabel=22B8CF&sideLabels=4DABF7)](https://git.io/streak-stats)

![Contribution snake](https://raw.githubusercontent.com/AbdelRahman-Madboly/AbdelRahman-Madboly/gh-pages/github-contribution-grid-snake-dark.svg#gh-dark-mode-only)
![Contribution snake](https://raw.githubusercontent.com/AbdelRahman-Madboly/AbdelRahman-Madboly/gh-pages/github-contribution-grid-snake.svg#gh-light-mode-only)

</div>

## Get in touch

For AI engineering, backend and platform work, or research collaboration.

<div align="center">

**[LinkedIn](https://linkedin.com/in/abdllrhmh) · [Email](mailto:abdllrhmh24@gmail.com) · [VOTECHX](https://votechx.com) · [VINEX](https://github.com/VINEX-Tech) · [Repositories](https://github.com/AbdelRahman-Madboly?tab=repositories)**

![Footer](https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:071A2B,45:0B7285,100:22B8CF)

</div>
