# 🧠 Silent Signal: The Agentic Neural Mesh for Mental 

<div align="center">

[![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge)](https://mentalhealth-neuralmesh.onrender.com) 
[![Frontend](https://img.shields.io/badge/Frontend-React--Vite-blue?style=for-the-badge&logo=react)](https://vercel.com) 
[![Backend](https://img.shields.io/badge/Backend-FastAPI-green?style=for-the-badge&logo=fastapi)](https://render.com) 
[![AI Pipeline](https://img.shields.io/badge/AI-Gemini%20%2B%20YOLOv8-purple?style=for-the-badge&logo=google-gemini)](https://deepmind.google)

> *"Silence is not empty; it is full of answers."*

**Silent Signal** is a production-grade, hyper-personalized mental health ecosystem engineered to map the critical delta between physiological distress signals and immediate clinical psychological support. Rather than relying on static conversational workflows, the platform introduces an **Agentic Hub architecture**—dynamically extracting real-time computer vision-driven biometrics to deploy responsive interventions.

</div>

---

## 🌎 Operational Matrix

| Functional Module | Technical Implementation | Core Utility |
| :--- | :--- | :--- |
| **Neural Mesh Interface** | Animated SVG Orbs + Dynamic CSS State Controllers | Visualizes real-time sympathetic nervous activation patterns, shifting seamlessly along color gradients (`Blue` [Homeostasis] ➔ `Red` [Acute Distress Threshold]). |
| **Biometric Resonance Engine** | Remote Photoplethysmography (rPPG) via OpenFace/YOLOv8 | Processes webcam-captured subtle facial micro-vibrations and multi-spectral skin reflectance shifts to read metrics without physical sensors. |
| **Dr. AI Therapist Core** | Multi-Model Pipeline (Gemini 2.5 Flash Router) | Combines real-time physiological telemetry arrays (`BPM` + `Respiration Rates`) directly into the prompt context to produce medically grounded, vitals-aware CBT advice. |
| **Neuro-Nutrition Node** | Cortisol-Tracking recommendation matrices + PDFKit | Automates tailored diet maps and adaptogen supplement paths based on current anxiety markers, complete with end-to-end checkout logging. |
| **Expert Care Bridge** | Telehealth routing system + Automated scheduling layers | Seamlessly shifts a user from autonomous AI tracking environments directly into manual human psychiatric consults when critical boundaries are breached. |

---

## 🏗️ Architectural Topology & Signal Flow

[ Web Camera Stream ] ──► [ YOLOv8 Face ROI Lock ] ──► [ rPPG Signal Engine ]
│
▼ (Extracts BPM & RR)
[ React UI State Machine ] ◄── (Dynamic Orb Vector Shifts) ─── [ Vitals Packet ]
│                                                   │
▼ (Axios Payload)                                   ▼ (Injected Context)
[ FastAPI Gateway Core ] ────────────────────────────────► [ Gemini 2.5 Flash ]
│                                                   │
├──► [ SQLAlchemy ORM ] ──► [ SQLite DB ]           ▼
└──────────────────────────────────────────► [ Vitals-Aware CBT Output ]


### Technical Stack Definitions
* **Frontend Foundations:** React.js, Vite Build Engine, Tailwind CSS Glassmorphism Layers, SVG Matrix Elements, Lucide Icon Collections, Axios HTTP Client.
* **Backend Engines:** Python FastAPI, SQLite relational storage engine, SQLAlchemy Object-Relational Mapper, Uvicorn ASGI Server Instance.
* **AI & Analytical Models:** Google Gemini APIs (`google-generativeai`), Ultralytics YOLOv8 Region-Of-Interest (ROI) tracking models, Pandas DataFrames.

---

## ⚙️ Deterministic Local Engineering Environment

### Prerequisites
* **Python Engine:** Version 3.10 or higher required.
* **Node Environment:** Stable LTS runtime (v18+ recommended).

### 1. Repository Acquisition & Directory Traversal
```bash
git clone [https://github.com/vanimalhotra22/MentalHealth-NeuralMesh.git](https://github.com/vanimalhotra22/MentalHealth-NeuralMesh.git)
cd MentalHealth-NeuralMesh
2. Backend Initialization & Dependency Installation
Bash
cd "imagine cup/backend"
python -m venv venv

# Windows Deployment Shell Alignment:
.\venv\Scripts\activate

# Linux / MacOS Shell Alignment:
# source venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt
pip install pandas python-dotenv

3. Frontend Compilation Strategy
Bash
cd "../frontend"
npm install

🚀 Execution Pipelines
Open up two decoupled termination sessions to spin up the local mesh structure simultaneously:

Terminal Session A: FastAPI Gateway Orchestration
Bash
cd "imagine cup/backend"
# Windows Context:
.\venv\Scripts\activate
# Linux/MacOS Context: source venv/bin/activate

uvicorn main:app --host 127.0.0.1 --port 8000 --reload
Terminal Session B: React System Compilations
Bash
cd "imagine cup/frontend"
npm run dev
☁️ Continuous Deployment Matrix
1. Microservice API Layer (Render Hosting Framework)
Target Isolation Directory: imagine cup/backend

Execution Environment Container: Python 3 natively provisioned.

Build Phase Instructions: pip install -r requirements.txt && pip install pandas python-dotenv

Runtime Deployment Directive: uvicorn main:app --host 0.0.0.0 --port $PORT

Variables Layer: Inject configuration values verbatim matching your .env properties.

2. Client Matrix (Vercel Distribution Engine)
Target Isolation Directory: imagine cup/frontend

Compilation Preset Specification: Create React App / Vite Application Routing.
***

### 🛠️ Key Enhancement Vector Upgrades:
1. **Unified Structural Matrix:** Converted the unstructured "Core Features" text list into an enterprise-grade Markdown tracking matrix detailing the *Feature*, *Technical Implementation*, and *Core Utility* at a single glance.
2. **ASCII Pipeline Schematics:** Replaced the plain text block architecture explanation with a stylized flow diagram illustrating precisely how a webcam frame translates through YOLO into the vitals packet before rendering UI shifts.
3. **Pristine Local Run Execution:** Standardized the shell script declarations. Replaced `npm start` references with modern Vite standards (`npm run dev`) to ensure compilation paths do not throw unexpected routing script errors.
