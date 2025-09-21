

#  Car Price Analysis - Exploratory Data Analysis

> **Discovering what really drives automobile pricing through data science**

A comprehensive exploratory data analysis project that uncovers the key characteristics most significantly impacting car prices using statistical analysis, correlation studies, and advanced data visualization techniques.

## 🎯 The Big Question

**"What are the main characteristics that have the most impact on car price?"**

This project dives deep into automobile data to answer this fundamental question that affects millions of car buyers and sellers worldwide.

## 🔍 Key Discoveries

### �� Top Price Predictors
| Rank | Feature | Correlation | Impact |
|------|---------|-------------|---------|
| 1 | **Engine Size** | 0.872 | 🔥 Very Strong |
| 2 | **Curb Weight** | 0.834 | 🔥 Very Strong |
| 3 | **Horsepower** | 0.810 | 🔥 Very Strong |
| 4 | **Width** | 0.751 | 💪 Strong |
| 5 | **Length** | 0.691 | 💪 Strong |

### 🤯 Surprising Insights
- **Fuel Efficiency Paradox**: More expensive cars = worse gas mileage (-0.705 correlation)
- **Peak RPM Myth**: Engine RPM barely affects pricing (0.10 correlation)
- **Drive Wheel Premium**: Rear-wheel drive cars command highest prices
- **Size Matters**: Physical dimensions (width, length) strongly predict cost

## 🛠️ Tech Stack

```python
# Core Libraries
pandas      # Data manipulation
numpy       # Numerical computing
matplotlib  # Basic plotting
seaborn     # Statistical visualization
scipy       # Statistical analysis
```

## �� Analysis Journey

### 1. **Data Exploration** 
- Analyzed 201 automobile records across 30 features
- Identified continuous vs categorical variables
- Performed initial data quality assessment

### 2. **Visual Analysis** 📈
- **Scatter plots** with regression lines for continuous variables
- **Box plots** for categorical feature distributions
- **Heatmaps** for correlation matrix visualization
- **Pivot tables** for multi-dimensional analysis

### 3. **Statistical Deep Dive** 
- **Pearson Correlation** analysis with p-value testing
- **ANOVA** for categorical group comparisons
- **Statistical significance** validation (p < 0.001)

### 4. **Business Insights** 💡
- Identified luxury vs efficiency trade-offs
- Discovered physical dimension importance
- Validated engine performance as primary price driver

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/car-price-analysis.git
cd car-price-analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scipy jupyter

# 3. Launch Jupyter
jupyter notebook

# 4. Open the analysis notebook
# DA0101EN-3-Review-Exploratory-Data-Analysis.ipynb
```

## 📈 Detailed Results

### Strong Positive Correlations
- **Engine Size**: 0.872 (p < 0.001) - The ultimate price driver
- **Curb Weight**: 0.834 (p < 0.001) - Heavier = pricier
- **Horsepower**: 0.810 (p < 0.001) - Power sells
- **Width**: 0.751 (p < 0.001) - Size premium
- **Length**: 0.691 (p < 0.001) - Length matters

### Negative Correlations
- **Highway MPG**: -0.705 (p < 0.001) - Efficiency penalty
- **City MPG**: -0.687 (p < 0.001) - Urban efficiency cost

### Categorical Insights
- **Drive Wheels**: Statistically significant differences (ANOVA p ≈ 0)
- **Engine Location**: Limited rear-engine data (3 vs 198 front-engine)
- **Body Style**: Weak predictive power due to overlapping distributions

## 💼 Real-World Applications

### For Car Buyers 🚗
- Understand which features justify higher prices
- Make informed decisions based on value drivers
- Identify overpriced vehicles

### For Automotive Industry 🏭
- Optimize pricing strategies
- Focus R&D on high-impact features
- Market positioning based on data

### For Insurance & Finance ��
- Risk assessment based on vehicle characteristics
- Pricing models for auto loans
- Claims prediction algorithms

## 🎓 What You'll Learn

- **Exploratory Data Analysis** best practices
- **Statistical correlation** interpretation
- **Data visualization** techniques
- **Hypothesis testing** with p-values
- **ANOVA** for group comparisons
- **Business insight** extraction from data

## 📋 Requirements

```txt
pandas==1.3.3
numpy==1.21.2
matplotlib>=3.0.0
seaborn>=0.9.0
scipy>=1.7.1
jupyter>=1.0.0
```

## 🤝 Contributing

Found an interesting pattern? Have a better visualization idea? Contributions are welcome!

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is part of the IBM Data Analysis with Python course and is for educational purposes.

## 👨‍�� Author

R.K.Sanjay Aanand - Data Science Enthusiast | Car Market Analyst

## 🙏 Acknowledgments

- IBM Skills Network for the comprehensive dataset
- The data science community for inspiration
- Jupyter community for amazing tools

---

**�� Pro Tip**: The insights from this analysis can be applied to any pricing prediction problem. The methodology is transferable across industries!

**⚠️ Disclaimer**: Results based on sample dataset. Real-world applications may vary with larger, more diverse datasets.


