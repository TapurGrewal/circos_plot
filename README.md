# circos_plot

Circos Plot:
Circos, is a circular ideogram layout to display relationships between genomic intervals. It greatly enhances the visualization of scientific results (especially in Genomics field). Thus, plots with circular layout are normally named as “circos plot”. Here the circlize package aims to implement Circos in R.

Procedure:
1. First of all we have to build the basic chromosome ideogram core using Human Chromosome Ideogram Version 38 data.
2. Cyto.info with only chromosome name and without stain and name.
3. Ideogram plot with different color in X and Y chromosome.
4. Tracking upregulated genes on chromosome dragging from deg.csv file.
5. Tracking those upregulated genes having pvalue and log2FC value less than 3.
6. Calculate maximum number of gene names to be plotted for each chromosome based on plot RCircos plot parameters.
7. Draw heatmap for one data track.

Result Interpretation:
Ideogram plot shows the differentially expressed upregulated genes expression patterns and the distribution of the chromosomal location where they are located, with the outer circle representing the chromosome and the location of the gene in the chromosome, and the heatmap in the inner circle representing the expression of all upregulated differentially expressed genes (DEGs)
