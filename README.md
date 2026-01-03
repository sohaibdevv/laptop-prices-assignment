# 💻 Laptop Specifications & Prices Dataset (2025-2026)

## 📝 Project Overview
This repository hosts a curated dataset of **30 modern laptops** representing the 2025-2026 hardware market. It includes a balanced variety of machines, from ultra-budget student laptops to high-end professional and gaming workstations featuring the latest Intel Core Ultra, Apple M4, and NVIDIA RTX 50-series hardware.

The primary goal of this project is to provide a clean, structured dataset for practicing:
* **Exploratory Data Analysis (EDA)**: Understanding price trends across brands.
* **Data Visualization**: Comparing hardware specs vs. cost.
* **Machine Learning**: Predicting laptop prices based on technical specifications.

## 📊 Dataset Details
The data is stored in `laptop_prices.csv`. Each row represents a unique laptop model with the following attributes:

| Column Name | Description | Example |
| :--- | :--- | :--- |
| **Brand** | Manufacturer of the laptop | Apple, ASUS, Lenovo |
| **Model** | Specific series or model name | Vivobook 16, MacBook Air |
| **CPU** | Processor model | Core Ultra 7, M4 |
| **RAM_GB** | System memory in Gigabytes (GB) | 16, 32 |
| **Storage_GB** | SSD/Storage capacity in Gigabytes (GB) | 512, 1024 |
| **GPU** | Graphics card model | RTX 5060, Integrated |
| **Price_USD** | Current retail market price in USD | 899 |
| **Category** | Market segment classification | Budget, Gaming, Premium |

## 🚀 How to Use

### 1. Installation & Setup
To use this dataset on your local machine, clone the repository using Git:
```bash
git clone [https://github.com/YOUR_USERNAME/laptop-price-dataset.git](https://github.com/YOUR_USERNAME/laptop-price-dataset.git)

```

### 2. Loading the Data

You can easily load the data into a Python environment using the `pandas` library:

```python
import pandas as pd

# Load the CSV file
df = pd.read_csv('laptop_prices.csv')

# Display basic statistics
print(df.describe())

# Filter for budget laptops under $700
budget_laptops = df[df['Price_USD'] < 700]
print(budget_laptops[['Brand', 'Model', 'Price_USD']])

```

## 🔗 Live Connections

* **Kaggle Dataset**: [Link to your Kaggle Page]
* **Data Source**: This dataset is maintained and version-controlled via GitHub.

## 📜 License

This project is licensed under the **CC0: Public Domain** license, meaning you are free to use, modify, and distribute this data for any purpose.


---

### Final Checklist for You (Remove this in the README after completing all things):
1.  **Replace placeholders**: In the `README.md` above, make sure to change `YOUR_USERNAME` and the **Kaggle Link** once you have them.
2.  **Kaggle Description**: You can copy the **Project Overview** and **Dataset Details** sections from this README and paste them directly into the "About" section on Kaggle so both sites match.
