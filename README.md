# Replication of Imai, Horiuchi & Taniguchi (2007 AJPS)

This repository contains my replication work of:

**Horiuchi, Yusaku, Kosuke Imai, and Naoko Taniguchi (2007).  
"Designing and Analyzing Randomized Experiments: Application to a Japanese Election Survey Experiment."  
American Journal of Political Science, 51(3): 669–687.**

---

## 🎯 Objective
Systematically **replicate** the tables and figures in the AJPS 2007 paper and **extend** the analysis with modern robustness and sensitivity tools.

---

## 📂 Contents
- `day1_report.Rmd` / `day1_report.html` — Baseline replication (Tables 2, 3, Figure 3).  
- `day2_report.Rmd` / `day2_report.html` — Robustness checks (S1, S2).  
- `day3_report.Rmd` / `day3_report.html` — Bayesian SAFE & Appendix extensions (delta sensitivity, subgroup runner, one-click pipeline).  
- `.gitignore` — Keep the repo clean (optionally ignore knitted HTML).

---

## ✅ Progress

**Day 1 — Core results**  
- Reproduced **Table 2** (ITT & CACE), **Table 3** (subgroup analyses), **Figure 3** (heterogeneous effects).  
- Matches the main empirical results in the paper.

**Day 2 — Robustness checks (Section 4 / Appendix)**  
- **S1:** Alternative treatment receipt definitions (D1=visited; D2/D3 if available).  
- **S2:** Missingness robustness (complete-case, worst/best bounds, multiple imputation).  
- Findings are **stable** across reasonable definitions and missing-data assumptions.

**Day 3 — Bayesian SAFE & Appendix Extensions**  
-  **SAFE** run 
- **Delta-adjusted missingness sensitivity** (LI/NI-style), beyond MAR/MI.  
- **Subgroup runner** and **one-click pipeline** to reproduce S1/S2/Delta for any subgroup; fully reusable code.

---

## 👩‍🎓 About Me
**Cara Li** —  **Harvard Business School MBA (Class of 2027)**

**Background**:  
- B.A. in Economics (Statistics), Peking University  
- Schwarzman Scholar, Tsinghua University  
- Goldman Sachs (IB), **Zhipu AI** (AI agent & LLM applications)

Interests: **causal inference, experimental design, governance & technology**.  
🔗 LinkedIn: https://www.linkedin.com/in/carali7769/  
📧 qinghongli98@gmail.com

---

## ⭐ Acknowledgment
Inspired by the pioneering work of **Professor Kosuke Imai** on experimental methods and causal inference.
