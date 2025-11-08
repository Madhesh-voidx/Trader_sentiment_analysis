# 🚀 Trader Sentiment Analysis

This project is a complete data analysis pipeline that analyzes historical trader data from **historical_data** against the **Fear & Greed Index**.  
The goal is to uncover hidden patterns in trader profitability, risk-taking, and market activity based on overall market sentiment.

---

## ✨ Key Features

This project loads, cleans, and analyzes two large CSV datasets to generate a full report on trader behavior.

- **Data Cleaning & Prep:** Automatically loads and cleans thousands of trades, handles date/time conversions, and coerces numeric data.
- **Data Merging:** Merges a time-series dataset of individual trades with a daily sentiment index to “stamp” each trade with the market’s mood.
- **Automated Analysis:** Programmatically performs four key analyses (Profitability, Volume, Behavior) by grouping and aggregating the data.
- **Plot Generation:** Generates and saves four professional, publication-ready plots as `.png` files in the outputs folder.
- **Formal Report:** Includes a `report.pdf` file summarizing all key findings and insights.

---

## 🛠️ Technologies Used

| Category | Technology | Purpose |
|-----------|-------------|----------|
| Data Analysis | pandas | For loading, cleaning, merging, and grouping all data. |
| Data Visualization | matplotlib | The core library for creating figures and axes. |
| Data Visualization | seaborn | Used to create styled, attractive statistical plots. |
| Core Language | Python | The main language used for the analysis script. |
| Reporting | pdf | Used to create the final, formal `report.pdf`. |

---

## 📂 Project Structure

```
ds_Madheshwaran/
│
├──notebook1.ipynb
│
├─Csv files/
│   ├─fear_greed_index.csv
│   ├─historical_data.csv
├── outputs/
│   ├── pnl_vs_market_sentiment.png
│   ├── total_volume_vs_sentiment.png
│   ├── Buy_sell_proportion_v_sentiment.png
├── README.md 
└── report.pdf
```

---

## 📊 Generated Outputs

The script generates the following files in the `/outputs` folder:

1. **pnl_vs_market_sentiment.png** — Average *Closed PnL* per trade, grouped by market sentiment.  
2. **total_volume_vs_sentimentt.png** — Total USD volume traded during each sentiment period.  
3. **Buy_sell_proportion_v_sentiment.png** — Stacked bar chart showing the ratio of *BUY* vs. *SELL* volume.  

## 📊 Analysis Performed

This script performs and plots **four main analyses**:

1. **Profits Analysis:** Calculates the average *Closed PnL* per trade, grouped by sentiment.  
2. **Volume Analysis:** Calculates the total USD volume traded during each sentiment period.  
3. **Behavior Analysis:** Calculates the proportion of *BUY* vs. *SELL* volume within each sentiment.  


---

## 🚀 Getting Started

To run this project locally, clone the repository, install dependencies, and execute the analysis script.

### 1️⃣ Clone the repository (replace with your own repo URL):
```bash
git clone https://github.com/Madhesh-voidx/Trader_sentiment_analysis.git
```

### 2️⃣ Navigate to the project directory:
```bash
cd Trader_sentiment_analysis
```

### 3️⃣ Install required dependencies:
```bash
pip install pandas matplotlib seaborn
```

### 4️⃣ Run the analysis notebook:
```bash
Trader_sentiment_analysis.ipynb
```

The script will print all analysis tables to the console and save the four plot images to the `/outputs` folder.


## 📜 License

This project is released under the MIT License.  
Feel free to modify, use, and distribute with attribution.

---

**Author:** Madheshwaran M  
**Contact:** Madheshwaran299@gmail.com
**GitHub:** [https://github.com/Madhesh-voidx](https://github.com/Madhesh-voidx)
