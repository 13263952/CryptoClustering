# Crypto Market Data Analysis

This repository contains code for analyzing crypto market data using various data analysis techniques. The code uses Python and several libraries, including Pandas, hvPlot, scikit-learn, and more.

## Installation

To run the code locally, you need to have Python installed on your machine. Additionally, you'll need to install the required libraries and dependencies.


## Usage

1. Clone the repository to your local machine.
2. Navigate to the repository's directory.
3. Ensure that the crypto market data CSV file is available in the `Resources` directory.
4. Run the `crypto_analysis.py` file to execute the code.
5. The output will be displayed in the console and visualized using line plots.

## Data

The code loads the crypto market data from a CSV file (`crypto_market_data.csv`). The data includes various price change percentages for different cryptocurrencies over different time periods.

## Code Structure

The code is structured into the following sections:

1. Importing the required libraries and dependencies.
2. Loading the data into a Pandas DataFrame.
3. Displaying sample data.
4. Generating summary statistics for the data.
5. Plotting the data using line plots.
6. Preparing the data by normalizing it using the `StandardScaler` module from scikit-learn.

## Results

The code provides various insights into the crypto market data, including summary statistics and visualizations of the price change percentages for different cryptocurrencies. Additionally, the data is preprocessed by standardizing it using the `StandardScaler` module. The visualizations are interactive, some sample visualizations of the data below. 


![Clusters](resources/clusters.png)
![Clusters_2](resources/clusters_2.png)
![Clusters_3](resources/clusters_3.png)
![Value_k](resources/Value_k.png)
![Value_k2](resources/Value_k2.png)
