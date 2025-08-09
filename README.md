# ZIC3-WNT-scRNA-seq

## Overview
This repository contains code for reproducibility of the single-cell RNA sequencing analysis results in our paper Barratt et al 2025:  
"Disruption of lineage allocation and fate via loss of canonical WNT co-repression underlies ZIC3-associated congenital heart defects" (DOI: TBA)

Please cite this paper if you use this data or code. 

## Requirements
- R version 4.2.2-4.3.2
- R studio (v2022.02.0 – v2024.04.2+764)
- Cell Ranger (v7.1.0)
- The following R packages were used in this analysis:

o	Matrix, v1.5-1
o	SeuratObject, (v4.1.3-5.0.2)
o	Seurat (v4.3.0-5.2.1)
o	DESeq2 v1.42.1
o	SummarizedExperiment v1.32.0
o	Biobase v2.62.0
o	MatrixGenerics v1.14.0
o	matrixStats v1.5.0
o	GenomicRanges v1.54.1
o	GenomeInfoDb v1.38.8
o	IRanges v2.36.0
o	S4Vectors v0.40.2
o	BiocGenerics v0.48.1
o	BiocManager v1.30.25
o	dittoSeq v1.14.3
o	plyr v1.8.9
o	stringr v1.5.1
o	reshape2 v1.4.4
o	htmlwidgets v1.6.4
o	plotly v4.10.4
o	ggplot2 v3.5.1
o	dplyr v1.1.4
o	readr v2.1.5
o	tidyr v1.3.1
o	sp v2.2-0
o	clusterProfiler v4.10.1
o	enrichplot v1.22.0
o	DOSE v3.28.2
o	AnnotationDbi v1.64.1
o	Org.Mm.eg.db v3.18.0
o	ComplexUpset v1.3.3
o	openxlsx_4.2.8


## Data Availability
Raw counts matrices and the processed file (.rds) are available on GEO with accession code GSE301621 (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE301621).

## Paper Figures and Extended Data Generated via This Code
Figures:

- Figure 4A: UMAPs for all 8 samples merged together and individual UMAPs per genotype (WT and Ka/Y)
- Sup. Figure 5B: UMAPs for each individual sample (all 8)
- Figure 4B: 3D UMAPs
- Figure 4C and Supp Figure 5C: Cell Type Proportions WT vs Mut
- Supp Figure 5D: heatmap of WT cluster identification
- Figure 4D: Apoptosis and Proliferation DEGs
- Figure 5A: Lineage Marker Expression
- Figure 5F: New biological processes regulated by Zic3
- Supp Figure 6B: Cell morphology, adhesion and polarity markers
- Supp Figure 6C: Upset plot depiciting simplified GO terms associated with cluster DEGs

Extended data:

- 3D UMAPs
- DEG list (DEseq2)
- GO terms associated with DEG list

## Code notes

Throughout these markdowns, 'WT' refers to all 4 *Zic3^+/+* embryos together and Mut refers to all four *Zic3^Ka/Y* embryos together.

Merged data refers to all 8 embryos (WT and Mut) together. 

When individual embryos are analysed they will be referred to by their sample name: 
- WT (*Zic3^+/+*) embryos are Sample 9, 10, 11 and 12. 
- Mut (*Zic3^Ka/Y*) embryos are Sample 13, 14, 15 and 16. 

## License
Apache 2.0
