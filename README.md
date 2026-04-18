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
How does rumen microbial alpha diversity vary across samples in this dataset, and to what extent is this variation influenced by sequencing depth?

#Response Variable
- Observed Richness
- Alpha diversity (Shannon diversityn index) 
- Simpson diversity index

#Predictor Variable
- Total reads per sample i.e., Sequencing depth: (Continuous Variable)

# Hypothesis

## Null Hypothesis
There is no meaningful variation in rumen microbial alpha diversity across samples 
beyond random variation, and alpha diversity is not associated with sequencing depth. 
## Alternative Hypothesis Rumen microbial alpha diversity varies across samplesy, and 
this variation is not solely explained by sequencing depth.

