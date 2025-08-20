# web3_trading_behavior_analysis

## Candidate: `Sirajuddin`{=html}

This repository contains web3_trading_behavior_analysis.\
The project analyzes the relationship between **trader behavior**
(profitability, risk, volume, leverage) and **market sentiment** (Fear
vs Greed Index).

------------------------------------------------------------------------

## 📂 Project Structure

    ds_<sirajuddin>/
    ├── notebook_1.ipynb          # Main analysis notebook
    ├── csv_files/
    │   ├── historical_data.csv   # Historical trader data
    │   └── fear_greed_index.csv  # Bitcoin market sentiment data
    ├── outputs/
    │   ├── corr_matrix.png
    │   ├── pnl_by_sentiment_box.png
    │   ├── volume_over_time.png
    │   ├── pnl_vs_sentiment_value.png
    │   └── winrate_by_sentiment.png
    ├── ds_report_with_plots.pdf  # Final report with analysis and visualizations
    └── README.md                 # Project documentation

------------------------------------------------------------------------

## 🚀 Steps to Run

1.  Open `notebook_1.ipynb` in **Google Colab** (recommended).\
2.  Upload the datasets from `csv_files/` if not already in place.\
3.  Run all cells to reproduce the analysis and plots.\
4.  Generated outputs will be saved in the `outputs/` directory.\
5.  Final insights can be found in `ds_report_with_plots.pdf`.

------------------------------------------------------------------------

## 📊 Key Findings

-   Trading profitability tends to diverge from sentiment during
    **extreme fear** periods.\
-   High leverage trades are more common in **greed** phases but show
    higher risk.\
-   Correlation analysis highlights weak direct links, suggesting
    traders do not always follow sentiment signals.\
-   Hidden signals:
    -   **PnL distributions** show better performance in
        neutral-to-greed markets.\
    -   **Win rate by sentiment** indicates systematic biases worth
        exploiting.

------------------------------------------------------------------------

## 🔗 Notes

-   All code is written in Python using **pandas, matplotlib,
    seaborn**.\
-   Runs in Google Colab with minimal setup.\
-   Report and outputs included for review.
