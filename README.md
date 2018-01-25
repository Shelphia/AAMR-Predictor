# AAMR-Predictor
Alu elements, the short interspersed element numbering >1 million copies per human genome, are often found at the breakpoint junctions of genomic rearrangements that can cause disease. To identify the impact of Alu/Alu-mediated rearrangement (AAMR) on genomic variation and human health, we developed a bioinformatic approach to characterize CNV-Alus that are involved in mediating CNVs and predicted genome-wide AAMR hotspot loci. 

To query a gene or pairwise interval of interest for the predicted AAMR hotspots, we developed a tool, AAMR-Predictor, which is publicly available (http://omimexplorer.research.bcm.edu:3838/xiaofei/Alu_app/).

##Query prediction results at a gene-level

We assigned an AAMR risk score for each of 12,074 OMIM genes as well as 23,637 Refseq genes. The user could input a gene name (e.g., SPAST) and receive the count of all Alu pairs and predicted CNV-Alu pairs, score, rank and the position (a red line) on the distribution of AAMR risk scores. We suggest a score of 0.6 as a loose ‘cut off’ for at-risk genes. Genes with a score greater than 0.6 might be more susceptible for AAMR. 
 

##Query prediction results at a genomic interval-level 

For pairs of genomic intervals, such as the uncertain regions of aCGH results, we could indicate whether any predicted Alu pair is intersecting with the range pair of interest. We show the query results in a table. This process may take minutes as ~13 millions of predicted Alu pairs are quired. Data in both hg19 and hg38 are available. Of note, the analyses were performed using hg19 reference build, and the results were remapped to hg38. About 99.6% of tested Alu pairs remained after liftover.
