# FDA Epigenomics Quality Control Study

## Introduction

Detection of DNA cytosine modifications such as 5-methylcytosine (5mC) and 5-hydroxy-methylcytosine (5hmC) are essential for understanding the epigenetic changes that guide development, cellular lineage specification, and disease. However, the variety of approaches available to interrogate these modifications have created the need for harmonized materials, methods, and rigorous benchmarking. Such benchmarking efforts will be instrumental for improving and advancing genome-wide methylomic sequencing applications in clinical and basic research.  

The FDA's Epigenomics Quality Control (EpiQC) Study is a multi-platform, multi-site assessment, and a global resource for epigenetics research. The general study design leverages seven human cell lines publicly available from the National Institute of Standards and Technology (NIST) Genome in a Bottle (GIAB) consortium subjected to a variety of genome-wide methylation interrogation approaches in six independent laboratories. Our primary focus was on cytosine modifications found in mammalian genomes (5mC,5hmC). Each sample was processed in two or more technical replicates by three whole-genome bisulfite sequencing (WGBS) protocols (TruSeq DNA methylation, Accel-NGS, SPLAT), oxidative bisulfite sequencing (oxBS), enzymatic Methyl-seq (EM-seq), Illumina EPIC targeted-methylation sequencing, and ATAC-seq. Each library was sequenced to high coverage on an Illumina NovaSeq 6000. The data were subjected to rigorous quality assessment and subsequently compared to Illumina methylation arrays. Our goals are to identify best-practices, data types, laboratory methods, and computational algorithms to inform ongoing and future efforts in epigenomics research. We hope these results simplify applications of 5-cytosine modification information in the context of understanding of cellular identity in development, health, and disease.

## Data Availability

Current Notes (as of February 25, 2020):

* All WGBS (and EM-Seq) replicates are being re-uploaded.
* All microarray data are being uploaded.
* All md5sums are being created and will be listed next to each file.

### ATAC-seq

- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP01-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB01_REP01-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP01-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB01_REP01-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP01_EPIN-R1.fq.gz">  ATACSeq_HG001_LAB01_REP01_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP01_EPIN-R2.fq.gz">  ATACSeq_HG001_LAB01_REP01_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP02-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB01_REP02-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP02-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB01_REP02-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP02_EPIN-R1.fq.gz">  ATACSeq_HG001_LAB01_REP02_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP02_EPIN-R2.fq.gz">  ATACSeq_HG001_LAB01_REP02_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP03-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB01_REP03-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP03-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB01_REP03-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP03_EPIN-R1.fq.gz">  ATACSeq_HG001_LAB01_REP03_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB01_REP03_EPIN-R2.fq.gz">  ATACSeq_HG001_LAB01_REP03_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB02_REP01-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB02_REP01-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01-BUEN-LANE02-R1.fq.gz">  ATACSeq_HG001_LAB02_REP01-BUEN-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01-BUEN-LANE02-R2.fq.gz">  ATACSeq_HG001_LAB02_REP01-BUEN-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB02_REP01-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB02_REP01-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01_BUEN-R1.fq.gz">  ATACSeq_HG001_LAB02_REP01_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01_BUEN-R2.fq.gz">  ATACSeq_HG001_LAB02_REP01_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01_OMNI-R1.fq.gz">  ATACSeq_HG001_LAB02_REP01_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP01_OMNI-R2.fq.gz">  ATACSeq_HG001_LAB02_REP01_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB02_REP02-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB02_REP02-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB02_REP02-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB02_REP02-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02_BUEN-R1.fq.gz">  ATACSeq_HG001_LAB02_REP02_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02_BUEN-R2.fq.gz">  ATACSeq_HG001_LAB02_REP02_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02_OMNI-R1.fq.gz">  ATACSeq_HG001_LAB02_REP02_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP02_OMNI-R2.fq.gz">  ATACSeq_HG001_LAB02_REP02_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB02_REP03-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB02_REP03-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG001_LAB02_REP03-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG001_LAB02_REP03-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03_BUEN-R1.fq.gz">  ATACSeq_HG001_LAB02_REP03_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03_BUEN-R2.fq.gz">  ATACSeq_HG001_LAB02_REP03_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03_OMNI-R1.fq.gz">  ATACSeq_HG001_LAB02_REP03_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG001_LAB02_REP03_OMNI-R2.fq.gz">  ATACSeq_HG001_LAB02_REP03_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE02-R1.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE02-R2.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE03-R1.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE03-R2.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE04-R1.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01-LANE04-R2.fq.gz">  ATACSeq_HG002_LAB01_REP01-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01_EPIN_lane01-R1.fq.gz">  ATACSeq_HG002_LAB01_REP01_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01_EPIN_lane01-R2.fq.gz">  ATACSeq_HG002_LAB01_REP01_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01_EPIN_lane02-R1.fq.gz">  ATACSeq_HG002_LAB01_REP01_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01_EPIN_lane02-R2.fq.gz">  ATACSeq_HG002_LAB01_REP01_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01_EPIN_lane03-R1.fq.gz">  ATACSeq_HG002_LAB01_REP01_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP01_EPIN_lane03-R2.fq.gz">  ATACSeq_HG002_LAB01_REP01_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE02-R1.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE02-R2.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE03-R1.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE03-R2.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE04-R1.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02-LANE04-R2.fq.gz">  ATACSeq_HG002_LAB01_REP02-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02_EPIN_lane01-R1.fq.gz">  ATACSeq_HG002_LAB01_REP02_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02_EPIN_lane01-R2.fq.gz">  ATACSeq_HG002_LAB01_REP02_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02_EPIN_lane02-R1.fq.gz">  ATACSeq_HG002_LAB01_REP02_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02_EPIN_lane02-R2.fq.gz">  ATACSeq_HG002_LAB01_REP02_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02_EPIN_lane03-R1.fq.gz">  ATACSeq_HG002_LAB01_REP02_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP02_EPIN_lane03-R2.fq.gz">  ATACSeq_HG002_LAB01_REP02_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE02-R1.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE02-R2.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE03-R1.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE03-R2.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE04-R1.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03-LANE04-R2.fq.gz">  ATACSeq_HG002_LAB01_REP03-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03_EPIN_lane01-R1.fq.gz">  ATACSeq_HG002_LAB01_REP03_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03_EPIN_lane01-R2.fq.gz">  ATACSeq_HG002_LAB01_REP03_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03_EPIN_lane02-R1.fq.gz">  ATACSeq_HG002_LAB01_REP03_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03_EPIN_lane02-R2.fq.gz">  ATACSeq_HG002_LAB01_REP03_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03_EPIN_lane03-R1.fq.gz">  ATACSeq_HG002_LAB01_REP03_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB01_REP03_EPIN_lane03-R2.fq.gz">  ATACSeq_HG002_LAB01_REP03_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB02_REP01-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB02_REP01-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01-BUEN-LANE02-R1.fq.gz">  ATACSeq_HG002_LAB02_REP01-BUEN-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01-BUEN-LANE02-R2.fq.gz">  ATACSeq_HG002_LAB02_REP01-BUEN-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB02_REP01-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB02_REP01-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01_BUEN-R1.fq.gz">  ATACSeq_HG002_LAB02_REP01_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01_BUEN-R2.fq.gz">  ATACSeq_HG002_LAB02_REP01_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01_OMNI-R1.fq.gz">  ATACSeq_HG002_LAB02_REP01_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP01_OMNI-R2.fq.gz">  ATACSeq_HG002_LAB02_REP01_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB02_REP02-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB02_REP02-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB02_REP02-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB02_REP02-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02_BUEN-R1.fq.gz">  ATACSeq_HG002_LAB02_REP02_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02_BUEN-R2.fq.gz">  ATACSeq_HG002_LAB02_REP02_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02_OMNI-R1.fq.gz">  ATACSeq_HG002_LAB02_REP02_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP02_OMNI-R2.fq.gz">  ATACSeq_HG002_LAB02_REP02_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB02_REP03-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB02_REP03-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG002_LAB02_REP03-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG002_LAB02_REP03-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03_BUEN-R1.fq.gz">  ATACSeq_HG002_LAB02_REP03_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03_BUEN-R2.fq.gz">  ATACSeq_HG002_LAB02_REP03_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03_OMNI-R1.fq.gz">  ATACSeq_HG002_LAB02_REP03_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG002_LAB02_REP03_OMNI-R2.fq.gz">  ATACSeq_HG002_LAB02_REP03_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP01-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB01_REP01-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP01-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB01_REP01-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP01_EPIN-R1.fq.gz">  ATACSeq_HG003_LAB01_REP01_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP01_EPIN-R2.fq.gz">  ATACSeq_HG003_LAB01_REP01_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP02-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB01_REP02-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP02-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB01_REP02-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP02_EPIN-R1.fq.gz">  ATACSeq_HG003_LAB01_REP02_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP02_EPIN-R2.fq.gz">  ATACSeq_HG003_LAB01_REP02_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP03-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB01_REP03-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP03-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB01_REP03-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP03_EPIN-R1.fq.gz">  ATACSeq_HG003_LAB01_REP03_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB01_REP03_EPIN-R2.fq.gz">  ATACSeq_HG003_LAB01_REP03_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB02_REP01-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB02_REP01-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB02_REP01-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB02_REP01-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01_BUEN-R1.fq.gz">  ATACSeq_HG003_LAB02_REP01_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01_BUEN-R2.fq.gz">  ATACSeq_HG003_LAB02_REP01_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01_OMNI-R1.fq.gz">  ATACSeq_HG003_LAB02_REP01_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP01_OMNI-R2.fq.gz">  ATACSeq_HG003_LAB02_REP01_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB02_REP02-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB02_REP02-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB02_REP02-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB02_REP02-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02_BUEN-R1.fq.gz">  ATACSeq_HG003_LAB02_REP02_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02_BUEN-R2.fq.gz">  ATACSeq_HG003_LAB02_REP02_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02_OMNI-R1.fq.gz">  ATACSeq_HG003_LAB02_REP02_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP02_OMNI-R2.fq.gz">  ATACSeq_HG003_LAB02_REP02_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB02_REP03-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB02_REP03-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG003_LAB02_REP03-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG003_LAB02_REP03-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03_BUEN-R1.fq.gz">  ATACSeq_HG003_LAB02_REP03_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03_BUEN-R2.fq.gz">  ATACSeq_HG003_LAB02_REP03_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03_OMNI-R1.fq.gz">  ATACSeq_HG003_LAB02_REP03_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003_LAB02_REP03_OMNI-R2.fq.gz">  ATACSeq_HG003_LAB02_REP03_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003maybe_LAB02_REP01-BUEN-LANE02-R1.fq.gz">  ATACSeq_HG003maybe_LAB02_REP01-BUEN-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG003maybe_LAB02_REP01-BUEN-LANE02-R2.fq.gz">  ATACSeq_HG003maybe_LAB02_REP01-BUEN-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP01-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB01_REP01-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP01-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB01_REP01-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP01_EPIN-R1.fq.gz">  ATACSeq_HG004_LAB01_REP01_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP01_EPIN-R2.fq.gz">  ATACSeq_HG004_LAB01_REP01_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP02-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB01_REP02-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP02-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB01_REP02-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP02_EPIN-R1.fq.gz">  ATACSeq_HG004_LAB01_REP02_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP02_EPIN-R2.fq.gz">  ATACSeq_HG004_LAB01_REP02_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP03-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB01_REP03-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP03-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB01_REP03-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP03_EPIN-R1.fq.gz">  ATACSeq_HG004_LAB01_REP03_EPIN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB01_REP03_EPIN-R2.fq.gz">  ATACSeq_HG004_LAB01_REP03_EPIN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB02_REP01-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB02_REP01-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01-BUEN-LANE02-R1.fq.gz">  ATACSeq_HG004_LAB02_REP01-BUEN-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01-BUEN-LANE02-R2.fq.gz">  ATACSeq_HG004_LAB02_REP01-BUEN-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB02_REP01-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB02_REP01-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01_BUEN-R1.fq.gz">  ATACSeq_HG004_LAB02_REP01_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01_BUEN-R2.fq.gz">  ATACSeq_HG004_LAB02_REP01_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01_OMNI-R1.fq.gz">  ATACSeq_HG004_LAB02_REP01_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP01_OMNI-R2.fq.gz">  ATACSeq_HG004_LAB02_REP01_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB02_REP02-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB02_REP02-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB02_REP02-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB02_REP02-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02_BUEN-R1.fq.gz">  ATACSeq_HG004_LAB02_REP02_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02_BUEN-R2.fq.gz">  ATACSeq_HG004_LAB02_REP02_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02_OMNI-R1.fq.gz">  ATACSeq_HG004_LAB02_REP02_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP02_OMNI-R2.fq.gz">  ATACSeq_HG004_LAB02_REP02_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB02_REP03-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB02_REP03-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG004_LAB02_REP03-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG004_LAB02_REP03-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03_BUEN-R1.fq.gz">  ATACSeq_HG004_LAB02_REP03_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03_BUEN-R2.fq.gz">  ATACSeq_HG004_LAB02_REP03_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03_OMNI-R1.fq.gz">  ATACSeq_HG004_LAB02_REP03_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG004_LAB02_REP03_OMNI-R2.fq.gz">  ATACSeq_HG004_LAB02_REP03_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE02-R1.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE02-R2.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE03-R1.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE03-R2.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE04-R1.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01-LANE04-R2.fq.gz">  ATACSeq_HG005_LAB01_REP01-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01_EPIN_lane01-R1.fq.gz">  ATACSeq_HG005_LAB01_REP01_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01_EPIN_lane01-R2.fq.gz">  ATACSeq_HG005_LAB01_REP01_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01_EPIN_lane02-R1.fq.gz">  ATACSeq_HG005_LAB01_REP01_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01_EPIN_lane02-R2.fq.gz">  ATACSeq_HG005_LAB01_REP01_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01_EPIN_lane03-R1.fq.gz">  ATACSeq_HG005_LAB01_REP01_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP01_EPIN_lane03-R2.fq.gz">  ATACSeq_HG005_LAB01_REP01_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE02-R1.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE02-R2.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE03-R1.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE03-R2.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE04-R1.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02-LANE04-R2.fq.gz">  ATACSeq_HG005_LAB01_REP02-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02_EPIN_lane01-R1.fq.gz">  ATACSeq_HG005_LAB01_REP02_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02_EPIN_lane01-R2.fq.gz">  ATACSeq_HG005_LAB01_REP02_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02_EPIN_lane02-R1.fq.gz">  ATACSeq_HG005_LAB01_REP02_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02_EPIN_lane02-R2.fq.gz">  ATACSeq_HG005_LAB01_REP02_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02_EPIN_lane03-R1.fq.gz">  ATACSeq_HG005_LAB01_REP02_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP02_EPIN_lane03-R2.fq.gz">  ATACSeq_HG005_LAB01_REP02_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE02-R1.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE02-R2.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE03-R1.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE03-R2.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE04-R1.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03-LANE04-R2.fq.gz">  ATACSeq_HG005_LAB01_REP03-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03_EPIN_lane01-R1.fq.gz">  ATACSeq_HG005_LAB01_REP03_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03_EPIN_lane01-R2.fq.gz">  ATACSeq_HG005_LAB01_REP03_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03_EPIN_lane02-R1.fq.gz">  ATACSeq_HG005_LAB01_REP03_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03_EPIN_lane02-R2.fq.gz">  ATACSeq_HG005_LAB01_REP03_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03_EPIN_lane03-R1.fq.gz">  ATACSeq_HG005_LAB01_REP03_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB01_REP03_EPIN_lane03-R2.fq.gz">  ATACSeq_HG005_LAB01_REP03_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB02_REP01-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB02_REP01-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB02_REP01-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB02_REP01-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01_BUEN-R1.fq.gz">  ATACSeq_HG005_LAB02_REP01_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01_BUEN-R2.fq.gz">  ATACSeq_HG005_LAB02_REP01_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01_OMNI-R1.fq.gz">  ATACSeq_HG005_LAB02_REP01_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP01_OMNI-R2.fq.gz">  ATACSeq_HG005_LAB02_REP01_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB02_REP02-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB02_REP02-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB02_REP02-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB02_REP02-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02_BUEN-R1.fq.gz">  ATACSeq_HG005_LAB02_REP02_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02_BUEN-R2.fq.gz">  ATACSeq_HG005_LAB02_REP02_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02_OMNI-R1.fq.gz">  ATACSeq_HG005_LAB02_REP02_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP02_OMNI-R2.fq.gz">  ATACSeq_HG005_LAB02_REP02_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB02_REP03-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB02_REP03-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG005_LAB02_REP03-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG005_LAB02_REP03-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03_BUEN-R1.fq.gz">  ATACSeq_HG005_LAB02_REP03_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03_BUEN-R2.fq.gz">  ATACSeq_HG005_LAB02_REP03_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03_OMNI-R1.fq.gz">  ATACSeq_HG005_LAB02_REP03_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005_LAB02_REP03_OMNI-R2.fq.gz">  ATACSeq_HG005_LAB02_REP03_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005maybe_LAB02_REP01-BUEN-LANE02-R1.fq.gz">  ATACSeq_HG005maybe_LAB02_REP01-BUEN-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG005maybe_LAB02_REP01-BUEN-LANE02-R2.fq.gz">  ATACSeq_HG005maybe_LAB02_REP01-BUEN-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE02-R1.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE02-R2.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE03-R1.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE03-R2.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE04-R1.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01-LANE04-R2.fq.gz">  ATACSeq_HG006_LAB01_REP01-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01_EPIN_lane01-R1.fq.gz">  ATACSeq_HG006_LAB01_REP01_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01_EPIN_lane01-R2.fq.gz">  ATACSeq_HG006_LAB01_REP01_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01_EPIN_lane02-R1.fq.gz">  ATACSeq_HG006_LAB01_REP01_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01_EPIN_lane02-R2.fq.gz">  ATACSeq_HG006_LAB01_REP01_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01_EPIN_lane03-R1.fq.gz">  ATACSeq_HG006_LAB01_REP01_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP01_EPIN_lane03-R2.fq.gz">  ATACSeq_HG006_LAB01_REP01_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE02-R1.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE02-R2.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE03-R1.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE03-R2.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE04-R1.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02-LANE04-R2.fq.gz">  ATACSeq_HG006_LAB01_REP02-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02_EPIN_lane01-R1.fq.gz">  ATACSeq_HG006_LAB01_REP02_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02_EPIN_lane01-R2.fq.gz">  ATACSeq_HG006_LAB01_REP02_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02_EPIN_lane02-R1.fq.gz">  ATACSeq_HG006_LAB01_REP02_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02_EPIN_lane02-R2.fq.gz">  ATACSeq_HG006_LAB01_REP02_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02_EPIN_lane03-R1.fq.gz">  ATACSeq_HG006_LAB01_REP02_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP02_EPIN_lane03-R2.fq.gz">  ATACSeq_HG006_LAB01_REP02_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE02-R1.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE02-R2.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE03-R1.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE03-R2.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE04-R1.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03-LANE04-R2.fq.gz">  ATACSeq_HG006_LAB01_REP03-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03_EPIN_lane01-R1.fq.gz">  ATACSeq_HG006_LAB01_REP03_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03_EPIN_lane01-R2.fq.gz">  ATACSeq_HG006_LAB01_REP03_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03_EPIN_lane02-R1.fq.gz">  ATACSeq_HG006_LAB01_REP03_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03_EPIN_lane02-R2.fq.gz">  ATACSeq_HG006_LAB01_REP03_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03_EPIN_lane03-R1.fq.gz">  ATACSeq_HG006_LAB01_REP03_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB01_REP03_EPIN_lane03-R2.fq.gz">  ATACSeq_HG006_LAB01_REP03_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB02_REP01-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB02_REP01-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01-BUEN-LANE02-R1.fq.gz">  ATACSeq_HG006_LAB02_REP01-BUEN-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01-BUEN-LANE02-R2.fq.gz">  ATACSeq_HG006_LAB02_REP01-BUEN-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB02_REP01-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB02_REP01-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01_BUEN-R1.fq.gz">  ATACSeq_HG006_LAB02_REP01_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01_BUEN-R2.fq.gz">  ATACSeq_HG006_LAB02_REP01_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01_OMNI-R1.fq.gz">  ATACSeq_HG006_LAB02_REP01_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP01_OMNI-R2.fq.gz">  ATACSeq_HG006_LAB02_REP01_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB02_REP02-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB02_REP02-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB02_REP02-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB02_REP02-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02_BUEN-R1.fq.gz">  ATACSeq_HG006_LAB02_REP02_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02_BUEN-R2.fq.gz">  ATACSeq_HG006_LAB02_REP02_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02_OMNI-R1.fq.gz">  ATACSeq_HG006_LAB02_REP02_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP02_OMNI-R2.fq.gz">  ATACSeq_HG006_LAB02_REP02_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB02_REP03-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB02_REP03-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG006_LAB02_REP03-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG006_LAB02_REP03-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03_BUEN-R1.fq.gz">  ATACSeq_HG006_LAB02_REP03_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03_BUEN-R2.fq.gz">  ATACSeq_HG006_LAB02_REP03_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03_OMNI-R1.fq.gz">  ATACSeq_HG006_LAB02_REP03_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG006_LAB02_REP03_OMNI-R2.fq.gz">  ATACSeq_HG006_LAB02_REP03_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE02-R1.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE02-R2.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE03-R1.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE03-R2.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE04-R1.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01-LANE04-R2.fq.gz">  ATACSeq_HG007_LAB01_REP01-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01_EPIN_lane01-R1.fq.gz">  ATACSeq_HG007_LAB01_REP01_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01_EPIN_lane01-R2.fq.gz">  ATACSeq_HG007_LAB01_REP01_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01_EPIN_lane02-R1.fq.gz">  ATACSeq_HG007_LAB01_REP01_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01_EPIN_lane02-R2.fq.gz">  ATACSeq_HG007_LAB01_REP01_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01_EPIN_lane03-R1.fq.gz">  ATACSeq_HG007_LAB01_REP01_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP01_EPIN_lane03-R2.fq.gz">  ATACSeq_HG007_LAB01_REP01_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE02-R1.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE02-R2.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE03-R1.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE03-R2.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE04-R1.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02-LANE04-R2.fq.gz">  ATACSeq_HG007_LAB01_REP02-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02_EPIN_lane01-R1.fq.gz">  ATACSeq_HG007_LAB01_REP02_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02_EPIN_lane01-R2.fq.gz">  ATACSeq_HG007_LAB01_REP02_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02_EPIN_lane02-R1.fq.gz">  ATACSeq_HG007_LAB01_REP02_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02_EPIN_lane02-R2.fq.gz">  ATACSeq_HG007_LAB01_REP02_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02_EPIN_lane03-R1.fq.gz">  ATACSeq_HG007_LAB01_REP02_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP02_EPIN_lane03-R2.fq.gz">  ATACSeq_HG007_LAB01_REP02_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE02-R1.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE02-R2.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE03-R1.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE03-R2.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE04-R1.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE04-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03-LANE04-R2.fq.gz">  ATACSeq_HG007_LAB01_REP03-LANE04-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03_EPIN_lane01-R1.fq.gz">  ATACSeq_HG007_LAB01_REP03_EPIN_lane01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03_EPIN_lane01-R2.fq.gz">  ATACSeq_HG007_LAB01_REP03_EPIN_lane01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03_EPIN_lane02-R1.fq.gz">  ATACSeq_HG007_LAB01_REP03_EPIN_lane02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03_EPIN_lane02-R2.fq.gz">  ATACSeq_HG007_LAB01_REP03_EPIN_lane02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03_EPIN_lane03-R1.fq.gz">  ATACSeq_HG007_LAB01_REP03_EPIN_lane03-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB01_REP03_EPIN_lane03-R2.fq.gz">  ATACSeq_HG007_LAB01_REP03_EPIN_lane03-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB02_REP01-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB02_REP01-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01-BUEN-LANE02-R1.fq.gz">  ATACSeq_HG007_LAB02_REP01-BUEN-LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01-BUEN-LANE02-R2.fq.gz">  ATACSeq_HG007_LAB02_REP01-BUEN-LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB02_REP01-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB02_REP01-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01_BUEN-R1.fq.gz">  ATACSeq_HG007_LAB02_REP01_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01_BUEN-R2.fq.gz">  ATACSeq_HG007_LAB02_REP01_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01_OMNI-R1.fq.gz">  ATACSeq_HG007_LAB02_REP01_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP01_OMNI-R2.fq.gz">  ATACSeq_HG007_LAB02_REP01_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB02_REP02-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB02_REP02-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB02_REP02-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB02_REP02-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02_BUEN-R1.fq.gz">  ATACSeq_HG007_LAB02_REP02_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02_BUEN-R2.fq.gz">  ATACSeq_HG007_LAB02_REP02_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02_OMNI-R1.fq.gz">  ATACSeq_HG007_LAB02_REP02_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP02_OMNI-R2.fq.gz">  ATACSeq_HG007_LAB02_REP02_OMNI-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03-BUEN-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB02_REP03-BUEN-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03-BUEN-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB02_REP03-BUEN-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03-OMNI-LANE01-R1.fq.gz">  ATACSeq_HG007_LAB02_REP03-OMNI-LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03-OMNI-LANE01-R2.fq.gz">  ATACSeq_HG007_LAB02_REP03-OMNI-LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03_BUEN-R1.fq.gz">  ATACSeq_HG007_LAB02_REP03_BUEN-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03_BUEN-R2.fq.gz">  ATACSeq_HG007_LAB02_REP03_BUEN-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03_OMNI-R1.fq.gz">  ATACSeq_HG007_LAB02_REP03_OMNI-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/ATACSeq_HG007_LAB02_REP03_OMNI-R2.fq.gz">  ATACSeq_HG007_LAB02_REP03_OMNI-R2.fq.gz</a>


### WGBS

#### BS-Tag

These data are currently being re-uploaded.

#### Methyl-Seq

These data are currently being re-uploaded.

#### Tru-Seq

These data are currently being re-uploaded.

#### SPLAT

These data are currently being re-uploaded.

#### EM-Seq

These data are currently being re-uploaded.

### EPIC Capture Panel

- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG001_LAB01_REP01_LANE01-R1.fq.gz">  EPIC_HG001_LAB01_REP01_LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG001_LAB01_REP01_LANE01-R2.fq.gz">  EPIC_HG001_LAB01_REP01_LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG001_LAB01_REP01_LANE02-R1.fq.gz">  EPIC_HG001_LAB01_REP01_LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG001_LAB01_REP01_LANE02-R2.fq.gz">  EPIC_HG001_LAB01_REP01_LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG002_LAB01_REP01_LANE01-R1.fq.gz">  EPIC_HG002_LAB01_REP01_LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG002_LAB01_REP01_LANE01-R2.fq.gz">  EPIC_HG002_LAB01_REP01_LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG002_LAB01_REP01_LANE02-R1.fq.gz">  EPIC_HG002_LAB01_REP01_LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG002_LAB01_REP01_LANE02-R2.fq.gz">  EPIC_HG002_LAB01_REP01_LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG003_LAB01_REP01_LANE01-R1.fq.gz">  EPIC_HG003_LAB01_REP01_LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG003_LAB01_REP01_LANE01-R2.fq.gz">  EPIC_HG003_LAB01_REP01_LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG003_LAB01_REP01_LANE02-R1.fq.gz">  EPIC_HG003_LAB01_REP01_LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG003_LAB01_REP01_LANE02-R2.fq.gz">  EPIC_HG003_LAB01_REP01_LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG004_LAB01_REP01_LANE01-R1.fq.gz">  EPIC_HG004_LAB01_REP01_LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG004_LAB01_REP01_LANE01-R2.fq.gz">  EPIC_HG004_LAB01_REP01_LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG004_LAB01_REP01_LANE02-R1.fq.gz">  EPIC_HG004_LAB01_REP01_LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG004_LAB01_REP01_LANE02-R2.fq.gz">  EPIC_HG004_LAB01_REP01_LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG005_LAB01_REP01_LANE01-R1.fq.gz">  EPIC_HG005_LAB01_REP01_LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG005_LAB01_REP01_LANE01-R2.fq.gz">  EPIC_HG005_LAB01_REP01_LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG005_LAB01_REP01_LANE02-R1.fq.gz">  EPIC_HG005_LAB01_REP01_LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG005_LAB01_REP01_LANE02-R2.fq.gz">  EPIC_HG005_LAB01_REP01_LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG006_LAB01_REP01_LANE01-R1.fq.gz">  EPIC_HG006_LAB01_REP01_LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG006_LAB01_REP01_LANE01-R2.fq.gz">  EPIC_HG006_LAB01_REP01_LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG006_LAB01_REP01_LANE02-R1.fq.gz">  EPIC_HG006_LAB01_REP01_LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG006_LAB01_REP01_LANE02-R2.fq.gz">  EPIC_HG006_LAB01_REP01_LANE02-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG007_LAB01_REP01_LANE01-R1.fq.gz">  EPIC_HG007_LAB01_REP01_LANE01-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG007_LAB01_REP01_LANE01-R2.fq.gz">  EPIC_HG007_LAB01_REP01_LANE01-R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG007_LAB01_REP01_LANE02-R1.fq.gz">  EPIC_HG007_LAB01_REP01_LANE02-R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/EPIC_HG007_LAB01_REP01_LANE02-R2.fq.gz">  EPIC_HG007_LAB01_REP01_LANE02-R2.fq.gz</a>


### 5hmC detection 

#### OX-BS

- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP01-bs.R1.fq.gz">  OXBS_HG001_LAB01_REP01-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP01-bs.R2.fq.gz">  OXBS_HG001_LAB01_REP01-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP01-ox.R1.fq.gz">  OXBS_HG001_LAB01_REP01-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP01-ox.R2.fq.gz">  OXBS_HG001_LAB01_REP01-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP02-bs.R1.fq.gz">  OXBS_HG001_LAB01_REP02-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP02-bs.R2.fq.gz">  OXBS_HG001_LAB01_REP02-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP02-ox.R1.fq.gz">  OXBS_HG001_LAB01_REP02-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG001_LAB01_REP02-ox.R2.fq.gz">  OXBS_HG001_LAB01_REP02-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP01-bs.R1.fq.gz">  OXBS_HG002_LAB01_REP01-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP01-bs.R2.fq.gz">  OXBS_HG002_LAB01_REP01-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP01-ox.R1.fq.gz">  OXBS_HG002_LAB01_REP01-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP01-ox.R2.fq.gz">  OXBS_HG002_LAB01_REP01-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP02-bs.R1.fq.gz">  OXBS_HG002_LAB01_REP02-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP02-bs.R2.fq.gz">  OXBS_HG002_LAB01_REP02-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP02-ox.R1.fq.gz">  OXBS_HG002_LAB01_REP02-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG002_LAB01_REP02-ox.R2.fq.gz">  OXBS_HG002_LAB01_REP02-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP01-bs.R1.fq.gz">  OXBS_HG003_LAB01_REP01-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP01-bs.R2.fq.gz">  OXBS_HG003_LAB01_REP01-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP01-ox.R1.fq.gz">  OXBS_HG003_LAB01_REP01-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP01-ox.R2.fq.gz">  OXBS_HG003_LAB01_REP01-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP02-bs.R1.fq.gz">  OXBS_HG003_LAB01_REP02-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP02-bs.R2.fq.gz">  OXBS_HG003_LAB01_REP02-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP02-ox.R1.fq.gz">  OXBS_HG003_LAB01_REP02-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG003_LAB01_REP02-ox.R2.fq.gz">  OXBS_HG003_LAB01_REP02-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP01-bs.R1.fq.gz">  OXBS_HG004_LAB01_REP01-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP01-bs.R2.fq.gz">  OXBS_HG004_LAB01_REP01-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP01-ox.R1.fq.gz">  OXBS_HG004_LAB01_REP01-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP01-ox.R2.fq.gz">  OXBS_HG004_LAB01_REP01-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP02-bs.R1.fq.gz">  OXBS_HG004_LAB01_REP02-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP02-bs.R2.fq.gz">  OXBS_HG004_LAB01_REP02-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP02-ox.R1.fq.gz">  OXBS_HG004_LAB01_REP02-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG004_LAB01_REP02-ox.R2.fq.gz">  OXBS_HG004_LAB01_REP02-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP01-bs.R1.fq.gz">  OXBS_HG005_LAB01_REP01-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP01-bs.R2.fq.gz">  OXBS_HG005_LAB01_REP01-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP01-ox.R1.fq.gz">  OXBS_HG005_LAB01_REP01-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP01-ox.R2.fq.gz">  OXBS_HG005_LAB01_REP01-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP02-bs.R1.fq.gz">  OXBS_HG005_LAB01_REP02-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP02-bs.R2.fq.gz">  OXBS_HG005_LAB01_REP02-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP02-ox.R1.fq.gz">  OXBS_HG005_LAB01_REP02-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG005_LAB01_REP02-ox.R2.fq.gz">  OXBS_HG005_LAB01_REP02-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP01-bs.R1.fq.gz">  OXBS_HG006_LAB01_REP01-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP01-bs.R2.fq.gz">  OXBS_HG006_LAB01_REP01-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP01-ox.R1.fq.gz">  OXBS_HG006_LAB01_REP01-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP01-ox.R2.fq.gz">  OXBS_HG006_LAB01_REP01-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP02-bs.R1.fq.gz">  OXBS_HG006_LAB01_REP02-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP02-bs.R2.fq.gz">  OXBS_HG006_LAB01_REP02-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP02-ox.R1.fq.gz">  OXBS_HG006_LAB01_REP02-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG006_LAB01_REP02-ox.R2.fq.gz">  OXBS_HG006_LAB01_REP02-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP01-bs.R1.fq.gz">  OXBS_HG007_LAB01_REP01-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP01-bs.R2.fq.gz">  OXBS_HG007_LAB01_REP01-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP01-ox.R1.fq.gz">  OXBS_HG007_LAB01_REP01-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP01-ox.R2.fq.gz">  OXBS_HG007_LAB01_REP01-ox.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP02-bs.R1.fq.gz">  OXBS_HG007_LAB01_REP02-bs.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP02-bs.R2.fq.gz">  OXBS_HG007_LAB01_REP02-bs.R2.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP02-ox.R1.fq.gz">  OXBS_HG007_LAB01_REP02-ox.R1.fq.gz</a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/OXBS_HG007_LAB01_REP02-ox.R2.fq.gz">  OXBS_HG007_LAB01_REP02-ox.R2.fq.gz</a>


#### (h)Me-DIP

- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA12878_22_CGTGAT_S1_L007_R1_001.fastq.gz"> 5hmC_NA12878_22_CGTGAT_S1_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA12878_23_ACATCG_S2_L007_R1_001.fastq.gz"> 5hmC_NA12878_23_ACATCG_S2_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA12878_24_GCCTAA_S3_L007_R1_001.fastq.gz"> 5hmC_NA12878_24_GCCTAA_S3_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24143_28_GATCTG_S7_L007_R1_001.fastq.gz"> 5hmC_NA24143_28_GATCTG_S7_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24143_29_TCAAGT_S8_L007_R1_001.fastq.gz"> 5hmC_NA24143_29_TCAAGT_S8_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24143_30_CTGATC_S9_L007_R1_001.fastq.gz"> 5hmC_NA24143_30_CTGATC_S9_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24149_25_TGGTCA_S4_L007_R1_001.fastq.gz"> 5hmC_NA24149_25_TGGTCA_S4_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24149_26_CACTGT_S5_L007_R1_001.fastq.gz"> 5hmC_NA24149_26_CACTGT_S5_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24149_27_ATTGGC_S6_L007_R1_001.fastq.gz"> 5hmC_NA24149_27_ATTGGC_S6_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24385_40_GGCCAC_S19_L007_R1_001.fastq.gz"> 5hmC_NA24385_40_GGCCAC_S19_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24385_41_CGAAAC_S20_L007_R1_001.fastq.gz"> 5hmC_NA24385_41_CGAAAC_S20_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24385_42_CGTACG_S21_L007_R1_001.fastq.gz"> 5hmC_NA24385_42_CGTACG_S21_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24631_31_AAGCTA_S10_L007_R1_001.fastq.gz"> 5hmC_NA24631_31_AAGCTA_S10_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24631_32_GTAGCC_S11_L007_R1_001.fastq.gz"> 5hmC_NA24631_32_GTAGCC_S11_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24631_33_TACAAG_S12_L007_R1_001.fastq.gz"> 5hmC_NA24631_33_TACAAG_S12_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24644_37_GGACGG_S16_L007_R1_001.fastq.gz"> 5hmC_NA24644_37_GGACGG_S16_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24644_38_GCGGAC_S17_L007_R1_001.fastq.gz"> 5hmC_NA24644_38_GCGGAC_S17_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24644_39_TTTCAC_S18_L007_R1_001.fastq.gz"> 5hmC_NA24644_39_TTTCAC_S18_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24645_34_TTGACT_S13_L007_R1_001.fastq.gz"> 5hmC_NA24645_34_TTGACT_S13_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24645_35_GGAACT_S14_L007_R1_001.fastq.gz"> 5hmC_NA24645_35_GGAACT_S14_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5hmC_NA24645_36_TGACAT_S15_L007_R1_001.fastq.gz"> 5hmC_NA24645_36_TGACAT_S15_L007_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA12878_1_CGTGAT_S8_L005_R1_001.fastq.gz"> 5mC_NA12878_1_CGTGAT_S8_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA12878_2_ACATCG_S9_L005_R1_001.fastq.gz"> 5mC_NA12878_2_ACATCG_S9_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA12878_3_GCCTAA_S10_L005_R1_001.fastq.gz"> 5mC_NA12878_3_GCCTAA_S10_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24143_7_GATCTG_S14_L005_R1_001.fastq.gz"> 5mC_NA24143_7_GATCTG_S14_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24143_8_TCAAGT_S15_L005_R1_001.fastq.gz"> 5mC_NA24143_8_TCAAGT_S15_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24143_9_CTGATC_S16_L005_R1_001.fastq.gz"> 5mC_NA24143_9_CTGATC_S16_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24149_4_TGGTCA_S11_L005_R1_001.fastq.gz"> 5mC_NA24149_4_TGGTCA_S11_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24149_5_CACTGT_S12_L005_R1_001.fastq.gz"> 5mC_NA24149_5_CACTGT_S12_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24149_6_ATTGGC_S13_L005_R1_001.fastq.gz"> 5mC_NA24149_6_ATTGGC_S13_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24385_19_GGCCAC_S26_L005_R1_001.fastq.gz"> 5mC_NA24385_19_GGCCAC_S26_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24385_20_CGAAAC_S27_L005_R1_001.fastq.gz"> 5mC_NA24385_20_CGAAAC_S27_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24385_21_CGTACG_S28_L005_R1_001.fastq.gz"> 5mC_NA24385_21_CGTACG_S28_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24631_10_AAGCTA_S17_L005_R1_001.fastq.gz"> 5mC_NA24631_10_AAGCTA_S17_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24631_11_GTAGCC_S18_L005_R1_001.fastq.gz"> 5mC_NA24631_11_GTAGCC_S18_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24631_12_TACAAG_S19_L005_R1_001.fastq.gz"> 5mC_NA24631_12_TACAAG_S19_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24644_16_GGACGG_S23_L005_R1_001.fastq.gz"> 5mC_NA24644_16_GGACGG_S23_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24644_17_GCGGAC_S24_L005_R1_001.fastq.gz"> 5mC_NA24644_17_GCGGAC_S24_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24644_18_TTTCAC_S25_L005_R1_001.fastq.gz"> 5mC_NA24644_18_TTTCAC_S25_L005_R1.fastq.gz </a>
- <a href="https://epiqc.s3.us-east-2.amazonaws.com/5mC_NA24645_13_TTGACT_S20_L005_R1_001.fastq.gz">  5mC_NA24645_13_TTGACT_S20_L005_R1.fastq.gz </a>


# Download notes

Please refer to the Amazon Web Services <a href="https://aws.amazon.com/cli/">command-line interface documentation</a> for best practices, particularly for batch downloads. Append `s3://` to the start of each hyperlink for command-line retrieval.
