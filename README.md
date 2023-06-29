Data Breach Analysis

This repository contains a Python script for analyzing data breaches and an interactive dashboard created using Power BI. The script utilizes the pandas library for data manipulation, matplotlib and seaborn libraries for data visualization. The analysis aims to provide insights into breached organization types, breach methods, and the number of breaches over the years.
Project Timeline

    Start Date: June 27, 2023
    End Date: June 29, 2023

Data Source

The data for this analysis was obtained from Kaggle. The 'Data breacher.csv' file contains information about breached organizations, including the entity name, year of breach, number of compromised records, organization type, breach method, and sources from which the data was collected.
Prerequisites

    Python 3.x
    pandas
    matplotlib
    seaborn

Getting Started

    Clone the repository:

bash

git clone https://github.com/mebatesfaye05/data-breach-analysis.git

    Navigate to the project directory:

bash

cd data-breach-analysis

    Install the required dependencies:

pip install pandas matplotlib seaborn

    Place the 'Data breacher.csv' file in the project directory.

Usage

    Run the Python script to perform the data analysis:

python data_analysis.py

    Launch the Power BI application.

    Open the interactive dashboard file located in the 'power-bi-dashboard' folder.

Data Analysis (Python Script)

The Python script performs the following steps:

    Data Loading:
        The 'Data breacher.csv' file is loaded into a pandas DataFrame using the pd.read_csv() function.

    Data Cleaning:
        Missing values are handled by dropping rows with missing values using the df.dropna() function.
        Duplicate rows are removed using the df.drop_duplicates() function.

    Data Analysis:
        The script calculates the frequency of breached organization types and breach methods.
        It also groups the data by year and calculates the number of attacks for each year.
        The results are displayed, including the methods used for attacks and the total number of breaches for each year.

Interactive Dashboard (Power BI)

The interactive dashboard provides a visually appealing representation of the data analysis. It includes the following visualizations:

    Bar charts showcasing the frequency of breached organization types and breach methods.
    Line chart displaying the number of attacks for each year.
    Tables presenting the methods used for attacks and the total number of breaches for each year.

To interact with the dashboard, open the Power BI application and navigate to the 'power-bi-dashboard' folder. Open the interactive dashboard file, and explore the various visualizations to gain insights into the data.
License

This project is made by Meba Tesfaye
