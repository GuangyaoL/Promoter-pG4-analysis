# Promoter-pG4-analysis
Li Guangyue

Code and processed data for paper in submission assessing evidence for negative selection in gnomAD and 1000 Genomes project over promoter G-quadruplex forming sequences and enrichment for functional associations using data from ENCODE and GTEx.

The analysis is broadly separated into two major parts:

1. Putative G-quadruplex (pG4) forming sequences and the stable scores within promoter were obtained from Quadron software.
2. Population genetics analysis of canonical, putative G-quadruplex (pG4) forming sequences within promoters (we split this result codes part into 4 parts:2.1-2.4).
3. The effects of G4s on promoter activity by comparing the BG4 ChIP-seq data and RNA-seq data in K562 and HepG2 cells.
4. We used the BG4 ChIP-seq and TT-seq datasets from this study (GSE178668) to interrogate the relationship between G4 formation and gene expression.
5. Testing for enrichment of functional associations, including cis-eQTLs mapped by GTEx, and histone marker, chromatin remodeler and transcript factor binding sites mapped by ENCODE.

## Folders

Script: contains all of the analysis scripts used to generate main figures of the paper
Data: contains processed, publicly available data organized by source

#### All of the code(jupyter notebook) used to generate all of the figures are in Scripts.
