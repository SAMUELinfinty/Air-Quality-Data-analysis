# Air Pollution Analysis (India - AQI Trends)

This project analyzes air quality data to understand trends in the Air Quality Index (AQI) and various pollutants across India.

## Project Structure
⦁	`Data/`: Contains the dataset used for analysis (`final\_dataset.csv`).
⦁	`Plots/`: Stores generated visualizations and plots from the analysis.
⦁	`main.ipynb`: The primary Jupyter Notebook containing the data cleaning, analysis, and visualization code.

##Dataset
The analysis uses `final\_dataset.csv`, which includes daily records with the following features:
⦁	Temporal: Date, Month, Year
⦁	Pollutants: PM2.5, PM10, NO2, SO2, CO, Ozone
⦁	Metrics: AQI (Air Quality Index)
⦁	Other: Holidays Count, Days

## Analysis Keypoints
The notebook `main.ipynb` performs the following detailed analysis:
1.	Data Preprocessing:
⦁	Loading the dataset.
⦁	Handling null values and duplicates.
⦁	Feature Engineering (e.g., creating a `Full\_Date` column).
2.	Univariate Analysis:
⦁	Statistical summary of air quality parameters.
⦁	Histogram Charts to visualize the distribution of AQI and other metrics.
3.	Visualization & Trends:
⦁	Correlation Heatmaps: To understand relationships between different pollutants and AQI.
⦁	Time Series Analysis (TSA): Analyzing Weekly and Monthly trends in air quality.

## Conclusion
The analysis clearly shows that air quality between 2021–2024 is primarily driven by particulate matter, especially PM10 and PM2.5, which have the strongest correlation with AQI and are responsible for almost all pollution spikes. Seasonal trends reveal a consistent cycle across all years: winter months experience the worst air quality due to stagnant atmospheric conditions, while monsoon months show the cleanest air as rainfall naturally removes pollutants. Weekly trends confirm this pattern with high pollution during early and late-year weeks and cleaner air during mid-year periods.
Overall, the study confirms that particulate pollution and seasonal atmospheric behavior are the dominant factors shaping air quality in this region.

## Recommendations
Based on the EDA, the following actions can significantly improve air quality:
⦁	Focus on reducing PM10 & PM2.5, as they are the main AQI drivers.
⦁	Strengthen construction dust regulation, especially during dry months.
⦁	Implement stricter winter pollution management strategies.
⦁	Promote public transport and electric vehicles to reduce NO₂ spikes.
⦁	Increase industrial and emission monitoring during winter and post-monsoon.
⦁	Use public awareness campaigns to warn citizens during seasonal peak pollution periods.

## Prerequisites
To explore the analysis or run the notebook, ensure you have the following Python libraries installed:
⦁	pandas
⦁	numpy
⦁	matplotlib
⦁	seaborn

## Future Work
Although the project is complete, further extensions are possible:
⦁	Develop AQI prediction models (Random Forest, XGBoost, LSTM).
⦁	Build a dashboard for real-time visualization.
⦁	Analyze health impacts of pollutant exposure.
⦁	Forecast future pollution using ARIMA/Prophet models.
⦁	Implement geospatial analysis if location data becomes available.

## Usage
1.	Clone this repository or download the project files.
2.	Navigate to the project directory.
3.	Open `main.ipynb` using Jupyter Notebook or your preferred IDE (e.g., VS Code).
4.	Execute the cells to replicate the analysis and view the visualizations.
