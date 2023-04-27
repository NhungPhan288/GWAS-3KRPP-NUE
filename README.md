# GWAS-3KRPP-NUE
Genotypic data using in GWAS on NUE-related traits in 3K RGP

Data for GWAS analysis were downloaded from website: https://snp-seek.irri.org

There are many dataset of SNPs on the website of 3K RGP (snp-seek.irri.org).

Data name "1M2391G" and "1M1332G" were extracted from dataset "3K RG 1M GWAS SNP Dataset, all chromosomes". The files contain BED file, BIM file, and FAM file. Meanwhile, BIM file refers to information of SNP (name, chromosome, position, major allele, minor allele), FAM refers to information of genotypes (family ID, individual ID), and BED refers to main genotyping data. The downloaded files from this website name “pruned_v2.1.bed” (746,847 KB), “pruned_v2.1.bim” (26,272 KB), and “pruned_v2.1.fam” (101 KB). These original files contain information of 3,024 genotypes and 1,011,601 SNPs. It was written in the README file in the original website: "LD Pruned GWAS SNP Set Readme New LD pruned subset to try for GWAS: As before, it is based on the Filtered SNP set (4.8M) which is a subset of Base SNP (18M), unlike the 990k SNP set. It was done with just one round of LD pruning, r2 cutoff 0.8, window size 2kb and step 1 SNP, so that we will remove only SNPs that are less than ~2kb apart. This leaves 1,011,601 snps".

The other files were used for gene-based analysis or haplotype analysis, with high density of SNPs, call "32 M SNPs data". It is a full set of 3kRG (32mio) including biallelic & multiallelic SNP set v.5.
