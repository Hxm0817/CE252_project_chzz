# CE252 Project Code Description

Team 4
Group Member: Cheryl Chen, Xuanmian He, Jinglei Zeng, Yubo Zhang

## Directory structure
```
├── source_data
│   ├── hhpub.csv: Household-level survey data (raw)
│   ├── vehpub.csv: Veh-level survey data (raw)
│   ├── Strategy0_CPM.csv: Processed data (pilot pricing strategy, containing the features for VMT regression)
│   ├── Strategy1_CPM.csv: Processed data (vehicle-type-differentiated strategy)
│   ├── Strategy2_CPM.csv: Processed data (income-differentiated strategy)
│   ├── Strategy3_CPM.csv: Processed data (area-specific strategy)
├── data_description.ipynb: Process raw data from the national household travel survey
├── DataPreprocessing_strategy1_2.ipynb: Calculate Cost Per Mile (CPM) for strategy 1 and 2
├── DataPreprocessing_strategy3.ipynb: Calculate Cost Per Mile (CPM) for strategy 3
├── numerical_experiment.ipynb: Regression, elasticity and comparison analysis
```


