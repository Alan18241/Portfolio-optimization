# Portfolio-optimization
This project features a Python notebook that optimizes a 10-stock portfolio using Monte Carlo simulation, with historical stock data sourced from Yahoo Finance and stored in a .csv file. The repository includes the notebook for analysis and the raw data used in the optimization process.

## Repository Structure
- `notebooks/`: Jupyter notebooks for data analysis and visualization.
- `data/`: Original datasets (CSV files) used in the analysis.

## Installation
To run this project, you can use Google Colab, which allows you to execute the Jupyter notebook in the cloud without any local setup. Follow these steps:

1. **Open the Notebook in Google Colab**:
   Click on the following link to open the notebook directly in Google Colab:
   [Open Portfolio Optimization Notebook](https://colab.research.google.com/github/your-username/portfolio-optimization/blob/main/portfolio_optimization.ipynb)

2. **Upload the Data File**:
   The notebook requires a `.csv` file for the analysis. You can upload the file directly in Google Colab by following these steps:
   - Run the code cell that contains the upload command (typically using `files.upload()` from `google.colab`).
   - Choose the `.csv` file from your local machine when prompted.

3. **Run the Notebook Cells**:
   Once the data file is uploaded, run the code cells in order:
   - To run a cell, click on it and press `Shift + Enter` or click the "Run" button in the notebook toolbar.
   - The notebook will perform data preprocessing and execute the Monte Carlo simulation using the uploaded data.

4. **View the Results**:
   After running all the cells, you will see the simulation results, portfolio optimization output, and various visualizations, such as:
   - Monte Carlo simulated returns
   - Optimal portfolio allocation
   - Visual graphs showing risk vs. return trade-offs

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
