# Project Overview 
This project analyzes 16S rRNA gene amplicon sequencing data from umen microbiomes of 
dairy cows with different udder health conditions. The goal is to investigate how 
mastitis severity influences rumen microbial diversity.

This repository contains scripts, metadata, and documentation for computational 
microbiome analysis conducted in BIOMI4300.


# Dataset

This project uses publicly available 16S rRNA sequencing data from: Wang *et al* 
(2021) *Rumen microbiome structure and metabolites activity in dairy cows with 
clinical and subclinical mastitis* Journal of Animal Science and Biotechnology, 12:36: 
https://doi.org/10.1186/s40104-020-00543-1

NCBI BioProject:
https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA669201

The dataset consists of rumen fluid-derived 16S rRNA gene amplicon sequencing data 
targeting the V3–V4 region using 338F/806R primers. Sequencing Platform: Illumina 
MiSeq (2 x 300bp)

# Scientific Question
How does rumen microbial alpha diversity vary across samples in this dataset, and to which taxa are abundant across communities?

# Response Variable
- Observed Richness
- Alpha diversity (Shannon diversityn index) 
- Simpson diversity index

# Predictor Variable
- Group subdivisions (i.e., J, L and Y)

# Hypothesis

## Null Hypothesis
- There is no meaningful variation in rumen microbial alpha diversity across samples 
beyond random variationh.
 
## Alternative Hypothesis
-  Rumen microbial alpha diversity varies across samples, and 
there is a heterogeneous composition of taxa.

