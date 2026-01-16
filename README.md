# Stellar Luminosity Analysis

Exploring the relationship between stellar temperature, radius, and brightness using data science techniques.

This project analyzes the relationship between stellar luminosity, temperature and radius using an educational astronomy dataset. By applying data cleaning, visualization, and basic statistical analysis, this project demonstrates how physical properties of stars influence their brightness, inspired by the Hertzsprung-Russell (HR) diagram.

# Dataset
Source: Stars Dataset from Kaggle
https://www.kaggle.com/datasets/waqi786/stars-dataset

Features include:

  - Star Name  
  - Distance (light years)  
  - Luminosity (relative to the Sun)  
  - Radius (relative to the Sun)  
  - Temperature (Kelvin)  
  - Spectral Class  

The dataset was cleaned by removing missing values and non-physical values such as zero or negative values for temperatures and luminosities.

# Analysis 

1. Radius vs Luminosity

Visualized how stellar size affects brightness. The analysis shows that larger stars tend to have higher luminosities, which explains why some cooler stars can still be very bright.

2. Temperature vs Luminosity

Explored the relationship between surface temperature and luminosity using an HR diagram style visualization. A general positive trend was observed, where hotter stars are generally more luminous.

3. Correlation Analysis

Radius vs log(Luminosity): 0.461

Temperature vs log(Luminosity): 0.480

Both correlations are moderate and positive. Temperature has a slightly stronger relationship with luminosity than radius in this dataset. Due to moderate correlation coefficients, neither factor alone explains luminosity completely.

# Key Findings

- Stellar Luminosity depends on both temperature and radius.
- The HR diagram shows a general trend in accordance with main-sequence stellar behaviour.
- The moderate correlation highlights influence of other factors such as spectral class and evolutionary stage.
- The spread of data points shows diversity in stellar properties. 

# Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
