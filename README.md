﻿# BCL11A-paper

## [SLAM-seq analysis](SLAM-seq%20analysis/)
#### 4sU Conversion Analysis
To assess the dynamics of 4sU-labeled transcripts, we utilized the **GRAND-SLAM (version: 2.0.7b)** to analyze the aligned BAM files and quantify 4sU conversion rates across the transcriptome. The parameters were set to trim 10 nucleotides from both the 5' and 3' ends (`-trim5p 10 -trim5p 10`) of the reads to minimize sequencing biases.
#### Differential Expression Analysis
Differential expression analysis was conducted using the **DESeq2 package (version: 1.46.0)** in R, combined with the **grandR package (version: 0.2.6)** for handling GRAND-SLAM output. Differential expression analysis was analyzed for both total transcripts (total) and newly synthesized transcripts (new).

## [Sequence Charge Decoration Matrix (SCDM) analysis](SCDM%20analysis/)

To quantify the electrostatic interactions within the protein sequences and capture their conformational characteristics, we calculated the Sequence Charge Decoration Matrix (SCDM). The code for SCDM calculation was slightly from [the projcect](https://github.com/MaxCalLab/IDPTheory/tree/main) provided by [Valverde et al. (2023)](https://www.nature.com/articles/s41467-023-42049-0)
