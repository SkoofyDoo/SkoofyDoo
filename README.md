<div align="center">

# Evgeny Kvest
### Full Stack Developer · Berlin 🇩🇪
#### JavaScript · Node.js · React · AWS

![Location](https://img.shields.io/badge/Location-Berlin-111827?style=for-the-badge)
![Languages](https://img.shields.io/badge/Languages-DE%20%7C%20EN%20%7C%20RU-black?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Ready%20to%20Work-22c55e?style=for-the-badge)

</div>

---
Portfolio: https://portfolio-tawny-nine-79.vercel.app/
---

## 👨‍💻 Über mich

Fachinformatiker für Anwendungsentwicklung aus Berlin mit praktischer Erfahrung in JavaScript, React, Node.js und AWS.
Während meiner Ausbildung habe ich vier eigenständige Projekte entwickelt und produktiv eingesetzt – von clientseitiger Videoverarbeitung im Browser bis hin zu headless 3D-Rendering auf dem Server und einer vollständigen Serverless-Architektur auf AWS. Mein Fokus liegt auf durchdachten Architekturentscheidungen, sauberem Code und wartbaren Systemen.

Ich suche ein Team mit echtem Code Review, klaren Strukturen und Raum zum Wachsen.

---

## 🚀 Projekte

### 🔹 [3D-Vorschau-Pipeline](https://github.com/SkoofyDoo/3D-Vorschau-Pipeline-Headless-Rendering-Approval-Workflow) — Headless Rendering & Modellschutz

Serverseitige Pipeline zur automatisierten Vorschaugenerierung von 3D-Medizinscans. Puppeteer startet einen headless Chromium-Prozess, der Three.js mit WebGL2 ausführt und 12 Kameraansichten rendert – texturiert und als Wireframe. Frames werden per `exposeFunction` direkt an Node.js gestreamt und in Nextcloud gespeichert. Ein Express-Proxy schützt die Originaldateien vor direktem Zugriff.

- **Node.js · Express · Puppeteer · Three.js · Nextcloud WebDAV**
- 12 automatische Kameraansichten (6× texturiert + 6× Wireframe)
- Streaming-Architektur via `page.exposeFunction` – kein temporärer Speicher
- Geschützter `/dav/*`-Proxy – Nextcloud-Credentials bleiben ausschließlich serverseitig
- Automatische Modellzentrierung und -skalierung im Renderer

---

### 🔹 [Dallio](https://dallio.de) — Smartes Bürokratie-Tool

Eigenständig entwickelte und deployte Serverless-Webanwendung zur Unterstützung bei deutschen Behördenprozessen – Kündigung, Widerspruch, Rechnungserstellung.

- **AWS Lambda · DynamoDB · S3 · Cognito · Amplify**
- Amazon Bedrock Integration zur KI-gestützten Textanalyse
- Presigned URLs für sicheren Datei-Download
- PDF / CSV Generierung
- CI/CD via AWS Amplify

🌐 [dallio.de](https://dallio.de)

---

### 🔹 [Schärfeanalyse-Pipeline](#) — Automatische Frame-Qualitätsbewertung

Serverseitiges Node.js-Modul zur automatischen Schärfebewertung und Filterung von Video-Frames für medizinische 3D-Photogrammetrie.

- **Node.js · OpenCV.WASM · Sharp**
- Zwei kombinierte Schärfemetriken: Laplacian Variance + Tenengrad
- Relative Filterung (Top-X%) + Anti-Streak-Mechanismus
- ZIP-Archivierung der gefilterten Frames
- Echtzeit-Fortschritts-Tracking via progressMap

---

### 🔹 [VideoSlicer](#) — Clientseitige Frame-Extraktion

React-Komponente zur Frame-Extraktion direkt im Browser – ohne Backend, ohne Upload, ohne externe Bibliotheken.

- **React · Canvas API · HTML5 Video API**
- Vollständig clientseitig – keine Serverkosten, keine Dateiübertragung
- Konfigurierbare Frame-Anzahl je nach Aufnahmetyp
- Kompatibel mit mobilen Browsern (Safari, Chrome Mobile)
- Timeout-Handling, Speicherbereinigung, Fortschrittsanzeige

---

## 🧰 Tech Stack

**Frontend**
JavaScript · React · Vite · Tailwind CSS · HTML5 · CSS3 · React Three Fiber

**Backend**
Node.js · Express · REST API · OpenCV.WASM · Sharp · Puppeteer · Three.js

**Cloud & DevOps**
AWS Lambda · DynamoDB · S3 · Cognito · Amplify · Bedrock · Git · GitHub Actions

**Datenbanken**
MySQL · MongoDB

---

## 🎯 Was ich suche

Eine erste feste Stelle als Junior Developer in einem Team mit echtem Mentoring, Code Reviews und strukturiertem Onboarding.

---

