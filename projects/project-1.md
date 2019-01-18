---
layout: project
type: project
title: Bioinformatic Analysis of Campylobacter jejuni
image: images/campy.jpg
# All dates must be YYYY-MM-DD format!
date: 2017-08-01
labels:
  - Bioinformatics
  - BLAST
summary: I came up with a research project utilizng Bioinformatics tools.
---
  As part of an extra-curricular research opportunity through INBRE Hawaii, I conducted independent research on a bacterium called Campylobacter jejuni for an entire academic year. In most extra-curricular research projects, groups of students are given topics from their instructor. However, I was a special exception because no one in the microbiology research lab I was working in knew anything about Bioinformatics. Therefore, I had to come up with my own idea for the project by myself and also give my PI something he could relate to, as far as the microbiological aspect of it. While it was an extremely frustrating process, my PI and I eventually came to an agreed topic, which is the title of the project itself.

   C. jejuni is the leading cause of bacterial gastroenteritis, which in lay-man’s terms means that it is the number one cause of diarrhea. However, many of the biological processes, such as adherence and invasion, have not been definitively defined. The goal of my project was to test known DNA sequences of genes against whole genomes of different variations of C. jejuni. This included different strains as well as distant relatives of C. jejuni such as Campylobacter coli and Helicobacter pylori. Because whole genome sequences of bacteria are large sets of data, I could not run efficient analysis on my local machine. I utilized the HPC, hosted by UH ITS, in order to submit batch jobs and run other scripts for which I did not have a local compiler for. I obtained gene and whole DNA sequences from NCBI and submitted batch jobs (.slurm) to the HPC utilizing composition templates and Perl scripts by Dan Laspisa. The batch jobs essentially ran a large-scale BLAST (Basic Linear Alignment Search Tool), comparing the given annotated genes of interest and the whole genome sequences of the various Campylobacter. I also generated phylogeny and a recombinant genome visualization using Mega7 and MAUVE respectively. 
   
 Here is my modified batch job submission:
 ```
 #!/bin/bash
#SBATCH -J Campy_blast # Name for your job
#SBATCH -n 1 # Number of tasks when using MPI. Default is 1
#SBATCH -c 20 # Number of cores requested, Default is 1 (total cores requested = tasks x cores)
#SBATCH -N 1 # Number of nodes to spread cores across - default is 1 - if you are not using MPI this should likelybe 1
#SBATCH --mem-per-cpu 6400 
#SBATCH -t 03-00:00:00 # Runtime in minutes. Default is 10 minutes. The Maximum runtime currently is 72 hours, 4320 minutes -requests over that time will not run
#SBATCH -p community.q # Partition to submit to the standard compute node partition(community.q) or the large memory nodepartition(lm.q)
#SBATCH -e Campy_blast.err # Standard err goes to this file
#SBATCH --mail-user qauchida@hawaii.edu # this is the email you wish tobe notified at
#SBATCH --mail-type ALL # this specifies what events you should get an email about ALL will alert you of jobbeginning,completion, failure etc
source ~/.bash_profile #if you want to use modules or need environment variables use this if your shell isbash to load those
module load lang/Perl/5/5.22.1
module load bioinfo/NCBI/blast/plus/2.2.30

makeblastdb -in CAMPY_jejuni_NCTC11168_complete_genomesequence.fasta -parse_seqids -dbtype nucl
makeblastdb -in C_jejuni_01-1512.fasta -parse_seqids -dbtype nucl
makeblastdb -in C_jejuni_RM3194.fasta -parse_seqids -dbtype nucl
makeblastdb -in Cj_RM3420_Penner19.fa -parse_seqids -dbtype nucl
makeblastdb -in Cj_81-176_CP000538.1.fasta -parse_seqids -dbtype nucl
makeblastdb -in Cj_81116_GCF_000017905.1_ASM1790v1_genomic.fna -parse_seqids -dbtype nucl

blastn -query CAMPY_jejuni_11168.fix.fa -db CAMPY_jejuni_NCTC11168_complete_genomesequence.fasta -num_threads 20 -dust no -outfmt 6 > REFERENCE_GENOME_TO_GENOME_11168.out
blastn -query CAMPY_jejuni_11168.fix.fa -db C_jejuni_01-1512.fasta -num_threads 20 -dust no -outfmt 6 > REFERENCE_GENOME_TO_GENOME_11168.out
blastn -query CAMPY_jejuni_11168.fix.fa -db CAMPY_jejuni_NCTC11168_complete_genomesequence.fasta -num_threads 20 -dust no -outfmt 6 > REFERENCE_GENOME_TO_GENOME_11168.out
blastn -query CAMPY_jejuni_11168.fix.fa -db CAMPY_jejuni_NCTC11168_complete_genomesequence.fasta -num_threads 20 -dust no -outfmt 6 > REFERENCE_GENOME_TO_GENOME_11168.out
blastn -query CAMPY_jejuni_11168.fix.fa -db CAMPY_jejuni_NCTC11168_complete_genomesequence.fasta -num_threads 20 -dust no -outfmt 6 > REFERENCE_GENOME_TO_GENOME_11168.out
blastn -query CAMPY_jejuni_11168.fix.fa -db CAMPY_jejuni_NCTC11168_complete_genomesequence.fasta -num_threads 20 -dust no -outfmt 6 > REFERENCE_GENOME_TO_GENOME_11168.out
blastn -query CAMPY_jejuni_11168.fix.fa -db CAMPY_jejuni_NCTC11168_complete_genomesequence.fasta -num_threads 20 -dust no -outfmt 6 > REFERENCE_GENOME_TO_GENOME_11168.out


 ```
 All this code means is that I'm sending commands to BLAST different genomes against reference genes.
 
   While the research itself sounds like a lot to digest, I found presenting at the INBre symposium to be the most difficult aspect of this project. I neglected to state annotated genes that I compared against the whole genome sequences in my research poster which was a glaring hole in my overall presentation. Also, the judges felt that I either spent too much time on my processes and not enough time on the results or that I had spent too little time on the processes and insufficient time on the results. However, this research experience was specifically for undergraduate students who have never done formal research experience before, such as myself. Part of me realizes that just completing a research project, from conception to the end, is a great accomplishment. And yet, I treated the judge’s critiques as an opportunity to fully analyze and improve myself in attributes I didn’t even realize I lacked. But, no matter how difficult the project became, I had a blast.

---




