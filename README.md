# 🏭🌱 CO<sub>2</sub> emissions over the past 50 years

This repository contains an exploratory data analysis of carbon dioxide emissions over the last 50 years using Python. 

## Table of content
 - [Intro](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Introduction)
 - [Goal](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Goal)
 - [Project overview](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Project-Overview)
 - [Dependencies](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Dependencies)
 - [Technical skills](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Technical-skills)
 - [Dataset](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Data-set)
 - [Data loading](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Data-loading)
 - [Data cleaning](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Data-cleaning)
 - [Data exploration](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Data-exploration)
 - [Data visualization](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Data-visualization)
 - [Insights](https://github.com/herrerovir/Python-co2-emissions/blob/main/README.md#Insights)

## Introduction
Carbon dioxide (CO<sub>2</sub>) is a colorless, odorless, non-poisonous gas formed by the combustion of carbon and is considered a greenhouse gas. Greenhouse gases absorb infrared radiation and emit it back to Earth, increasing the temperature of the Earth's surface. This is known as the greenhouse effect. 

Emissions are the release of greenhouse gases into the atmosphere over a given area and time period. Carbon dioxide emissions or CO<sub>2</sub> emissions are emissions from the combustion of fossil fuels (coal, oil and gas) and the manufacture of cement.

Carbon dioxide emissions are the main cause of global warming.  Since the industrial revolution, the burning of fossil fuels has increased, which is directly correlated with the increase of carbon dioxide levels in the atmosphere and, therefore, with the rapid increase of global warming.

## Goal
The main objective of this project is to conduct an exploratory analysis of carbon dioxide emissions over the last 50 years to discover valuable information about carbon emissions and the factors that influence them. 

Through data exploration and analysis, it is expected to find answers to the following key points:

* Evolution of CO<sub>2</sub> emissions by year
* Evolution of CO<sub>2</sub> emissions by continent
* Main CO<sub>2</sub> emitters
* Main source of CO<sub>2</sub> emissions
* Factors influencing (positively or negatively) on CO<sub>2</sub> emissions

## Project overview
1. Data loading
2. Data cleaning
3. Data analysis
4. Insights

## Dependencies
The following tools are required to carry out this project:

* Python 3
* Jupyter Notebooks
* Python libraries: 
    - Numpy
    - Pandas
    - Matplotlib.pyplot
    - Seaborn

## Technical skills
Throughout the implementation of this project, the following skills were applied: 

* Data loading
* Data cleaning
* Data exploration
* Data analysis
* Data visualization

## Dataset
The dataset used for this analysis is a CSV file which can be found uploaded in this repository as co2-emissions-dataset.

The dataset consists of:
* 46523 entries
* 74 columns

## Data loading
The CSV dataset is loaded into Jupyter Notebooks as a Pandas DataFrame. 

## Data cleaning
Once the data is loaded, it must undergo a cleaning and preprocessing phase. This part of the analysis is essential and critical, as a clean and normalized data set will ensure data integrity and reliability. 

The cleaning workflow includes: remove and rename columns, filter data by year, change data types, and remove null and duplicated values.

## Data exploration
To obtain useful information from this dataset, an in-depth exploratory analysis was carried out. The dataset was analyzed in a univariate and bivariate basis.

Univariate analysis involved analyzing each variable in the dataset separately.

The bivariate analysis consisted of examining two different variables to determine whether there is a dependence or relationship between them.

## Data visualization
Data visualization plays a crucial role in data analysis, as it is the stage at which the conclusions drawn from the analysis are effectively communicated.

This stage focuses on creating visual representations of the insights gained during the analysis. The Python libraries Matplotlib and Seaborn were used for this purpose.

## Insights

The main goal of this project is to explore the CO<sub>2</sub> dataset to find insightful data on carbon dioxide emissions, their evolution over the last 50 years and the factors influencing them.

* __2021 the year with the highest CO<sub>2</sub> emissions__

Through this analysis, it was found that carbon dioxide emissions have been increasing over the last 50 years, with the year 2021 being the year of the highest CO<sub>2</sub> emissions. 

![Distribution of carbon dioxide emissions over the last 50 years](https://github.com/user-attachments/assets/d61d55ac-0494-428a-a6c9-af29a2dfa6fc)

* __Asia was the continent that emitted most CO<sub>2</sub>__

The continent that has produced the most CO<sub>2</sub> emissions over the last 50 years has been Asia, followed by Europe and North America. Since 1990, Europe has decreased its CO<sub>2</sub>  emissions, while North America has kept them stable and Asia has increased them dramatically. For this reason, Asia is the continent with the highest carbon dioxide emissions. Before 1990, Europe was the continent that emitted the most CO<sub>2</sub>.

![Carbon dioxide emissions by continent in the last 50 years](https://github.com/user-attachments/assets/9558cdfa-b354-4253-ad9f-d560bce374f7)

![Evolution of carbon dioxide emission by continent in the last 50 years](https://github.com/user-attachments/assets/deda5ef4-33a3-47e6-850b-8c9a242d3343)

* __The U.S. is the country that has emitted the most CO<sub>2</sub> in the last 50 years.__

The United States is the country that has emitted the most CO<sub>2</sub> in the last 50 years. While the U.S. has decreased its emission since 2008, China, on the contrary, has exponentially increased its emissions, becoming the top CO<sub>2</sub> emitter in 2021. On the other hand, Germany has been slowly decreasing its emission since 1990 to reach its lowest point in 2020.

![World largest carbon dioxide emitters in the last 50 years](https://github.com/user-attachments/assets/05fbcf08-7b6f-4d3b-bbda-7e7b30e6dd77)

![U S  emissions in the last 50 years](https://github.com/user-attachments/assets/a4cd4ba3-3ab9-427f-913a-f31cbe162fb4)

![China emissions in the last 50 years](https://github.com/user-attachments/assets/3b0e49e6-556d-4ab0-bad7-3700ee75c0e3)

![Germany emissions in the last 50 years](https://github.com/user-attachments/assets/7dad55d5-146d-41f1-82ca-1bdaa9a5204b)

* __Coal is the main source of CO<sub>2</sub> emissions__

Coal is the main source of CO<sub>2</sub> emissions, followed by oil and gas. Since 2000, coal emissions have increased dramatically. This is due to increased emissions in China, which mainly uses coal as fuel. 

The main source of CO<sub>2</sub> emissions in the United States is oil and coal, while in China it is mainly coal, followed by a high amount of emissions from land use change. This is easily explained by the country's development and the deforestation and construction of new cities. Germany, as well as the United States, emits CO<sub>2</sub> mainly through coal and oil. It should not be forgotten that land use change in Germany is negative, which means that CO<sub>2</sub> from the atmosphere is captured and removed, thus reducing the amount of CO<sub>2</sub> in the atmosphere.

![Evolution of carbon dioxide emission by source over the last 50 years](https://github.com/user-attachments/assets/164e9bfc-3de9-4be2-8e32-37d328f43d33)

![U S  sources of emissions](https://github.com/user-attachments/assets/7f12e3cf-4469-4d2b-aab3-a6091afbf8b3)

![China sources of emissions](https://github.com/user-attachments/assets/81ae2119-6342-4423-99a8-f732a1fdb3ce)

![Germany sources of emissions](https://github.com/user-attachments/assets/1b9b0e9f-4d18-4c34-9b6f-b7f514d56fa8)

* __Land use change emissions__

Land plays an important role in the global cycles of greenhouse gases such as carbon dioxide. Land use activities can lead to emissions of carbon dioxide into the atmosphere or its removal from the atmosphere. Positive emissions mean that carbon dioxide is emitted into the atmosphere, while negative emissions mean that carbon dioxide is captured and removed from the atmosphere.

The countries that contributed positively, i.e., emitted CO<sub>2</sub> into the atmosphere, through land use change were Brazil, Indonesia and China. On the other hand, the countries that contributed negatively, i.e. removed CO<sub>2</sub> from the atmosphere, were Italy, Poland and France. This is due to environmental policies in the European Union and the commitment to reduce carbon dioxide emissions into the atmosphere. 

![Positive land use change emissions](https://github.com/user-attachments/assets/fb6e1ecc-7753-44e2-975c-6d50465992c4)

![Negative land use change emissions](https://github.com/user-attachments/assets/3298ec55-e9e4-47a9-92a5-7e599e36994a)

* __GDP and population correlations__

During this study it was found that GDP has a strong positive correlation with total CO<sub>2</sub> emissions. Also, population has a moderate correlation with CO<sub>2</sub> total emissions.

![Correlations GDP and total emissions](https://github.com/user-attachments/assets/8ccac41a-4d21-4f48-911e-30a0a2deef78)

* __Sources of CO<sub>2</sub> emissions correlations__

During this study it was found that coal, oil, gas, and other industries have a high correlation with the total emission of CO<sub>2</sub>.

![Correlation sources vs total emissions](https://github.com/user-attachments/assets/6ddda813-9bb5-4bd0-b1e5-aa0fdf464829)

