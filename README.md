# Germline Variant calling pipeline comparison

Inspired by [this repository](https://github.com/aalnawfal1992/Clinical_Validation_Of_WES) and aalnawfal1992, who offered guidance and valuable discussions, I must say, "Thank you very much, aalnawfal1992."

# Overview of the data repos

The genome in a bottle project: https://www.nist.gov/programs-projects/genome-bottle

A quick overview of where the files are:
https://github.com/genome-in-a-bottle/giab_data_analysis


Data analysis files:
https://ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/data/NA12878/analysis/

Raw data file description:
https://github.com/genome-in-a-bottle/giab_data_indexes?tab=readme-ov-file


## Download one of the high confidence bed and VCF files from the analysis results repos

For example high confidence `bed` and `VCF` files for `NA12878_HG001`
https://ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/release/NA12878_HG001/NISTv4.2.1/GRCh38/

WGS dataset: https://ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/data/NA12878/NIST_NA12878_HG001_HiSeq_300x/140407_D00360_0017_BH947YADXX/Project_RM8398/

# Comparing two VCF files

https://github.com/RealTimeGenomics/rtg-tools

https://github.com/Illumina/hap.py

Somewhat naive approach:

https://www.biostars.org/p/136937/