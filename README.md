# 🚀 [Fab Mind AI]

> ⚠️ **Replace everything in `[ ]` brackets with your actual content before submission.**

---

## 👥 Team

| Field | Value |
|---|---|
| **Team Name** | [TEAM WARRIORS] |
| **Track** | [AI / DevOps / Sustainability / Open] |
| **Team Lead** | [Keval] — [26dce@charusat.edu.in] |
| **Members** | [Kush Vansadadiya], [Prtham Parmar], [Jainik Panchal] |

---

## 🎯 Problem Statement

At 3nm/5nm chip nodes, a 1% yield drop costs tens of millions per month. Root causes
hide across thousands of equipment sensors, process parameters, and defect images.
Engineers spend weeks finding the cause manually — every day of delay is lost
revenue. Process engineers also need to predict which upcoming batches are at risk
before they run, not after they fail.

---

## 💡 Solution

Phase 1: High-Throughput Edge Ingestion (The Senses)Deploy lightweight C++ edge agents directly on fab servers to stream sub-millisecond equipment data via standard SECS/GEM and OPC UA protocols. These agents compress and stream raw data into Apache Kafka, instantly routing text metrics to time-series databases and heavy defect images to object storage.Phase 2: Unified Data Fabric & Semantic Layer (The Brain)Consolidate the data into a unified platform like Databricks or Snowflake. Use a centralized Machine Learning Feature Store to map every physical wafer ID to its exact sensor profile, chemical log, and spatial defect map. This breaks down legacy vendor silos and gives the AI a complete, contextual picture of the manufacturing lifecycle.Phase 3: Hybrid AI Engine & Engineering Dashboard (The Action)Run dual-layered AI models: a Convolutional Neural Network (CNN) to instantly classify spatial wafer defects, and an XGBoost/LightGBM model to map feature relevance for root-cause isolation. Before an upcoming batch runs, a Physics-Informed Neural Network (PINN) runs a digital twin simulation, flagging out-of-bounds recipes and pushing proactive tuning alerts to engineers via a responsive React/WebGL dashboard.
---

## ✨ Key Features

Data Fusion & Root Cause IsolationMulti-Modal Data Ingestion: Automatically unifies time-series equipment sensors (FDC), spatial wafer maps, and high-resolution defect images into a single semantic layer.Automated Root-Cause Analysis: Uses advanced machine learning to instantly trace yield drops across thousands of process parameters, reducing troubleshooting time from weeks to minutes.Predictive Risk ModelingVirtual Metrology & Digital Twins: Simulates and predicts physical wafer properties between processing steps, catching deviations before actual physical inspection.Batch-Level Risk Scoring: Rates upcoming wafer lots using real-time machine learning models to identify high-risk anomalies before the recipe runs.Operational AutomationPrescriptive Parameter Tuning: Recommends exact equipment adjustments to process engineers to bring at-risk batches back into the safe yield window.Early-Warning Alerts: Flags drifting sensor signals or tool degradation before they cross critical control limits and cause scrap.

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | [ Python, C++] |
| **Frameworks** | [ FastAPI, REACT] |
| **IBM Technologies** | [ IBM Bob, IBM Cloud] |
| **Databases** | [ PostgreSQL, Redis] |
| **Other** | [Docker, GitHub Actions] |

---

## 📁 Repository Structure

```
├── src/                  # All source code
├── docs/                 # Written documentation
│   ├── problem-statement.md
│   ├── solution-overview.md
│   ├── architecture.md
│   └── setup-guide.md
├── demo/                 # Demo artifacts
│   ├── screenshots/      # App screenshots
│   └── demo-video-link.txt  # Link to demo video
├── presentation/         # Slide deck
└── submission.yaml       # Structured submission metadata
```

---

## ⚡ How to Run

> **Copy these exact steps from your [`docs/setup-guide.md`](docs/setup-guide.md)**

```bash
# 1. Clone the repo
git clone https://github.com/[your-repo].git
cd [your-repo]

# 2. Install dependencies
[your install command here]

# 3. Configure environment
cp .env.example .env
# Edit .env with your values

# 4. Run the project
[your run command here]
```

---

## 🖥️ Demo

| Artifact | Link |
|---|---|
| 📹 Demo Video | [See demo/demo-video-link.txt](demo/demo-video-link.txt) |
| 🌐 Live Demo | [See demo/live-demo-url.txt](demo/live-demo-url.txt) |
| 🖼️ Screenshots | [See demo/screenshots/](demo/screenshots/) |
| 📊 Presentation | [See presentation/slides.pdf](presentation/) |

---

## ⚠️ Known Limitations

> Be honest — judges appreciate transparency over overclaiming.

- [Limitation 1: e.g., "Authentication is mocked — not production-ready"]
- [Limitation 2: e.g., "Only tested on Chrome"]
- [Limitation 3: e.g., "Feature X is scaffolded but not fully implemented"]

---

## 🏅 What We're Most Proud Of

[Tell the judges what part of your submission is strongest and worth paying close attention to.]

---
