# Prevalence of Undernourishment Analysis

## Overview

This repository contains a comprehensive analysis of the prevalence of undernourishment across different regions and years using a comprehensive dataset. The analysis includes various statistical techniques, visualizations, and machine learning methods to provide insights into global food security and undernourishment trends.

## Dataset

The dataset includes the following columns:
- **Entity**: The region or country.
- **Year**: The year of the data.
- **2.1.1 Prevalence of undernourishment**: The prevalence of undernourishment.
- **percentage**: The percentage of the population that is undernourished.

The dataset is provided in the CSV file `prevalence-of-undernourishment new.csv`.

## Analysis

The analysis is performed in the Jupyter notebook `advanced_analysis_undernourishment_final.ipynb`, which includes the following sections:

1. **Data Loading and Cleaning**: 
    - Load the dataset and clean the data by handling non-numeric values and missing data.

2. **Basic Statistics and Visualizations**:
    - Summary statistics of the dataset.
    - Line plots showing the prevalence of undernourishment over time for different regions.

3. **Regions with Highest and Lowest Prevalence**:
    - Identify regions with the highest and lowest prevalence of undernourishment.

4. **Correlation Analysis**:
    - Analyze the correlation between the year and the prevalence of undernourishment.

5. **Advanced Analysis**:
    - **Time Series Forecasting**: Predict future prevalence of undernourishment using SARIMAX model.
    - **Improved Heatmap Visualization**: Visualize the prevalence of undernourishment by region and year using a heatmap.
    - **Clustering Analysis**: Identify groups of regions with similar patterns of undernourishment using K-Means clustering.
    - **Principal Component Analysis (PCA)**: Reduce the dimensionality of the dataset and visualize the main components.

6. **Insights**:
    - Key insights derived from the analysis.

7. **Conclusion**:
    - Summary of findings and the importance of targeted interventions to combat undernourishment.

## Installation

To run the notebook locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/debjit-mandal/undernourishment-analysis.git
    ```

2. Navigate to the repository directory:
    ```sh
    cd undernourishment-analysis
    ```

3. Create a virtual environment:
    ```sh
    python -m venv env
    ```

4. Activate the virtual environment:
    - On Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source env/bin/activate
        ```

5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

6. Launch Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

7. Open the `advanced_analysis_undernourishment.ipynb` notebook and run the cells.

## Requirements

The required Python packages are listed in `requirements.txt`. To generate this file, you can use:
```sh
pip freeze > requirements.txt
```
## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
