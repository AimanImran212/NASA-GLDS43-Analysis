# NASA GLDS-43 *Escherichia coli* Gene Expression Analysis

## Project Overview
This repository contains an independent bioinformatics and transcriptomics analysis of the public NASA GeneLab dataset **GLDS-43 / OSD-43**. The objective is to investigate differentially expressed genes (DEGs) in *Escherichia coli* under microgravity conditions compared to ground controls, with a special focus on biological processes such as stress response, DNA repair mechanisms, and metabolic adaptation.

## Repository Structure
* `GLDS-43_array_normalized_expression_probesets.txt` — Microarray normalized gene expression data.
* `s_OSD-43.csv` — Sample metadata detailing spaceflight vs. ground control experimental conditions.
* `i_investigation.txt` — Investigation metadata detailing experimental design and platform parameters.

## Key Research Questions
1. Which specific *E. coli* genes show significant upregulation or downregulation in spaceflight?
2. How do critical pathway genes (e.g., *recA*, *dnaK*) respond to space radiation and microgravity stress?
3. What are the broader metabolic adjustments required for bacterial survival in Low Earth Orbit (LEO)?

## Methodology & Tools
* **Data Source:** NASA Open Science Data Repository (OSDR / GeneLab)
* **Analysis Environment:** Python 3 (pandas, matplotlib,  Jupyter Notebooks)
* **Bioinformatics Workflow:** Data parsing, metadata matching, log fold-change calculation, and volcano plot visualization.

## Author
**Aiman Imran**  
BS Biotechnology, PMAS-Arid Agriculture University Rawalpindi
