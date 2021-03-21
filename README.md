# ANGSD_project
This is used for the final project of CMPB 5004 in Weill Cornell.

This project mainly focus on the gene expression analysis of CRPC.

Androgen receptor (AR) is a survival factor for prostate cancer cells that plays an essential role in cancer progression. However, after a period of androgen deprivation treatment (ADT), cancer cells will develop resistance to castration. Previous studies have shown that the acquisition of such resistance is caused by the tumor microenvironment. In this study, we hypothesize that castration-resistant cancer cells (CRPCs) have different gene expression profiles from normal prostate cancer cells. This drug resistance is not entirely caused by the reactivation of AR-related pathways. There might be other pathways that allow cancer cells to survive and CRPCs have different activated functional clusters from prostate cancer cells that have not developed drug resistance.

## Samples

Here, we have 4 samples, each sample has 3 replicates. 
- **Sample 1: DMSO (treated with DMSO (vehicle))**
- **Sample 2: Enz (treated with Enzalutamide, a androgen receptor (AR) target inhibitor)**
- **Sample 3: NRG1 (treated with recombinant NRG1 peptide, a factor that induce CRPCs gain resistance to Enz)**
- **Sample 4: Enz+NRG1 (treated with both Enz and NRG1 to show the resistance to Enz)**

Here you can find all my fastq files and bam files in my scratch folder. (Please note that all the fastq files are pair-ended)

**Fastq PATH: /athena/angsd/scratch/yuc4009/NRG1**

**Bams PATH: /athena/angsd/scratch/yuc4009/bams && /athena/angsd/scratch/yuc4009/bams_selected**

**Bamqc PATH: /athena/angsd/scratch/yuc4009/bamqc

In this repo, we show all of the bash files that we used to run STAR.

## FeatureCounts

We use all 4\*3=12 bam files (collected in the bams_selected) to run featurecounts. The result is shown in the /athena/angsd/scratch/yuc4009/featureCounts.

In this repo, we show the featureCounts result (.txt) and exploratory analysis result (.Rmd)
