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
  - [Day 1 HTML](path/to/day1_report.html)
- `day2_report.Rmd` / `day2_report.html` — Robustness checks (S1, S2).  
  - [Day 2 HTML](path/to/day2_report.html)
- `day3_report.Rmd` / `day3_report.html` — Bayesian SAFE & Appendix extensions (delta sensitivity, subgroup runner, one-click pipeline).  
  - [Day 3 HTML](path/to/day3_report.html)
- `data/` — Replication data & auxiliary scripts (`data.txt`, optional `bayes.RData`, authors’ scripts if available).
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
- Optional **SAFE** run (if authors’ `safe()` is available); otherwise frequentist pipeline remains the benchmark.  
- **Delta-adjusted missingness sensitivity** (LI/NI-style), beyond MAR/MI.  
- **Subgroup runner** and **one-click pipeline** to reproduce S1/S2/Delta for any subgroup; fully reusable code.

---

## 🔜 Next Steps
- If needed, run the **authors’ SAFE code** by dropping `bayes_safe.R`/`bayes.R` into `data/` (auto-sourced).
- Publish HTML via **GitHub Pages** or **Releases** for easy viewing.

---

## 👩‍🎓 About Me
**Cara Li** — Incoming MBA, **Harvard Business School (Class of 2027)**

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
