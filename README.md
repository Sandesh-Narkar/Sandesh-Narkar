<a id="top"></a>

<div align="center">

<img src="https://d8it4huxumps7.cloudfront.net/uploads/images/opportunity/banner/6ab0c43d9ff29_neura-x.png?d=1920x557" alt="NEURA X 2026 Global Hackathon 2K26 banner" width="100%"/>

<br/>

# 🛡️ VisionGuard AI 2.0

### AI-Powered Multimodal Infrastructure Defect Detection, Inspection & Citizen Reporting Platform

*See the defect. File the complaint. Track the repair. Fix the city.*

<a href="https://github.com/szeeshanZ123/visionGuard">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1200&color=3B82F6&center=true&vCenter=true&width=760&lines=Upload+a+photo+of+a+road+or+building;Gemini+Vision+finds+every+visible+defect;OpenCV+draws+severity-coded+overlays;One+click+to+a+formal+civic+complaint+PDF;Track+repair+progress+with+citizen+updates" alt="Typing animation"/>
</a>

<br/>

![NEURA X 2026](https://img.shields.io/badge/NEURA%20X-2026%20Global%20Hackathon%202K26-7C3AED?style=for-the-badge)
![Track](https://img.shields.io/badge/Track-Vision%20AI-1D4ED8?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Hackathon%20Submission-22C55E?style=for-the-badge)

![Python](https://img.shields.io/badge/Python-3.10--3.14-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.1-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Google-Gemini%20Vision-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Annotation-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Database](https://img.shields.io/badge/DB-SQLite%20%7C%20Neon%20PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Deployed on Render](https://img.shields.io/badge/Deployed-Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-81%20Passing-22C55E?style=flat-square)
![License](https://img.shields.io/badge/License-[ADD%20LICENSE]-blue?style=flat-square)

<br/>

[🚀 **Live Application**](https://visionguard-ttyp.onrender.com/) &nbsp;•&nbsp; [🎥 **Demo Video**]([ADD: VIDEO URL]) &nbsp;•&nbsp; [📊 **Presentation**]([ADD: PPT URL]) &nbsp;•&nbsp; [🐞 **Report Issue**](https://github.com/szeeshanZ123/visionGuard/issues)

</div>

---

## 🎯 Hackathon Problem Statement

> **Vision AI**
> *Build an AI system that analyses images and identifies meaningful real-world problems, defects, or abnormalities.*

**How VisionGuard answers it:** VisionGuard analyses photographs of roads and buildings, identifies multiple real-world defects (potholes, cracks, dampness, spalling and more), classifies them, estimates preliminary severity, marks them visually on the image, and turns the result into an actionable civic report that can be tracked until the issue is repaired.

---

## ⏱️ The 60-Second Summary

| | |
|---|---|
| **🎯 Problem** | Road and building defects go unreported because inspection is slow, manual and citizens have no easy way to file evidence-backed complaints or follow up on repairs. |
| **💡 Solution** | Upload one photo. Gemini Multimodal Vision finds every visible defect, OpenCV marks it, and the citizen files a formal complaint PDF pinned on a live map, then tracks repair progress over time. |
| **🧠 Core Tech** | Google Gemini Vision · OpenCV · Flask · ReportLab · Leaflet.js · Tailwind CSS |
| **✅ Proof** | 81 automated tests covering AI inference, security, complaints, maps and citizen updates. |
| **🔒 Responsible AI** | Every result is labelled a *preliminary visual assessment*, never a certified engineering survey. |
| **🌐 Live** | [visionguard-ttyp.onrender.com](https://visionguard-ttyp.onrender.com/) |

---

## 📑 Table of Contents

<details>
<summary><b>Click to expand</b></summary>

1. [Project Description](#-project-description)
2. [The Problem](#-the-problem)
3. [Our Solution](#-our-solution)
4. [Project Objectives](#-project-objectives)
5. [How It Works](#-how-it-works)
6. [Key Features](#-key-features)
7. [Citizen Report Update System](#-citizen-report-update-system)
8. [Why VisionGuard Stands Out](#-why-visionguard-stands-out)
9. [Screenshots & Demo](#-screenshots--demo)
10. [System Architecture](#-system-architecture)
11. [AI Detection & Image Processing](#-ai-detection--image-processing)
12. [Tech Stack](#-tech-stack)
13. [Database & Data Management](#-database--data-management)
14. [Security & Privacy](#-security--privacy)
15. [Project Structure](#-project-structure)
16. [Getting Started](#-getting-started)
17. [Environment Configuration](#-environment-configuration)
18. [Usage Walkthrough](#-usage-walkthrough)
19. [Testing & Quality](#-testing--quality)
20. [Deployment](#-deployment)
21. [Results & Impact](#-results--impact)
22. [Limitations](#-limitations)
23. [Roadmap & Future Scope](#-roadmap--future-scope)
24. [Contributors](#-contributors)
25. [Acknowledgements](#-acknowledgements)
26. [Project Links](#-project-links)
27. [License & Disclaimer](#-license--disclaimer)

</details>

---

## 📖 Project Description

**VisionGuard AI 2.0** is an AI-powered multimodal infrastructure inspection and citizen reporting platform designed to **identify, document, visualize and track** visible infrastructure defects in roads, highways and buildings.

The platform uses Google's **Gemini Multimodal Vision** model to analyse uploaded photographs, identify multiple visible defects, classify their categories, estimate preliminary severity and generate structured inspection reports.

VisionGuard combines **Artificial Intelligence, image processing, geospatial visualization and citizen participation** in one integrated platform.

Citizens can:

- Upload photographs of damaged roads or buildings
- Receive AI-generated inspection results
- View annotated defect images
- Generate PDF reports
- Submit civic complaint drafts
- Track the progress of previously reported issues

A key feature is the **Citizen Report Update System**, which lets users update an existing report when repair work begins, when an issue remains unresolved, when conditions worsen, or when a road appears to have been repaired. This creates a **continuous reporting and monitoring cycle** rather than treating each inspection as an isolated event.

---

## 🚨 The Problem

Urban infrastructure is continuously exposed to environmental conditions, heavy traffic, water infiltration, material deterioration and structural stress. This leads to common problems such as:

- 🕳️ Potholes and damaged road surfaces
- ↔️ Longitudinal and transverse road cracks
- 🕸️ Alligator cracking and pavement deterioration
- 🧱 Wall cracks and surface fractures
- 💧 Dampness and water infiltration
- 🎨 Peeling paint and plaster damage
- 🏗️ Concrete spalling and surface deterioration

Traditional inspection depends on manual observation and reporting, which creates several challenges:

| Challenge | Description |
|---|---|
| ⏳ **Time-consuming inspections** | Identifying and documenting defects manually requires significant time and human effort. |
| 📭 **Delayed reporting** | Citizens notice damage but lack a simple, accessible reporting mechanism. |
| 🖼️ **Limited visual documentation** | Reports often lack standardized photographs, defect classification or supporting evidence. |
| 📊 **No centralized tracking** | Citizens cannot easily know whether a reported issue is being addressed. |
| 👁️ **Poor progress visibility** | A reported pothole may be repaired, but the original report never reflects real-world progress. |
| 🗺️ **Limited geospatial awareness** | Defects must be tied to locations to support monitoring and prioritization. |

> 📌 [ADD: one real statistic about road or building damage in your region, with source]

There is a clear need for an **accessible, intelligent and transparent system** that connects defect detection with citizen reporting, location-based visualization and progress tracking.

---

## 💡 Our Solution

**VisionGuard AI** turns any smartphone photo into an **inspection report and an actionable civic complaint**, then keeps the report alive through progress tracking.

> **Elevator pitch:** *Upload a photo, get an AI inspection report, file a civic complaint, and track the repair, all in one flow.*

| Step | What happens |
|:---:|---|
| 1️⃣ | Citizen uploads a road or building photo |
| 2️⃣ | Gemini Vision identifies and itemizes defects (`D001`, `D002`, ...) |
| 3️⃣ | OpenCV draws severity-coded bounding boxes on a copy of the photo |
| 4️⃣ | A structured inspection report is generated (`#VG-xxx`) |
| 5️⃣ | Citizen reads safety guidance **or** files a complaint with PDF and map pin |
| 6️⃣ | Citizen later posts progress updates (work started, repaired, still exists, worse) |

### Solution Components

**3.1 AI-Powered Defect Detection:** Gemini Multimodal Vision analyses road and building photographs, identifies visible defects, categorizes them and generates preliminary severity assessments.

**3.2 Automated Image Annotation:** OpenCV draws bounding boxes around detected defects. Each defect gets an ID label (such as `D001`, `D002`) and a visual severity indicator.

**3.3 Structured Inspection Reports:** Each report contains the inspection reference ID, defect category, number of detected defects, preliminary severity, visual evidence, AI observations, suggested maintenance actions and safety recommendations.

**3.4 Citizen Reporting & Complaint Assistance:** Citizens review AI findings and prepare civic complaint reports. The platform supports report storage and PDF draft generation for further submission through appropriate channels.

**3.5 Geospatial Defect Visualization:** An interactive map visualizes eligible defect reports using geographic coordinates.

**3.6 Citizen Report Progress Tracking:** Citizens revisit previous reports and communicate real-world changes with comments and updated photos. Repair claims stay *pending verification* until an authorized inspector confirms them.

---

## 🎯 Project Objectives

- ✅ Automate the preliminary identification of visible infrastructure defects
- ✅ Reduce the effort required to document infrastructure problems
- ✅ Generate structured, visually supported inspection reports
- ✅ Improve accessibility of civic infrastructure reporting
- ✅ Provide geographical visualization of eligible reported defects
- ✅ Allow citizens to track the progress of their submitted reports
- ✅ Support transparent communication about repair progress
- ✅ Maintain historical inspection records and supporting evidence
- ✅ Provide a foundation for future smart-city infrastructure monitoring systems

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
    section Track
      Post repair progress updates: 5: Citizen
      Inspector verifies repair: 5: Inspector
```

---

## ✨ Key Features

### 🛣️ A. Road Infrastructure Inspection

| Defect | Description |
|---|---|
| **Potholes** | Cavities and damaged road surfaces |
| **Longitudinal Cracks** | Cracks running parallel to the road |
| **Transverse Cracks** | Cracks running across the road |
| **Alligator Cracking** | Interconnected fatigue cracks |
| **Surface Deterioration** | Visible pavement wear and material loss |
| **Raveling** | Loss of asphalt aggregate from the road surface |

### 🏢 B. Building Infrastructure Inspection

| Defect | Description |
|---|---|
| **Wall Cracks** | Visible fractures in walls and plaster |
| **Dampness** | Moisture-related surface damage |
| **Water Infiltration** | Visible signs of water seepage |
| **Peeling Paint** | Deterioration of painted surfaces |
| **Plaster Damage** | Cracking and deterioration of plaster |
| **Surface Spalling** | Visible loss or detachment of concrete or plaster |

### 🤖 C. AI-Based Image Analysis

- Google Gemini Multimodal Vision integration
- Multiple visible defect identification
- Structured JSON output
- Defect categorization
- Preliminary severity classification
- Image validation and preprocessing
- Handling of unclear or inconclusive images
- Automatic model fallback on rate limits

### 🎯 D. OpenCV Image Annotation

- Bounding box visualization
- Individual defect identification labels
- Color-coded severity indicators
- Normalized coordinate validation (`0.0 ≤ x1 < x2 ≤ 1.0`)
- **Original image preservation** (non-destructive overlay)
- Annotated image generation
- Toggle between annotated and original view

### 📝 E. Inspection Report Generation

Each inspection can include:

- Unique inspection reference (e.g. `#VG-104`)
- Original photograph
- Annotated photograph
- Defect identification and count
- Preliminary severity assessment
- AI-generated description
- Recommended maintenance actions and urgency priority
- Safety recommendations
- Geographical information when available

### 📄 F. PDF Report Generation

VisionGuard uses **ReportLab** to generate downloadable PDF documentation containing inspection and complaint information. These documents support record keeping and preparation of civic complaints.

### 🗺️ G. Interactive Geospatial Defect Map

- Interactive **Leaflet.js** map
- Location-based defect markers
- Defect category filters
- Inspection location information
- Marker details
- Map synchronization and data refresh
- Only **public-safe records** are exposed on the public map

### 🔁 H. Citizen Report Update System

See the [dedicated section](#-citizen-report-update-system) below.

### 🔐 I. Authentication & Access Control

- Citizen registration and login
- Password-based authentication
- Google OAuth integration
- Session-based authentication
- Role-based access control (RBAC)
- CSRF protection
- Report ownership validation
- Protected inspection and update endpoints
- Duplicate complaint prevention

### 🗂️ J. Historical Inspection Records

Users can revisit previously submitted inspection reports, view inspection details and review all associated progress updates.

### 🚦 Severity Color Code

| Severity | Color | Hex |
|---|---|---|
| Critical | 🔴 Crimson | `#EF4444` |
| High | 🟠 Orange | `#F97316` |
| Moderate | 🟡 Amber | `#F59E0B` |
| Low | 🔵 Blue | `#3B82F6` |
| Uncertain / Inconclusive | ⚪ Slate | `#64748B` |

---

## 🔁 Citizen Report Update System

A major feature of VisionGuard AI 2.0 is the ability to **update previously submitted reports** instead of treating every inspection as a one-time event.

**A citizen can:**

1. Open an existing inspection report
2. Select the current condition
3. Add an optional comment
4. Upload updated photographic evidence
5. Submit the progress update
6. View the chronological report timeline

**Supported update types:**

| Update | Meaning |
|---|---|
| 🛠️ **Work Started** | Citizen reports that repair activity has begun |
| ✅ **Road Repaired** | Citizen reports that the defect appears repaired |
| ⚠️ **Issue Still Exists** | Citizen reports that the problem remains |
| 📈 **Issue Has Become Worse** | Citizen reports further deterioration |

> ⚖️ **Important:** Citizen-reported updates are **separate from official inspection verification**. Selecting *Road Repaired* does **not** automatically mark an inspection as officially resolved. An authorized inspector must verify the repair.

```mermaid
stateDiagram-v2
    [*] --> Reported
    Reported --> WorkStarted: Citizen update
    Reported --> StillExists: Citizen update
    Reported --> Worse: Citizen update
    WorkStarted --> RepairedClaim: Citizen update
    StillExists --> RepairedClaim: Citizen update
    RepairedClaim --> PendingVerification
    PendingVerification --> OfficiallyVerified: Inspector confirms
    PendingVerification --> Reopened: Inspector rejects
```

---

## 🏆 Why VisionGuard Stands Out

| Criteria | Manual Inspection | Typical Photo-Upload Apps | **VisionGuard AI 2.0** |
|---|:---:|:---:|:---:|
| Turnaround | Days to weeks | Minutes | ✅ **Minutes** |
| Multiple defects in one image | ❌ Manual notes | ⚠️ Often one label | ✅ **Itemized with IDs and boxes** |
| Annotated visual evidence | ❌ | ⚠️ Plain photo | ✅ **Non-destructive overlay** |
| Formal complaint document | ❌ Written by hand | ❌ Rare | ✅ **Auto-generated PDF** |
| Location tracking | ❌ | ⚠️ Limited | ✅ **Live Leaflet map** |
| Repair progress tracking | ❌ | ❌ Rare | ✅ **Citizen update timeline** |
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

VisionGuard follows a **modular architecture** connecting the frontend, Flask backend, AI analysis engine, image processing layer, database and storage system.

### High-Level Architecture

```mermaid
flowchart TD
    A([👤 Citizen]) --> B[VisionGuard<br/>Web Application]
    B --> C[Authentication<br/>and Authorization]
    C --> D[Image Upload]
    D --> E[Image Validation<br/>and Preprocessing]
    E --> F[Google Gemini<br/>Vision]
    F --> G[Structured<br/>Defect Analysis]
    G --> H[OpenCV<br/>Annotation]
    H --> I[Inspection<br/>Report]
    I --> J[Citizen Review]

    J --> K[Report and<br/>Complaint Storage]
    J --> L[Citizen Progress<br/>Updates]

    K --> M[PDF Generation]
    K --> N[Geospatial<br/>Defect Map]
    L --> O[Inspection<br/>Update Timeline]

    K --> P[(SQLite /<br/>PostgreSQL)]
    M --> P
    N --> P
    O --> P

    P --> Q[Authorized Staff<br/>Verification]

    style A fill:#1D4ED8,color:#fff,stroke:#1E3A8A
    style F fill:#4285F4,color:#fff,stroke:#1E3A8A
    style H fill:#5C3EE8,color:#fff,stroke:#312E81
    style P fill:#336791,color:#fff,stroke:#1E3A5F
    style Q fill:#22C55E,color:#fff,stroke:#166534
```

**Layer-by-layer explanation:**

| Stage | Component | Responsibility |
|---|---|---|
| 1 | **Citizen** | Starts the inspection from the web app |
| 2 | **VisionGuard Web Application** | Flask backend and Tailwind frontend |
| 3 | **Authentication and Authorization** | Login, Google OAuth, sessions, RBAC and CSRF checks |
| 4 | **Image Upload** | Secure upload with safe filename handling |
| 5 | **Image Validation and Preprocessing** | Format, size and quality checks before AI analysis |
| 6 | **Google Gemini Vision** | Multimodal analysis of the photograph |
| 7 | **Structured Defect Analysis** | JSON of defects, categories, severity and bounding boxes |
| 8 | **OpenCV Annotation** | Draws severity-coded boxes and IDs on a copy of the image |
| 9 | **Inspection Report** | Structured report with reference ID `#VG-xxx` |
| 10 | **Citizen Review** | Citizen checks the results and chooses the next action |
| 11 | **Report and Complaint Storage** | Persists the report, complaint data and images |
| 12 | **PDF Generation** | ReportLab complaint and inspection PDF |
| 13 | **Geospatial Defect Map** | Leaflet map of eligible public-safe records |
| 14 | **Citizen Progress Updates** | Work started, repaired, still exists, worse |
| 15 | **Inspection Update Timeline** | Chronological history of every update |
| 16 | **SQLite / PostgreSQL** | Persistent storage of users, inspections and updates |
| 17 | **Authorized Staff Verification** | Inspector confirms or rejects repair claims |

### Inspection Workflow

```mermaid
flowchart TD
    A([🔑 Citizen Login]) --> B[Select Road or<br/>Building Inspection]
    B --> C[Upload<br/>Photograph]
    C --> D[Validate Image]
    D --> E[Gemini Vision<br/>Analysis]
    E --> F[Extract Defects<br/>and Severity]
    F --> G[OpenCV Bounding Box<br/>Annotation]
    G --> H[Generate<br/>Inspection Report]
    H --> I[Citizen Reviews<br/>Results]
    I --> J[Save Report]

    J --> K[Generate<br/>PDF Draft]
    J --> L[Display Eligible<br/>Map Marker]
    J --> M[Citizen Progress<br/>Updates]

    M --> N[Repair Verification]

    style A fill:#1D4ED8,color:#fff,stroke:#1E3A8A
    style E fill:#4285F4,color:#fff,stroke:#1E3A8A
    style G fill:#5C3EE8,color:#fff,stroke:#312E81
    style N fill:#22C55E,color:#fff,stroke:#166534
```

**Workflow steps:**

1. **Citizen Login** with username and password or Google OAuth
2. **Select Road or Building Inspection** to pick the defect domain
3. **Upload Photograph** from a phone or computer
4. **Validate Image** (format, size, readability)
5. **Gemini Vision Analysis** of the validated photo
6. **Extract Defects and Severity** into structured JSON
7. **OpenCV Bounding Box Annotation** on a copy of the original
8. **Generate Inspection Report** with ID `#VG-xxx`
9. **Citizen Reviews Results** and decides what to do
10. **Save Report** to the database and image storage
11. **Three outputs:** generate a **PDF draft**, display an **eligible map marker**, or post **citizen progress updates**
12. **Repair Verification** by an authorized inspector once a citizen reports progress

### Request Sequence

```mermaid
sequenceDiagram
    participant U as Citizen
    participant F as Frontend
    participant B as Flask Backend
    participant G as Gemini Vision
    participant O as OpenCV
    participant D as Database
    U->>F: Upload photo
    F->>B: POST image (CSRF + session)
    B->>B: Validate and preprocess image
    B->>G: Send image for analysis
    G-->>B: JSON (defects, severity, boxes)
    B->>O: Validate boxes and annotate
    O-->>B: Annotated image
    B->>D: Store inspection + images
    B-->>F: Report (#VG-xxx)
    F-->>U: Annotated image + report
```

### Resilience: Model Fallback

```mermaid
flowchart LR
    A[Backend request] --> B[Primary Gemini model]
    B -- Success --> C[Structured JSON]
    B -. Rate limit / version change .-> D[Fallback model 1]
    D -. Fails .-> E[Fallback model 2]
    D -- Success --> C
    E -- Success --> C
```

---

## 🧠 AI Detection & Image Processing

### Google Gemini Vision

VisionGuard uses Google's **Gemini multimodal model** as its primary active image-analysis engine. The AI analyses uploaded photographs and returns **structured defect information**. The backend uses the official **Google Gen AI Python SDK**.

```env
AI_PROVIDER=gemini
GEMINI_MODEL=gemini-3.1-flash-lite
```

### OpenCV Annotation

After receiving structured defect information, the image-processing layer converts **normalized bounding box coordinates** into pixel coordinates. The annotation engine validates coordinate boundaries before drawing overlays.

```python
x1 = int(normalized_x1 * image_width)
y1 = int(normalized_y1 * image_height)

x2 = int(normalized_x2 * image_width)
y2 = int(normalized_y2 * image_height)
```

The resulting image shows defect bounding boxes and ID labels. **The original photograph remains unchanged.**

### Severity Classification

| Level | Meaning |
|---|---|
| **Critical** | Immediate attention recommended |
| **High** | Serious defect, prompt action advised |
| **Moderate** | Noticeable deterioration |
| **Low** | Minor defect |
| **Uncertain / Inconclusive** | Image quality or content insufficient |

> These are **AI-generated screening assessments** and not certified engineering conclusions.

### Model Management

- **Automatic fallback rotation:** if the primary model hits rate limits or a version change, the engine rotates across backup vision models.
- **Research artifacts:** historical **YOLOv8** checkpoints (`ai/models/best.pt`, `home_best.pt`) are preserved only for offline comparative research and future edge-model development. They are **not** the active production inference engine.

---

## 🧰 Tech Stack

| Component | Technology | Purpose |
|---|---|---|
| 🐍 Language | Python 3.10+ | Backend and AI integration |
| ⚙️ Web Framework | Flask 3.1 | Application backend and REST APIs |
| 🧠 AI Engine | Google Gemini Vision | Multimodal defect analysis |
| 🔌 AI SDK | Google Gen AI SDK (`google-genai`) | Gemini API integration |
| 🤖 Active Model | `gemini-3.1-flash-lite` | Image understanding and analysis |
| 🎨 Image Processing | OpenCV (`opencv-python`) | Bounding boxes and annotations |
| 🔢 Data Processing | NumPy | Numerical and image operations |
| 🌐 Frontend | HTML5 · Vanilla JavaScript | Page structure and interactions |
| 💅 Styling | Tailwind CSS | Responsive user interface |
| 🗺️ Maps | Leaflet.js | Geospatial visualization |
| 🗄️ Database | SQLite / PostgreSQL | Users and inspection records |
| ☁️ Cloud Database | Neon PostgreSQL | Hosted relational persistence |
| 📦 Object Storage | Local Disk / Cloudflare R2 | Inspection image storage |
| 📄 PDF | ReportLab 4.x | PDF documentation |
| 🔐 Authentication | Flask Sessions / Google OAuth | User authentication |
| 🖥️ Server | Waitress (Windows) · Gunicorn (Linux) | Production serving |
| 🧪 Testing | Pytest | Automated testing |
| 🚀 Deployment | Render | Web application hosting |

<div align="center">

<img src="https://skillicons.dev/icons?i=python,flask,sqlite,postgres,html,tailwind,js,opencv,git,github" alt="Tech stack icons"/>

</div>

---

## 🗄️ Database & Data Management

VisionGuard supports **SQLite** for local development and **PostgreSQL (Neon)** for hosted deployment.

**Major data entities:**

- Users
- Inspection records
- Defect information
- Complaint information
- Citizen inspection updates
- Maintenance activity records

### Citizen Inspection Updates (`inspection_updates`)

| Field | Purpose |
|---|---|
| `id` | Unique update identifier |
| `inspection_id` | Associated inspection |
| `user_id` | User submitting the update |
| `username` | Associated username, where stored |
| `update_type` | Reported progress condition |
| `comment` | Optional citizen description |
| `image_path` | Optional supporting photograph |
| `verification_status` | Verification state |
| `created_at` | Update timestamp |

The update history is linked to the **original inspection** rather than creating a new inspection for every progress update.

---

## 🔒 Security & Privacy

VisionGuard implements application-level protections to safeguard user information and inspection records.

- 🔑 Password-based authentication
- 🌐 Google OAuth authentication
- 🍪 Session management
- 🛡️ Role-based route protection
- 🧾 CSRF validation
- 👤 Inspection ownership verification
- 📤 Secure image upload validation
- 📁 Safe filename handling
- 🖼️ Protected image retrieval
- 🚫 Restricted access to private inspection records
- 🧼 Public-map data sanitization
- 🔏 API key never exposed to frontend, logs or responses

**Integrity and privacy rules:**

- Citizen repair claims **do not** directly overwrite official inspection statuses.
- Private comments, user identities and private inspection photographs **must not** be exposed through public map endpoints.
- API keys and secrets must be stored in **environment variables**, never in frontend code or source control.

---

## 📁 Project Structure

```text
visionGuard/
├── ai/
│   ├── vision_service.py      # Gemini Vision calls, defect analysis, model fallback
│   └── models/                # Legacy YOLO weights (research only)
├── database/
│   └── db.py                  # SQLite / PostgreSQL persistence
├── data/
│   ├── visionguard.db         # Default local database
│   └── evaluation_benchmark/  # Benchmark images
├── tests/                     # Automated test suite
├── assets/                    # README images, screenshots and GIFs
├── wsgi.py                    # App entry point
├── requirements.txt
└── .env.example
```

> ✏️ [ADD: adjust any folder or file name that differs from your real repo]

---

## 🚀 Getting Started

### Prerequisites

- Python **3.10 or later** (3.10 to 3.14 supported)
- Git
- Internet connection
- A free **Google Gemini API key** from [Google AI Studio](https://aistudio.google.com/)
- A code editor such as VS Code

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/szeeshanZ123/visionGuard.git
cd visionGuard

# 2. Create a virtual environment
python -m venv venv

# Windows
.\venv\Scripts\activate

# Linux / macOS
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure environment
cp .env.example .env            # Windows: copy .env.example .env

# 5. Run the application
python wsgi.py
```

Open **http://127.0.0.1:5000** 🎉

> 🔒 Never commit `.env` or expose API keys in public repositories.

---

## ⚙️ Environment Configuration

Create a `.env` file in the project root:

```env
AI_PROVIDER=gemini
GEMINI_API_KEY=your_gemini_api_key
GEMINI_MODEL=gemini-3.1-flash-lite

VISIONGUARD_SECRET_KEY=your_secure_random_secret
VISIONGUARD_DB_PATH=data/visionguard.db

STORAGE_BACKEND=local
```

Generate a secure secret key:

```bash
python -c "import secrets; print(secrets.token_hex(32))"
```

| Variable | Description |
|---|---|
| `AI_PROVIDER` | Selects the AI provider |
| `GEMINI_API_KEY` | Google Gemini API key |
| `GEMINI_MODEL` | Configured Gemini model |
| `VISIONGUARD_SECRET_KEY` | Flask session security key |
| `VISIONGUARD_DB_PATH` | Local SQLite database path |
| `DATABASE_URL` | PostgreSQL connection string (when configured) |
| `STORAGE_BACKEND` | Storage provider selection (`local` or Cloudflare R2) |
| `GOOGLE_CLIENT_ID` | Google OAuth client identifier |
| `GOOGLE_CLIENT_SECRET` | Google OAuth client secret |
| `GOOGLE_REDIRECT_URI` | OAuth callback URL |

Configure additional database, OAuth and object-storage variables according to `.env.example` and your deployment environment. In production, manage them through the hosting provider's environment settings.

**Get an API key:** open [Google AI Studio](https://aistudio.google.com/), sign in, click **Get API key**, and paste it into `.env`.

---

## 🎬 Usage Walkthrough

1. **Sign in** as a citizen (session security and CSRF protection are active).
2. **Open Inspection Studio** (`/create_home`) and choose *Road Surface Distress* or *Home & Building Defect*.
3. **Upload a photo**, for example `data/evaluation_benchmark/images/benchmark_08_d20_alligator_urban.jpg`.
4. **Click Detect Defect.** Watch five steps: Upload → AI analysis → Defect and severity identification → OpenCV overlay → Report compilation.
5. **Toggle** between the annotated overlay and the original photo.
6. **Review the report:** severity badge, summary, itemized defects, repair recommendations.
7. **Choose a pathway:**
   - **Option A:** read full guidance and safety steps.
   - **Option B:** check pre-filled GPS, address and notes, then confirm the complaint.
8. **Download the PDF** and find the new pin on the **Interactive Map**.
9. **Come back later** to open the report, post a progress update (Work Started, Road Repaired, Issue Still Exists, Issue Has Become Worse) with an optional comment and photo, and view the timeline.

---

## ✅ Testing & Quality

```bash
python -m pytest tests/ -v
```

<div align="center">

**81 automated tests · 100% passing**

</div>

| Suite | What it proves |
|---|---|
| `test_gemini_multimodal_platform.py` | Road and building detection, multi-defect boxes, zero false positives on clean roads, blurry and invalid uploads, coordinate clamping, quota (HTTP 429) and timeout handling, missing-key diagnostics, non-destructive annotation, SQLite and PostgreSQL persistence, duplicate complaint prevention |
| `test_auth_and_roles.py` | Role-based access enforcement |
| `test_citizen_csrf_security_routing.py` | CSRF token validation and secure routing |
| `test_complaint_assistance.py` | Draft updates and PDF generation |
| `test_defect_map.py` | Geocoded marker queries and public-map data safety |
| Citizen update suites | Update types, ownership, privacy, report access and repair verification integrity (42 passing tests in the latest feature-specific regression report) |

**Important testing areas:** Gemini image analysis · road and building defect detection · multiple defect identification · bounding box validation · OpenCV annotation · invalid image handling · database persistence · citizen authentication · role-based access control · CSRF protection · inspection ownership · PDF generation · public map data · citizen progress updates · repair verification integrity · image upload and retrieval.

---

## 🚀 Deployment

VisionGuard AI is hosted on **Render**.

🔗 **Production:** https://visionguard-ttyp.onrender.com/

**Deployment requires:**

- Python dependencies installed
- WSGI application startup (Gunicorn on Linux, Waitress on Windows)
- Gemini API credentials
- Secure Flask secret key
- Persistent database configuration (Neon PostgreSQL)
- Appropriate image storage configuration (Cloudflare R2)
- Google OAuth configuration, when enabled
- Correct production callback URLs

> ⚠️ For production, database and image storage **must be persistent**. Local filesystem storage on an ephemeral hosting instance should **not** be treated as durable storage.

---

## 📈 Results & Impact

| Metric | Value |
|---|---|
| Automated tests passing | **81 / 81** |
| Defect categories supported | **12** (6 road · 6 building) |
| Detection accuracy | [ADD: value and how it was measured] |
| Average analysis time per image | [ADD: seconds] |
| Benchmark images evaluated | [ADD: count] |
| People who tested the app | [ADD: count] |

> Only add numbers you actually measured. Judges trust real metrics.

### Expected Impact

- ⚡ Faster preliminary defect identification
- 🖼️ Better visual documentation
- 📱 More accessible citizen reporting
- 🗺️ Improved geographical awareness of infrastructure problems
- 🕓 Historical tracking of reported defects
- 👀 Better visibility into repair progress
- 🔗 Structured information flow between citizens and inspection teams
- 🏙️ A foundation for a more transparent, data-driven reporting process

---

## ⚠️ Limitations

VisionGuard is designed for **preliminary visual infrastructure assessment**.

- **Visual analysis only:** photographs cannot reveal subsurface voids, internal rebar corrosion or underground leaks, which need specialized NDT equipment.
- **Image quality dependency:** poor lighting, low resolution and blur may reduce detection accuracy.
- **No physical measurement guarantee:** bounding boxes do not establish actual crack width, depth or structural capacity.
- **Preliminary severity:** AI-generated severity does not replace a professional engineering assessment.
- **Location dependency:** accurate mapping requires valid location information.
- **Internet dependency:** Gemini-based inference requires connectivity to the configured API.
- **Verification requirement:** citizen-reported repair progress needs verification before being treated as an official resolution.
- **Municipal integration:** generating a complaint PDF does not itself submit an official complaint to a municipal authority.

---

## 🗺️ Roadmap & Future Scope

**Completed**

- [x] Gemini multimodal AI defect detection
- [x] Multi-defect itemization with OpenCV overlays
- [x] Structured inspection reports and PDF export
- [x] Complaint workflow with duplicate prevention
- [x] Interactive defect map
- [x] Citizen Report Update System with timeline
- [x] RBAC, CSRF protection, Google OAuth and automated test suite
- [x] Cloud deployment on Render

**Planned**

- [ ] Fine-tuned edge models (YOLOv8 Nano) for offline dashcam inference
- [ ] Offline infrastructure defect detection
- [ ] Drone-based infrastructure inspection (orthomosaic batches for roads and roofs)
- [ ] Automated road condition monitoring
- [ ] Advanced infrastructure deterioration analytics
- [ ] Municipal complaint portal and authority integration
- [ ] Open311-compatible integrations / webhooks
- [ ] Geographic hotspot analysis
- [ ] Predictive infrastructure maintenance
- [ ] Time-series defect progression analysis
- [ ] Mobile application improvements

---

## 👥 Contributors

<div align="center">

**Team [ADD: TEAM NAME]** · NEURA X 2026 — Global Hackathon 2K26

<table>
  <tr>
    <td align="center" width="180">
      <a href="https://github.com/szeeshanZ123">
        <img src="https://avatars.githubusercontent.com/u/222632383?v=4" width="100" alt="Zeeshan"/><br/>
        <b>Zeeshan</b>
      </a><br/>
      <sub>⚙️ Backend Developer</sub><br/><br/>
      <a href="https://github.com/szeeshanZ123"><img src="https://img.shields.io/badge/GitHub-szeeshanZ123-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
    <td align="center" width="180">
      <a href="https://github.com/Sandesh-Narkar">
        <img src="https://avatars.githubusercontent.com/u/267092211?s=400&u=7d09b000dc3681a650dbe37a1e7cd35a467d52f2&v=4" width="100" alt="Sandesh"/><br/>
        <b>Sandesh</b>
      </a><br/>
      <sub>🎨 Frontend & UI/UX Design</sub><br/><br/>
      <a href="https://github.com/Sandesh-Narkar"><img src="https://img.shields.io/badge/GitHub-Sandesh--Narkar-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
    <td align="center" width="180">
      <a href="https://github.com/Yaswanth8407">
        <img src="https://avatars.githubusercontent.com/u/217727881?v=4" width="100" alt="Yaswanth"/><br/>
        <b>Yaswanth</b>
      </a><br/>
      <sub>⚙️ Backend Developer</sub><br/><br/>
      <a href="https://github.com/Yaswanth8407"><img src="https://img.shields.io/badge/GitHub-Yaswanth8407-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
    <td align="center" width="180">
      <a href="https://github.com/Sifatshaikh07">
        <img src="https://github.com/Sifatshaikh07.png" width="100" alt="Sifat Shaikh"/><br/>
        <b>Sifat Shaikh</b>
      </a><br/>
      <sub>💻 Frontend Developer</sub><br/><br/>
      <a href="https://github.com/Sifatshaikh07"><img src="https://img.shields.io/badge/GitHub-Sifatshaikh07-181717?style=flat-square&logo=github" alt="GitHub"/></a>
    </td>
  </tr>
</table>

</div>

---

## 🙏 Acknowledgements

- **NEURA X 2026** organizers, mentors and judges
- Google Gemini and Google AI Studio
- OpenCV · Flask · ReportLab · Leaflet.js · Tailwind CSS · Neon · Cloudflare R2 · Render

---

## 🔗 Project Links

| Resource | Link |
|---|---|
| 🚀 Live Application | https://visionguard-ttyp.onrender.com/ |
| 💻 GitHub Repository | https://github.com/szeeshanZ123/visionGuard |
| 🔑 Google AI Studio | https://aistudio.google.com/ |
| 📚 Gemini Documentation | https://ai.google.dev/gemini-api/docs |
| 📚 Flask Documentation | https://flask.palletsprojects.com/ |
| 📚 OpenCV Documentation | https://docs.opencv.org/ |
| 📚 Leaflet Documentation | https://leafletjs.com/ |

---

## 📜 License & Disclaimer

Licensed under **[ADD: LICENSE]**. See `LICENSE` for details.

> ⚖️ **Disclaimer:** VisionGuard AI 2.0 provides AI-generated preliminary visual assessments for informational, educational and civic assistance purposes only. Its outputs are **not** certified structural engineering surveys, safety certifications, legal warranties or guarantees of municipal repair. All significant structural and safety decisions must be reviewed by appropriately qualified professionals. Citizen-submitted repair updates represent reported observations and do not constitute official verification.

📬 **Contact:** [ADD: email] · [Repository](https://github.com/szeeshanZ123/visionGuard)

---

<div align="center">

**Built with ❤️ for NEURA X 2026 — Global Hackathon 2K26**

*If VisionGuard impressed you, please ⭐ the repo.*

[⬆ Back to top](#top)

</div>
