## Single Cell RNA-seq Analysis of Human Calcified Atherosclerotic Plaque 

### 1. Raw data 

- GEO: [159677](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE159677)

- Samples: Calcified atherosclerotic core (AC) plaques and patient-matched proximal adjacent (PA) portions of carotid artery were collected from three patients undergoing carotid endarterectomy and were assessed using single cell RNA-seq

- Input file: [GSE159677_AGGREGATEMAPPED-tisCAR6samples_featurebcmatrixfiltered.tar.gz](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE159677&format=file&file=GSE159677%5FAGGREGATEMAPPED%2DtisCAR6samples%5Ffeaturebcmatrixfiltered%2Etar%2Egz)


### 2. Workflow 

- Preparation of cell cycle marker genes: [cellcycle_markers.Rmd](https://github.com/Mira0507/scRNAseq_calcifiedAC/blob/master/cellcycle_markers.Rmd)

- Quality control, integration, sctransformation, clustering, marker identification: [scRNAseq_v1.Rmd](https://github.com/Mira0507/scRNAseq_calcifiedAC/blob/master/scRNAseq_v1.Rmd)

- Differential expression (DE) analysis in AC vs PA: [scRNAseq_v2.Rmd](https://github.com/Mira0507/scRNAseq_calcifiedAC/blob/master/scRNAseq_v2.Rmd)

- Pseudobulk DE analysis in AC vs PA by cluster: [scRNAseq_v3.Rmd](https://github.com/Mira0507/scRNAseq_calcifiedAC/blob/master/scRNAseq_v3.Rmd)

- Pseudobulk DE analysis and GSEA in AC vs PA in ECM and CTL/NK clusters: [scRNAseq_v4.Rmd]



