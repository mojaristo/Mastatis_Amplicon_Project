# Project Overview 
This project analyzes 16S rRNA gene amplicon sequencing data from umen microbiomes of dairy cows with different udder health conditions. The goal is to investigate how mastitis severity influences rumen microbial diversity.

This repository contains scripts, metadata, and documentation for computational microbiome analysis conducted in BIOMI4300.


# Dataset

This project uses publicly available 16S rRNA sequencing data from:
Wang *et al* (2021)
*Rumen microbiome structure and metabolites activity in dairy cows with clinical and subclinical mastitis*
Journal of Animal Science and Biotechnology, 12:36:
https://doi.org/10.1186/s40104-020-00543-1

NCBI BioProject:
https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA669201

The dataset consists of rumen fluid-derived 16S rRNA gene amplicon sequencing data targeting the V3–V4 region using 338F/806R primers. 
Sequencing Platform: Illumina MiSeq (2 x 300bp)

# Scientific Question
Does rumen microbial alpha diversity differ across cows with varying mastitis severity?

#Response Variable
Alpha diversity (Shannon index) derived from 16S rRNA gene sequencing data.

#Predictor Variable
Udder health status (categorical):

- Healthy 
- Clinical Mastitis
- Subclinical Mastitis

# Hypothesis

- ##Null Hypothesis
There is no difference in rumen microbial alpha diversity between healthy cows and cows with mastitis.
- ##Alternative Hypothesis 
Cows with mastitis (SM and CM), particularly clinical mastitis, exhibit reduced rumen microbial alpha diversity compared to healthy cows.


