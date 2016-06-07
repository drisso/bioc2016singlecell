# BioC 2016 workshop
## Analysis of single-cell RNA-seq data with R and Bioconductor
__Davide Risso (@drisso), Michael Cole (@mbcole), and Kelly Street (@kstreet13)__

This repository contains the code and data needed for the workshop.

The workshop is divided in three parts:

1. Quality control (QC) and normalization with [scone](https://github.com/YosefLab/scone).
  1. Exploratory Data Analysis (EDA): sample quality and QC measures.
  2. Sample and gene filtering.
  3. Normalization: how sample quality and batch effects affect the data and how to account for it.
  4. Comparison of normalizations and selection of top method.
2. Cluster analysis with [clusterExperiment](https://github.com/epurdom/clusterExperiment).
  1. Compare different clustering approaches (varying number of PCs, clustering algorithm, ...).
  2. Combine multiple clustering into a consensus and visualization of "final" clusters.
  3. Selection of cluster-specific marker genes.
3. Lineage inference and trajectory analysis with [slingshot](https://github.com/kstreet13/slingshot).
  1. Lineage reconstruction.
  2. Trajectory analysis and visualization.
  3. Selection of genes that correlate with pseudotime.

