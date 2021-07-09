# Exoplanets

<img src="images/kepler-186f.jpg" width ="500">

## Description

This project focuses on data wrangling as much as the exoplanet topic. The data was then loaded into a Postgres database.

## Postgres Screenshots

<img src="images/proofpostgres.PNG" width ="500">

<img src="images/proofpostgres2.PNG" width ="500">

## Data

The data was retrieved from api.nasa.gov and requires a login. The [folder](data/) containing the two CSV files is a part of this repository.

_As of my testing on July 9, 2021, the link to the exoplanet [api](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/nstedAPI/nph-nstedAPI) used by the exolplanets function in nasapy module was unavailable._

## EDA 

The pandas report is built into the code [here](https://nbviewer.jupyter.org/github/SDLoyd/Exoplanets/blob/master/code/finalprojectdcs.ipynb).

## Code

The [code](code/finalprojectdcs.ipynb) is a python program created in Jupyter notebook. To view the pandas-profile, you will need to download and view in Jupyter notebook or use the link on the next line.

If you have trouble with GitHub rendering the file, please try [here](https://nbviewer.jupyter.org/github/SDLoyd/Exoplanets/blob/master/code/finalprojectdcs.ipynb).

## Documentation

The final [report](docs/Finalproject.pdf) analysis is included.

## Instructions

To run this notebook locally, install Jupyter, download the data set, change the file location to load the code and data, and install all the library dependencies.

The R code is best run from RStudio. You will also need to download the code and data.

[Anaconda](https://www.anaconda.com/) can be used for both.

## Tools

* Python
* Jupyter Notebook

## Credits

_Planet [image](https://www.nasa.gov/ames/kepler/kepler-186f-the-first-earth-size-planet-in-the-habitable-zone) by T. Pyle at [NASA Ames](https://www.nasa.gov/ames)_
