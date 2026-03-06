# 🧬 Recellion — ImmunoReset Digital Platform

<div align="center">

**SOSTAC® Marketing Plan — Resetting the Immune System**

**M9 Strategic Marketing in Life Sciences — Master Course Project**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 📖 About

This project was developed as part of the **M9 Strategic Marketing in Life Sciences** master course. It presents the **SOSTAC® Marketing Plan** for **Recellion ImmunoReset** — an off-the-shelf mRNA CAR-T cell therapy targeting refractory autoimmune diseases, specifically **Systemic Lupus Erythematosus (SLE)** and **Rheumatoid Arthritis (RA)** in the EU market.

The interactive, single-page web dashboard demonstrates the end-to-end digital platform concept for managing the full patient journey: from screening and enrollment, through manufacturing and infusion logistics, to adverse event monitoring, clinical analytics, and strategic marketing planning.

> ⚠️ **Disclaimer:** This is a demonstration/educational platform developed for academic purposes. It does not process real patient data, and it is not intended for clinical use.

---

## ✨ Features

### 📊 Dashboard Overview
- Real-time summary cards: active patients, manufacturing status, adverse event alerts, and 3-month remission rates
- Visual chart placeholders for Treatment Journey Progress and Toxicity Trend Analysis
- Animated metric cards with gradient styling

### 🔍 Patient Screening & Enrollment
- Eligibility questionnaire form (Patient ID, Primary Diagnosis, Refractory Status)
- Interactive eligibility assessment with real-time feedback
- Candidate patient list with priority status indicators (Green/Yellow/Red)

### 📅 Therapy Logistics & Scheduling
- mRNA CAR-T production pipeline with animated progress bars
- Appointment scheduling for leukapheresis, infusion, and follow-ups
- Automated reminder system simulation

### 🛡️ Adverse Event Monitoring
- Active patient monitoring dashboard for CRS and ICANS detection
- Real-time symptom reporting form (Patient ID, Symptom, Severity 1–5)
- Status-based alerting system (Grade 1 CRS, Stable, etc.)

### 📈 Clinical Insights & Analytics
- Long-term remission rate tracking (SLE & RA)
- Adverse event trend analysis
- Patient Reported Outcomes (PROs)
- Cost-effectiveness modeling (Recellion vs. lifelong biologics)

### 📚 Patient & HCP Resources
- Patient journey educational videos (placeholder)
- Healthcare Professional (HCP) training modules
- Frequently Asked Questions (FAQs)
- Support group information and advocacy contacts

### 🎯 SOSTAC® Marketing Framework
Full strategic marketing plan covering all six SOSTAC® stages:
1. **Situation Analysis** — Market size, competitive landscape, customer segments
2. **Objectives** — Regulatory milestones, market penetration, revenue targets
3. **Strategy** — Positioning, segmentation, go-to-market, communication
4. **Tactics** — Clinical development, HCP education, patient advocacy, market access
5. **Action** — Timeline from preclinical (Q2 2025) to EU launch (Q2 2029)
6. **Control** — KPIs across clinical, regulatory, commercial, financial, and digital metrics

### 🎯 Marketing Objectives
- Year 1 & Year 2 targets: certified centers, physician training, patient treatment volumes, market share, and reimbursement goals

### 💰 Cost Comparison Calculator
- Interactive tool comparing lifetime costs of traditional biologics vs. Recellion's one-time CAR-T therapy
- Configurable annual treatment cost, treatment duration, and CAR-T cost inputs

### 🔬 Treatment Process Demo
- Step-by-step interactive walkthrough of the mRNA-LNP CAR-T treatment process:
  1. T-cell Collection (Leukapheresis)
  2. Engineer-Reprogram (mRNA-LNP Delivery)
  3. Expansion
  4. Chemotherapy & Infusion
  5. Autoreactive Cell Elimination (Immune Reset)

### 💵 Budget Analysis
- Detailed Phase 2 & Phase 3 clinical trial budget breakdown
- Fully-loaded production cost per patient: ~$3,970

### 🤝 Key Partners
- Academic & clinical research centers
- Contract Manufacturing Organizations (CMOs)
- Biotech & pharma companies
- Patient advocacy groups
- Regulatory consultants
- Technology providers (CRISPR, TALEN, viral vectors)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Glassmorphism design, gradients, animations, responsive layout |
| **Vanilla JavaScript** | SPA navigation, interactive demos, form handling |
| **Font Awesome 6** | Icon library for UI elements |

**No frameworks or build tools required** — the entire application is a single `index.html` file (~1,668 lines) that can be opened directly in any modern browser.

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- No server or build tools needed

### Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ugrersoz/car-t-dashboard-course.git
   ```

2. **Navigate to the project:**
   ```bash
   cd car-t-dashboard-course/car-t-main
   ```

3. **Open in browser:**
   ```bash
   # Simply open the file
   start index.html        # Windows
   open index.html          # macOS
   xdg-open index.html      # Linux
   ```

   Or use a local development server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve .
   ```

---

## 📐 Design System

The dashboard features a modern, premium design with:

- **Color Palette:**
  - Primary Gradient: `#ff69b4` (Hot Pink) → `#8a2be2` (Blue Violet)
  - Background: Soft cream-pink gradient (`#fce4ec` → `#e1bee7` → `#fff3e0`)
  - Status Colors: Green (success), Yellow (warning), Red (alert)

- **UI Components:**
  - Glassmorphism cards with `backdrop-filter: blur(20px)`
  - Animated progress bars with shimmer effect
  - Hover micro-animations (translateY, scale, rotate)
  - Slide-in alerts with auto-dismiss

- **Typography:** Inter / Segoe UI font family

- **Responsive:** Full mobile support with breakpoint at 768px

---

## 📁 Project Structure

```
car-t-dashboard-course/
└── car-t-main/
    ├── index.html          # Complete single-page application
    ├── README.md           # Project documentation
    └── .github/
        └── workflows/      # GitHub Actions (if any)
```

---

## 🗺️ Roadmap

- [ ] Integrate real chart libraries (Chart.js / D3.js) for data visualization
- [ ] Add backend API for persistent patient data
- [ ] Implement user authentication (HCP vs. Patient roles)
- [ ] Connect real-time adverse event alerting system
- [ ] Localization for EU markets (DE, FR, ES, IT)
- [ ] PDF report generation for clinical insights

---

## 👥 Team

This project was created as a group project for the **M9 Strategic Marketing in Life Sciences** master course:

| Team Member | 
|---|
| **Asaf Ronel** |
| **Maiia Talashvili** |
| **Daria Krasavina** |
| **Ugur Ersöz** |
| **Natalia Inozemtseva** |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

*Built with ❤️ for the future of autoimmune disease treatment*

*M9 Strategic Marketing in Life Sciences — Master Course Project*

</div>
