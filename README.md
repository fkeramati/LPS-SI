# Systemic inflammation impairs human myelopoiesis and interferon type I responses

This repository contains code for reproducing the key figures and findings of the short and long-term effects of LPS-induced systemic inflammation (**LPS-SI**) on hematopoiesis, especially myelopoiesis manuscript.
<br></br>
![alt text](./Header%20Image.png)
<br></br>
In order to run codes you need to:
 1. Download gene-cell count matrix from Gene Expression Omnibus (GEO) with the accession number of [GSE212093](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212093).
 <br></br>

 2. Download following list of cells used to generate single cell objects for the analysis (e.g. Seurat objects):
    * [Bone marrow mononuclear cells of all time points](./Cell%20Lists/CellName_Whole_BoneMarrow_All_TimePoints.tsv) (used to generate Fig. 2b)
    * [Myeloid cells from day 0 and 4 hour time points](./Cell%20Lists/CellName_Myeloid_Day0_4h_TimePoints.tsv) (used to generate Fig. 2d)
    * [Lymphoid T and NK cells from day 0 and 4 hour time points](./Cell%20Lists/CellName_LymphoidT_NK_Day0_4h_TimePoints.tsv) (used to generate Fig. 2g)
    * [Lymphoid B and pDC cells from day 0 and 4 hour time points](./Cell%20Lists/CellName_LymphoidB_pDC_Day0_4h_TimePoints.tsv) (used to generate Extended Fig. 5f)
    * [Myeloid cells from all time points (day 0, 4h, day 7)](./Cell%20Lists/CellName_Myeloid_All_TimePoints.tsv) (used to generate Fig. 3a)
<br></br>

 3. Follow any of the following analysis pipelines to replicate results of the paper:
    * [Visualize whole bone marrow data from all time points using UMAP](./Analysis%20Scripts/All%20Bone%20Marrow%20Mononuclear%20Cell%20from%20All%20Time%20Points.ipynb)
    * Acute (4h) response of bone marrow myeloid cells to LPS-SI
    * Acute (4h) response of bone marrow lymphoid T and NK cells to LPS-SI
    * Acute (4h) response of bone marrow lymphoid B and pDCs to LPS-SI
    * Late phase (day 7) effect of LPS-SI on myelopoiesis
