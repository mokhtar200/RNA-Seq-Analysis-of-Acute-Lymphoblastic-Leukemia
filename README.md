#DEMO Project: RNA-Seq Analysis of Acute Lymphoblastic Leukemia (ALL) Sample TARGET-10-PARPNM-09A-01R

Project Overview
This project conducts a comprehensive RNA-Seq analysis of the acute lymphoblastic leukemia (ALL) sample TARGET-10-PARPNM-09A-01R. The goal is to investigate the gene expression profile of this leukemia sample, identifying differentially expressed genes (DEGs), gene fusions, and enriched biological pathways.

## Objectives
- **Preprocess** the raw RNA-Seq data (FASTQ files) using FastQC and trimming.
- **Align** the reads to the human genome using HISAT2.
- **Quantify** the expression levels of genes using FeatureCounts.
- **Identify DEGs** between leukemia and control samples using DESeq2.
- **Detect gene fusions** using STAR-Fusion.
- **Conduct GO and Pathway enrichment** analysis for DEGs.

## Prerequisites
- FastQC (for quality control)
- HISAT2 (for read alignment)
- FeatureCounts (for gene quantification)
- DESeq2 (for differential expression analysis)
- STAR-Fusion (for gene fusion detection)
- R (with ggplot2 and DESeq2 packages installed)
