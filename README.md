# Portfolio-optimization
This project features a Python notebook that optimizes a 10-stock portfolio using Monte Carlo simulation, with historical stock data sourced from Yahoo Finance and stored in a .csv file. The repository includes the notebook for analysis and the raw data used in the optimization process.

## Repository Structure
- `notebooks/`: Jupyter notebooks for data analysis and visualization.
- `data/`: Original datasets (CSV files) used in the analysis.

## Installation
To set up and run this project locally, follow these steps:

1. **Clone the repository**:
   Open your terminal and run the following command to clone the repository to your local machine:
   ```bash
   git clone https://github.com/Alan18241/portfolio-optimization.git
    ```
2. Navigate to the project directory:
    ```bash
    cd portfolio-optimization
    ```
3. Install the required Python packages:
    ```bash
    pip install pandas numpy matplotlib seaborn plotly
    ```

## Running the Notebooks
The notebook in the `notebooks/` folder provides a portfolio optimization.

- `notebooks/analysis_loan_portfolio.ipynb`: Analyzes loan portfolio data from `data/raw/dataset_1.csv` and performs valuation.
- `notebooks/exploratory_analysis.ipynb`: Performs exploratory data analysis on the loan portfolio datasets.

To run a notebook:
1. Install Jupyter if it's not already installed:
    ```bash
    pip install jupyter
    ```
2. Start the Jupyter notebook server:
    ```bash
    jupyter notebook
    ```
3. Open the desired notebook from the `notebooks/` folder.

## Data Files
The project uses datasets stored in the `data/` folder.

- `data/raw/`: Contains the original datasets used for analysis.
- `data/processed/`: Contains datasets that have been cleaned or transformed.
 
Example: 
- `dataset_1.csv`: Raw loan portfolio data used for valuation.
- `processed_data_1.csv`: Cleaned dataset used for model training.

## Utility Scripts
The `src/` folder contains reusable Python functions for data cleaning, processing, and visualization.

- `utils.py`: A collection of helper functions used across multiple notebooks.

## Results and Reports
The final analysis and conclusions are documented in the `reports/` folder.

- `final_report.md`: A summary of the loan portfolio valuation findings and recommendations.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
