# RNAseq_analyses

RNAseq analysis of specific cell types(Astrocytes, smNPC, dopaminergic neurons at day 15,30,50). 
Three biological samples are present per each condition. 
First the Deseq object is built to tun the differential expression genes analyses. The z-score for the gene relative expression in each condition are calculated to then plot the heatmaps. Finally RPKM are calculated to then visualize the expression of a selected gene.