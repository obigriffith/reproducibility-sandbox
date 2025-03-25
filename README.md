# Acute Myeloid Leukemia Heatmap Analysis

A bioinformatics pipeline for analyzing RNA sequencing data from Shih et al.'s 2017 study on Acute Myeloid Leukemia (AML) using refined bio data.

## Overview

This analysis examines gene expression patterns across 19 AML model mouse samples, focusing on treatment responses in IDH2 and TET2 mutant AML cases. The pipeline performs differential gene expression analysis and visualizes results through an annotated heatmap.

## Key Features

* Analysis of 19 AML model mouse samples
* Treatment comparison between vehicle & therapeutic interventions
* Gene selection based on variance analysis
* Visualization through clustered heatmaps
* Comprehensive statistical annotations

## Dependencies

Required R packages:
```r
pheatmap
magrittr
readr
dplyr
tibble
sessionInfo
```

## Data Requirements

* RNA sequencing data from SRP070849 experiment
* Pre-processed and quantile normalized data from refine.bio
* Metadata file containing sample information

## Pipeline Structure

The analysis consists of several key steps:
