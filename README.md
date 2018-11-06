# Pilot Analysis

## Download References

The reference files we will use come from the [GATK Resource Bundle](https://software.broadinstitute.org/gatk/download/bundle).


```bash
mkdir -p refs
cd refs

# Download reference
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.dict
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta.fai

# Download BWT index
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta.64.alt
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta.64.amb
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta.64.ann
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta.64.bwt
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta.64.pac
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.fasta.64.sa

# Download SNPs
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.dbsnp138.vcf
wget https://storage.googleapis.com/genomics-public-data/resources/broad/hg38/v0/Homo_sapiens_assembly38.dbsnp138.vcf.idx

cd ..
```

## Raw Data

TODO: Describe how the fellowing raw data are organized
Under the directory production a file called P001 has been created refering to patient number 1 
2 folders have been created under P001 : P001_N for normal tissue and P001_T for tumor tissue
Each folder (e.g P001_N) contains 2 files that end by R1.fastq.gz and R2.fastq.gz


