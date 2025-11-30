# E-commerce Customer Value Prediction

A comprehensive linear regression analysis project that predicts yearly customer spending based on e-commerce behavioral metrics.

## Project Overview

This project analyzes synthetic e-commerce customer data to build a predictive model for yearly customer spending. Using linear regression, we identify which customer behavior metrics (session length, app usage, website time, and membership duration) most significantly impact annual revenue.

## Objectives

- Perform exploratory data analysis on e-commerce customer behavior
- Build and train a linear regression model to predict yearly spending
- Identify key factors driving customer value
- Provide actionable insights for e-commerce business optimization

## Dataset

The dataset `Ecommerce_Customers_Synthetic.csv` contains 500 synthetic customer records with the following features:

- **Avg. Session Length**: Average session duration (minutes)
- **Time on App**: Time spent on mobile application (minutes)
- **Time on Website**: Time spent on website (minutes)
- **Length of Membership**: Customer membership duration (years)
- **Yearly Amount Spent**: Target variable - total yearly spending ($)

## Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Scikit-learn** - Machine learning modeling
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## Key Features

### Data Exploration
- Comprehensive statistical analysis
- Data quality assessment
- Correlation analysis between features

### Visualization
- Pairplot analysis for feature relationships
- Distribution analysis
- Correlation heatmaps

### Machine Learning
- Train-test split for model validation
- Linear regression implementation
- Model performance evaluation
- Feature importance analysis

## Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/augo-amos/ecommerce-customer-value-prediction.git
```

2. Navigate to the project directory:
```bash
cd ecommerce-customer-value-prediction
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open and run `Linear Regression Example 1.ipynb`

## Project Structure

```
ecommerce-customer-value-prediction/
│
├── Linear Regression Example 1.ipynb  # Main analysis notebook
├── Ecommerce_Customers_Synthetic.csv   # Dataset
├── requirements.txt                    # Python dependencies
├── README.md                          # Project documentation
└── images/                            # Visualization outputs
```

## Key Insights

The analysis reveals:
- **Membership length** as the strongest predictor of customer spending
- **Mobile app engagement** showing significant impact on revenue
- **Website time** having comparatively lower correlation with spending
- Clear opportunities for optimizing customer retention strategies

## Model Performance

The linear regression model demonstrates strong predictive capability with:
- High R-squared value indicating good fit
- Low mean squared error
- Statistically significant coefficients

## Business Applications

- **Customer Lifetime Value Prediction**: Identify high-value customers
- **Resource Allocation**: Optimize marketing spend and platform development
- **Personalization**: Tailor user experiences based on behavior patterns
- **Retention Strategies**: Focus on membership duration extension

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- Additional machine learning models
- Enhanced visualization techniques
- Feature engineering improvements
- Performance optimizations

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Authors

- Amos Augo 
