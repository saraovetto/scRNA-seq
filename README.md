# scRNA-seq

I performed this analysis as a project for the Transcriptomics course delivered by Università statale di Milano as a part of the MSc in Bioinformatics for Computational Genomics.
The single cell analysis has been performed with *Seurat*. 

### Description

The data is a sample of mammalian tissue from the [Tabula Muris](https://tabula-muris.ds.czbiohub.org) article, downloaded from [PanglaoDB](https://panglaodb.se/view_data.php?sra=SRA653146&srs=SRS3044257&plot=tSNE). The goal of the project was to identify and annotate all the different cell types present in the sample. The pipeline consists of 3 main steps: 
+ clustering
+ marker gene identification
+ cell types imputation

Keep in mind that the term "marker gene" here is in general intended as “found over-expressed in clusters of that cell type". 

### Preview
A preview of the markdown can be seen [here](https://htmlpreview.github.io/?https://github.com/saraovetto/scRNA-seq/blob/main/scRNAseq.html)!
