# Airbnb Price Analysis

## Project Overview
This project explores Airbnb listing data in New York City to better understand pricing patterns and key factors influencing listing prices.

The goal was to practice structured exploratory data analysis (EDA) and communicate findings clearly.

## Dataset
The dataset contains 48,895 Airbnb listings with 16 features including:
- Price
- Room type
- Borough (neighbourhood group)
- Number of reviews
- Availability
- Host-related information

## Key Insights
- The price distribution is highly right-skewed due to extreme outliers.
- After removing the top 1% (prices above 799 USD), the distribution becomes more interpretable.
- Entire homes/apartments are significantly more expensive than private or shared rooms.
- Manhattan has the highest median prices across all boroughs.
- There is almost no linear correlation between price and number of reviews.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
```
Airbnb-Price-Analysis/
│
├── data/                  # Raw dataset
├── notebooks/             # Full exploratory analysis
│   └── 01_airbnb_eda.ipynb
├── README.md
└── .gitignore
```

## Conclusion
This analysis highlights how strongly Airbnb prices vary depending on room type and borough. 
After addressing extreme outliers, clearer pricing patterns emerged, particularly the premium associated with entire homes and listings in Manhattan.

Overall, this project strengthened my ability to structure exploratory analysis, interpret distributions, and translate data findings into meaningful insights.

## ML Model (Baseline)

First baseline model for predicting Airbnb prices.

- Model: Linear Regression
- Features: neighbourhood_group, room_type, minimum_nights, number_of_reviews, calculated_host_listings_count, availability_365
- MAE: ~71
- RMSE: ~198
- R^2: ~0.11

This is a first baseline model and will be improved in the next steps.