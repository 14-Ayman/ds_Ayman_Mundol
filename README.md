
# 🧠 Data Science Internship Project

## 📄 Overview
This project analyzes trading and market sentiment data to derive daily trading insights.
The workflow covers data cleaning, preprocessing, merging, feature engineering, and exploratory data analysis (EDA),
culminating in an automated PDF report with charts and key metrics.

## 🧱 Folder Structure

ds_<your_name>/
├── notebook_1.ipynb
├── csv_files/
│ ├── historical_data.csv
│ ├── fear_greed_index.csv
│ ├── cleaned_merged.csv
│ └── daily_features.csv
├── outputs/
│ ├── basic_statistics.txt
│ ├── total_pnl_over_time.png
│ ├── daily_trade_count.png
│ ├── pnl_vs_volume_by_sentiment.png
│ └── correlation_heatmap.png
├── ds_report.pdf
└── README.md


## 🚀 Steps Summary
1. **Data Cleaning & Preprocessing** — handled missing values and standardized date formats
2. **Merging** — combined trader and sentiment datasets
3. **Feature Engineering** — aggregated daily metrics (PnL, trade count, volume, etc.)
4. **EDA** — visualized daily performance and relationships
5. **Reporting** — auto-generated `ds_report.pdf` and this README

## ⚙️ Requirements
This project runs entirely in **Google Colab** or any Python 3 environment with the following libraries:
- pandas
- matplotlib
- seaborn
- reportlab

## 🏁 How to Run
1. Mount your Google Drive in Colab.
2. Set your `BASE_DIR` path to your folder (`/content/drive/MyDrive/ds_<your_name>`).
3. Run all cells in `notebook_1.ipynb` from top to bottom.
4. Find generated files in:
   - `/csv_files/` → processed CSVs
   - `/outputs/` → charts and summary stats
   - `/ds_report.pdf` → final report

- [cleaned_merged.csv]-https://drive.google.com/file/d/1SrIcTLnXVRilDCRl4lJstthDImX3qvfu/view?usp=sharing
- [daily_features.csv]-https://drive.google.com/file/d/1uxPQXZdUhFipuB1IHfz1r9i-6kRnnIoa/view?usp=drive_link
## ✍️ Author
AYMAN ABBAS MUNDOL
Data Science Internship Assignment, 2025
