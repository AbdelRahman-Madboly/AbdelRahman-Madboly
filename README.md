<div align="center">

# Abdel Rahman Madboly

**Software and AI Engineer** · Cairo, Egypt

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdllrhmh-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdllrhmh)
[![Email](https://img.shields.io/badge/Email-abdllrhmh24%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abdllrhmh24@gmail.com)

</div>

I build production backends, multi-tenant SaaS and AI automation, and edge AI products that run
from device firmware to the mobile app. Software Engineer at **VOTECHX** and founding engineer at
**VINEX**.

### Open-source products (VINEX)

Hardware, firmware, backend and apps, each in one public repository with CI, printable enclosures
and wiring where there is a device.

<table>
<tr>
<td align="center" width="25%"><a href="https://github.com/VINEX-Tech/nazer"><img src="https://raw.githubusercontent.com/VINEX-Tech/nazer/main/hardware/tracker-box/images/concept-product.jpg" alt="Nazer"><br><b>Nazer</b></a><br><sub>Vehicle tracker</sub></td>
<td align="center" width="25%"><a href="https://github.com/VINEX-Tech/farmlens"><img src="https://raw.githubusercontent.com/VINEX-Tech/farmlens/main/hardware/pi-cam-case/images/concept-field.jpg" alt="FarmLens"><br><b>FarmLens</b></a><br><sub>Crop-health node</sub></td>
<td align="center" width="25%"><a href="https://github.com/VINEX-Tech/swimtrack"><img src="https://raw.githubusercontent.com/VINEX-Tech/swimtrack/main/docs/images/concept-kit.jpg" alt="SwimTrack"><br><b>SwimTrack</b></a><br><sub>Swim tracker</sub></td>
<td align="center" width="25%"><a href="https://github.com/VINEX-Tech/monion"><img src="https://raw.githubusercontent.com/VINEX-Tech/monion/main/docs/images/concept-bus-door.jpg" alt="Monion"><br><b>Monion</b></a><br><sub>Bus attendance</sub></td>
</tr>
</table>

| Project | What it does | Stack |
|---|---|---|
| **[Nazer](https://github.com/VINEX-Tech/nazer)** | Vehicle tracker: ESP32 with GPS, IMU, GPRS and BLE, speed limits looked up on the device from OpenStreetMap, FastAPI backend, React admin map, Flutter app, sealed printed enclosure | ESP32 · FastAPI · React · Flutter · CAD |
| **[FarmLens](https://github.com/VINEX-Tech/farmlens)** | Crop-health node: Raspberry Pi server fusing a camera score with soil and water readings into one risk score, ESP32 sensor firmware, Flutter app with a live camera over a phone hotspot, outdoor printed case | Raspberry Pi · FastAPI · ESP32 · Flutter · CAD |
| **[SwimTrack](https://github.com/VINEX-Tech/swimtrack)** | Wrist-worn swim tracker: stroke and lap detection on an ESP32-S2, a decision-tree stroke classifier trained on self-collected IMU data and exported to C++, Flutter app | ESP32-S2 · IMU · Python ML · Flutter |
| **[Monion](https://github.com/VINEX-Tech/monion)** | University bus attendance: Flutter card scanner, NestJS API with idempotent IN/OUT records, Prisma schema checked against PostgreSQL in CI, React dashboard | Flutter · NestJS · Prisma · React |

<sub>Pictures are concept images of each product in use. Status, tests and limits are in each repository.</sub>

### Personal apps and tools

Apps I built for my own phone and laptop and use every day. Each repository has screenshots from
demo data, tests in CI and install steps.

<table>
<tr>
<td align="center" width="14%"><a href="https://github.com/AbdelRahman-Madboly/charge-monitor"><img src="https://raw.githubusercontent.com/AbdelRahman-Madboly/charge-monitor/main/docs/readme-icon.png" width="64" alt="Charge Monitor"><br><b>Charge Monitor</b></a><br><sub>Android</sub></td>
<td align="center" width="14%"><a href="https://github.com/AbdelRahman-Madboly/spending-tracker"><img src="https://raw.githubusercontent.com/AbdelRahman-Madboly/spending-tracker/master/docs/readme-icon.png" width="64" alt="Spending Tracker"><br><b>Spending Tracker</b></a><br><sub>Android</sub></td>
<td align="center" width="14%"><a href="https://github.com/AbdelRahman-Madboly/netusage"><img src="https://raw.githubusercontent.com/AbdelRahman-Madboly/netusage/main/docs/readme-icon.png" width="64" alt="netusage"><br><b>netusage</b></a><br><sub>Linux + Android</sub></td>
<td align="center" width="14%"><a href="https://github.com/AbdelRahman-Madboly/laptop-doctor"><img src="https://raw.githubusercontent.com/AbdelRahman-Madboly/laptop-doctor/main/docs/readme-icon.png" width="64" alt="Laptop Doctor"><br><b>Laptop Doctor</b></a><br><sub>Linux</sub></td>
<td align="center" width="14%"><a href="https://github.com/AbdelRahman-Madboly/tools-hub"><img src="https://raw.githubusercontent.com/AbdelRahman-Madboly/tools-hub/master/docs/readme-icon.png" width="64" alt="Tools Hub"><br><b>Tools Hub</b></a><br><sub>Linux</sub></td>
<td align="center" width="14%"><a href="https://github.com/AbdelRahman-Madboly/pdf-to-markdown"><img src="https://raw.githubusercontent.com/AbdelRahman-Madboly/pdf-to-markdown/master/docs/readme-icon.png" width="64" alt="PDF to Markdown"><br><b>PDF to Markdown</b></a><br><sub>Linux</sub></td>
<td align="center" width="14%"><a href="https://github.com/AbdelRahman-Madboly/video-collector"><img src="https://raw.githubusercontent.com/AbdelRahman-Madboly/video-collector/master/docs/readme-icon.png" width="64" alt="Video Collector"><br><b>Video Collector</b></a><br><sub>Linux</sub></td>
</tr>
</table>

| App | What it does | Stack |
|---|---|---|
| **[Charge Monitor](https://github.com/AbdelRahman-Madboly/charge-monitor)** | Logs every phone charge per source and measures real power bank capacity and charger output, with a 3D-printed power bank case | Kotlin · Android · Room |
| **[Spending Tracker](https://github.com/AbdelRahman-Madboly/spending-tracker)** | Offline-first Arabic RTL spending log: two-tap entry, voice, photo, barcode and note capture, Excel export | Flutter · Drift (SQLite) |
| **[netusage](https://github.com/AbdelRahman-Madboly/netusage)** | Per-app internet accounting on Linux with eBPF, billing-cycle limits, a GTK dashboard and an Android companion | Python · eBPF · GTK · Kotlin |
| **[Laptop Doctor](https://github.com/AbdelRahman-Madboly/laptop-doctor)** | Health checks, live monitor, crash triage and daily reports for an Ubuntu laptop, read-only by default | Python · PySide6 · systemd |

### Selected work

| Project | What it does | Stack |
|---|---|---|
| **Clinic SaaS** | Arabic RTL multi-tenant platform for dental clinics: appointments, patients, finance, stock, HR | Next.js · NestJS · Prisma · PostgreSQL · CI |
| **Clinic assistant** | AI reservation assistant for clinics on WhatsApp and web, with an operator console | NestJS · React · PostgreSQL + pgvector |
| **AI outreach CRM** | Lead collection, Arabic WhatsApp outreach, LLM reply classification and an AI agent with human escalation | FastAPI · n8n · PostgreSQL · React |
| **Workforce records system** | Encrypted, offline-first system that replaced an MS Access database; migrated 4,928 employee records | Python · SQLCipher · Windows CI |
| **3D-printing ERP** | Orders, filament stock, printers and finance for a business that runs on it daily | Python · FastAPI · SQLite |
| **WaveGate** | Deepfake detection research: wavelet boundary gating, trained on real faces only | PyTorch |
| **USV link manager** | Mission-aware classifier choosing cellular or satellite for unmanned boats; 97% held-out accuracy on simulated link data | Python · NumPy MLP |

The work above is private client or employer code. Walkthroughs on request.

### Stack

**AI:** PyTorch · OpenCV · YOLO · LLM agents · RAG · n8n
**Backend:** Python · FastAPI · TypeScript · NestJS · C#/.NET · PostgreSQL · Prisma
**Apps:** Next.js · React · Flutter · Kotlin · Arabic RTL
**Ops and edge:** Docker · Linux · VPS · GitHub Actions · ESP32 · Raspberry Pi
