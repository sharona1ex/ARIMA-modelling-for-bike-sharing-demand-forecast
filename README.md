# ARIMA-modelling-for-bike-sharing-demand-forecast
## Objective
ARIMA modelling for a bike rental company to forecast its demand.

## Project Scenario
A bike rental company is looking to improve its demand forecasting accuracy to optimize its fleet management and pricing strategy. They collect data on daily rental transactions and want to use it to predict future demand. 
The company aims to use the forecasts to determine the optimal number of bikes to keep in each station and to set dynamic pricing based on the predicted demand. Making these forecasts will enhance the company's logistic processes, help reduce costs, and maximize profits.

## Dataset
You can download the dataset folder in this repo. (This dataset is taken from [coursera](https://www.coursera.org/projects/showcase-forecast-bikeshare-demand-using-time-series-models-in-r))

## Data Visualiztion
I have used both Tableau and Python to visualize data. For prelimanary and quick analysis I use Tableau and for modelling related analysis I used Python.

View these Tableau charts to get a feel of the data,

### Bike users on each day
![cnt vs day](https://github.com/StarRider/ARIMA-modelling-for-bike-sharing-demand-forecast/assets/30108439/855ace30-bc2a-4246-8ba7-77652440f47b)

### Avergae monthly users for each month
![Screenshot 2024-02-09 132154](https://github.com/StarRider/ARIMA-modelling-for-bike-sharing-demand-forecast/assets/30108439/1e5e284d-43e2-46f2-ae9a-6cf759f149c8)

### Temperature vs Demand
![temp vs cnt](https://github.com/StarRider/ARIMA-modelling-for-bike-sharing-demand-forecast/assets/30108439/4e96c728-34e3-4468-8cca-1e4c76b6dc9d)


## Observations
1. This series has trend.
2. It has seasonality. (You can see a peak at both year's July's)
3. There are no outliers as per boxplot, but the series is noisy.
4. The variance is increasing.

**Checkout my Jupyter notebook on how I modelled ARIMA around this dataset.**



