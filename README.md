# Ford-car-price-prediction
An Exploratory Data Analysis (EDA) and data preprocessing pipeline built with Python to analyze and predict the market prices of used Ford vehicles using Pandas and Seaborn.
**GitHub Repository Description**
An Exploratory Data Analysis (EDA) and data preprocessing pipeline built with Python to analyze and predict the market prices of used Ford vehicles using Pandas and Seaborn.

# Ford Used Car Price Analysis

## Overview

This project focuses on Exploratory Data Analysis (EDA) and data preprocessing for a dataset of used Ford vehicles. The primary objective is to analyze the relationships between different car specifications and their selling prices, preparing the data for future machine learning model training.

## Dataset

The analysis uses the `ford.csv` dataset.

* **Dimensions:** The dataset contains 17,966 rows and 9 columns.


* **Data Quality:** The data is clean with zero missing or null values.


* **Target Variable:** `price`.


* **Features:**
* `model`

* `year`

* `transmission`

* `mileage`

* `fuelType`

* `tax`

* `mpg`

* `engineSize`




## Tech Stack

* **Language:** Python


* **Data Manipulation:** NumPy, Pandas


* **Data Visualization:** Seaborn, Matplotlib



## Project Workflow

* **Data Inspection:** Initial exploration of dataset shape, column data types, and statistical summaries.


* **Univariate Analysis:** Visualization of the `price` distribution using a histogram with a Kernel Density Estimate (KDE).


* **Bivariate & Correlation Analysis:**
* Computes a correlation matrix and visualizes it using a heatmap to identify linear relationships between numerical variables.


* Explores the impact of variables on `price` using scatterplots (e.g., `mileage` vs. `price`) and boxplots (e.g., `year`, `engineSize`, `transmission`, `tax`, and `fuelType` vs. `price`).




* **Data Splitting:** Separates the target variable (`y`) from the feature matrix (`X`) to prepare the dataset for predictive modeling.



## Setup & Installation

1. Clone this repository to your local machine.
2. Install the required Python dependencies:
```bash
pip install numpy pandas seaborn matplotlib

```


3. Ensure the `ford.csv` dataset is located in the same directory as the notebook.


4. Run the Jupyter Notebook to explore the visualizations and data pipeline.
