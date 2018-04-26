MICMIC

Methylation regulation network inference with Conditional Mutual information based PC-algorithem

Package: MICMIC

Type: Package

# Title: Methylation regulation network inference with Conditional Mutual information based PC-algorithem

# Introduction: 
Cancer, a complex and fatal disease, is the result of combined genetic and epigenetic alteration. It is widely accepted that hypermethylation on gene promoters would lead to downregulation of tumor suppressor, but the regulation network between epigenome and transcriptom involved with distal methylation variations is still unknown. Here we present a new method named MICMIC : Methylation Regulation Network Inference by Conditional Mutual Information based PC‐algorithm. Using this method, we can construct the cisacting regulation network in a given range on the genome, and narrow down the number of potential regulatory sites by distinguishing direct correlation and indirect(conditional) correlation. These regulatory sites may act as functional genomic elements such as promoters and enhancers, which are responsible for regulation of gene expression. In the MICMIC package, we provide several functions based on information theory to implement the identification of regulators: 

-Learning Mutual information (MI) and conditional mutual information (CMI)

-Infering direct network of variables based on PCAlgorithm

-Infering the cisacting methylation regulatory network for genes

-Visualization of the direct regulations

Version: 0.99.6

Author: Y. Tong, J. Zhang*

Facilities: http://cis.hku.hk/ Zhang Lab, School of Biological Sciences, The University of Hong Kong

Maintainer: Y.Tong, J. Zhang tongyin9002@gmail.com


# Installation: 

To install MICMIC from GitHub you need devtools package:

To install devtools:

> install.packages("devtools")

To install MICMIC:

download the source package, then
> install.packages("MICMIC_0.99.6.tar.gz",repos=NULL)



