# UAMS-SURF-Jupyter-Notebook

# Welcome!
This jupyter notebook records the creation and testing of a [software tool for alignment free construction of pan-genomes](https://github.com/mdttrump97/Kmer_pangenomes). This project was undertaken during the summer of 2019 for the Summer Undergraduate Research Fellowship at the University of Arkansas for Medical Sciences (UAMS SURF). 

To view the notebook, click any of the WeekX.ipynb files and documentation should appear!

## **What is a pan-genome?**
A pan-genome is the total collection of genes present in a group of organisms. As bacteria can quickly transfer and receieve genetic material via mechanisms of horizontal gene transfer, 
a diverse set of genes may be present among organisms of the same species. Pan-genomes are composed of core genes (genes present in all genomes analyzed), accessory genes (genes present in some genomes analyzed), 
and singleton genes (genes present in only one genome). These divisions carry biological signficance, with core genes typically being associated with essential housekeeping functions, and accessory and singleton genes
being associated with dispensable, adaptable functions.

## **Alignment-free?**
Alignment-free methods are used to compare sequences without using sequence alignment. Alignment-free methods scale better than sequence alignment methods as input data sizes increase, so development using alignment-free methods has increased as more genomes have been sequenced and have become available. 

## **K-mer counting?**
A *k-mer* is a subsequence of length k of a larger sequence. K-mers are recorded by finding all overlapping subsequences by sliding a small window of length k across a sequence. By recording the occurrence of k-mers
in a sequence, information about the original sequence is stored. K-mer occurrences can then be converted to vectors, and multiple vectors can be compared using metrics from linear algebra, such as the cosine similarity or the euclidean distance.