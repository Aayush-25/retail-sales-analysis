# 📊 Retail Sales Data Analysis

A comprehensive Python data analysis project examining retail sales patterns, customer behavior, and regional performance across 9,789 sales records spanning 2015-2018.

## 🎯 Project Overview

This project analyzes retail sales data to uncover business insights, identify top-performing categories and regions, and provide actionable recommendations for strategic decision-making. The analysis demonstrates proficiency in data cleaning, exploratory data analysis, statistical analysis, and data visualization.

## 🔍 Key Findings

- **Technology** dominates as the top-performing category with **$825,856** in sales (36.7% of total revenue)
- **West region** leads in sales performance with **$710,220** in total sales
- **Sean Miller** is the top customer, generating **$25,043** in individual sales
- **November 2018** recorded peak sales of **$117,938**
- Analysis covers **January 2015 to December 2018** with **$2.25M** total revenue

## 🛠️ Technologies Used

- **Python 3.8+** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Static data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 📁 Project Structure

```
retail-sales-analysis/
├── README.md                          # Project documentation
├── retail_analysis.ipynb             # Main analysis notebook
├── requirements.txt                   # Python dependencies
├── data/
│   └── train.csv                     # Raw dataset
├── visualizations/
│   ├── retail_sales_dashboard.png    # Main dashboard (PNG)
│   └── retail_sales_dashboard.pdf    # Main dashboard (PDF)
├── results/
│   ├── category_sales.csv            # Sales by category summary
│   └── region_sales.csv              # Sales by region summary
└── presentation/
    └── executive_summary.txt         # Executive summary report
```

## 🚀 Quick Start

### Prerequisites
```bash
Python 3.8 or higher
```

### Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/retail-sales-analysis.git
cd retail-sales-analysis
```

2. Install required packages
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook
```bash
jupyter notebook retail_analysis.ipynb
```

4. Run all cells to reproduce the analysis

## 📊 Analysis Highlights

### Data Processing
- **Data Cleaning**: Handled 11 missing postal codes (0.1% of data)
- **Feature Engineering**: Created time-based features (Year, Month, Quarter, Day of Week)
- **Data Quality**: Achieved 99.9% data completeness with zero duplicates

### Key Visualizations
1. **Sales by Category** - Bar chart showing Technology category leadership
2. **Regional Performance** - Geographic sales distribution analysis
3. **Monthly Trends** - Time series revealing seasonal patterns
4. **Top Customers** - Customer performance ranking visualization
5. **Market Segmentation** - Pie chart of customer segments
6. **Shipping Analysis** - Logistics performance metrics

### Business Insights
- **Category Performance**: Technology (36.7%), Furniture (32.3%), Office Supplies (30.9%)
- **Regional Distribution**: West (32.1%), East (28.3%), Central (23.3%), South (16.3%)
- **Customer Segments**: Consumer (52.1%), Corporate (30.1%), Home Office (17.8%)
- **Seasonality**: Clear Q4 peaks with November showing highest performance

## 💡 Business Recommendations

1. **🎯 Category Focus**: Expand Technology product lines and inventory given 36.7% market dominance
2. **🗺️ Geographic Strategy**: Replicate West region success strategies in underperforming areas
3. **👥 Customer Retention**: Develop loyalty programs targeting top-performing customers
4. **📈 Seasonal Planning**: Prepare enhanced inventory and marketing for Q4 demand spikes
5. **🚚 Logistics Optimization**: Improve Standard Class shipping (59.8% of orders) for better customer experience

## 📈 Results & Impact

- **Identified $825K revenue opportunity** in Technology category expansion
- **Discovered 45% performance gap** between West and South regions
- **Mapped seasonal patterns** showing 40% sales increase in peak months
- **Segmented customer base** for targeted marketing strategies

## 🔗 Dataset Information

- **Source**: Retail sales transaction data
- **Size**: 9,789 records after cleaning
- **Time Period**: January 2015 - December 2018
- **Columns**: 18 features including sales, geography, products, and customer data
- **Data Quality**: 99.9% complete with comprehensive validation


*This project demonstrates proficiency in Python data analysis, statistical thinking, and business intelligence - key skills for data science and analytics roles.*
