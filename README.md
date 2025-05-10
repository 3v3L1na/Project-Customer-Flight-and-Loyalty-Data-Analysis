# Customer Flight and Loyalty Data Analysis

This project presents an Exploratory Data Analysis (EDA) and data preprocessing workflow applied to customer flight activity and loyalty history datasets. The notebook guides you through loading the necessary libraries, merging datasets, exploring data quality, and visualizing key aspects of the data. 

Although the analysis is preliminary, it lays a solid foundation for building more advanced models and deriving insights. Our primary focus was to merge two distinct datasets, assess data quality, and visualize key aspects to gain initial insights. We believe that this groundwork is essential for building sophisticated models and uncovering deeper patterns.

## Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Analysis Methodology](#analysis-methodology)
- [Key Libraries and Tools](#key-libraries-and-tools)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results and Visualizations](#results-and-visualizations)


## Overview

This repository contains a Jupyter Notebook (`bda_module_3_final_evaluation_evelina.ipynb`) that demonstrates the following steps:

- **Downloading and Importing Libraries:** The first stage includes loading libraries for data processing, visualization, and statistical analysis. For example, as seen in the first code cell, libraries such as Pandas, NumPy, Seaborn, Matplotlib, and several scikit-learn modules for imputation are used.

- **Merging Datasets:** The notebook reads two CSV files - one for flight activity and one for loyalty history - and merges them into a single DataFrame. This is outlined in the "STAGE 1. MERGING THE TWO DATAFRAMES" markdown cell.

- **Exploratory Data Analysis (EDA):** Subsequent stages perform data inspections by checking columns, managing null values, and visualizing data distributions. For an example of the detailed EDA stages, please see the markdown cell titled "STAGE 3. EXPLORATORY DATA ANALYSIS (EDA)".

## Dataset Description

The analysis uses two primary datasets:
- **Customer Flight Activity:** This dataset provided us with detailed information concerning flight bookings, companion details, flight frequencies, and other travel-related data.
- 
- **Customer Loyalty History:** This dataset illuminated customer demographics, loyalty program engagement, point accumulation, and redemption records.

## Analysis Methodology

1. **Data Import and Library Loading:**  
   All necessary libraries for data manipulation and visualization are imported in the first stage.

2. **Unveiling the Datasets:**  
   The CSV files are read using Pandas. For instance, the notebook reads the datasets as shown in the code cell where `pd.read_csv` is used.

3. **Data Inspection and Preprocessing:**  
   We proceeded with a thorough inspection of the DataFrame structures, merging the two datasets into a unified view. We meticulously identified and addressed null values using diverse imputation techniques, ensuring data integrity.

4. **Visualization:**  
   A wide array of visualizations such as histograms, pie charts, box plots, scatterplots, and violin plots are generated to illustrate the distribution of key metrics (e.g., cancellation dates and salary distributions). These graphs are created using Matplotlib and Seaborn, accompanied by best practices for scientific plotting, ensuring both clarity and precision.

5. **Statistical Analysis (Planned):**  
   While further statistically driven insights are hinted at, the notebook sets a preparatory foundation for these analyses. It’s convenient to underline that our current  data analysis is of a primarily exploratory nature, yet we have laid the foundation for future statistical investigations, including the application of chi-square tests and t-tests.

## Key Libraries and Tools

- **Pandas & NumPy:** Essential for data manipulation and processing.
- **Matplotlib & Seaborn:** Our instruments for creating insightful visualizations.
- **Scikit-Learn:** For various imputation techniques (Simple, Iterative, and KNN Imputer).
- **SciPy:** For performing statistical tests related to data distributions and hypothesis testing.

## Project Structure

```
├── bda_module_3_final_evaluation_evelina.ipynb   # Main Jupyter Notebook with analysis
├── Customer Flight Activity.csv                   # Flight activity dataset
└── Customer Loyalty History.csv                   # Loyalty history dataset
```

## Usage

1. **Clone the Repository:**
   ```
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Dependencies:**  
   Ensure you have Python 3.8+ installed along with the required packages. You can install all necessary packages via:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

3. **Follow Our Steps:**  
   Open `bda_module_3_final_evaluation_evelina.ipynb` in Jupyter Notebook or JupyterLab and execute the cells in sequence to reproduce the analysis.

## Results and Visualizations

The notebook features several visualizations including:
- Histograms of key variables (e.g., cancellation dates, salary distributions)
- Preliminary scatter or distribution plots for merged data insights

These visualizations are designed following a scientific theme to ensure clarity and precision:
- **Size & Layout:** Figures are plotted with large sizes (e.g., `plt.subplots(figsize=(9, 6))`) and adjusted margins.
- **Colors & Typography:** We utilized a modern color palette and typography guidelines that emphasize clarity and contrast, while they simultaneously enhance readability. 

## Reflections and discoveries 

Our preliminary analysis has enabled us to:
- Successfully merge disparate datasets into a cohesive DataFrame
- Gain initial insights into data distributions and potential relationships.

## The path ahead 

We plan to further our analysis by:
* Conducting in-depth statistical tests to validate hypotheses.
* Developing predictive models to forecast customer behavior.
* Exploring additional visualizations to uncover deeper patterns.
