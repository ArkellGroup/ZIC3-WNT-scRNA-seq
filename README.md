# ZIC3-WNT-scRNA-seq

## Overview
This repository contains code for reproducibility of the single-cell RNA sequencing analysis results in our paper Barratt et al 2025:  
"[Title of Paper]" (DOI: [if available])

Please cite this paper if you use this data or code. 

## Requirements
- R version 4.2.2
- The following R packages were used in this analysis:

  - DESeq2 v1.42.1  
  - SummarizedExperiment v1.32.0  
  - Biobase v2.62.0  
  - MatrixGenerics v1.14.0  
  - matrixStats v1.5.0  
  - GenomicRanges v1.54.1  
  - GenomeInfoDb v1.38.8  
  - IRanges v2.36.0  
  - S4Vectors v0.40.2  
  - BiocGenerics v0.48.1  
  - BiocManager v1.30.25  
  - dittoSeq v1.14.3  
  - plyr v1.8.9  
  - stringr v1.5.1  
  - reshape2 v1.4.4  
  - htmlwidgets v1.6.4  
  - plotly v4.10.4  
  - ggplot2 v3.5.1  
  - dplyr v1.1.4  
  - readr v2.1.5  
  - tidyr v1.3.1  
  - Seurat v4.3.0-5.2.1  
  - SeuratObject v4.1.3-5.0.2  
  - sp v2.2-0
  - clusterProfiler v4.10.1
  - enrichplot v1.22.0
  - DOSE v3.28.2
  - AnnotationDbi v1.64.1
  - Org.Mm.eg.db v3.18.0
  - ComplexUpset v1.3.3

  
## Data Availability
Raw counts matrices are available on GEO with accession code XXXX

## Paper Figures and Extended Data Generated via This Code
Figures:

- Figure 4A: UMAPs for all 8 samples merged together and individual UMAPs per genotype (WT and Ka/Y)
- Sup. Figure 5B: UMAPs for each individual sample (all 8)
- Figure 4B: 3D UMAPs
- Figure 4C and Supp Figure 5C: Cell Type Proportions WT vs Mut
- Supp Figure 5D: heatmap of WT cluster identification
- Figure 4D: Apoptosis and Proliferation DEGs
- Figure 5A: Lineage Marker Expression
- Supp Figure 6B: Cell morphology, adhesion and polarity markers
- Figure 5F: New biological processes regulated by Zic3

Extended data:

- 3D UMAPs
- DEG list (DEseq2)

## Code notes

Throughout these markdowns, 'WT' refers to all 4 *Zic3^+/+* embryos together and Mut refers to all four *Zic3^Ka/Y* embryos together.

Merged data refers to all 8 embryos (WT and Mut) together. 

When individual embryos are analysed they will be referred to by their sample name: 
- WT (*Zic3^+/+*) embryos are Sample 9, 10, 11 and 12. 
- Mut (*Zic3^Ka/Y*) embryos are Sample 13, 14, 15 and 16. 

## License
Apache 2.0
