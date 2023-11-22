# YumTum
A Food Delivery like App for CMPE 256
Overview of the proposed project structure:

restaurant-recommendation-system/
│
├── docs/                               # Project documentation
│   ├── project_description.pdf         # Detailed project overview and problem statement
│   └── kdd_process.pdf                 # Documentation of the KDD process applied
│
├── data/                               # Data storage
│   ├── raw/                            # Unprocessed data
│   │   ├── customer_details.csv        # Customer details data
│   │   ├── location_details.csv        # Location details data
│   │   └── restaurant_details.csv      # Restaurant details data
│   │
│   ├── processed/                      # Processed and cleaned data
│   │   ├── customer_data_processed.csv
│   │   ├── location_data_processed.csv
│   │   └── restaurant_data_processed.csv
│   │
│   └── masked/                         # Masked data for security
│       ├── customer_data_masked.csv
│       ├── location_data_masked.csv
│       └── restaurant_data_masked.csv
│
├── notebooks/                          # Jupyter notebooks for exploration and analysis
│   ├── data_preprocessing.ipynb
│   ├── exploratory_analysis.ipynb
│   └── model_development.ipynb
│
├── src/                                # Source code
│   ├── data_preprocessing/             # Scripts for data preprocessing
│   ├── model/                          # Machine learning models
│   └── utils/                          # Utility scripts
│
├── tests/                              # Test cases
│   └── test_data_processing.py
│
├── requirements.txt                    # Project dependencies
└── README.md                           # Project README with setup and run instructions
