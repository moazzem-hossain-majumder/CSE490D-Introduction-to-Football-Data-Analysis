# CSE490(D): Introduction to Football Data & Analytics

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Department](https://img.shields.io/badge/BRAC%20University-CSE490D-red.svg)](https://www.bracu.ac.bd/)

Welcome to the official course repository for **CSE490(D): Introduction to Football Data & Analytics** at **BRAC University**.

This repository contains comprehensive lecture reading materials, mathematical derivations, Jupyter notebook implementations, spatial diagrams, statistical hypothesis testing models, and research project guidelines.

---

## 📚 Course Modules & Syllabus Roadmap

```
                          CSE490D Course Modules
=============================================================================
Module 1: Data Foundations & Visualization
  ├── Introduction to Event Data & KPIs
  ├── Visualizing Football & Coordinate Geometries (StatsBomb, WyScout, Opta)
  └── Passing Networks & Team Topology

Module 2: Statistical Models & Expected Goals (xG)
  ├── Choosing & Fitting Statistical Models
  ├── Advanced Machine Learning Models (Logistic Regression, XGBoost)
  └── Building, Calibrating & Evaluating an xG Model

Module 3: Player & Action Valuation
  ├── Scouting, Player Profiling & Radar Charts
  └── Valuing Specific Actions (xT, VAEP, Markov Decision Processes)

Module 4: Uncertainty, Prediction & Trends
  ├── Randomness & Variance in Football (Poisson Processes)
  └── Team-Level KPIs, Rolling Metrics & Trend Analysis

Module 5: Space Control & Player Movement
  ├── Pitch Control Tools (Spearman Potential Field Models)
  └── Off-Ball Movement & Positional Dynamics

Module 6: Physical Data & Clustering Techniques
  ├── Physical Performance Metrics & High-Speed Running (HSR)
  └── Unsupervised Machine Learning (K-Means, GMM, Dimensionality Reduction)
=============================================================================
```

---

## 📂 Repository Structure

```
CSE490D-Introduction-to-Football-Data-Analysis/
├── Lecture 1/
│   ├── README.md                     # Comprehensive Lecture 1 Reading Material & Study Guide
│   ├── Introduction_Statsbomb.ipynb  # Hands-on Code: StatsBomb API, Events, Shot Maps, 360 Data
│   ├── Introduction_Wycout.ipynb     # Hands-on Code: WyScout Data, Sign Test, Student's t-Tests
│   └── images/                       # High-Resolution Pitch Maps, Slides & Statistical Plots
│       ├── competitions_df_slide.png
│       ├── event_vs_tracking_table_slide.png
│       ├── events_nan_table_slide.png
│       ├── matches_df_slide.png
│       ├── pitch_coordinate_comparison.png
│       ├── shot_map_hd.png
│       ├── shot_map_slide.png
│       ├── shots_non_nan_cols_slide.png
│       ├── sign_test_visualization.png
│       ├── statsbomb_360_frame_info.png
│       ├── statsbomb_360_hd.png
│       ├── statsbomb_360_pitch_slide.png
│       ├── statsbomb_360_player_coords.png
│       ├── statsbomb_hierarchy_slide.png
│       └── t_test_visualization.png
├── pdfs/
│   └── Lecture 1/                    # Original Faculty Lecture Slides & Colab Notebooks
│       ├── CSE490D_Lecture_1.pdf
│       ├── Lecture_1.pdf
│       ├── Introduction_Statsbomb.ipynb
│       └── Introduction_Wycout.ipynb
├── .gitignore                        # Git ignore rules for Python, Jupyter & temp files
└── README.md                         # Main repository portal
```

---

## 📖 Lecture Reading Materials Index

| Lecture | Topic | Core Concepts | Resources |
| :---: | :--- | :--- | :---: |
| **01** | **[Introduction to Football Data & Analytics](Lecture%201/README.md)** | Course overview, Event vs Tracking vs 360, Coordinate math, Shot maps, Sign test, 1-sample & 2-sample t-tests | [Lecture 1 Notes](Lecture%201/README.md) • [StatsBomb Notebook](Lecture%201/Introduction_Statsbomb.ipynb) • [WyScout Notebook](Lecture%201/Introduction_Wycout.ipynb) |

---

## 🛠️ Environment Setup & Quickstart

### 1. Clone the Repository
```bash
git clone https://github.com/moazzem-hossain-majumder/CSE490D-Introduction-to-Football-Data-Analysis.git
cd CSE490D-Introduction-to-Football-Data-Analysis
```

### 2. Set Up a Virtual Environment (Recommended)
```bash
python -m venv venv

# On Windows (PowerShell):
.\venv\Scripts\Activate.ps1

# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Required Dependencies
```bash
pip install --upgrade pip
pip install pandas numpy matplotlib seaborn scipy statsmodels mplsoccer statsbombpy jupyterlab
```

### 4. Launch Jupyter Notebooks
```bash
jupyter lab
```
Navigate to [`Lecture 1/Introduction_Statsbomb.ipynb`](Lecture%201/Introduction_Statsbomb.ipynb) or [`Lecture 1/Introduction_Wycout.ipynb`](Lecture%201/Introduction_Wycout.ipynb) and run all cells.

---

## 📊 Course Assessment Structure

| Assessment Component | Weight | Focus |
| :--- | :---: | :--- |
| **Research Project** | **25%** | Team scientific paper (Methodology 20% + Analysis/Validation 25% = 45%) |
| **Midterm Examination** | **20%** | Mathematical formulations, coordinate transforms, event log analysis |
| **Final Examination** | **20%** | Advanced spatial models, pitch control, and expected metrics |
| **Quiz** | **10%** | Coding implementation, Pandas manipulations, and API usage |
| **Mini Case Study** | **10%** | Tactical analytics brief |
| **Research Presentation**| **10%** | Oral defense of project methodology and tactical insights |
| **Attendance & Participation**| **5%** | Active engagement |
| **Total** | **100%** | |

---

## 👥 Course Instructors & Acknowledgments
- **Tasneem Mazhar** — Lecturer, Department of Computer Science & Engineering, BRAC University
- **Tanvir Anjum Aditto** — Lecturer, Department of Computer Science & Engineering, BRAC University
- Inspired by open-source football analytics materials from David Sumpter (*Soccermatics*), StatsBomb, and WyScout.

---

## 📄 License
This repository is released under the [MIT License](LICENSE).
