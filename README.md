# Data Science Assignment - Web3 Trading Team
## Market Sentiment vs Trading Behavior Analysis

### 🎯 Objective
Analyze the relationship between trader behavior and market sentiment using Bitcoin Fear & Greed Index data and Historical Trader Data from Hyperliquid to identify hidden trends and signals for smarter trading strategies.

### 📁 Project Structure
```
ds_VivekkumarChauhan/
├── notebook_1.ipynb          # Complete analysis in Google Colab
├── csv_files/                # All processed data files
│   ├── merged_trading_sentiment_data.csv
│   ├── profitability_analysis.csv
│   ├── risk_analysis.csv
│   ├── volume_analysis.csv
│   ├── side_analysis.csv
│   └── key_insights.txt
|    ............
├── outputs/                  # All visualizations and charts
│   ├── sentiment_distribution.png
│   ├── trading_metrics_by_sentiment.png
│   ├── correlation_heatmap.png
│   └── time_series_analysis.png
|    .............
├── ds_report.pdf            # Final summarized insights and explanations
└── README.md                # This file
```

### 🔗 Links
- **Google Colab Notebook**: [[Click here to vist](https://colab.research.google.com/drive/166oMvDSDVvyPyyU67-IFdcHcwcTa0wE4?usp=sharing)]
- **GitHub Repository**: [[Click here to vist](https://github.com/vivekchauhan3/ds-assignment-VivekkumarChauhan.git)]

### 📊 Datasets Used
1. **Bitcoin Market Sentiment Dataset** - Fear & Greed Index data
2. **Historical Trader Data from Hyperliquid** - Trading behavior data including PnL, leverage, volume, etc.

### 🛠️ Setup Instructions

#### For Google Colab:
1. Open Google Colab
2. Create a new notebook
3. Copy and paste the complete code from the solution
4. Download the datasets using these commands:
   ```python
   !wget -O hyperliquid_data.csv "https://drive.google.com/uc?id=1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs"
   !wget -O fear_greed_data.csv "https://drive.google.com/uc?id=1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf"
   ```
5. Run all cells sequentially

#### For Local Environment:
1. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Download datasets from the provided Google Drive links
3. Run the Python script

### 📈 Key Analyses Performed

1. **Data Exploration & Cleaning**
   - Comprehensive data profiling
   - Missing value handling
   - Date standardization and merging

2. **Sentiment Distribution Analysis**
   - Market sentiment breakdown (Fear vs Greed)
   - Temporal patterns in sentiment

3. **Trading Behavior Analysis**
   - Profitability patterns by sentiment
   - Risk assessment (leverage usage)
   - Trading volume patterns
   - Buy/Sell side analysis

4. **Correlation Analysis**
   - Relationship between sentiment and trading metrics
   - Statistical significance testing

5. **Time Series Analysis**
   - Daily trading patterns
   - Sentiment evolution over time

### 💡 Key Findings

**🎯 Profitability Insights:**
- [Analysis will reveal whether traders are more profitable during Fear or Greed periods]

**⚠️ Risk Patterns:**
- [Analysis will show leverage usage patterns during different sentiment periods]

**📊 Volume Trends:**
- [Analysis will reveal trading volume differences between Fear and Greed periods]

**🔄 Trading Behavior:**
- [Analysis will show buy/sell distribution patterns by sentiment]

### 🎨 Visualizations Created

1. **Sentiment Distribution Charts** - Pie chart and bar chart showing market sentiment breakdown
2. **Trading Metrics by Sentiment** - Box plots comparing volume, leverage, and PnL across sentiment periods
3. **Correlation Heatmap** - Correlation matrix showing relationships between all variables
4. **Time Series Analysis** - Daily trends in trading metrics and sentiment

### 📋 Technical Implementation

- **Data Processing**: Pandas for data manipulation and cleaning
- **Visualization**: Matplotlib and Seaborn for comprehensive charts
- **Statistical Analysis**: NumPy for numerical computations
- **File Management**: Organized output structure as per requirements

### 🚀 Strategic Recommendations

Based on the analysis, the following trading strategies emerge:

1. **Sentiment-Based Position Sizing**
2. **Risk Management by Market Sentiment**
3. **Volume-Based Entry/Exit Strategies**
4. **Leverage Adjustment Protocols**



### 🔄 Reproducibility
All code is documented and reproducible. The Google Colab notebook includes:
- Step-by-step comments
- Error handling
- Data validation checks
- Automated file structure creation

### 📝 Next Steps
This analysis provides a foundation for:
1. **Algorithmic Trading Strategy Development**
2. **Real-time Sentiment Integration**
3. **Risk Management System Enhancement**
4. **Performance Optimization Models**

---

*This analysis was completed as part of the Web3 Trading Team Data Science Assignment. All code and insights are original work demonstrating advanced analytical capabilities in cryptocurrency trading behavior analysis.*
