# earthquake_damage_ml
This project contains the code to predict the damage grade of a building.



## Problem description
We're trying to predict the ordinal variable damage_grade, which represents a level of damage to the building that was hit by the earthquake. There are 3 grades of the damage:

    1 represents low damage
    2 represents a medium amount of damage
    3 represents almost complete destruction

<img src="img/nepal-quake-bm-2.jpg" width="500">

## Dataset

### Features
The dataset mainly consists of information on the buildings' structure and their legal ownership. Each row in the dataset represents a specific building in the region that was hit by Gorkha earthquake.

There are 39 columns in this dataset, where the building_id column is a unique and random identifier. The remaining 38 features are described in the section below. Categorical variables have been obfuscated random lowercase ascii characters. The appearance of the same character in distinct columns does not imply the same original value.







### Run
#### Programming Language:
- Python >=3.6

#### Dependencies:
- pandas
- numpy 
- plotly
- streamlit
- xgboost

