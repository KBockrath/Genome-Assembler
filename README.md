# Genome-Assembler
Docker image for the assembly of Illumina whole genome short read sequences using both a reference genome and de novo assembly. Image goes through file conversion, quality control, and assembly. Based on Debian GNU/Linux version 8 3.10.0-514.21.1.el7.x86_64

Programs included in the Dockerfile: 
- bcl2fastq2 
- fastq-mcf 
- fastQC 
- biopython 
- bowtie2 
- Velvet Optimzer 
- Velvet Assembler 

