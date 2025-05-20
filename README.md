# Gene-Expression-Genotype-Analysis

📝 Project Overview

This project involves exercises using gene expression and genotype data, to perform an Expression Quantitative Trait Loci (eQTL) analysis. The primary goal is to identify associations between genetic variants (SNPs) and gene expression levels.

The R Markdown notebook (`BGGN239_mcvicker_hw2.Rmd`) guides through reading sample information, genotype data (specifically for chromosome 22), and gene expression data (in TPM). A key exercise involves retrieving expression data for a specific gene (e.g., ENSG00000069998), identifying nearby SNPs (within a 50kb window), and testing for associations between SNP genotypes and the gene's expression level.

## 📁 Files in this Repository

* **`BGGN239_mcvicker_hw2.Rmd`**: The R Markdown file containing the R code, exercises, and analysis steps.
* **`samples.txt`**: A plain text file listing the sample IDs used in the analysis.
* **`gene_expr_tpm.txt`**: A plain text file containing gene expression data, quantified in Transcripts Per Million (TPM), for the samples.
* **`chr22_genotypes.txt`**: A plain text file containing genotype information for variants (likely SNPs) on chromosome 22 for the samples.

## 🛠️ Tools & Technologies

* **R:** For statistical analysis and scripting.
* **R Markdown:** For creating reproducible notebooks.
* **Key R functions/packages used:** `read.table()`, data subsetting and manipulation (e.g., `which()`, matrix operations), potentially functions for association testing (e.g., `lm()` for linear regression).

## 🚀 How to Run/Use

1.  **Prerequisites:**
    * An R environment with R Markdown support (e.g., RStudio).
2.  **To reproduce the analysis:**
    * Open `BGGN239_mcvicker_hw2.Rmd` in RStudio.
    * Ensure the data files (`samples.txt`, `gene_expr_tpm.txt`, `chr22_genotypes.txt`) are in the same directory as the Rmd file, or update the file paths within the script if necessary.
    * Run the R code chunks sequentially to perform the data loading and analysis exercises.

## ✨ Key Concepts Explored

* Reading and integrating multiple bioinformatics data types: sample lists, gene expression matrices, and genotype data.
* Subsetting and querying data based on genomic location (e.g., finding SNPs near a gene).
* Performing association tests between genotypes and quantitative traits (gene expression levels), a fundamental concept in eQTL analysis.
* Data manipulation in R for bioinformatics.

---
