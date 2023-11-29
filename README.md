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
| | ├── test_0.zip # zipped for memory savingns
| | ├── train_0.zip 
| | ├── vendors.csv # simulated restaurant vendor information
│ │ └── VariableDefinitions.txt # data dictionary
│ │
│ ├── processed/ # Processed and cleaned data
│ │ ├── train_data_processed.csv # **TO-DO**
│ │ ├── test_data_processed.csv # **TO-DO**
│
│
├── notebooks/ # Jupyter notebooks for exploration and analysis
│ ├── data_preprocessing.ipynb
│ ├── exploratory_analysis.ipynb # **TO-DO**
│ └── model_development.ipynb
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
