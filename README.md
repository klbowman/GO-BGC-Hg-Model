# GO-BGC-Hg-Model

Supervised machine learning and neural network models to predict monomethylmercury concentrations.

## Description

This repository is designed to model oceanographic data with the goal of predicting dissolved methylmercury concentrations. Data were downloaded from [BCO-DMO](https://www.bco-dmo.org/) as CSV files and merged (bottle, profile, and mercury datasets) in Jupyter Notebook. Supervised machine learning models (Linear Regression and k-nearest neighbors) and neural network model were unsuccessful (accuray scores < 0.1) in predicting dissolved methylmercury concentrations given input data (temperature, salinity, dissolved oxygen, nitrate) available from the [Global Ocean Biogeochemical Array](https://www.go-bgc.org/floats). 

## Getting Started

### Technologies Used 

* Python
* Pandas
* SciKit-learn
* Matplotlib

### Installing

* Clone this repository to your desktop.
* Cleaned datasets can be found in the **Data** Folder as CSV files.
* Model construction and parameters can be found in the **Models** folder.

### Data Sources

Agather, Alison M., et al. "US GEOTRACES: Distribution of Mercury Species in the Western Arctic Ocean." American Geophysical Union 2016 (2016): CT34B-0184. [https://www.bco-dmo.org/dataset/738136](https://www.bco-dmo.org/dataset/738136)

Bowman, Katlin L., et al. "Mercury in the North Atlantic Ocean: The US GEOTRACES zonal and meridional sections." Deep Sea Research Part II: Topical Studies in Oceanography 116 (2015): 251-261. [https://www.bco-dmo.org/dataset/3860](https://www.bco-dmo.org/dataset/3860) 

Bowman, Katlin L., et al. "Distribution of mercury species across a zonal section of the eastern tropical South Pacific Ocean (US GEOTRACES GP16)." Marine Chemistry 186 (2016): 156-166. [https://www.bco-dmo.org/dataset/643494](https://www.bco-dmo.org/dataset/643494)

Munson, Kathleen M., et al. "Mercury species concentrations and fluxes in the Central Tropical Pacific Ocean." Global Biogeochemical Cycles 29.5 (2015): 656-676.[https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015GB005120](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015GB005120)



## Author

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)
