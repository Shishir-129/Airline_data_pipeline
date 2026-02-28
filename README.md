# Airline Delay Analysis Pipeline

## Project Overview
This project analyzes airline delay patterns using a comprehensive dataset of flight delays. The analysis explores various delay causes, identifies airlines with the most delays, and examines seasonal trends in flight delays.

## Key Analyses
- **Delay Causes:** Analysis of carrier, weather, NAS (National Airspace System), security, and late aircraft delays
- **Carrier Performance:** Comparison of average delays and delay frequency across different airlines
- **Temporal Trends:** Monthly patterns and seasonal variations in flight delays
- **Delay Distribution:** Statistical examination of delay durations and outliers

## Visualizations
The notebook includes multiple visualizations:
- Correlation heatmap of delay factors
- Distribution histograms of arrival delays
- Bar plots comparing carrier performance
- Count plots for delayed flight frequency
- Box plots for statistical summaries of delay causes
- Line plots showing monthly delay trends
- Scatter plots examining relationships between delay factors

## Files
- `airline.ipynb` - Main analysis notebook
- `Airline_Delay_Cause.csv` - Original dataset : Link: https://www.kaggle.com/datasets/sriharshaeedala/airline-delay/data
- `cleaned_airline_data.csv` - Processed dataset with cleaned data and derived features

## Dataset
The dataset contains information about flight delays including:
- Carrier information
- Arrival and departure delays
- Various delay causes (carrier, weather, NAS, security, late aircraft)
- Monthly and temporal data

### Dataset Source
**Original CSV File:** [Kaggle Link](https://www.kaggle.com/datasets/sriharshaeedala/airline-delay/data)

## Technologies Used
- Python
- Pandas - Data manipulation and analysis
- NumPy - Numerical operations
- Matplotlib - Plotting and visualization
- Seaborn - Statistical data visualization

## Key Findings (see this in detail in the notebook file)
- Southwest Airlines (WN) has the highest number of delayed flights
- Late aircraft delay is the most significant contributing factor
- Summer months (June-August) show peak delay periods
- SkyWest Airlines (OO) has frequent delays but with lower severity

## Setup and Usage
1. Ensure you have the required libraries installed
2. Place `Airline_Delay_Cause.csv` in the project directory
3. Run the notebook cells sequentially to reproduce the analysis
