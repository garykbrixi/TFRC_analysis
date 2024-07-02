# TFRC expression level plots

This repository containts scripts for analysis of TFRC expression levels, part of the paper ["Transferrin Receptor Targeting Chimeras (TransTACs) for Membrane Protein Degradation"](https://www.biorxiv.org/content/10.1101/2023.08.10.552782v1.abstract).

### Data

Data files needed to replicate the plots, as well as data used for preliminary analysis, are included in the `data/` folder. Data were downloaded from MERAV and GENT2 databases, with the final plots being made from MERAV data.

### Notebooks

`expression_analysis.ipynb`: scripts for plotting MERAV data of TFRC expression and conducting statistical tests
`gent2_plots.ipynb`: analysis of GENT2 data

### Installation

Package requirements are in `requirements.txt`. Installation should take a few minutes. \
To install, do:
`conda create --name tfrc_env python==3.10.5`\
`conda activate tfrc_env`\
`pip install -r requirements.txt`

