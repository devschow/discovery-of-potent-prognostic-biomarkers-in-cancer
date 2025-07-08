# Discovery of Potent Prognostic Biomarkers in Cancer

## Overview
This project explores the use of a machine learning-based pipeline for the discovery of prognostic biomarkers in **breast cancer** using **bulk mRNA-sequencing (mRNA-Seq)** data. Rather than aiming for a single fixed solution, the objective is to demonstrate a range of computational techniques including differential expression analysis, dimensionality reduction, unsupervised clustering, and visualisation that can support biomarker discovery.

The pipeline is developed in a tutorial-style format to guide researchers through each analytical stage, offering flexibility in method selection and reproducible results. The final outcome is intended to serve as a resource for biologists and data scientists seeking practical tools to explore transcriptomic datasets in cancer research.

## Objectives

- **Differential Expression Analysis**: Identify significantly up- or down-regulated genes between clinical subgroups using PyDESeq2.
- **Dimensionality Reduction**: Use PCA, t-SNE, or UMAP to reduce data complexity and uncover dominant patterns.
- **Unsupervised Clustering**: Categorise tumour samples based on gene expression profiles using algorithms like K-means and hierarchical clustering.
- **Biomarker Discovery**: Output ranked gene lists from multiple approaches (e.g. DEGs, cluster representatives) and visualise their overlaps via Venn diagrams.
- **Visual Outputs**: Provide visualisation at each stage to aid biological interpretation, including volcano plots, clustermaps, and PCA scatterplots.

## Dataset

The study utilises a large-scale breast cancer dataset (GSE202203) from the **SCAN-B project**, obtained via the **NCBI Gene Expression Omnibus (GEO)**. The dataset contains:

- **Molecular Data**: Raw mRNA-seq gene count matrix from 3,207 primary breast tumour samples.
- **Clinical Metadata**: Includes patient age, tumour size, hormone receptor status (ER/PR/HER2), PAM50 subtype, treatment history, and survival data (OS, RFS).

All data used is fully anonymised, open-access, and ethically compliant.

## Methodology
*(To be filled)*  
The methodology section will describe each computational stage, including preprocessing, normalisation, feature selection, model training, and visualisation.

## Results
*(To be filled)*  
This section will include analytical findings, key genes identified as biomarkers, clustering outputs, and performance evaluations of various ML methods.

## Acknowledgements

Special thanks to the mentors and research inspirations who guided the conceptualisation of this project.

**Institution**: University of Liverpool  
**Supervisor**: Dr. Anosova Olga

## Ethical Compliance
This project uses anonymised human transcriptomic data retrieved from open-access sources (GEO). No personally identifiable information is used, and all project activities comply with ethical guidelines under Category D2.
