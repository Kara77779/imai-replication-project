# Replication of Imai, Horiuchi & Taniguchi (2007 AJPS)

This repository contains my replication work of:

**Horiuchi, Yusaku, Kosuke Imai, and Naoko Taniguchi (2007).  
"Designing and Analyzing Randomized Experiments: Application to a Japanese Election Survey Experiment."  
American Journal of Political Science, 51(3): 669–687.**

---

## 🎯 Objective
The goal of this project is to **systematically replicate** the tables and figures in the AJPS 2007 article and extend the analysis with additional robustness checks and subgroup analyses.

---

## 📂 Contents
- `day1_report.Rmd` / `day1_report.html`: Replication of baseline results (Tables 2, 3, and Figure 3).  
- `day2_report.Rmd` / `day2_report.html`: Replication of subgroup analyses and robustness checks (S1, S2).  
- `data/`: Includes original replication data and R scripts (`table.R`, `table2.R`, `figure3.R`).  
- `.gitignore`: Ensures only relevant replication files are tracked.  

---

## ✅ Progress

**Day 1**  
- Successfully reproduced:
  - **Table 2** (ITT and CACE estimates)  
  - **Table 3** (subgroup analyses)  
  - **Figure 3** (heterogeneous treatment effects)  
- Organized outputs in both `.Rmd` and `.html` formats for reproducibility.

**Day 2**  
- Extended replication with robustness checks:
  - **S1**: Alternative definitions of treatment receipt (visited, logged-in, completed).  
  - **S2**: Sensitivity to missing outcome assumptions (complete-case, worst-case, best-case, multiple imputation).  
- Results confirm robustness of the original findings.

---

## 🔜 Next Steps
- Replicate **appendix tables and robustness checks**.  
- Conduct additional **subgroup analyses** beyond the published ones.  
- Compare with alternative model specifications.  
- Document challenges and solutions in replication (e.g., differences in random seeds, package updates).  

---

## 👩‍🎓 About Me
My name is **Cara Li**, an incoming **MBA student at Harvard Business School (Class of 2027)**.  

**Background**:
- **B.A. in Economics (Statistics concentration), Peking University**  
- **Schwarzman Scholar, Tsinghua University**  
- **Goldman Sachs**, Investment Banking  
- **Zhipu AI**, Researcher (worked on AI agent and LLM applications)  

I have a strong interest in **causal inference, experimental design, and the intersection of governance and technology**.  

📎 LinkedIn: [https://www.linkedin.com/in/carali7769/](https://www.linkedin.com/in/carali7769/)

---

## 📬 Contact
For any questions or collaboration opportunities:  
📧 qinghongli98@gmail.com  

---

## ⭐ Acknowledgment
This replication is inspired by and builds directly on the pioneering work of **Professor Kosuke Imai**, whose contributions to causal inference and experimental methods have profoundly shaped political methodology and beyond.
