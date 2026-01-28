# Integration of human or mice abdominal aortic aneurysm scRNAseq data
This repository provides a reproducible pipeline for integrating and analyzing single-cell RNA sequencing (scRNA-seq) data from human and mice abdominal aortic aneurysm (AAA) tissues, as detailed in our manuscript. The workflow handles data preprocessing, batch correction with Harmony, clustering, differential expression (DEGs), cell type annotation, and cell-cell communication inference using Seurat and CellChat. Outputs include UMAP visualizations, heatmaps, and interaction networks that align with the paper's figures—enabling full reproducibility for researchers studying AAA pathogenesis, lymphangiogenesis, and tertiary lymphoid structures (TLS).

Seurat (version 5.1.0) in R (version 4.3.0).

Public and custom datasets processed here:
Human AAA (GSE166676, GSE226492, GSE237230)
Mice AAA (GSE164678, GSE221789, GSE231306),
 (AngII-infused LDLRKO/Sparcl1MKO: CRA023910)
