# Food Price Inflation Analysis

A comprehensive data analysis project designed to track, analyze, and visualize food price trends and inflation indicators over time. This repository contains the data processing pipeline and visualization dashboards used to monitor price volatility.

## 🚀 Project Overview

This project aims to quantify the impact of inflation on food prices by analyzing historical data. It utilizes Python for data extraction and processing, and Microsoft Power BI for interactive reporting.

**Key Features:**
* **Data Processing:** Automated cleaning and structuring of raw price data using Pandas.
* **Inflation Analysis:** Calculation of price changes and percentage growth over specific timeframes.
* **Visualization:** Interactive Power BI dashboards to explore trends by product category and time period.

## 📂 Repository Structure

| File/Folder | Description |
| :--- | :--- |
| `analysis.ipynb` | Jupyter Notebook containing the core logic for data cleaning, EDA (Exploratory Data Analysis), and statistical metrics. |
| `PowerBI/` | Directory containing the `.pbix` dashboard files for visual reporting. |
| `data/` | Storage for raw input datasets and processed CSV files. |
| `requirements.txt` | List of Python libraries required to reproduce the analysis. |

## 🛠️ Technologies Used

* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Visualization:** Microsoft Power BI
* **Environment:** Jupyter Notebook

## ⚙️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ikartiksavaliya/food-price-inflation-analysis.git](https://github.com/ikartiksavaliya/food-price-inflation-analysis.git)
    cd food-price-inflation-analysis
    ```

2.  **Install Python dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 📊 Usage

1.  **Data Preparation:**
    Open `analysis.ipynb` in your preferred Jupyter environment (VS Code, JupyterLab, etc.) and run the cells to process the data found in the `data/` folder.

2.  **Dashboarding:**
    Navigate to the `PowerBI/` folder and open the `.pbix` file. Ensure the data source paths in Power BI are updated to point to your local `data/` directory.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
