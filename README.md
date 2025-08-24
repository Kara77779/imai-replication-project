# Replication of Horiuchi, Imai & Taniguchi (2007 AJPS)

This repository contains replication materials for:

**Horiuchi, Yusaku, Kosuke Imai, and Naoko Taniguchi (2007).  
_Designing and Analyzing Randomized Experiments: Application to a Japanese Election Survey Experiment._  
American Journal of Political Science, Vol. 51, No. 3 (July), pp. 669–687.**

---

## Contents

- `week1_report.Rmd` – R Markdown file documenting replication steps  
- `week1_report.html` – compiled report with tables and figures  
- `data/` – raw replication files from the authors (tables, figures, R scripts)  

---

## Progress

- ✅ Replicated **Table 2** (ITT and CACE estimates)  
- ✅ Replicated **Table 3** (subgroup analyses)  
- ✅ Replicated **Figure 3** (heterogeneous treatment effects)  
- 🔜 Next steps: robustness checks, appendix tables, cross-check against original article  

---

## How to Run

1. Clone this repo  
2. Open `week1_report.Rmd` in RStudio  
3. Run `knit` to produce the `.html` report  

Dependencies:  
```r
tidyverse
coda
xtable
knitr
kableExtra
