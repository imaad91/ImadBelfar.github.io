# Imad BELFAR — Industrial & Quality Engineer

> **Master 2 in Complex Systems Engineering, Industrial Track** · University of Évry Paris-Saclay  
> Apprenticeship @ **LIEM / Castles Technology** (2024–2026)

<p align="center">
  <img src="https://img.shields.io/badge/Process-BPMN%20%7C%20VSM%20%7C%20Lean-blue" />
  <img src="https://img.shields.io/badge/Data-Python%20%7C%20Excel%2FVBA-success" />
  <img src="https://img.shields.io/badge/Low--Code-AppSheet%20%7C%20ProcessMaker-orange" />
  <img src="https://img.shields.io/badge/ERP-ERPNext%20%7C%20NetSuite-red" />
  <img src="https://img.shields.io/badge/Android-Kotlin%20%7C%20ML%20Kit-brightgreen" />
</p>

---

## 👤 About

Industrial engineer with 2 years of hands‑on experience inside a fast‑changing payment terminal services company. I work at the intersection of **operations**, **process engineering**, and **digital tools** — diagnosing bottlenecks, deploying systems from scratch, and coordinating cross‑functional projects with clients like **BNP Paribas**.

I thrive in ambiguous, high‑stakes environments where the answer isn’t given — and where a well‑structured solution beats a perfect one that arrives too late.

📍 Paris, France · 🎓 Graduating June 2026  
📧 [imad.belfar@email.com](mailto:imad.belfar@email.com) · 🔗 [LinkedIn](https://linkedin.com/in/imadbelfar) · 🖥️ [GitHub](https://github.com/imadbelfar)

---

## 🛠️ Core skills

| Domain | Tools & Methods |
|--------|------------------|
| **Process Engineering** | BPMN / Draw.io, VSM, Lean / Theory of Constraints, 5 Whys, RMA optimisation |
| **Data & Simulation** | Python (pandas, matplotlib, scipy), Excel / VBA, Power Query / Power BI, statistical distributions, Flexsim |
| **Digital & Low‑Code** | AppSheet, ProcessMaker, Google Apps Script, Base44 (BaaS) |
| **ERP & Systems** | ERPNext (implementation & feasibility), Matrix42, Odoo, NetSuite |
| **Mobile Dev** | Android / Kotlin, ML Kit (OCR), PdfRenderer |
| **Project Management** | Cross‑functional coordination, client workshops, test & UAT, change management |
| **Languages** | French (native), English (professional) |

---

## 📁 Featured projects

### 01 · Operational audit – Vallery repair site
`Python` `Statistics` `Simulation` `Lean` `Theory of Constraints`

**Context:** The Vallery site (repair level 2 & 3 for Castles Technology terminals) showed mounting backlogs, unstable lead times, and missed SLAs. I was sent for a 2‑week diagnostic mission — with results expected by the group's EMEA Operations Director.

**What I did:**
- Analysed 6 months of operational KPIs (3,000+ units in WIP, SHP collapse in May 2025)
- Designed a **physical flow tracking experiment** — tagged 40 terminals, measured processing times at each station (screening → repair → cleaning → update/injection → QC test)
- Built **statistical distributions** (histograms, variance analysis) by model and by station in Python
- Identified the **update/injection station as the primary bottleneck** using Theory of Constraints logic
- Ran **4 scheduling simulations** → best scenario: **−33% lead time** vs baseline

**Results delivered:**
- Capacity reallocation actioned on the bottleneck station
- Weekly production planning meeting introduced
- Custom multi‑plug power station designed to reduce ergonomic friction
- Presented findings in English to the EMEA Operations Director

> 💡 *Key insight: doubling repair capacity without fixing the downstream bottleneck produced zero improvement. The constraint was never where people thought it was.*

---

### 02 · Order Management System – myPOS launch (5 countries)
`AppSheet` `Low‑Code` `Process Design` `UX` `Google Cloud`

**Context:** myPOS (European fintech, 500k+ clients) needed to launch logistics operations in France within **2 weeks** — with no ready‑to‑use system on either side. I designed and deployed the solution independently.

**What I built:**
- Evaluated Excel vs custom app vs low‑code → chose **AppSheet** on Google Cloud
- Designed the full **data model** (orders, line items, shipments, returns) and **role‑based access** (myPOS agents vs LIEM operators)
- Implemented a **6‑stage workflow** with conditional actions, automated status transitions, and timestamped traceability (who did what, when)
- Added Google Maps address validation, color‑coded priority views, automated packing slip generation, DOM‑TOM regulatory document handling
- Rolled out progressively: France → Belgium → Spain → Portugal → Netherlands (~20 users)

**Impact:**
- Go‑live on time, day 1
- Enabled reliable billing (SN‑linked invoicing)
- Usage logs used for continuous improvement across 5 countries
- Freed internal IT capacity for the BNP Paribas project
- 
**Stack:**  
`AppSheet` · `Google Cloud native DB` · `Chronopost API` · `Google Maps API`

**Users:** ~20 across 5 countries  
**Timeline:** designed + deployed in 2 weeks
---

### 03 · BNP Paribas – Full‑cycle service platform (CaSERV)
`Matrix42` `BPMN` `API Integration` `Bright Pattern` `Project Coordination`

**Context:** Following Castles Technology winning a strategic bid with BNP Paribas Services Monétiques (60,000+ terminals), LIEM had to build, from scratch, an integrated service platform and customer support centre. **Go Live: May 2026. Time to build: < 7 months.**

**My role:** Local Project Leader, embedded full‑time alongside the Transition Manager and a UK‑based IT Project Manager.

**What I contributed:**

*Process Engineering*
- Formalised **12 end‑to‑end business processes** (order prep, installation, L1/L2 support, standard swap, billing, returns, SIM/accessory management…)
- Modelled workflows in **BPMN on Draw.io**, iterated weekly with BNP Paribas stakeholders
- Translated business requirements into Matrix42 configuration specs for integrator Neokumo

*System Integration (CaSERV ecosystem)*
- Coordinated API mapping between **Mon TPE** (BNP Paribas), **Matrix42**, **CasHub** (Castles provisioning), **Chronopost**, **Lemon Group** (field installation), and **Oracle NetSuite** (group ERP)
- Participated in weekly IT alignment sessions with BNP Paribas IT and CaSERV Connect (API orchestration)
- Ran iterative **UAT cycles** on Matrix42 staging; logged anomalies and drove resolution

*Call Centre Setup (Bright Pattern)*
- Defined call flows, IVR scripts, and SLA‑aligned agent procedures for 8‑agent team (6 tech support + 2 admin)
- Trained first‑wave agents on Bright Pattern
- Conducted on‑site audit in Romania at **iNETcc** (outsourced call centre) to validate agent readiness (see project #04)

*PennyLane Pilot*
- Used PennyLane (accounting SaaS with Castles terminals) as a live pre‑production test environment
- Validated Bright Pattern ↔ Matrix42 integration under real conditions
- Took over operational management of PennyLane + BPCE portfolios (7 technicians) from May 2026

---

### 04 · On‑site audit & knowledge capture – iNETcc (BNP Paribas call centre)
`Call centre audit` `Process transfer` `Best practices` `Change management`

**Context:** iNETcc ([www.inetcc.com](https://www.inetcc.com)), a specialist telephone support provider, was brought in as reinforcement for BNPP merchant hotline. I was sent on a **4‑day mission** to:
- Verify that the tools we provided (Bright Pattern, knowledge base, escalation paths) worked correctly
- Clarify processes and scripts with their agents
- **Learn from their expertise** – iNETcc runs a pure‑play call centre; we wanted to capture their organisation, shift management, and quality methods to feed back into Castles Technology’s new support activity.

**What I did:**
- Audited agent adherence to defined workflows (call opening → diagnosis → resolution / escalation)
- Tested integration of our Matrix42 ticketing with their local environment
- Shadowed their team leads to document **best practices** (real‑time dashboards, coaching rituals, break scheduling, KPI board)
- Proposed 5 actionable improvements for our own centre (e.g., staggered breaks, voice‑of‑customer short feedback loop)

**Delivered:**  
A 2‑page knowledge memo for Castles management, plus a list of quick‑win changes applied immediately to the BNPP support ramp‑up.

> 💡 *Turning an external audit into a learning opportunity – we came to verify, but also to steal with pride.*

---

### 05 · 442Plan – Operational control web app for BPCE & PennyLane
`React` `Tailwind CSS` `Base44` `Real‑time dashboard` `Incentive calculation`

**Context:** Managing 7+ technicians across two clients (BPCE, PennyLane) with fragmented tools – Excel sheets for planning, paper for time tracking, manual bonus calculation. I designed and built **442Plan**, a full‑stack web application to centralise everything.

**Key modules & innovations:**

| Module | What it does |
|--------|---------------|
| **Dashboard** | Real‑time KPIs: production vs targets, team status (working/break/absent), individual performance |
| **HR** | Technician profiles, skill sliders per client/activity, absence & **late tracking** – any arrival >2 min late is auto‑logged here. Visual severity indicator (minutes cumulated) |
| **Time tracking** | Clock‑in/out, lunch & short breaks. Auto‑calculates total hours and feeds late records to HR |
| **Planning & Production** | Assign tasks by client/activity, track daily volumes, skill‑based workload optimisation |
| **Production counter** | Technicians record quantities (receptions, tests, etc.) per morning/afternoon – status: pending / validated / refused |
| **Volumes** | Logistic & lab reception forecasts, parcel distribution probabilities |
| **Reports & Settings** | Custom reports, configurable standard times per activity, competence impact factors |
| **BPCE Workflow** | Client‑specific processes |

**Why it matters:**  
- **Bonuses** are automatically calculated from actual performance vs targets (transparency, fairness)  
- Built with **React + Tailwind CSS**, backend as a service **Base44** (no infrastructure headaches)  
- Deployed and used daily by the PennyLane & BPCE teams  

> 💡 *From Excel chaos to a single source of truth: 442Plan saves ~3h/week of manual reporting and eliminates bonus disputes.*

---

### 06 · ERPNext feasibility & PoC – replacing legacy OGI
`ERPNext` `Benchmark` `Phantom BOM` `RMA` `Docker`

**Context:** The legacy “OGI” tool had critical limits: fragmented flows, redundant entries, costly external dependencies. I led the transformation pilot to evaluate and prove a new ERP.

**What I did:**
- **Benchmark** 4 solutions: Odoo, Solam, ERPNext, NetSuite → selected ERPNext (native manufacturing (MES) and WMS, perfect for S/N traceability in repair)
- **Technical PoC**: Installed ERPNext v14 on a Docker VM
- **Innovation – Phantom BOM**: Classic BOMs force a fixed parts list before diagnosis → I designed a “phantom item” workaround to create repair orders without predefining components. This made ERPNext viable for repair logistics.
- **Configured complex flows**: RMA returns, quotes (PRV/PRF), final quality control
- Delivered a **structured go/no‑go recommendation** to the IT steering committee

---

### 07 · Spare parts tracking tool – AVEM client
`Excel/VBA` `Barcode scanning` `5 Whys` `Inventory accuracy`

**Context:** 35% stock discrepancy (physical vs digital) for AVEM’s spare parts → caused repair delays and overstock.

**Methodology:** Used **5 Whys** to trace root causes → missing precise consumption traceability.

**Solution:**
- Excel/VBA UserForm to record movements by barcode scan
- Each movement gets a unique ID and “correction mode” audit trail
- **Clever trick**: A macro plays a silent audio file in a loop to prevent test stations from going to sleep (ensures availability on the shop floor)

**Result:** Stock discrepancies dropped from **35% to near zero**; automated reorder alerts.

---

### 08 · ICCHI – Android OCR quality control app
`Kotlin` `ML Kit (OCR)` `PdfRenderer` `Offline first`

**Context:** Terminal inversion errors in 2024 caused costly reconditioning and shipping delays. Manual verification was error‑prone and stressful.

**How it works:**
- Extracts data from mission order PDFs (PdfRenderer) and from photos of test tickets (ML Kit OCR)
- **DataComparator** logic: cross‑checks addresses, software versions, access numbers using a synonym dictionary (e.g., "FRV6 CB Contact" ↔ "CB EMV")
- **100% offline** – no internet, financial data never leaves the device

**Result:** 39/40 tests successful (97.5% accuracy) – eliminated operator stress and restored client confidence.

---

### 09 · RMA process optimisation with BPMN / ProcessMaker
`BPMN` `ProcessMaker` `Loop modelling` `RMA`

**Context:** At Vallery site, manual data entry for 4 repairs took 25 minutes – a major productivity loss.

**What I redesigned:**
- Mapped the **“final process”** integrating ignored ground realities:
  - **Level 0 bypass**: Terminals needing only a simple component swap go directly to cleaning without heavy lab step
  - **Feedback loops**: Routes back to repair if a defect is detected during cleaning or final test – ensures traceability up to shipping
- Designed the logic in BPMN, prototyped in ProcessMaker

**Impact:** Although not immediately deployed (OGI tool lock‑in), the study defined requirements for the future ERPNext and served as the functional spec for the RMA module.

---

## 📊 By the numbers

| Metric | Value |
|--------|-------|
| **300k+** terminals processed annually at LIEM | **−33%** lead time simulated (Vallery audit) |
| **2 weeks** to design + deploy myPOS system | **35% → near 0** stock discrepancy (AVEM) |
| **12 BPMN processes** for BNP Paribas | **60k+** terminals in CaSERV scope |
| **97.5%** OCR accuracy (39/40) | **8‑agent** support centre built from scratch |
| **4 days** on‑site audit (iNETcc) | **5 countries** live on AppSheet solution |
| **3h/week** saved with 442Plan | **7 technicians** managed daily via 442Plan |

---

## 🎓 Education

**Master 2 in Complex Systems Engineering, Industrial Track**  
University of Évry Paris‑Saclay (UEVE) · 2024–2026 · Apprenticeship

**Bachelor’s Degree in Engineering Science**  
University of Évry Paris‑Saclay (UEVE) · 2021–2024 ·

---

## 📌 Portfolio philosophy

> Every project here solved a real, painful operational problem. I don’t just analyse – I build, deploy, and measure. My tools change, but the approach stays: **understand the flow, find the constraint, implement the simplest working solution, then iterate.**

*This portfolio is updated regularly. More projects coming soon.*
