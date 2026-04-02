# RNA-Seq-Exploration

### Overview
This repository contains my initial self-directed explorations into single-cell RNA-sequencing (scRNA-seq) analysis. As a Human Physiologist transitioning into computational neurogenomics, I am currently adapting my Python (Pandas/NumPy) background to standard bioinformatics pipelines. 

### Current Project: PBMC 3k Scanpy Pipeline
**File:** `Scanpy_PBMC3k_Exploration.ipynb`

This notebook uses the `Scanpy` library to process the standard 10x Genomics Peripheral Blood Mononuclear Cells (PBMC) dataset. 

**Steps covered in this notebook:**
1. **Environment Setup:** Importing Scanpy and loading raw count matrices.
2. **Quality Control (QC):** Filtering out low-quality cells (min_genes) and uninformative genes (min_cells).
3. **Mitochondrial Filtering:** Calculating mitochondrial gene percentages (`MT-`) to identify and prepare to remove apoptotic cells.
4. **Data Visualization:** Generating violin plots for QC metrics and visualizing highest-expressing genes.

### Next Steps
* Implement data normalization and log transformation.
* Run Principal Component Analysis (PCA).
* Perform clustering (Leiden graph-based clustering) and UMAP visualization.
* <img width="493" height="486" alt="genes" src="https://github.com/user-attachments/assets/34e3d91e-dc80-405d-a163-9ddf5ffcb0a3" />
