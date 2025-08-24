# Replication Project: Imai, Horiuchi & Taniguchi (2007 AJPS)

This repository contains my replication notes and code for the paper:

> Kosuke Imai, Yuki Shiraito, and Jun Shimizu. *The Political Impact of the Internet: Evidence from the 2004 Japanese Upper House Election*. American Journal of Political Science, 2007.

## Structure

- `week1_report.Rmd` – R Markdown file for Week 1 replication.
- `week1_report.html` – Rendered report (knitted from Rmd).
- `data/` – Raw scripts and data files (ignored via `.gitignore`).
- `.gitignore` – Ensures only replication reports are committed.

## Progress

- **Week 1**: Replicated Table 2, Table 3, and Figure 3.  
- **Next steps**: Extend replication to additional tables and robustness checks.

## How to Knit

Open the `.Rmd` file in RStudio and click **Knit** → **HTML**.  
Ensure the `data/` folder is in the correct path and required packages are installed.

```r
install.packages(c("tidyverse", "coda", "xtable", "knitr", "kableExtra"))
