# 🎓 GPA Planner — Academic Analytics & Degree Simulation Suite

<div align="center">

[![HTML5 / Vanilla JS](https://img.shields.io/badge/Stack-HTML5%20%7C%20Vanilla%20JS-E34F26?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![Chart.js](https://img.shields.io/badge/Visuals-Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![jsPDF](https://img.shields.io/badge/Export-jsPDF-FF9900?style=for-the-badge)](https://github.com/parallax/jsPDF)
[![Privacy First](https://img.shields.io/badge/Privacy-100%25%20Client--Side-brightgreen?style=for-the-badge&logo=shield&logoColor=white)](#privacy--client-side-guarantee)
[![Dark Mode](https://img.shields.io/badge/Theme-Light%20%2F%20Dark-6366F1?style=for-the-badge&logo=affinitydesigner&logoColor=white)](index.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**A modern, responsive, zero-dependency academic planning suite for university students. Calculate weighted GPAs dynamically, simulate what-if grade scenarios, plan milestones for Latin Honors, and generate printable PDF planning transcripts.**

[Features](#-key-features) • [Application Pages](#-application-modules) • [How to Run](#-quick-start) • [Grading Model](#-grading-scale--calculation-logic) • [Data & Privacy](#-privacy--client-side-guarantee)

</div>

---

## 🌟 Key Features

- **⚡ Instant Weighted Calculations**: Computes semester GPA, cumulative GPA, completed credit hours, and total quality points dynamically on every keystroke.
- **🔮 What-If Scenario Simulator**: Forecasts prospective course grades and simulates their exact impact on cumulative standing before taking exams or enrolling.
- **🎯 Target GPA Planner**: Input your desired graduation GPA (e.g. 3.50, 3.80) and remaining credit hours to find the exact required GPA and letter grade distribution needed.
- **📊 Interactive Chart.js Visuals**: Track semester-by-semester GPA trends, credit distribution by subject category, grade breakdown percentages, and graduation trajectories.
- **📄 Client-Side PDF Transcripts**: Generate downloadable, professional academic planning summaries formatted with jsPDF right in the browser.
- **📥 Import / Export Flexibility**: Seamlessly import existing coursework from CSV spreadsheets or export full JSON backups for safekeeping.
- **🌓 Adaptive Theme**: Smooth toggle between Light and Dark modes with persistent browser preferences.

---

## 🖥️ Application Modules

| Module | Icon | Description |
|---|:---:|---|
| **Dashboard** | 📊 | Metric cards for Cumulative GPA, Total Credits, Academic Standing (Summa / Magna / Cum Laude / Dean's List), and quick charts. |
| **Course Registry** | 📋 | Filterable course directory with search by keyword, semester, category (*Major, Minor, Core, Elective*), and letter grade. |
| **What-If Simulator** | 🔮 | Test multiple hypothetical future course scenarios with instant side-by-side cumulative GPA diff previews. |
| **Target Planner** | 🎯 | Computes the required GPA and realistic letter grade allocations needed across remaining semesters to reach target academic tiers. |
| **Detailed Analytics** | 📈 | Full-width trend curves, grade frequency distribution histograms, and credit category doughnuts. |
| **Export & Backup** | 📤 | Export styled PDF transcripts, download CSV records, or save/restore complete JSON course archives. |
| **Settings** | ⚙️ | Configure custom GPA scales (4.0, 4.33, or custom weights), edit grade cutoff thresholds, and manage course categories. |

---

## 🧮 Grading Scale & Calculation Logic

Weighted Cumulative GPA is computed using the standard universal quality points formula:

$$\text{Cumulative GPA} = \frac{\sum (\text{Course Credits} \times \text{Grade Point})}{\sum \text{Earned Credit Hours}}$$

### Standard 4.0 Scale Reference

| Grade | Points | Percentage Range | Standing Equivalent |
|:---:|:---:|:---:|:---|
| **A+ / A** | **4.00** | 90% – 100% | Excellent / High Distinction |
| **A-** | **3.67** | 85% – 89% | Superior |
| **B+** | **3.33** | 80% – 84% | Very Good |
| **B** | **3.00** | 75% – 79% | Good |
| **B-** | **2.67** | 70% – 74% | Above Average |
| **C+** | **2.33** | 65% – 69% | Average |
| **C** | **2.00** | 60% – 64% | Satisfactory |
| **D** | **1.00** | 50% – 59% | Minimum Passing |
| **F** | **0.00** | Below 50% | Fail |

*Note: Non-credit courses, Incompletes (I), and Withdrawals (W) are excluded from the GPA divisor.*

---

## 🚀 Quick Start

No installations, build steps, or backend servers required!

### 1. Clone or Download
```bash
git clone https://github.com/Rahim36712/gpa-planner.git
cd gpa-planner
```

### 2. Launch
Double-click `index.html` or open it directly in Google Chrome, Firefox, Edge, or Safari:
```powershell
start index.html
```

Or serve via any static HTTP utility:
```bash
python -m http.server 8000
# Open http://localhost:8000
```

---

## 🔒 Privacy & Client-Side Guarantee

> [!NOTE]
> All student data, course rosters, grades, and scenarios are stored **exclusively in your browser's `localStorage`**. No academic records, grades, or personal identifiers are ever sent to an external server.

---

## 📁 Repository Structure

```
gpa-planner/
├── index.html        # Monolithic single-page application (UI, CSS, Engine, JS)
├── .gitignore        # Git ignore rules
└── README.md         # Documentation
```

---

<div align="center">
  <sub>Empowering students to take control of their degree trajectory with data clarity.</sub>
</div>
