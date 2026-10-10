# Intelligent Solar-Battery Energy Management System

An interactive software prototype designed to simulate and optimize domestic electricity dispatch among solar panels, battery storage, and the WAPDA grid for Pakistani households.

---

## 📌 Project Overview

Residential solar installations in Pakistan face daily operational inefficiencies due to reliance on manual switches or static inverter rules. Inverters often draw expensive WAPDA grid power while battery storage sits unused, or discharge batteries during non-critical hours, leaving insufficient reserve when scheduled load shedding occurs.

The **Intelligent Solar-Battery Energy Management System** addresses these challenges through a simulation-based web application. Without requiring physical electrical equipment or direct inverter coupling, the prototype evaluates simulated solar generation, battery state of charge (SOC), household demand, and scheduled load-shedding windows. It recommends optimal source switching, preserves emergency battery reserves for outages, estimates electricity costs under configurable tariffs, and provides transparent text explanations for each decision.

---

## 🎯 Key Features

- **Interactive Telemetry Dashboard:** Displays simulated solar output, battery SOC, house load, and WAPDA grid status in real time.
- **Intelligent Switching Logic:** Algorithmic decision engine evaluating real-time conditions to recommend whether solar, battery, or WAPDA should power the house.
- **Load-Shedding Reserve Planning:** Computes and protects the necessary battery reserve margin ahead of scheduled grid blackouts.
- **Tariff Cost Estimation:** Models peak, off-peak, and net metering rates to calculate operational electricity costs.
- **Explainable Recommendations:** Delivers human-readable justifications for every automated switching suggestion.
- **Comparative Baseline Benchmarking:** Compares the proposed intelligent logic against a standard fixed-threshold switching mode using identical simulated test profiles.

---

## 🛠️ Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Frontend Framework** | React.js (via Vite) |
| **UI Styling** | Tailwind CSS |
| **Data Visualization** | Recharts |
| **Backend API** | Python (FastAPI) |
| **Simulation & Modeling** | NumPy, Pandas, scikit-learn |
| **Database** | PostgreSQL (with SQLAlchemy ORM) |
| **Testing & API Inspection** | Pytest, Postman |
| **Design & Architecture** | Figma, draw.io |
| **Version Control** | Git & GitHub |

---

## 👥 Contributors

Department of Computer Sciences, Namal University, Mianwali  
**Course:** CSC-225 Software Engineering  

| # | Name | Roll No. | University Email |
| :-: | :--- | :-: | :--- |
| 1 | **Muhammad Uzair Sajid** | NUM-BSCS-2025-42 | `bscs25f42@namal.edu.pk` |
| 2 | **Muhammad Awais** | NUM-BSCS-2025-32 | `bscs25f32@namal.edu.pk` |
| 3 | **Iqra Bibi** | NUM-BSCS-2025-21 | `bscs25f21@namal.edu.pk` |
| 4 | **Tayyaba Akhtar** | NUM-BSCS-2025-59 | `bscs25f59@namal.edu.pk` |

- **Course Instructor:** Mam Asiya Batool (`asiya.batool@namal.edu.pk`)
- **Requirement Provider (RP):** Dr. Ali Shahid (HoD Computer Science, Namal University)

---
