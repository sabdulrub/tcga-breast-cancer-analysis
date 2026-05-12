# tcga-breast-cancer-analysis
Gene expression analysis of TP53, BRCA1, and ERBB2 in breast cancer vs normal tissue using TCGA data

# TCGA Breast Cancer Gene Expression Analysis
**By Sabah Abdulrub**

## Project Overview
This project compares the expression levels of three cancer-related genes, TP53, BRCA1, and ERBB2, between breast cancer tumor samples and normal tissue samples using RNA sequencing data from The Cancer Genome Atlas (TCGA) Breast Cancer cohort.

## Biological Question
How do TP53, BRCA1, and ERBB2 differ in their expression levels between breast cancer tumor samples and normal tissue samples?

## Dataset
Data was obtained from the UCSC Xena Browser under the GDC TCGA Breast Cancer (BRCA) cohort.
- Gene Expression RNAseq (STAR-TPM): 60,660 genes across 1,226 samples in log2(TPM+1) format
- Clinical/Phenotype Data: 1,255 samples with tissue type labels

## Tools and Libraries
- Python (Google Colab)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Key Findings
- BRCA1 and TP53 were both significantly upregulated in tumor tissue (p < 0.05)
- ERBB2 showed no statistically significant difference across the full dataset, likely because its overexpression is specific to the HER2-positive subtype

## Repository Contents
- `notebook.ipynb` - Full analysis notebook (runs in Google Colab)
- `figures/` - All figures generated from the analysis
