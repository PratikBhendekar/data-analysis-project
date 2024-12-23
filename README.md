# Data Analysis Project

This project performs data analysis on an Excel file containing details about user sessions, orders, and cooking sessions. It processes the data, generates visualizations, and outputs the results to an Excel file.

## Project Structure

data-analysis-project/ │ ├── data/ # Input data files (e.g., "Data set.xlsx") │ └── Data set.xlsx │ ├── scripts/ # Python scripts for data processing │ └── data_analysis.py # Main Python script for analysis │ ├── plots/ # Plot images saved during the analysis │ ├── rating_plot.png │ ├── top_dishes_plot.png │ └── location_plot.png │ ├── output/ # Output files, including Excel reports │ └── output_data.xlsx │ └── README.md # Project documentation

## Requirements

To run this project, you'll need the following Python libraries:

- `pandas`: Used for data manipulation and analysis.
- `matplotlib`: Used for generating static, animated, and interactive visualizations.
- `seaborn`: Used for making statistical graphics in Python.
- `xlsxwriter`: Used to write Excel files with added features such as charts.

You can install these libraries by running:

```bash
pip install pandas matplotlib seaborn xlsxwriter

python scripts/data_analysis.py or using Jupyter notebook you want install it and keep input file and script in same folder then run it 
