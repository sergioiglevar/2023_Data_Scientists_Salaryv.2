Telework Ratio Analysis
Overview

This repository contains a Jupyter Notebook that analyzes the telework ratio across different countries based on a dataset of remote job postings. The primary goal of this analysis is to identify countries with the highest ratio of remote work opportunities and visualize the data through engaging graphical representations.
Table of Contents

    Technologies Used
    Dataset Description
    Key Features
    Analysis Steps
    Visualizations
    Usage
    Contributing
    License

Technologies Used

    Python
    Jupyter Notebook
    Pandas
    Matplotlib
    Seaborn

Dataset Description

The dataset used for this analysis includes various remote job postings and includes the following key columns:

    company_location: The geographic location of the company.
    employment_type: The type of employment (e.g., remote, part-time, full-time).
    remote_ratio: The percentage of remote work associated with each job posting.

Key Features

    Calculate the remote work ratio by country.
    Identify the top 5 countries with the highest telework ratios.
    Create 2D and 3D visualizations to present the findings clearly.

Analysis Steps

    Data Loading: Load the dataset into a Pandas DataFrame.
    Data Cleaning: Filter and clean the data to ensure accurate analysis.
    Ratio Calculation: Calculate the ratio of remote job postings per country.
    Top Country Identification: Identify the top 5 countries with a remote work ratio of 100%.
    Visualization: Use Matplotlib and Seaborn to create bar plots and 3D plots for better representation.

Visualizations

The notebook includes the following visualizations:

    A 2D bar chart showing the top 5 countries with the highest telework ratios.
    A 3D bar chart providing a dynamic view of the same data.

These visualizations aim to enhance understanding and facilitate decision-making regarding remote work trends globally.
Usage

To run the analysis, follow these steps:

    Clone the repository: bash git clone https://github.com/yourusername/telework-ratio-analysis.git
    Navigate to the project directory: bash cd telework-ratio-analysis
    Install the required packages: bash pip install -r requirements.txt
    Open the Jupyter Notebook: bash jupyter notebook Telework_Ratio_Analysis.ipynb

Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.
