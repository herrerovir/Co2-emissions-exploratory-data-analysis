# 🗺️🌱 CO₂ Emissions Over the Past 50 Years

This repository contains an exploratory data analysis (EDA) of carbon dioxide (CO₂) emissions over the last 50 years using Python. The goal is to extract meaningful insights about the trends, sources, and drivers of CO₂ emissions worldwide.

## 📚 Table of Contents

- [Introduction](#introduction)
- [Goal](#goal)
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [How to Run the Project](#how-to-run-the-project)
- [Repository Structure](#repository-structure)
- [Technical Skills](#technical-skills)
- [Dataset](#dataset)
- [Data Loading](#data-loading)
- [Data Cleaning](#data-cleaning)
- [Data Exploration](#data-exploration)
- [Data Visualization](#data-visualization)
- [Key Insights](#key-insights)

## 📖 Introduction

CO₂ is a colorless, odorless gas that's a significant contributor to climate change. It's released during the burning of fossil fuels like coal, oil, and gas, and plays a major role in the greenhouse effect, which warms our planet.

Since the industrial revolution, human activities have significantly increased CO₂ levels in the atmosphere, directly contributing to global warming. This project uses data analysis to examine how CO₂ emissions have changed over time, identify major emitters, and understand the factors influencing these trends.

## 🎯 Goal

The primary objective of this project is to conduct an exploratory analysis of CO₂ emissions over the past 50 years to uncover valuable insights about emission trends and their influencing factors.

Key questions addressed include:

- How have CO₂ emissions evolved by year and continent?
- Which countries are the largest emitters?
- What are the primary sources of CO₂ emissions?
- How do factors like GDP and population influence CO₂ emissions?

## 🔍 Project Overview

The project is structured into four main phases:

1. **Data Loading**: Importing the dataset into Python.
2. **Data Cleaning**: Preparing the data for analysis by handling missing values, correcting data types, and filtering relevant information.
3. **Data Exploration**: Performing exploratory data analysis to identify patterns and relationships within the data.
4. **Insights**: Drawing conclusions and highlighting key findings from the analysis.

## 🛠️ Dependencies

To run this project, you'll need:

- Python 3
- Jupyter Notebooks (for interactive analysis)
- Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`

## 💻 How to Run the Project

1. **Clone the Repository**

   Start by cloning the repository to your local machine using the following command:

   ```shell
   git clone https://github.com/herrerovir/Co2-emissions-exploratory-data-analysis.git
   ```

   Change to the project directory:

   ```shell
   cd Co2-emissions-exploratory-data-analysis
   ```

2. **Install Dependencies**

   Install the required dependencies listed in the `requirements.txt`:

   ```shell
   pip install -r requirements.txt
   ```

   This will install all necessary libraries such as pandas, numpy, matplotlib, and seaborn.

3. **Run the Jupyter Notebook**

   After installing the dependencies, you can run the Jupyter notebook to perform the data analysis. To start the notebook, use the following command:

   ```shell
   jupyter notebook notebooks/EDA-co2-emissions.ipynb
   ```

## 📁 Repository Structure

```
Co2-emissions-exploratory-data-analysis
├── data/
│   ├── raw/
│   │   └── co2-emissions-dataset.csv          # Original dataset
│   └── processed/
│       └── co2-emissions-cleaned.csv          # Cleaned and preprocessed data
├── figures/
│   ├── co2-emissions-sources-heatmpa.png      # Sample visualization
│   ├── correlation-heatmap.png                # Charts of top CO₂-emitting countries
│   └── ...                                    # Additional plots from analysis
├── requirements.txt                           # Requirements file
├── notebooks/
│   └── EDA-co2-emissions.ipynb                # Jupyter notebook with the full analysis
└── README.md                                  # Project overview and documentation
```

## 🧠 Technical Skills

Throughout this project, the following skills were applied:

- Data loading and preprocessing
- Exploratory data analysis (EDA)
- Data visualization
- Statistical analysis

## 📊 Dataset

The dataset used for this analysis is a CSV file (`co2-emissions-dataset.csv`) containing:

- 46,523 entries
- 74 columns

## 📥 Data Loading

The dataset is loaded into a Pandas DataFrame using the following code:

```python
import pandas as pd

df = pd.read_csv("data/raw/co2-emissions-dataset.csv")
```

## 🧹 Data Cleaning

Data cleaning involves:

- Removing unnecessary or duplicate columns
- Renaming columns for clarity
- Filtering data by year
- Converting data types as needed
- Handling missing or null values

These steps ensure the dataset is ready for analysis.

## 🔍 Data Exploration

Exploratory data analysis (EDA) includes:

- **Univariate analysis**: Examining individual variables to understand their distribution and characteristics.
- **Bivariate analysis**: Investigating relationships between two variables to identify correlations or dependencies.

## 📈 Data Visualization

Data visualization is crucial for communicating insights. This project uses `matplotlib` and `seaborn` to create various plots, including:

- Line charts to show trends over time
- Bar charts for comparing emissions across countries and continents
- Heatmaps to visualize correlations between variables

## 💡 Key Insights

**2021 Was the Peak Year for CO₂ Emissions**
CO₂ emissions have been increasing for decades, and 2021 marked the highest level recorded in the last 50 years.

**Asia Is Now the Biggest Emitter**
Since around 1990, Asia has taken the lead in global CO₂ emissions. Europe has steadily reduced its emissions, North America has remained fairly consistent, but Asia’s numbers have increased sharply.

**The U.S. Has Emitted the Most Over Time** 
Looking at the last five decades, the United States is the top historical emitter. While emissions there have dropped since 2008, China’s output has skyrocketed — and by 2021, it had overtaken the U.S.

**Coal Is the Largest Source of Emissions**
Coal is by far the biggest contributor to CO₂ emissions, followed by oil and gas. China relies heavily on coal, while countries like the U.S. and Germany have a more mixed energy profile, using both coal and oil extensively.

**Land Use Makes a Big Difference**
Changes in land use — like deforestation or reforestation — can either increase or reduce emissions. Countries like Brazil and Indonesia are adding CO₂ through deforestation, while places like Italy and France are actually removing CO₂ thanks to greener land policies.

**GDP and Emissions Go Hand in Hand**
There’s a strong connection between how much a country produces economically (its GDP) and how much CO₂ it emits. In short: more production usually means more emissions.

**Population Matters Too (But Not as Much as GDP)**
Larger populations tend to emit more CO₂, but the correlation isn’t as strong as it is with economic activity. Still, it’s an important factor.
