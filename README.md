# Systemic inflammation impairs human myelopoiesis and interferon type I responses

This repository contains code for reproducing the key figures and findings of the short and long-term effects of LPS-induced systemic inflammation (**LPS-SI**) on hematopoiesis, especially myelopoiesis manuscript.
<br></br>
![alt text](./Header%20Image.png)
<br></br>
In order to run codes you need to:
 1. Download gene-cell count matrix from Gene Expression Omnibus (GEO) with the accession number of [GSE212093](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212093).
 <br></br>

 2. Download following list of cells used to generate single cell objects for the analysis (e.g. Seurat objects):
    * [Bone marrow mononuclear cells of all time points](./Cell%20Lists/CellName_Whole_BoneMarrow_All_TimePoints.tsv)
<br></br>

 3. Follow any of the following analysis pipelines to replicate results of the paper:
    * [Visualize whole bone marrow data from all time points using UMAP](./Analysis%20Scripts/All%20Bone%20Marrow%20Mononuclear%20Cell%20from%20All%20Time%20Points.ipynb)
    * [Acute (4h) response of bone marrow myeloid cells to LPS-SI](./Analysis%20Scripts/Myeloid%20Cells%20Acute%20Response%20to%20LPS-SI.ipynb)
    * [Acute (4h) response of bone marrow lymphoid T and NK cells to LPS-SI](./Analysis%20Scripts/Lymphoid%20T%20and%20NK%20Cells%20Acute%20Response%20to%20LPS-SI.ipynb)
    * [Acute (4h) response of bone marrow lymphoid B and pDCs to LPS-SI](./Analysis%20Scripts/Lymphoid%20B%20and%20pDC%20Cells%20Acute%20Response%20to%20LPS-SI.ipynb)
    * Late phase (day 7) effect of LPS-SI on myelopoiesis
<br></br>  

For any further information or questions related to the analysis please contact Farid Keramati via [farid.karamati@gmail.com](mailto:farid.karamati@gmail.com) email address.
