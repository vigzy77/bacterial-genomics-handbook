---
layout: page
title:  "What is your data?"
categories: question
step: data_preparation
---

In most scenarios, your input data may come in the form of either a FASTQ file or a FASTA file. 

A **FASTQ file** is a text file that contains sequence read data and its corresponding quality score. These files are generated by sequencing machines and have a strict format. FASTQ files contain four line-separated fields for each sequence. 
- The first field begins with “@” and contains the sequence or read identifier.
- The next field contains the actual sequence information.
- The third field contains the separator “+”, and
- the last field contains the quality scores for each character or base in the second field. 

A **FASTA file** is a text file that contains nucleotide or protein sequences. They are formatted differently than FASTQ files and are generated by assembling FASTQ files using a genomic assembler such as Unicycler, SPAdes, or Flye. Each sequence in a FASTA file contains two fields. 
- The first field always begins with a “>” followed by a sequence identifier.
- The next lines immediately following the sequence identifier contains the sequence information.
