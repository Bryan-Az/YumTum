# YumTum
A Food Delivery like App for CMPE 256

*Sourced from* [Dataset Link](https://www.kaggle.com/datasets/mrmorj/restaurant-recommendation-challenge/code) (Kaggle Datasets)

*Test it out!* [Simulated Run Environment](https://www.kaggle.com/bryambz/yumtum) (Kaggle Code)

## Overview of the proposed project structure:
```markdown

restaurant-recommendation-system/
│
├── docs/ # Project documentation
│ ├── project_description.pdf # Detailed project overview and problem statement
│ └── kdd_process.pdf # Documentation of the KDD process applied
│
├── data/ # Data storage
│ ├── raw/ # Unprocessed data
│ │ ├── orders.csv # simulated orders from customers
│ │ ├── test_customers.csv # test & train : simulated customer profile data
| | ├── test_0.zip # test & train : the full test dataset (a zip of a csv for memory saving)
| | ├── test_1.zip
| | ├── test_locations.csv # test & train: simulated customer locations
| | ├── train_customers.csv
| | ├── train_0.zip (a zip of a csv for memory saving)
| | ├── train_1.zip (a zip of a csv for memory saving)
| | ├── train_2.zip (a zip of a csv for memory saving)
| | ├── train_3.zip (a zip of a csv for memory saving)
| | ├── train_4.zip (a zip of a csv for memory saving)
| | ├── train_5.zip (a zip of a csv for memory saving)
| | ├── train_6.zip (a zip of a csv for memory saving)
| | ├── train_7.zip (a zip of a csv for memory saving)
| | ├── train_locations.csv
| | ├── vendors.csv # simulated restaurant vendor information
│ │ └── VariableDefinitions.txt # data dictionary
│ │
│ ├── processed/ # Processed and cleaned data
│ │ ├── customer_data_processed.csv # **TO-DO**
│ │ ├── location_data_processed.csv # **TO-DO**
│ │ └── restaurant_data_processed.csv # **TO-DO**
│ │
│ └── masked/ # Masked data for security
│ ├── customer_data_masked.csv # **TO-DO**
│ ├── location_data_masked.csv # **TO-DO**
│ └── restaurant_data_masked.csv # **TO-DO**
│
├── notebooks/ # Jupyter notebooks for exploration and analysis
│ ├── data_preprocessing.ipynb # **TO-DO**
│ ├── exploratory_analysis.ipynb # **TO-DO**
│ └── model_development.ipynb # **TO-DO**
│
├── src/ # Source code # **TO-DO**
│ ├── data_preprocessing/ # Scripts for data preprocessing
│ ├── model/ # Machine learning models
│ └── utils/ # Utility scripts
│
├── tests/ # Test cases # **TO-DO**
│ └── test_data_processing.py
│
├── requirements.txt # Project dependencies # **TO-DO**
└── README.md # Project README with setup and run instructions
```
