# Single cell transposable Elements
Single cell analysis of transposable Elements in Human Testis

## Analysis software for obtaining single cell TE count matrix
- scTE: An algorithm that quantifies TE expression in single-cell sequence data [scTE GitHub](https://github.com/JiekaiLab/scTE)
- Inputs: (1) Aligned sequence reads (BAM/SAM format). (2) The genomic location of TEs (BED format). (3) The genomic location of genes (GTF format)
- Human Genome annotations:
  
$ ftp://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_30/gencode.v30.annotation.gtf.gz

$ http://hgdownload.soe.ucsc.edu/goldenPath/hg38/database/rmsk.txt.gz


## Raw datasets for single cell testis 
- GSE112013 (Guo et al, 2018): [Available here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE120508)
- Additional data: [Available here](http://firebrowse.org/?cohort=BRCA&download_dialog=true%27)
- cBioportal BIC microbiome scores: [Access the scores](https://www.cbioportal.org/comparison/generic_assay_microbiome_signature?comparisonId=61b7a0b4f8f71021ce57cfca&unselectedGroups=%5B%5D)

## Relevant Publications
1. He, J., Babarinde, I.A., Sun, L. et al. Identifying transposable element expression dynamics and heterogeneity during development at the single-cell level with a processing pipeline scTE. Nat Commun 12, 1456 (2021). [Read here](https://doi.org/10.1038/s41467-021-21808-x)

2. Guo J, Grow EJ, Mlcochova H, Maher GJ et al. The adult human testis transcriptional cell atlas. Cell Res 2018 Dec;28(12):1141-1157. PMID: 30315278 [Read here](https://doi.org/10.1038/s41523-023-00505-6)
