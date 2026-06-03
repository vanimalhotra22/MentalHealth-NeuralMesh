# 🧠 Silent Signal: The Agentic Neural Mesh for Mental Health
[![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge)](https://mentalhealth-neuralmesh.onrender.com) 
[![Frontend](https://img.shields.io/badge/Frontend-React--Vite-blue?style=for-the-badge&logo=react)](https://vercel.com) 
[![Backend](https://img.shields.io/badge/Backend-FastAPI-green?style=for-the-badge&logo=fastapi)](https://render.com) 
[![AI Pipeline](https://img.shields.io/badge/AI-Gemini%20%2B%20YOLOv8-purple?style=for-the-badge&logo=google-gemini)](https://deepmind.google)
> *"Silence is not empty; it is full of answers."*
**Silent Signal** is a hyper-personalized mental health ecosystem designed to bridge the gap between biological distress signals and immediate clinical psychological support. Unlike traditional chatbots, our platform is **Agentic**—it actively senses distress through computer-vision-based biometrics and intervenes dynamically before a crisis occurs.
---
## 🌟 Core Features
### 1. Neural Mesh (Live Analysis)
The central nervous system of the application. A glowing, animated SVG Orb visualizes the user's real-time mental state, shifting colors dynamically (Blue for Calm, Red for Stress) based on live biometric data.
### 2. Biometric Resonance (rPPG Scanner)
Non-invasive diagnosis using computer vision.
* **Technology:** Uses the device camera to track face micro-movements (Remote Photoplethysmography).
* **Metrics:** Extracts **Heart Rate (BPM)** and **Respiration Rate** without requiring physical wearables.
* **Smart Flow:** Auto-triggers the "Dr. AI" consultation if high stress levels are registered.
### 3. Dr. AI (Hybrid Intelligence)
A next-generation empathetic therapist powered by a **Multi-Model Pipeline**:
* **Reasoning (Google Gemini 2.5 Flash):** Generates medically grounded, context-aware CBT therapeutic advice.
* **Vitals-Aware:** Adapts tone and guidance dynamically based on your current heart rate and anxiety score.
* **Hands-Free:** Supports real-time browser voice recognition dictation during acute panic states.
### 4. Neuro-Nutrition & Pharmacy Engine
* **Diet Plans:** Analyzes stress levels to suggest meal plans containing cortisol-lowering nutrients.
* **Curated Supplements Store:** Purchase supplements (Ashwagandha, Magnesium) tailored to current stress scores.
* **Full Cart & Invoicing:** Features a simulation payment system with custom-generated, downloadable PDF invoices.
### 5. Expert Care Loop (Telehealth)
* **Smart Booking:** Recommends medical specialists (Psychiatrists, Neurologists) based on anxiety levels.
* **Consultations:** Select dates, schedule appointments, and connect securely.
### 6. Emergency SOS Dashboard
* High-contrast distress interface.
* Generates a dynamic QR health card containing current vitals for first responders to scan instantly.
---
## 🏗️ Technical Architecture
```mermaid
graph TD
    A[React Frontend] -->|axios| B(FastAPI Gateway)
    B -->|google-generativeai| C[Gemini 2.5 Flash]
    B -->|ultralytics| D[YOLOv8 Face ROI Lock]
    B -->|SQLAlchemy| E[(SQLite Database)]
    A -->|OAuth 2.0| F[Google Authentication]
Frontend: React.js, Tailwind CSS/Glassmorphism, SVG Visualizations, Lucide React, Axios.
Backend: Python FastAPI, SQLite, SQLAlchemy ORM, Uvicorn.
AI & Computervision: Google Gemini API, YOLOv8 (ultralytics), Pandas.
