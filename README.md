---
# Day-Ahead Power Price Forecasting Challenge

- This repository contains my solution to the coding challenge. 
- The objective is to design and implement models for forecasting day-ahead power prices in the energy market.

## Project Structure

```
ml-electricity-price-forecast/
├── .venv/                         # Python virtual environment
├── .gitignore                     # untracked files
├── day_ahead_price_forecasting.ipynb # containing all code, analysis, and results
├── ml-engineer-dataset.csv        # dataset
└── README.md                      

```
---
## Setup and How to Run the Solution

To run this solution locally, please follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/RNstu08/Electricity-Price-Forecast.git](https://github.com/RNstu08/Electricity-Price-Forecast.git)
    cd Electricity-Price-Forecast
    ```

2.  **Create and Activate a Python Virtual Environment:**
    ```bash
    python -m venv .venv
    ```
    * **On Windows (Command Prompt/PowerShell):**
        ```bash
        .venv\Scripts\activate
        ```
    * **On macOS/Linux (Bash/Zsh):**
        ```bash
        source .venv/bin/activate
        ```

3.  **Install Dependencies:**
    Install all required Python packages.
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter xgboost lightgbm shap
    ```

4.  **Download the Dataset:**
    Download `ml-engineer-dataset.csv` and place it directly into the root of the cloned repository.

5.  **Launch Jupyter Notebook in VS Code:**
    * Open the project folder (`ml-electricity-price-forecast`) in VS Code.
    * Open `day_ahead_price_forecasting.ipynb`.
    * Select the Python interpreter associated with your virtual environment (`.venv`).
    * Run all cells in the notebook (`Run All` button or `Kernel -> Restart Kernel and Run All Cells`).
---
---
