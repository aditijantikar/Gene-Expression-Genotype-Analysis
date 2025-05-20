# Gene-Expression-Genotype-Analysis

📝 Project Overview

This project involves exercises using gene expression and genotype data, to perform an Expression Quantitative Trait Loci (eQTL) analysis. The primary goal is to identify associations between genetic variants (SNPs) and gene expression levels.

The R Markdown notebook (`BGGN239_mcvicker_hw2.Rmd`) guides through reading sample information, genotype data (specifically for chromosome 22), and gene expression data (in TPM). A key exercise involves retrieving expression data for a specific gene (e.g., ENSG00000069998), identifying nearby SNPs (within a 50kb window), and testing for associations between SNP genotypes and the gene's expression level.

## 📁 Files in this Repository

* **`BGGN239_mcvicker_hw2.Rmd`**: The R Markdown file containing the R code, exercises, and analysis steps. This is the primary file to include directly in this GitHub repository.
* **Large Data Files (`samples.txt`, `gene_expr_tpm.txt`, `chr22_genotypes.txt`):** Due to their size, these core data files are hosted in a shared Google Drive folder.
    * **Google Drive Link:** [Access Data Files Here](https://drive.google.com/drive/folders/1KWNZm0iYJAOdW3LzF-O3lRQ2GM5gBR-Z?usp=drive_link)
    * Please find `samples.txt`, `gene_expr_tpm.txt`, and `chr22_genotypes.txt` within this folder.

## 🛠️ Tools & Technologies

* **R:** For statistical analysis and scripting.
* **R Markdown:** For creating reproducible notebooks.
* **Key R functions/packages used:** `read.table()`, data subsetting and manipulation (e.g., `which()`, matrix operations), potentially functions for association testing (e.g., `lm()` for linear regression).

## 🚀 How to Run/Use

1.  **Prerequisites:**
    * An R environment with R Markdown support (e.g., RStudio).
2.  **Download Data Files:**
    * Go to the Google Drive Folder Link in the "Files in this Repository" section.
    * Download `samples.txt`, `gene_expr_tpm.txt`, and `chr22_genotypes.txt`.
    * Place these downloaded files into the same directory as the `BGGN239_mcvicker_hw2.Rmd` script (which is in this GitHub repository).
3.  **To reproduce the analysis:**
    * Open `BGGN239_mcvicker_hw2.Rmd` in RStudio.
    * Ensure the file paths within the script correctly point to the data files in the current directory.
    * Run the R code chunks sequentially.
## ✨ Key Concepts Explored

* Reading and integrating multiple bioinformatics data types: sample lists, gene expression matrices, and genotype data.
* Subset and query data based on genomic location (e.g., finding SNPs near a gene).
* Performing association tests between genotypes and quantitative traits (gene expression levels), a fundamental concept in eQTL analysis.
* Data manipulation in R for bioinformatics.

---
