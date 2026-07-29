# DEA-Efficiency-Toolkit
### Generalized Data Envelopment Analysis (DEA) Toolkit for Eco‑Efficiency

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📖 Overview

This repository implements Data Envelopment Analysis (DEA) models, including the Slacks‑Based Measure (SBM) with undesirable outputs, for benchmarking eco‑efficiency. It is designed for energy and environmental applications but is modular enough for any production frontier analysis.

---

## 🛠 Models Included

- **CCR (CRS) and BCC (VRS)** radial DEA.
- **SBM‑DEA** (Tone, 2001) with undesirable outputs.
- **Dynamic DEA** (window analysis) – planned.
- **Meta‑Frontier** – planned.

---

## 🗂 Structure
```text
DEA-Efficiency-Toolkit/
├── src/
│ ├── sbm_dea.py # SBM solver (using pulp or scipy)
│ ├── utils.py # Data preprocessing helpers
│ └── visualization.py # Frontier plotting
├── examples/
│ └── energy_benchmark.ipynb # Example on energy sector
├── tests/
├── requirements.txt
└── README.md
