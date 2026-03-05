# Office Building Operation Optimization

This project analyzes sensor data from a smart office building to understand occupant behavior and its impact on energy consumption.

## Project Goal
The goal is to identify patterns in building usage and detect situations of energy waste (for example lights on when no occupants are present).

## Dataset
The dataset contains sensor data collected over one year (2013) from a university office building in Vienna.  
The data includes:

- Occupancy data
- Window state
- Lighting usage
- Energy consumption (plug loads)
- Indoor temperature and humidity
- Outdoor weather conditions

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Data Processing
The project includes several preprocessing steps:
- Integration of multiple CSV data sources
- Timestamp conversion and time-series alignment
- Handling missing values using interpolation and forward filling
- Aggregation of variables (total occupancy, lights usage, energy consumption)

These steps create a clean dataset suitable for analysis and modeling. :contentReference[oaicite:0]{index=0}

## Analysis
Exploratory data analysis was used to identify relationships between variables such as:

- occupancy vs energy consumption
- lighting vs solar radiation
- window usage vs outdoor temperature

Correlation analysis showed that higher occupancy generally leads to higher energy consumption. :contentReference[oaicite:1]{index=1}

## Modeling
Machine learning techniques were used to analyze building behavior:

- Clustering (K-Means) to identify different energy usage patterns
- Feature selection methods (Lasso, RFE)
- Predictive models such as Random Forest for energy consumption estimation

Random Forest produced the most accurate results for predicting energy consumption. :contentReference[oaicite:2]{index=2}

## Results
The analysis revealed several important insights:

- Energy consumption strongly depends on occupant presence.
- Lighting represents one of the largest sources of energy waste.
- Automated control systems could significantly reduce energy losses.

## Author
Ana-Maria Oneț  
Technical University of Cluj-Napoca  
Automation and Applied Informatics
