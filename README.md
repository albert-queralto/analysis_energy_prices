# Analysis of Energy Prices Data and Renewable Energy Production

## Description

This repository contains the code, data and documentation done in the framework
of a practice exercise for the class *Tipologia i cicle de vida de les dades*
from the *Master in Data Science* of the *Universitat Oberta de Catalunya*.

The exercise consisted in analyzing data using R language from different sources: *AEMET*'s API 
dataset (Agencia Estatal de Meteorologia) and together with *ESIOS* dataset (Operador del Sistema 
de Red Eléctrica).

**Disclaimer:** Express consent has been given by *Red Eléctrica de España*, the
source and propietary of the data, to perform this exercise and under no
circumstance they support the reutilization of the data. We express our
intention to use the data for the purpose of the activity and decline any
commercial interest in the use of the data extracted.

## Authors 

The authors of this activity are: **Esther Manzano i Martín** and **Albert
Queraltó i López**.

## Source Code

* **PRA2_preprocessing.Rmd (and PRA2_preprocessing.pdf):** contains code and explanations for the preprocessing part for both datasets (ESIOS and AEMET).
* **PRA2_final.Rmd (and PRA2_final.pdf):** contains code and explanations for the dataset description, data integration and selection, null values and outlier identification, analysis and final conclusions performed.
* **aemet_preprocessing.ipynb:** code in Python to preprocess the data contained in the *data/aemet_data.zip* file and generate the CSV file with the AEMET data that will be used in *PRA2_preprocessing.Rmd*.
* **aemet_dataset.csv:** contains the data from AEMET dataset obtained using the *aemet_preprocessing.ipynb*.
* **data/aemet_data.zip:** contains all data downloaded using the API from AEMET website.
* **data/aemet_dictionary.txt:** contains dictionary with the description of variables for the AEMET dataset.
* **data/esios_dataset.csv:** contains the ESIOS dataset obtained in the first assignment delivery for the same subject (https://github.com/albert-queralto/scraping-energy-prices-spain).
* **data/final_dataset.zip:** contains a CSV file with the merged data from AEMET and ESIOS datasets.

## Dataset

The data extracted from the website is stored in the folder **data**. The data for AEMET dataset is stored in different format files, being those *.zip*, *.txt* and *.csv*, and contains meteorological information (e.g., temperature, precipitation, wind speed, insolation, pressure, etc.) from different stations and provinces in Spain. The data for ESIOS dataset is stored in *.csv* format as it was submitted for the first assignment delivery on this same subject. It contains information from the electricity prices in Spain, the renewable energy production and energy generation.

Both datasets cover a range of dates from *01-11-2020* to *31-10-2022*.

ESIOS dataset was published in Zenodo and it can be accessed through the following link: *https://doi.org/10.5281/zenodo.7335618*
