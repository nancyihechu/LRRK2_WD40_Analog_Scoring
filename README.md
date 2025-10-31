# 🧬 LRRK2 WD40 Analog Scoring for Parkinson’s Drug Discovery
Implementation of weighted and SkNN-based composite scoring for analog prioritization in Parkinson’s LRRK2 WD40 domain drug design.

This repository contains the workflow, datasets, and Jupyter notebooks used for the **computational scoring and prioritization of small-molecule analogs** targeting the **WD40 domain of LRRK2**, a key protein implicated in **Parkinson’s disease**.

---

## 📘 Overview

This project explores two approaches for analog scoring and selection:

1. **Weighted Composite Score** – combines binder count, similarity ranking, and total similarity into a unified metric.  
2. **SkNN Composite Score** – a refined, data-driven approach based on Tanimoto similarity, binary binding labels, and rank-weighted k-nearest neighbors.

These workflows were used to evaluate analogs of the **reference hits MU8843 and A1AUU**, retrieved from **Enamine** and **MolPort** compound libraries.

---

## ⚙️ Methods & Tools

- **Programming:** Python (Jupyter Notebooks)  
- **Libraries:** RDKit, pandas, NumPy, scikit-learn, matplotlib, openpyxl  
- **Data:** Ligand analogs of MU8843 and A1AUU  
- **Output:** Ranked analog lists with composite scores and aligned structures (Maestro format)

---


