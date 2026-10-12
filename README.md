# Used Cars Dataset Analysis

Exploratory Data Analysis (EDA) of **426,880 Craigslist vehicle listings** using Python, Pandas, Matplotlib, and Seaborn.

## Overview

This project explores a dataset of used-car listings to understand vehicle availability, pricing patterns, and relationships between vehicle characteristics.

The analysis includes data assessment, cleaning, exploratory analysis, and visualization.

## Dataset

**Source:** [Craigslist Cars and Trucks Dataset — Kaggle](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data)

The original dataset contains **426,880 records and 26 columns**, including:

- **Vehicle information:** Manufacturer, model, year, condition, and type
- **Technical attributes:** Fuel, transmission, cylinders, and odometer
- **Pricing:** Listed vehicle price
- **Location:** State, latitude, and longitude

The dataset is not included in this repository.

## Analysis Workflow

### 1. Data Assessment

The initial assessment identifies:

- Missing values across numerical and categorical attributes
- Invalid zero-price entries
- Inconsistent model-name capitalization
- Columns not required for the analysis
- Data types requiring conversion

### 2. Data Cleaning

The notebook applies the following preprocessing steps:

- Fills missing categorical values with `Unknown`
- Imputes missing numerical values using the median
- Replaces zero prices with the median of nonzero prices
- Converts vehicle years and posting dates to appropriate data types
- Standardizes vehicle model capitalization
- Removes unnecessary columns, including URLs and listing descriptions

These preprocessing choices support exploratory analysis but may affect calculated statistics, particularly average prices.

### 3. Exploratory Data Analysis

The analysis investigates:

- Most frequently listed manufacturers and models
- Distribution of vehicle conditions and listings by state
- Average prices across vehicle conditions and types
- Fuel-type distributions among popular manufacturers
- Relationships between vehicle prices and transmission, fuel type, and cylinder configuration

### 4. Data Visualization

The notebook uses bar charts, stacked bar charts, and other visualizations to present distributions and pricing comparisons.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## View the Analysis

**[Open the Jupyter Notebook](analysis.ipynb)**

The notebook contains the data cleaning steps, analysis code, and saved visualizations.

## Installation and Usage

**1. Clone the repository**

```bash
git clone https://github.com/asaazamaan/UsedCars_Dataset_Analysis.git
cd UsedCars_Dataset_Analysis
```

**2. Install the analysis dependencies**

```bash
pip install pandas numpy matplotlib seaborn notebook
```

**3. Download the dataset**

Download the dataset from the [Kaggle source](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data) and place `vehicles.csv` in the repository's root directory.

**4. Open the notebook**

```bash
jupyter notebook analysis.ipynb
```

Run the notebook cells in order to reproduce the analysis.

## Acknowledgments

- **Dataset:** [Craigslist Cars and Trucks Dataset](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data)
- **Inspiration:** [Netflix EDA Project](https://github.com/Mohamed2bdelaziz/Netflix_EDA/blob/main/Netflix__EDA.ipynb)
- **Course:** Developed as part of the **MLSC Data Science & Machine Learning Course**

## License

This repository includes an [Apache License 2.0](LICENSE).
