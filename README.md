# HER2+ Breast Cancer Gene Expression Analysis

## Overview
This contains the analysis of gene expression differences between HER2 amplified and non-amplified breast cancer samples from TCGA data.

## Data
Data Source: TCGA Breast Cancer (BRCA) dataset from cBioPortal
- RNA-seq expression data
- Clinical Information
- Copy number abberation data

## Scripts
Gene Expression Analysis Quarto Document
- data processing
- differential expression analysis
- pathway analysis
- survival analysis

## Usage
1. Download data from cBioPortal
2. Run Script

## Dependencies
- R >= 4.0
- Required Packages
  - DESeq2
  - ggplot2
  - survival
  - glmnet
  - tidyr
  - dplyr
  - tibble
  - clusterProfiler
  - org.Hs.eg.db
  - enrichplot
  - pheatmap
  - survminer