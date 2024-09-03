# Real-Time Data Dashboard

## Overview

The **Real-Time Data Dashboard** is an interactive web application developed using Streamlit. It simulates and visualizes real-time data updates, providing a dynamic view of a dataset with various insights and visualizations.

## Features

- **Real-Time Simulation:** Simulates live data updates to create a near real-time experience.
- **Interactive Filters:** Filter data based on job roles.
- **Key Performance Indicators (KPIs):** Metrics such as average age, married count, and average account balance.
- **Interactive Charts:** Visualizations using density heatmaps and histograms.
- **Detailed Data View:** Tabular view of the filtered data.

## Requirements

To run this application, you need Python installed along with the following libraries:
- streamlit
- numpy
- pandas
- plotly

You can install these dependencies using pip:

```sh
pip install streamlit numpy pandas plotly
```

## Running the Application

1. **Save the Script:** Save the provided script as `app.py` or another preferred name.
2. **Open Terminal or Command Prompt:** Navigate to the directory where the script is saved.
3. **Run the Application:** Execute the following command to start the Streamlit server:

   ```sh
   streamlit run app.py
   ```

4. **View in Browser:** Streamlit will provide a local URL (typically `http://localhost:8501`) where you can view the application in your web browser.

## Script Details

- **Data Source:** The application reads data from a CSV file hosted on GitHub: `https://raw.githubusercontent.com/Lexie88rus/bank-marketing-analysis/master/bank.csv`.
- **Real-Time Simulation:** The `for` loop simulates real-time updates by modifying the 'age' and 'balance' columns in the dataset.
- **KPIs and Charts:** Displays key metrics and interactive charts for data insights.

## Usage

- **Select Job Role:** Use the dropdown menu to filter data based on job roles.
- **View KPIs:** See updated metrics such as average age, married count, and average account balance.
- **Interactive Charts:** Explore density heatmaps and histograms for data visualization.
- **Detailed Data View:** Review the filtered dataset in a tabular format.

