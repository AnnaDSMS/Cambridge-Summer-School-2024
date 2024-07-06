This repository contains introductory training material on climate and weather modelling,
focussing on Observation System Simulation Experience (OSSE), based on the article:

> Denvil-Sommer, A., Gehlen, M., and Vrac, M.: Observation system simulation experiments in the Atlantic Ocean for enhanced surface ocean pCO2 reconstructions, Ocean Sci., 17, 1011–1030, https://doi.org/10.5194/os-17-1011-2021, 2021.

## Base requirements

- Python 3

The instructions below will install the necessary packages

## Getting started

1. Clone this repository into a directory, e.g.

      git clone https://github.com/AnnaDSMS/Cambridge-Summer-School-2024

2. Download the data set from:

> Denvil-Sommer, A. (2024). Dataset for OSSE exercise at ICCS Summer School 2024 Cambridge [Data set]. Zenodo. https://doi.org/10.5281/zenodo.12567970

It is easiest to download `Data_SS.zip` and unzip it into the same directory as the code so that the .csv
files are alongside the notebook file.

3. To setup the Notebook, we recommend running it in a virtual environment:

       python -m venv venv
       source ./venv/bin/activate
       pip install -r requirements.txt

From here you can load the notebook using your favourite mechanism. For example,
using Jupyter notebook you can do:

      jupyter notebook

and then choose the `SOCAT_20082010_AtlOcean_ADS_05062024.ipynb` notebook.