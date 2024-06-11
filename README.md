# How to choose the optimal RNA-Seq library characteristics for alternative splicing analysis (with MAJIQ)
****
This Github repository provides the code the for the publication Ladwig et al. 2023.

## Authors
- Annika Ladwig
- Melina Klostermann
- Kathi Zarnack

## 1 Preprocessing and alternative splicing analysis with MAJIQ
****
The Rmarkdown contains the code for the preprocessing of the raw reads and for the subsequent alternative splice analysis with MAJIQ.

The rendered HTML file is available at https://annikala.github.io/. 

## 2 Impact of library characteristics on alternative splice analysis
****
The R scripts contain the code used to investigate the influence of read length (2.1a - *U2AF2* KD, 2.1b - *UPF1* KD), read depth (2.2) and replicate number (2.3) on: 
- read alignment
- LSV detection
- LSV quantification
- alternative splicing event types distribution

## 3 Impact of library characteristics on the detection of local splice variations (LSVs) in lowly expressed genes

The R script '3_TPM_analysis.Rmd' contains the code for analysing the impact of read length and read depth on the detection of local splice variations (LSVs) in lowly expressed genes. 

