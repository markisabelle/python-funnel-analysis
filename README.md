# Funnel Analysis Project

An end-to-end Python analysis of an e-commerce customer journey to identify drop-off points and optimize conversion rates.
docs/Funnel Analysis.png

## Project Overview

This project analyzes 434,268 customer interactions from an online store to understand what prevents customers from completing purchases. Using funnel analysis techniques, I identified critical drop-off points and provided actionable recommendations to improve conversion rates.

## Dataset

- **Source**: E-commerce platform event data
- **Size**: 434,268 customer interactions
- **Key Fields**: user_id, date, category, device, event_type
- **Event Types**: visit, view, add_to_cart, purchase
- **Product Categories**: Office Supplies, Furniture, Technology

## Analysis Approach

### 1. Customer Journey Mapping
Built a complete funnel visualization tracking customers through four stages:
- **Visits**: 192,000 initial visitors
- **Product Views**: 78% viewed products
- **Add to Cart**: 41% added items to cart
- **Purchase**: Only 6% completed purchase

### 2. Drop-Off Analysis
Created a custom Python function to calculate percentage drops between each funnel stage:
- Identified the largest drop-off point: **85.1% of customers abandoned their carts** before purchasing
- This represents the critical conversion bottleneck

### 3. Time-to-Conversion Analysis
Analyzed how long it takes customers to progress through each funnel stage:
- Tracked days elapsed from visit to view, add to cart, and purchase
- Created time-based curves for each conversion event
- Visualized customer behavior patterns over time

## Key Findings

- **Critical Issue**: 85.1% cart abandonment rate at the purchase stage
- **Conversion Rate**: Only 6% of visitors complete a purchase
- **View Rate**: Strong initial engagement with 78% of visitors viewing products
- **Add to Cart Rate**: 41% engagement shows purchase intent, but poor follow-through

## Recommendations

Based on the analysis, I identified three potential solutions to reduce cart abandonment:

1. **Value Communication**: Increase perceived value by improving product pricing transparency and highlighting benefits
2. **Trust Building**: Implement warranty programs and buy-back guarantees to increase customer confidence
3. **Promotional Strategy**: Create stronger promotional campaigns, discounts, and urgency-driven offers

## Technical Skills Demonstrated

- Data manipulation with **Pandas** and **NumPy**
- Interactive visualizations using **Plotly**
- Custom function development for business logic
- Time-series analysis and conversion tracking
- Statistical analysis of customer behavior patterns

## Tools & Technologies

- **Python**: Pandas, NumPy, Plotly, Matplotlib
- **Analysis Type**: Funnel analysis, conversion optimization, time-series
- **Visualization**: Interactive funnel charts, time-based conversion curves

## Business Impact

Implementing these recommendations could:
- Reduce cart abandonment by 20-30%
- Increase overall conversion rate from 6% to 8-10%
- Improve customer lifetime value through trust-building initiatives
- Generate significant revenue growth with minimal acquisition cost increase

## Repository Structure

```
funnel_analysis/
├── README.md
├── Funnel_Analysis.ipynb
└── raw_data.csv
```

## How to Use

1. Install required packages: `pip install pandas numpy plotly matplotlib`
2. Load the Jupyter notebook: `Funnel_Analysis.ipynb`
3. Run cells sequentially to reproduce the analysis

## Author

Mark Isabelle  
[LinkedIn](https://linkedin.com/in/mark-isabelle-a113b8325) | [GitHub](https://github.com/markisabelle)
