# ds_ramesh_tare
Analysis of 209K crypto trades reveals sentiment-performance correlations: 43.2% win rate during fear vs 39.8% greed periods. Sentiment-adaptive strategies show 42% improvement. Provides actionable insights for optimizing trading based on market psychology and timing patterns.




# 📊 Trader Behavior & Market Sentiment Analysis

## 📋 Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and cryptocurrency trader behavior on the Hyperliquid platform. Through comprehensive analysis of 209,110 trades over two years, we uncover significant correlations between market sentiment and trader profitability, leverage usage, and risk management strategies.

## 🔍 Key Findings
- **Fear periods** show higher win rates (43.2% vs 41.1% average) with conservative leverage
- **Greed periods** generate higher absolute returns (+26% avg PnL) but with increased risk
- **Sentiment-adaptive strategies** demonstrate 42% improvement over baseline approaches
- Strong correlation (r=0.72) between Greed sentiment and trading volume
- Most active trading hour: 20:00 UTC (Late US/Early Asia session overlap)

## 📁 Repository Structure
```
ds_yourname/
├── notebook_1.ipynb           # Fear & Greed Index Analysis
├── notebook_2.ipynb           # Historical Trader Data Analysis
├── csv_files/                 # All data files
│   ├── processed_trader_data.csv
│   ├── trader_performance_summary.csv
│   └── fear_greed_data.csv
├── outputs/                   # Visualizations
│   └── trader_data_comprehensive_analysis.png
├── ds_report.pdf             # Final insights report (5+ pages)
└── README.md                # This file
```

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)
1. Open the notebooks in Google Colab using the links below
2. Run all cells sequentially
3. No installation required - runs in your browser



## 🔗 Google Colab Notebooks
- **[Notebook 1: Fear & Greed Analysis](COLAB_LINK_1)** - Market sentiment analysis and visualization
- **[Notebook 2: Trader Data Analysis](COLAB_LINK_2)** - 200K+ trades analysis with performance metrics

## 📊 Analysis Methodology

### 1. Data Processing
- **211,224 raw trades** → **209,110 cleaned trades** (1% outlier removal)
- Timestamp standardization across datasets
- Feature engineering: Estimated leverage, win flags, time-based features
- Sentiment alignment with daily Fear & Greed Index

### 2. Statistical Analysis
- Comparative metrics across sentiment categories (Fear/Neutral/Greed)
- Correlation analysis between sentiment and trader behavior
- Risk-adjusted return calculations (Sharpe Ratio: 3.604)
- Machine learning model for trade prediction (78% accuracy)

### 3. Visualization
- Comprehensive performance dashboards
- Time-series analysis of trading patterns
- Sentiment-behavior correlation heatmaps
- Risk-return scatter plots

## 📈 Performance Metrics
| Metric | Value |
|--------|-------|
| Total Trades Analyzed | 209,110 |
| Total Trade Volume | $1.05B |
| Total PnL | $5.95M |
| Win Rate | 41.1% |
| Sharpe Ratio | 3.604 |
| Profit Factor | 12.00 |
| Analysis Period | May 2023 - May 2025 |

## 🎯 Strategic Recommendations

### For Risk-Averse Traders
- **Trade during Fear sentiment** (higher win probability: 43.2%)
- Use conservative leverage (1.5-2.5x)
- Focus on smaller, frequent trades
- **Expected Sharpe Ratio**: 4.12

### For Aggressive Traders
- **Capitalize on Greed periods** (higher volume: +28%)
- Use moderate leverage (3-4x) with strict stop-losses
- Focus on larger position sizes
- **Expected Avg PnL**: $61.45

### Hybrid Approach
- Fear periods: Increase frequency, decrease size
- Greed periods: Decrease frequency, increase size
- Neutral periods: Maintain baseline strategy
- **Overall Improvement**: +42% over baseline

## 🛠️ Technical Stack
- **Python 3.9+** with Pandas, NumPy, Scikit-learn
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Google Colab
- **Version Control**: GitHub
- **Documentation**: Jupyter Notebooks, Markdown, PDF report

## 📚 Files Description
- **notebook_1.ipynb**: Comprehensive Fear & Greed Index analysis with sentiment classification
- **notebook_2.ipynb**: Historical trader data analysis (200K+ trades) with performance metrics
- **ds_report.pdf**: Complete 8-page report with insights and recommendations
- **csv_files/**: All processed and raw data files
- **outputs/**: Generated visualizations and analysis charts

## 📊 Results Interpretation
1. **Sentiment matters**: Market psychology significantly impacts trading outcomes
2. **Risk management**: Different sentiment periods require different risk approaches
3. **Timing is crucial**: Specific hours yield consistently better results
4. **Adaptive strategies**: Sentiment-aware approaches outperform static ones

## 🤝 Contributing
This is a submission for the PrimeTrade.ai Data Science position. The analysis is complete and ready for review.

## 📧 Contact
**Analyst**: Ramesh Ladak Tare 
**Email**: tareramesh28@gmail.com 
**LinkedIn**:http://www.linkedin.com/in/ramesh-tare   


## 📄 License
This project is created as part of a job application submission. All rights reserved by the candidate.


## 🎉 Acknowledgments
- Data provided by Hyperliquid and Alternative.me
- Analysis conducted for PrimeTrade.ai Data Science position
- Tools: Google Colab, GitHub, Python Data Science Stack

