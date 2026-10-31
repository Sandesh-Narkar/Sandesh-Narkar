<div align="center">

<img src="https://d8it4huxumps7.cloudfront.net/uploads/images/opportunity/banner/6ab0c43d9ff29_neura-x.png?d=1920x557" alt="NEURA X 2026 Global Hackathon 2K26 banner" width="100%"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1D4ED8,100:7C3AED&height=170&section=header&text=VisionGuard%20AI%202.0&fontColor=ffffff&fontSize=46&fontAlignY=38&desc=See%20the%20defect.%20File%20the%20complaint.%20Fix%20the%20city.&descAlignY=60&descSize=16" alt="VisionGuard AI 2.0" width="100%"/>

### 🛡️ Gemini-Powered Multimodal Infrastructure Defect Detection Platform

<a href="https://github.com/szeeshanZ123/visionGuard">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1200&color=3B82F6&center=true&vCenter=true&width=720&lines=Upload+a+photo+of+a+road+or+building;Gemini+Vision+finds+every+visible+defect;OpenCV+draws+severity-coded+overlays;One+click+to+a+formal+civic+complaint+PDF" alt="Typing animation"/>
</a>

<br/>

![NEURA X 2026](https://img.shields.io/badge/NEURA%20X-2026%20Global%20Hackathon%202K26-7C3AED?style=for-the-badge)
![Track](https://img.shields.io/badge/Track-[ADD%20TRACK]-1D4ED8?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Hackathon%20Submission-22C55E?style=for-the-badge)

![Python](https://img.shields.io/badge/Python-3.10--3.14-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.1-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Google-Gemini%20Vision-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Annotation-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-81%20Passing-22C55E?style=flat-square)
![Free Tier](https://img.shields.io/badge/Gemini-Free%20Tier%20Safe-F59E0B?style=flat-square)
![License](https://img.shields.io/badge/License-[ADD%20LICENSE]-blue?style=flat-square)

<br/>

[🚀 **Live Demo**]([ADD: LIVE DEMO URL]) &nbsp;•&nbsp; [🎥 **Demo Video**]([ADD: VIDEO URL]) &nbsp;•&nbsp; [📊 **Presentation**]([ADD: PPT URL]) &nbsp;•&nbsp; [🐞 **Report Issue**](https://github.com/szeeshanZ123/visionGuard/issues)

</div>

---

## ⏱️ The 60-Second Summary

| | |
|---|---|
| **🎯 Problem** | Road and building defects go unreported because inspection is slow and citizens have no easy way to file evidence-backed complaints. |
| **💡 Solution** | Upload one photo. Gemini Vision finds every visible defect, OpenCV marks it, and the citizen files a formal complaint PDF pinned on a live map. |
| **🧠 Core Tech** | Google Gemini Multimodal Vision · OpenCV · Flask · ReportLab · Leaflet.js |
| **✅ Proof** | 81 automated tests passing across AI inference, security and complaint workflows. |
| **🔒 Responsible AI** | Every result is labeled a *preliminary visual assessment*, never a certified survey. |

---

## 📑 Table of Contents

<details>
<summary><b>Click to expand</b></summary>

1. [The Problem](#-the-problem)
2. [Our Solution](#-our-solution)
3. [How It Works](#-how-it-works)
4. [Key Features](#-key-features)
5. [Why VisionGuard Stands Out](#-why-visionguard-stands-out)
6. [Screenshots & Demo](#-screenshots--demo)
7. [System Architecture](#-system-architecture)
8. [Tech Stack](#-tech-stack)
9. [Project Structure](#-project-structure)
10. [Getting Started](#-getting-started)
11. [Usage Walkthrough](#-usage-walkthrough)
12. [Testing & Quality](#-testing--quality)
13. [Results & Impact](#-results--impact)
14. [Limitations](#-limitations)
15. [Roadmap](#-roadmap)
16. [Contributors](#-contributors)
17. [Acknowledgements](#-acknowledgements)
18. [License & Disclaimer](#-license--disclaimer)

</details>

---

## 🚨 The Problem

Potholes, wall cracks, damp patches and spalling concrete are direct safety hazards for drivers, pedestrians and building occupants.

- 🐢 Manual inspections are **slow, subjective and hard to audit**.
- 📭 Citizens rarely have a way to **document evidence** and write a **formal municipal complaint**.
- 📉 Small defects are never reported, so they grow into expensive failures.

> 📌 [ADD: one real statistic about road or building damage in your region, with source]

---

## 💡 Our Solution

**VisionGuard AI** turns any smartphone photo into an **inspection report and an actionable civic complaint**.

> **Elevator pitch:** *Upload a photo, get an AI inspection report, and file a verified civic complaint in one flow.*

| Step | What happens |
|:---:|---|
| 1️⃣ | Citizen uploads a road or building photo |
| 2️⃣ | Gemini Vision identifies and itemizes defects (`[D001]`, `[D002]`) |
| 3️⃣ | OpenCV draws severity-coded boxes on a copy of the photo |
| 4️⃣ | An inspection report is generated (`#VG-xxx`) |
| 5️⃣ | Citizen reads safety guidance **or** files a complaint with PDF and map pin |

---

## 🔄 How It Works

```mermaid
journey
    title Citizen Journey with VisionGuard
    section Capture
      Take a photo of the defect: 5: Citizen
      Upload to Inspection Studio: 5: Citizen
    section Analyse
      Gemini Vision detects defects: 5: AI
      OpenCV renders overlays: 5: AI
      Report is compiled: 5: AI
    section Act
      Read safety guidance: 4: Citizen
      Confirm and file complaint: 5: Citizen
      Download PDF and see map pin: 5: Citizen
```

---

## ✨ Key Features

<table>
<tr>
<td width="50%" valign="top">

### 🔍 Detection
- **Multi-defect itemization** with unique IDs
- **Road:** potholes, longitudinal, transverse and alligator cracks, raveling
- **Building:** wall cracks, dampness, peeling paint, plaster damage, spalling

</td>
<td width="50%" valign="top">

### 🎯 Visual Evidence
- **Non-destructive** OpenCV overlays; the original photo is never altered
- Normalized coordinate validation (`0.0 ≤ x1 < x2 ≤ 1.0`)
- Severity pills with defect IDs

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📝 Reports & Action
- Inspection reference ID (e.g. `#VG-104`)
- Remediation steps and urgency priority
- **Option A:** read guidance only
- **Option B:** verified complaint, PDF and map pin

</td>
<td width="50%" valign="top">

### 🔐 Reliability & Security
- CSRF validation and role-based access control
- API key never exposed to frontend, logs or responses
- **Automatic model fallback** on rate limits
- Duplicate complaint prevention

</td>
</tr>
</table>

### 🚦 Severity Color Code

| Severity | Color | Hex |
|---|---|---|
| Critical | 🔴 Crimson | `#EF4444` |
| High | 🟠 Orange | `#F97316` |
| Moderate | 🟡 Amber | `#F59E0B` |
| Low | 🔵 Blue | `#3B82F6` |
| Uncertain | ⚪ Slate | `#64748B` |

---

## 🏆 Why VisionGuard Stands Out

| Criteria | Manual Inspection | Typical Photo-Upload Apps | **VisionGuard AI 2.0** |
|---|:---:|:---:|:---:|
| Turnaround | Days to weeks | Minutes | ✅ **Minutes** |
| Multiple defects in one image | ❌ Manual notes | ⚠️ Often one label | ✅ **Itemized with IDs and boxes** |
| Annotated visual evidence | ❌ | ⚠️ Plain photo | ✅ **Non-destructive overlay** |
| Formal complaint document | ❌ Written by hand | ❌ Rare | ✅ **Auto-generated PDF** |
| Location tracking | ❌ | ⚠️ Limited | ✅ **Live Leaflet map** |
| Honest AI disclaimers | N/A | ⚠️ Often overclaims | ✅ **Built into every result** |
| Failure handling | N/A | ⚠️ Varies | ✅ **Model fallback, quota and timeout tests** |
| Running cost | High labor | Varies | ✅ **Free-tier-friendly model** |

> ✏️ [EDIT: replace the middle column with the real competitors you researched]

---

## 📸 Screenshots & Demo

<div align="center">

<img src="assets/demo.gif" alt="VisionGuard AI end-to-end demo" width="85%"/>

<br/><br/>

| 🏠 Landing Page | 🧪 Inspection Studio |
|:---:|:---:|
| <img src="assets/screenshots/01-landing.png" alt="Landing page" width="100%"/> | <img src="assets/screenshots/02-inspection-studio.png" alt="Inspection studio" width="100%"/> |
| **🎯 Annotated Overlay** | **📋 AI Inspection Report** |
| <img src="assets/screenshots/03-annotated-overlay.png" alt="Annotated overlay with defect IDs" width="100%"/> | <img src="assets/screenshots/04-ai-report.png" alt="AI inspection report" width="100%"/> |
| **✅ Complaint Confirmation** | **🗺️ Defect Map** |
| <img src="assets/screenshots/05-complaint-modal.png" alt="Complaint confirmation modal" width="100%"/> | <img src="assets/screenshots/06-defect-map.png" alt="Leaflet defect map" width="100%"/> |

</div>

---

## 🏗️ System Architecture

```mermaid
flowchart LR
    A[👤 Citizen uploads photo] --> B[Flask Backend<br/>CSRF + Auth]
    B --> C[Gemini Vision<br/>google-genai SDK]
    C -->|Structured JSON:<br/>defects, severity, boxes| D[Coordinate Validation<br/>normalized 0.0 to 1.0]
    D --> E[OpenCV Annotation<br/>non-destructive overlay]
    E --> F[AI Inspection Report<br/>#VG-xxx]
    F --> G{Citizen choice}
    G -->|Option A| H[Read Safety Guidance]
    G -->|Option B| I[Confirm Complaint]
    I --> J[(SQLite / Neon PostgreSQL)]
    I --> K[ReportLab PDF]
    J --> L[🗺️ Leaflet Map]
    B --> M[(Local Disk / Cloudflare R2)]
    C -.rate limit.-> N[Fallback models]
    N -.-> C
```

<details>
<summary><b>🧠 AI model management</b></summary>

- **Engine:** Google Gemini Multimodal Vision via the official `google-genai` SDK
- **Active model:** `gemini-3.1-flash-lite`, set with `GEMINI_MODEL`
- **Fallback rotation:** `gemini-flash-latest` → `gemini-3.8-flash` → `gemini-2.5-flash`
- **Research artifacts:** legacy YOLO weights (`ai/models/best.pt`, `home_best.pt`) are kept only for offline ablation studies and are **not** used in production

</details>

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| 🧠 **AI Vision** | Google Gemini Multimodal Vision · `google-genai` SDK |
| 🎨 **Annotation** | OpenCV (`opencv-python`) |
| ⚙️ **Backend** | Python 3.10+ · Flask 3.1 |
| 🖥️ **Server** | Waitress (Windows) · Gunicorn (Linux) |
| 🗄️ **Database** | SQLite · Neon PostgreSQL |
| ☁️ **Storage** | Local Disk · Cloudflare R2 |
| 📄 **PDF** | ReportLab 4.x |
| 🌐 **Frontend** | HTML5 · Tailwind CSS · Vanilla JS · Leaflet.js |
| 🧪 **Testing** | pytest |

<div align="center">

<img src="https://skillicons.dev/icons?i=python,flask,sqlite,postgres,html,tailwind,js,opencv,git,github" alt="Tech stack icons"/>

</div>

---

## 📁 Project Structure

```text
visionGuard/
├── ai/
│   ├── gemini_service.py      # Gemini vision, defect analysis, model fallback
│   └── models/                # Legacy YOLO weights (research only)
├── database/
│   └── db.py                  # SQLite / PostgreSQL persistence
├── data/
│   ├── visionguard.db         # Default local database
│   └── evaluation_benchmark/  # Benchmark images
├── tests/                     # 81 automated tests
├── assets/                    # README images and GIFs
├── wsgi.py                    # App entry point
├── requirements.txt
└── .env.example
```

> ✏️ [ADD: adjust any folder that differs from your real repo]

---

## 🚀 Getting Started

**Prerequisites:** Python 3.10 to 3.14 · `venv` · internet access · a free [Gemini API key](https://aistudio.google.com/)

```bash
# 1. Clone
git clone https://github.com/szeeshanZ123/visionGuard.git
cd visionGuard

# 2. Virtual environment
python -m venv venv
source venv/bin/activate        # Linux/macOS
.\venv\Scripts\activate         # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure environment
cp .env.example .env            # Windows: copy .env.example .env

# 5. Run
python wsgi.py
```

Open **http://127.0.0.1:5000** 🎉

<details>
<summary><b>🔑 Environment variables</b></summary>

```env
AI_PROVIDER=gemini
GEMINI_API_KEY=your_actual_gemini_api_key_here
GEMINI_MODEL=gemini-3.1-flash-lite
VISIONGUARD_SECRET_KEY=your_random_64_character_secret_key_here
VISIONGUARD_DB_PATH=data/visionguard.db
STORAGE_BACKEND=local
```

Generate a secret key:

```bash
python -c "import secrets; print(secrets.token_hex(32))"
```

Get an API key: open [Google AI Studio](https://aistudio.google.com/), sign in, click **Get API key**, and paste it into `.env`.

> 🔒 The key is read only from environment variables and never reaches frontend JavaScript, logs or API responses.

</details>

---

## 🎬 Usage Walkthrough

1. **Sign in** as a citizen (session security and CSRF protection are active).
2. **Open Inspection Studio** (`/create_home`) and choose *Road Surface Distress* or *Home & Building Defect*.
3. **Upload a photo**, e.g. `data/evaluation_benchmark/images/benchmark_08_d20_alligator_urban.jpg`.
4. **Click Detect Defect.** Watch five steps: Upload → Gemini analysis → Defect and severity identification → OpenCV overlay → Report compilation.
5. **Toggle** between the annotated overlay and the original photo.
6. **Review the report:** severity badge, summary, itemized defects, repair recommendations.
7. **Choose a pathway:**
   - **Option A:** read full guidance and safety steps.
   - **Option B:** check pre-filled GPS, address and notes, then confirm the complaint.
8. **Download the PDF** and find the new pin on the **Interactive Map**.

---

## ✅ Testing & Quality

```bash
python -m pytest tests/ -v
```

<div align="center">

**81 automated tests · 100% passing**

</div>

| Suite | Tests | What it proves |
|---|:---:|---|
| `test_gemini_multimodal_platform.py` | 17 | Road and building detection, multi-defect boxes, zero false positives on clean roads, blurry and invalid uploads, coordinate clamping, quota (HTTP 429) and timeout handling, missing-key diagnostics, non-destructive annotation, SQLite and PostgreSQL persistence, duplicate complaint prevention |
| `test_auth_and_roles.py` | RBAC | Role-based access enforcement |
| `test_citizen_csrf_security_routing.py` | Security | CSRF token validation |
| `test_complaint_assistance.py` | Workflow | Draft updates and PDF generation |
| `test_defect_map.py` | Geo | Geocoded marker queries |

> Regression and security suites together account for the remaining 64 tests.

---

## 📈 Results & Impact

| Metric | Value |
|---|---|
| Automated tests passing | **81 / 81** |
| Defect categories supported | **10** (5 road · 5 building) |
| Detection accuracy | [ADD: value and how it was measured] |
| Average analysis time per image | [ADD: seconds] |
| Benchmark images evaluated | [ADD: count] |
| People who tested the app | [ADD: count] |

> Only add numbers you actually measured. Judges trust real metrics.

---

## ⚠️ Limitations

- **Visual line-of-sight only.** Subsurface voids, internal rebar corrosion and underground leaks need specialized NDT equipment.
- **Image quality matters.** Dark or blurred photos may produce uncertain localization.
- **Preliminary screening only.** Results do not replace a certified engineering survey.

---

## 🗺️ Roadmap

- [x] Gemini multimodal defect detection
- [x] Multi-defect itemization with OpenCV overlays
- [x] Complaint workflow with PDF export
- [x] Interactive defect map
- [x] RBAC, CSRF protection and automated test suite
- [ ] Fine-tuned edge models (YOLOv8 Nano) for offline dashcam inference
- [ ] Drone survey ingestion (orthomosaic batches for roads and roofs)
- [ ] Municipal grievance integration through Open311 webhooks

---

## 👥 Contributors

<div align="center">

**Team [ADD: TEAM NAME]** · NEURA X 2026 — Global Hackathon 2K26

<table>
  <tr>
    <td align="center" width="220">
      <a href="https://github.com/szeeshanZ123">
        <img src="https://avatars.githubusercontent.com/u/222632383?v=4" width="110" alt="Zeeshan"/><br/>
        <b>Zeeshan</b>
      </a><br/>
      <sub>[ADD: ROLE]</sub><br/><br/>
      <a href="https://github.com/szeeshanZ123"><img src="https://img.shields.io/badge/GitHub-szeeshanZ123-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
    <td align="center" width="220">
      <a href="https://github.com/Sandesh-Narkar">
        <img src="https://avatars.githubusercontent.com/u/267092211?s=400&u=7d09b000dc3681a650dbe37a1e7cd35a467d52f2&v=4" width="110" alt="Sandesh"/><br/>
        <b>Sandesh</b>
      </a><br/>
      <sub>[ADD: ROLE]</sub><br/><br/>
      <a href="https://github.com/Sandesh-Narkar"><img src="https://img.shields.io/badge/GitHub-Sandesh--Narkar-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
    <td align="center" width="220">
      <a href="https://github.com/Yaswanth8407">
        <img src="https://avatars.githubusercontent.com/u/217727881?v=4" width="110" alt="Yaswanth"/><br/>
        <b>Yaswanth</b>
      </a><br/>
      <sub>[ADD: ROLE]</sub><br/><br/>
      <a href="https://github.com/Yaswanth8407"><img src="https://img.shields.io/badge/GitHub-Yaswanth8407-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
    <td align="center" width="220">
      <a href="https://github.com/Sifatshaikh07">
        <img src="https://github.com/Sifatshaikh07.png" width="110" alt="Sifat Shaikh"/><br/>
        <b>Sifat Shaikh</b>
      </a><br/>
      <sub>[ADD: ROLE]</sub><br/><br/>
      <a href="https://github.com/Sifatshaikh07"><img src="https://img.shields.io/badge/GitHub-Sifatshaikh07-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
  </tr>
</table>

<a href="https://github.com/szeeshanZ123/visionGuard/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=szeeshanZ123/visionGuard" alt="Contributors graph"/>
</a>

</div>

---

## 🙏 Acknowledgements

- **NEURA X 2026** organizers, mentors and judges
- [Google Gemini](https://ai.google.dev/) and Google AI Studio
- OpenCV · Flask · ReportLab · Leaflet.js · Tailwind CSS · Neon · Cloudflare R2

---

## 📜 License & Disclaimer

Licensed under **[ADD: LICENSE]**. See `LICENSE` for details.

> ⚖️ Preliminary visual defect assessments from VisionGuard AI 2.0 are for informational and civic assistance purposes only. They are not a certified structural engineering survey, legal warranty or municipal repair guarantee.

📬 **Contact:** [ADD: email] · [Repository](https://github.com/szeeshanZ123/visionGuard)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:1D4ED8,100:0F172A&height=110&section=footer" width="100%" alt="footer wave"/>

**Built with ❤️ for NEURA X 2026 — Global Hackathon 2K26**

*If VisionGuard impressed you, please ⭐ the repo.*

[⬆ Back to top](#️-visionguard-ai-20)

</div>
