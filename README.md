# Hotel Booking Analysis

## Project Overview
This project analyzes hotel booking data to uncover patterns in bookings, cancellations, and customer behavior for both city and resort hotels. The analysis provides insights into booking trends, cancellation rates, guest demographics, and revenue patterns, along with a predictive model for booking cancellations.

## Dataset
The analysis uses the `bookings.csv` dataset containing 119,390 hotel booking records with 32 features, including:
- Hotel type (City Hotel or Resort Hotel)
- Booking status (canceled or not)
- Temporal information (arrival date, lead time)
- Stay duration (weekend nights, weekday nights)
- Guest information (adults, children, babies)
- Meal preferences
- Country of origin
- Market segment and distribution channel
- Room type information
- Pricing (ADR - Average Daily Rate)
- Special requests and requirements

## Key Features

### Data Exploration and Preprocessing
- Handling missing values in children, agent, and company fields
- Feature engineering to create derived metrics like total stays and total guests
- Date formatting and extraction of temporal components

### Exploratory Data Analysis
- **Cancellation Analysis:** Overall cancellation rate (37.04%) with City Hotels having a higher rate (41.73%) than Resort Hotels (27.76%)
- **Booking Patterns:** Monthly booking trends showing seasonality by hotel type
- **Stay Duration:** Average length of stay by hotel type
- **Guest Demographics:** Composition of guests (adults, children, babies), top countries of origin, and customer types
- **Revenue Analysis:** Average Daily Rate (ADR) trends by month and hotel type

### Interactive Visualizations
- Monthly booking trends
- Cancellation rates by country
- Distribution channel analysis

### Predictive Modeling
- Random Forest classifier to predict booking cancellations
- Model performance: 85.15% accuracy and 0.9189 ROC AUC
- Feature importance analysis highlighting key cancellation predictors

## Technologies Used
- **Python libraries:**
  - pandas & numpy: Data manipulation and analysis
  - matplotlib & seaborn: Statistical visualizations
  - plotly: Interactive visualizations
  - scikit-learn: Machine learning (Random Forest classifier)

## Key Insights
1. City Hotels experience significantly higher cancellation rates than Resort Hotels
2. Booking patterns show strong seasonality, with peak periods differing between hotel types
3. Lead time and deposit type are among the strongest predictors of cancellation
4. Distribution channels vary in their cancellation rates, with some channels having much higher risk
5. The predictive model achieved 85% accuracy in forecasting cancellations

## Applications
This analysis can help hotel management:
- Develop targeted overbooking strategies based on cancellation risk
- Optimize pricing and promotional strategies by season and hotel type
- Improve resource allocation and staffing based on booking patterns
- Implement focused retention strategies for high-risk bookings
- Enhance marketing efforts for specific distribution channels and market segments

## Author
Cansu Beyaz
