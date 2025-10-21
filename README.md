# Quality at Entry (QAE) of IDB Policy-Based Loans (2023–2025)
**Author:** Diego Vallarino, Ph.D.  
**Institution:** Inter-American Development Bank (IDB), Office of the Executive Director for Uruguay, Paraguay, and Bolivia  
**Date:** October 2025  
**Repository:** QAE-Structural-Intelligence-IDB-2025  

---

## Disclaimer

This repository and its contents are part of an independent analytical exercise conducted by the author in a personal academic capacity.  
The analysis, opinions, and conclusions expressed herein do **not** represent the official views of the Inter-American Development Bank (IDB),  
its Management, the Office of Evaluation and Oversight (OVE), or the Executive Director’s Office for Uruguay, Paraguay, and Bolivia.  
All responsibility for the analysis and interpretations lies solely with the author.

---

## Overview
This repository contains analytical resources and documentation related to the report  
**"Quality at Entry (QAE) of IDB Policy-Based Loans (2023–2025): Structural Context, Institutional Capability, and the Political Economy of Reform."**

The study evaluates **41 Policy-Based Loans (PBLs)** approved by the Inter-American Development Bank (IDB) between 2023 and 2025, using a **1–6 ordinal quality scale**.  
It integrates institutional indicators from **UNDP–OAS (2024)** with IDB’s Quality-at-Entry framework, applying an **AI-assisted ontology** for semantic evaluation of operational documents.

---

## Methodology
The analytical framework combines:
1. **Ten QAE criteria**: Ownership, Value Added, Choice & Design, Theory of Change, Size & Dimension, Criticality, Results Indicators, Risks, Truncation, and Narrative Coherence.  
2. **Structural context variables**: Risk and Capability indices derived from UNDP–OAS (2024).  
3. **Hybrid evaluation** using both quantitative scores and text-mined evidence extracted from PBL documentation.

All scores are standardized on a **1–6 ordinal scale**, consistent with IDB quality assurance protocols.  
Analyses were conducted using **R (tidyverse, ggplot2, readxl, corrplot)** and **Python (pandas, scikit-learn, networkx)**.

---

## Data
- **`/data/QAE_41PBLs.xlsx`** – Core dataset containing the 41 evaluated operations with their ten QAE dimensions.  
- **`/scripts/analysis_QAE.R`** – Main R script for data cleaning, statistical analysis, and visualization.  
- **`/scripts/ontology_extraction.py`** – Python script for semantic parsing and ontology-based tagging of PBL documents.  

**Note:**  
Due to internal confidentiality of IDB documents, **raw PBL data and code** are available **upon request** for academic or institutional replication.  
To request access, please contact the author or open an issue in this repository.

---

## Main Findings
- **Average QAE:** 5.0 (Satisfactory), up from the **2015–2020 OVE baseline of 4.3**.  
- **Institutional capability** is the strongest predictor of design quality.  
- **Risk** improves quality only when capability is high (“risk-compensated rationality”).  
- **Theory of Change** remains the weakest dimension across PBLs.  
- QAE operates as a form of **structural intelligence**, transforming uncertainty into coherent institutional reasoning.

---

## Formal Model
The empirical relationship between QAE (𝑄), risk (𝑅), and capability (𝐶) follows:

Qi = α + β1Ri + β2Ci + β3(Ri × Ci) + εi

where β₃ > 0 indicates the moderating effect of capability on the risk–quality relationship.  
The logistic representation models the equilibrium quality frontier under bounded institutional capacity.

---

## Citation
If using this repository, please cite:

> Vallarino, D. (2025). *Quality at Entry (QAE) of IDB Policy-Based Loans (2023–2025): Structural Context, Institutional Capability, and the Political Economy of Reform.* Inter-American Development Bank.

---

## License
This repository is distributed under a **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.  
You are free to use and adapt the materials with proper attribution for academic or institutional purposes.

---

## Contact
**Author:** Diego Vallarino, Ph.D.  
**Email:** diegoval@iadb.org  
**Location:** Washington, D.C., USA  

---

