# ExploringYouthLiteracy
 
In the Jupyter notebook, YouthLiteracyWorldBank.ipynb, I explore data related to youth literacy rates in different countries. The data is from [World Bank Open Data](https://data.worldbank.org/).

View the notebook using Jupyter nbviewer: 
[https://nbviewer.jupyter.org/github/KathrynDH/ExploringYouthLiteracy/blob/main/YouthLiteracyWorldBank.ipynb](https://nbviewer.jupyter.org/github/KathrynDH/ExploringYouthLiteracy/blob/main/YouthLiteracyWorldBank.ipynb)

## Questions 
1. How has youth literacy changed over time?
2. Which countries have the lowest youth literacy rates?
3. How are youth literacy rates, per capita income, and population related?

The youth literacy rate has been increasing for all country income groups. 

The countries that have the lowest youth literacy rates are:
- Somalia
- Chad
- Central African Republic
- Niger
- Guinea
- South Sudan
- Mali
- Liberia
- Burkina Faso
- Cote d'Ivoire

These countries all have youth literacy rates under 60%.

The countries with the lowest literacy rates had lower incomes than other countries in the dataset. There were 27 countires under 80% youth literacy. Their median GNI was 850.00 USD and max GNI of 2960.00 USD.

## Data
The data was obtained using the World Bank API. The data is stored in the data folder and the Python scripts in the data-scripts folder can be used to recreate the csv files.

## Required Python libraries
- numpy
- pandas
- matplotlib
- sklearn
- requests
