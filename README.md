# drug-discovery

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KmCuF4sk6_mkIJ0GhvpluSeLKrAxbmpq?usp=sharing)

# ChEMBL Data Analysis for Bioactivity Assessment


Multiple studies have demonstrated that secretory infertile men exhibit a higher estradiol to T ratio compared to men with normal spermatogenesis, indicating potential steroidogenic dysfunction in Leydig cells that might include enhanced aromatase (CYP19A1) activity (Lardone et al., 2017). The impact of disturbed hormonal homeostasis on Leydig cell morphology has also been described in transgenic mice with CYP19A1 overexpression (Strauss et al., 2009).

My research findings (Brzoskwinia et al., 2021) indicate that not only androgens, but also the proper ratio of androgens to estrogens can affect the morphology and activity of Leydig cells.

This repository contains scripts for searching the ChEMBL database to extract and analyze bioactivity data for the CYP19A1 target (aromatase enzyme), which is implicated in Leydig cell steroidogenesis.

## Description

The code performs the following actions:

1. Searches the ChEMBL database for the target CYP19A1.
2. Retrieves the bioactivity data associated with the target and filters it for IC50 values.
3. Cleans the data by removing entries without standard values and categorizes the bioactivities.
4. Computes Lipinski descriptors for the compound dataset.
5. Analyzes the data by comparing active and inactive compounds through statistical methods.
6. Visualizes the results through frequency plots and scatter plots.
7. Performs machine learning model training and evaluation with RandomForestRegressor and LazyPredict.


## References:

- [Lardone et al., 2017](https://pubmed.ncbi.nlm.nih.gov/27769104/)
- [Strauss et al., 2009](https://pubmed.ncbi.nlm.nih.gov/19196801/)
- [Brzoskwinia et al., 2021](https://pubmed.ncbi.nlm.nih.gov/34215832/)
- Chanin Nantasenamat [dataprofessor](https://www.youtube.com/dataprofessor)