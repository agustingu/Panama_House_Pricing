<img src='https://user-images.githubusercontent.com/54486202/199816336-e16ea740-ae0c-4128-8633-0ded391a411c.png' width=300/>
# Requirements:
Create a virtual environment with the dependencies in the requirements.txt file.
# Motivation

There is no existing data or tools to predict apartment pricing in Latin America which makes the development of housing policies very challenging. In this repository, I developed a data scraper to get apartment pricing information in Panama City (area, number of bathrooms, bedrooms, parking, location). This project will later scale to include other countries in the region as well as transportation networks.

## Objective
Assess the house pricing behavior in the Latin American Region to contribute in the development of housing policy for the benefit of communities considering:
- Area
- Years of construction 
- Mobility 
- Accessibility 
- Real-estate classification (low, medium, upper, luxury) 
- Services (electricity, water, garbage management, etc)

## Products:
- [Panama Add Data Scraper](https://github.com/agustingu/Panama_House_Pricing/blob/main/data_scraping.ipynb): Uses a web driver to extract apartments on sale in Panama City and export data to . a CSV file.
- [Data Preprosessing](https://github.com/agustingu/Panama_House_Pricing/blob/main/data_preprocessing.ipynb): Handles outliers, missing data, data scaling, normalization, etc

### Machine Learning algorithms evaluation
- [Regression](https://github.com/agustingu/Panama_House_Pricing/blob/main/Regression.ipynb)
- [Random Forest](https://github.com/agustingu/Panama_House_Pricing/blob/main/Random_Forest.ipynb)
- [ANN](https://github.com/agustingu/Panama_House_Pricing/blob/main/ANN.ipynb)
- Soon to evaluate XG-Boost
## Next Steps:
Get transportation network data and match it with apartment locations.

