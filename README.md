# Airbnb Istanbul

- Senih Berkay Akın - 26589
- Osman Arslan - 29127
- Ilgın Simay Özcan - 31099
- Deniz Gürleyen- 30919
- Zeynep Kılıçarslan - 28859
- Damla Aydın - 30825

## Project Description
This project explores a database from Kaggle, based on Airbnb. It is selected to analyze the prices of the properties in Istanbul. By exploring the dataset, our goal is to reveal what factors are driving pricing trends. The insights gained from data analysis will enable us to predict a comprehensive understanding of the Airbnb market in Istanbul.

![Alt Text]figures/map_heatmap.png

## Table of Contents
- [Project Description](#project-description)
- [Data Source](#data-source)
- [Features](#features)
- [Installation](#installation)
- [Contribution](#contribution)

## Data Source
Source: <a href="http://insideairbnb.com/get-the-data">InsiderAirbnb</a>

## Features
1. **Data Exploration**: The selected Airbnb dataset from Kaggle will be explored by analyzing various attributes and features related to Airbnb listings in Istanbul. We will examine factors such as location, access to public transportation, entertainment options (nightlife, museums), crime rates, pricing, property types, and reviews.

2. **Analysis of Pricing Trends**: This analysis will focus on pricing trends in the Airbnb market in Istanbul. We will identify variations caused by factors such as location, property attributes (number of rooms, number of guests), and other factors identified during the data exploration phase. These insights will assist prediction of the prices of the properties.

3. **Location**: Different neighborhoods and districts in Istanbul will be analyzed based on Airbnb listings. The districts will be labeled according to factors such as crime rates and the availability of facilities will be checked. We will examine factors associated with location, such as access to public transportation and entertainment options, to identify their impact on pricing.

4. **Properties of the Rental**: This analysis will explore the relationship between property types and pricing based on the Airbnb dataset. Additionally, we will investigate the relationship between pricing and factors such as the type of house/room. By examining these factors, we aim to identify trends that will help us understand the pricing based on the property's attributes.

5. **Data Visualization**: The findings from our investigation on the Kaggle dataset will be visualized using various techniques. Visualization will aid in presenting the results in a clear and visually appealing manner. It will also help us the results and understand the relationship between the factors considered and pricing while hypothesis testing.

## Installation

The repo can be cloned by the code below:

- Clone the repo: `https://github.com/senihberkay/Airbnb-Istanbul-CS210-TermProject.git`

</br>

To use this project, you need to install and import the following libraries:

</br>

For data manipulation, analysis and visualization
```bash
pip install geopandas
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import matplotlib.image as mpimg
%matplotlib inline
import seaborn as sns
import geopandas as gpd
```

For converting Unicode characters to ASCII for hadling with Turkish characters
```bash
from unidecode import unidecode
```

For creating interactive maps and visualization
```bash
pip install folium
import folium
from folium import plugins
from folium.plugins import HeatMap
```

For mathematical algorithms, functions and statistical tools 
```bash
from scipy import stats
```

For machine learning, data splitting, model training and evaluation and cross-validation 
```bash
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_squared_error, r2_score
from sklearn.model_selection import KFold, cross_val_score
```

## Contribution
We appreciate your interest in contributing to our project. We value contributions, collaboration, and involvement in the community. Your contribution could make the project even better. Whether you are reporting errors, suggesting new features, or offering code or documentation, we welcome your input.

**Types of Contributions:**
- **Bug reports**: If you encounter any problems or bugs while using our project, please let us know.
- **Feature requests**: If you have suggestions for new functions or improvements, please share them with us.
- **Code contribution**: If you feel confident diving into the source code,

 we invite you to add enhancements, bug fixes, or brand-new features.
- **Documentation Improvements**: Clear and comprehensive documentation is crucial. If you find areas that need clarification or have suggestions to improve our documentation, please let us know.
