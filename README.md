# SLE777 Assignment 4 – Part 1 & Part 2

This repository contains my R Markdown analysis and reports for **SLE777 Assignment 4**, including **Part 1** (data wrangling, visualisation, and basic statistics) and **Part 2** (biological sequence diversity and comparative genomics).  
It includes all code, comments, and written explanations required for the assignment.

Install required packages if not already installed:
   "seqinr", "ggplot2", "knitr"
---

## 📊 Part 1 – Data Import, Wrangling, Visualisation, and Statistical Analysis

**Purpose:**  
To develop an R-based workflow to solve bioinformatics problems, including reading and manipulating biological data, generating visualisations, and performing statistical tests.

### Files
- `assessment 4 (Part 1).Rmd` – main R Markdown script with all code, comments, and written answers  
- `assessment4 (Part 1).pdf` – knitted report generated from the Part 1 R Markdown  
- `gene_expression.tsv` – RNA-seq count data (input file)  
- `growth_data.csv` – tree growth data (input file)

### What this code does
- Imports and explores biological datasets  
- Calculates gene expression statistics and visualises distributions  
- Generates histograms and boxplots  
- Calculates mean and standard deviation of tree circumference  
- Performs a t-test to compare tree growth between two sites  
- Summarises findings with tables, plots, and written interpretations

### How to run
1. Download the `.Rmd` file and open it in **RStudio**.  
2. Place the input data files (`gene_expression.tsv`, `growth_data.csv`) in the same directory.  
3. Knit the `.Rmd` to produce the `.pdf` report.  

---

## 🧬 Part 2 – Biological Sequence Diversity Analysis

**Purpose:**  
To download, analyse, and compare coding DNA sequences between *Escherichia coli* and *Streptacidiphilus jiangxiensis*, exploring sequence composition, codon usage, and k-mer frequency differences.

### Files
- `assessment 4 (Part 2).Rmd` – main R Markdown script with all code, comments, and written answers  
- `assessment4 (Part 2).pdf` – knitted report generated from the Part 2 R Markdown  
- `ecoli_cds.fna.gz` – coding DNA sequences for *E. coli* (input file)  
- `strepto_cds.fna.gz` – coding DNA sequences for *Streptacidiphilus jiangxiensis* (input file)

### What this code does
- Downloads and reads full coding DNA sequences for both organisms  
- Counts total number of CDS and total coding DNA length  
- Calculates and visualises CDS length distribution (mean and median)  
- Computes nucleotide and amino acid frequencies with bar plots  
- Generates codon usage tables and analyses codon usage bias  
- Identifies most over- and under-represented 3–5-mer sequences and compares them between species

### How to run
1. Download the `.Rmd` file and open it in **RStudio**.  
2. Ensure the FASTA files (`ecoli_cds.fna.gz` and `strepto_cds.fna.gz`) are in the same directory.  
3. Knit the `.Rmd` to produce the `.pdf` report.  

---

## Notes
- All code is commented clearly to explain the purpose of each step.  
- Plots, tables, and statistical results are automatically generated during knitting.  
- Written answers and biological interpretations are included in the knitted reports.

