## Project Title

**Diamond Price Analysis using Exploratory Data Analysis (EDA)**

## Project Overview

This project analyzes the factors that influence diamond prices. Exploratory Data Analysis (EDA) is performed to clean the dataset, analyze numerical and categorical features, detect outliers, calculate statistical measures, and visualize relationships between diamond features and price.

The main goal is to understand how characteristics such as **carat, cut, color, and clarity** are related to diamond prices.

## Dataset Information

**Dataset:** Diamonds Dataset

**Kaggle Dataset Link:**https://www.kaggle.com/datasets/shivam2503/diamonds

The dataset contains information about diamonds, including:

* Carat
* Cut
* Color
* Clarity
* Depth
* Table
* Price
* X, Y, and Z dimensions

## Technologies Used

* **Python**
* **Google Colab**
* **Pandas** – Data cleaning and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization

## Installation Steps

Install the required libraries using:

```bash
pip install pandas numpy matplotlib
```

If you are using Google Colab, these libraries are generally available by default.

## How to Run

1. Download the Diamonds dataset from Kaggle.
2. Open **Google Colab**.
3. Upload the `diamonds.csv` file.
4. Import the required Python libraries.
5. Load the dataset using Pandas.
6. Run the notebook cells step by step.
7. Perform data cleaning, statistical analysis, outlier detection, correlation analysis, and visualization.
8. Review the results and business insights.

## Project Structure

```text
Diamond-Price-Analysis/
│
├── diamonds.csv
├── Diamond_Price_Analysis.ipynb
└── README.md
```

## Results

The analysis provided the following results:

* Missing values and duplicate records were checked and handled.
* Outliers in diamond prices were detected using the IQR method.
* Statistical measures such as mean, median, mode, variance, and standard deviation were calculated.
* Numerical and categorical features were analyzed.
* Correlation analysis was performed to identify relationships between numerical variables.
* Bar charts, histograms, scatter plots, and box plots were created.
* Carat was observed to have an important relationship with diamond price.
* Larger diamonds generally tend to have higher prices.

## Author Details

**Name:** Vinnakota  Yashaswi 

