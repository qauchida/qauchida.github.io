---
layout: project
type: project
title: Bioinformatic Analysis of Campylobacter jejuni
# All dates must be YYYY-MM-DD format!
date: 2017-08-01
labels:
  - Bioinformatics
  - Perl
  - BLAST
summary: I came up with a research project utilizng Bioinformatics tools.
---
  As part of an extra-curricular research opportunity through INBRE Hawaii, I conducted independent research on a bacterium called Campylobacter jejuni for an entire academic year. In most extra-curricular research projects, groups of students are given topics from their instructor. However, I was a special exception because no one in the microbiology research lab I was working in knew anything about Bioinformatics. Therefore, I had to come up with my own idea for the project by myself and also give my PI something he could relate to, as far as the microbiological aspect of it. While it was an extremely frustrating process, my PI and I eventually came to an agreed topic, which is the title of the project itself.
	C. jejuni is the leading cause of bacterial gastroenteritis, which in lay-man’s terms means that it is the number one cause of diarrhea. However, many of the biological processes, such as adherence and invasion, have not been definitively defined. The goal of my project was to test known DNA sequences of genes against whole genomes of different variations of C. jejuni. This included different strains as well as distant relatives of C. jejuni such as Campylobacter coli and Helicobacter pylori. Because whole genome sequences of bacteria are large sets of data, I could not run efficient analysis on my local machine. I utilized the HPC, hosted by UH ITS, in order to submit batch jobs and run other scripts for which I did not have a local compiler for. I obtained gene and whole DNA sequences from NCBI and submitted batch jobs to the HPC utilizing composition templates by Dan Laspisa and Perl scripts from other authors. The batch jobs essentially ran a large-scale BLAST (Basic Linear Alignment Search Tool), comparing the given annotated genes of interest and the whole genome sequences of the various Campylobacter. I also generated phylogeny and a recombinant genome visualization using Mega7 and MAUVE respectively. 
	While the research itself sounds like a lot to digest, I found presenting at the INBre symposium to be the most difficult aspect of this project. I neglected to state annotated genes that I compared against the whole genome sequences in my research poster which was a glaring hole in my overall presentation. Also, the judges felt that I either spent too much time on my processes and not enough time on the results or that I had spent too little time on the processes and insufficient time on the results. However, this research experience was specifically for undergraduate students who have never done formal research experience before, such as myself. Part of me realizes that just completing a research project, from conception to the end, is a great accomplishment. And yet, I treated the judge’s critiques as an opportunity to fully analyze and improve myself in attributes I didn’t even realize I lacked. But, no matter how difficult the project became, I had a blast.

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



