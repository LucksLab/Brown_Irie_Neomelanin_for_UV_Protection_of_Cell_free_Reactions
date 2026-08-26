# Brown_Irie_Neomelanin_for_UV_Protection_of_Cell_free_Reactions
Repository for Brown_Irie_Neomelanin_for_UV_Protection_of_Cell_free_Reactions

This repo contains python code and data files for analysis used in Brown and Irie et. al. “Neo-melanin for UV protection of cell-free biosensors"
1.	`117_NMNP_Light_Protection_Paper.ipynb` contains code for generating all of the heatmaps contained in the paper figures and supplementary information. 


## **Downloading Files**
Files can be downloaded manually or obtained by:
   
    git clone https://github.com/LucksLab/Brown_Irie_Neomelanin_for_UV_Protection_of_Cell_free_Reactions.git

## **System Requirements**
The python packages required for a Python 3 Jupyter Notebooks are as follows

    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import seaborn as sns
    import glob

## **Code Usage**

### *Figure Data*

Supplementary data and analysis code for the NMNP light-protection figures.

## Data files

The following Excel files are used by `117_NMNP_Light_Protection_Paper.ipynb` and should be downloaded into the same directory as the notebook before running it:

- `NMNP_FRS_Solar_Heatmap_FITC_Paper.xlsx`
- `NMNP_FRS_Solar_Heatmap_Paper.xlsx`
- `NMNP_FRS_Solar_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_FRS_Solar_Lyo_Heatmap_Paper.xlsx`
- `NMNP_FRS_UVB_Heatmap_FITC_Paper.xlsx`
- `NMNP_FRS_UVB_Heatmap_Paper.xlsx`
- `NMNP_FRS_UVB_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_FRS_UVB_Lyo_Heatmap_Paper.xlsx`
- `NMNP_J23119_Solar_Heatmap_FITC_Paper.xlsx`
- `NMNP_J23119_Solar_Heatmap_Paper.xlsx`
- `NMNP_J23119_Solar_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_J23119_Solar_Lyo_Heatmap_Paper.xlsx`
- `NMNP_J23119_UVB_Heatmap_FITC_Paper.xlsx`
- `NMNP_J23119_UVB_Heatmap_Paper.xlsx`
- `NMNP_J23119_UVB_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_J23119_UVB_Lyo_Heatmap_Paper.xlsx`
- `NMNP_T7_Solar_Heatmap_FITC_Paper.xlsx`
- `NMNP_T7_Solar_Heatmap_Paper.xlsx`
- `NMNP_T7_Solar_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_T7_Solar_Lyo_Heatmap_Paper.xlsx`
- `NMNP_T7_UVB_Heatmap_FITC_Paper.xlsx`
- `NMNP_T7_UVB_Heatmap_Paper.xlsx`
- `NMNP_T7_UVB_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_T7_UVB_Lyo_Heatmap_Paper.xlsx`
- `NMNP_TetR_Solar_Heatmap_FITC_Paper.xlsx`
- `NMNP_TetR_Solar_Heatmap_Paper.xlsx`
- `NMNP_TetR_Solar_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_TetR_Solar_Lyo_Heatmap_Paper.xlsx`
- `NMNP_TetR_UVB_Heatmap_FITC_Paper.xlsx`
- `NMNP_TetR_UVB_Heatmap_Paper.xlsx`
- `NMNP_TetR_UVB_Lyo_Heatmap_FITC_Paper.xlsx`
- `NMNP_TetR_UVB_Lyo_Heatmap_Paper.xlsx`

## Usage

1. Download all 32 Excel files listed above, keeping their original file names.
2. Place them in the same directory as `117_NMNP_Light_Protection_Paper.ipynb`.
3. Run the notebook top to bottom. Figures are written out as `.svg` files in the same directory.
Change the path found in the Jupyter notebook to the path of xlsx files

Running this notebook should generate output heatmap SVG files contained in each manuscript figure and SI figure

