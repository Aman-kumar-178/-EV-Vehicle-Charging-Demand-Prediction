# EV Adoption Forecasting —

As electric vehicles (EVs) become increasingly popular, forecasting future adoption is crucial for effective infrastructure development, especially EV charging networks. This project focuses on building a predictive model to estimate future EV demand using historical registration data from Washington State.


##  Project Motivation

The shift from traditional vehicles to electric vehicles is a key step toward reducing carbon emissions and promoting sustainable transportation. However, without accurate demand forecasting, infrastructure development (charging stations, grid planning, etc.) may fall short.  
**Goal**: Help urban planners and decision-makers predict EV adoption to avoid future infrastructure gaps.

##  Problem Statement

Using historical electric vehicle registration data from 2017 to 2024, the objective is to:
- Forecast future EV growth (monthly/yearly)
- Understand regional and vehicle-type-wise adoption trends
- Assist policymakers in making data-driven infrastructure decisions


## 🧠 Project Approach (Theoretical Pipeline)

### 1. **Data Understanding**
- Data from Washington DOL (2017–2024)
- Monthly vehicle registrations by county and type
- Features include:
  - **BEVs**, **PHEVs**
  - **Total EVs**, **Non-EVs**
  - **Passenger vs Truck Usage**
  - **Percent EV adoption**

### 2. **Exploratory Data Analysis (EDA)**
- Identify counties with the highest adoption
- Compare BEV vs PHEV trends
- Analyze seasonality and year-over-year growth

### 3. **Feature Engineering**
- Extract time-based features (month, year, quarter)
- Compute growth rates
- Create lag features for time series

### 4. **Modeling Approaches**
- **Regression models**:
  - Linear Regression
  - XGBoost

### 5. **Evaluation Metrics**
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score (Coefficient of Determination)


## 🌐 Real-World Applications

- **Urban Planning**: Helps plan charging station locations and capacity.
- **Energy Management**: Supports electric utilities in estimating future grid load.
- **Policy Making**: Aids in EV subsidy and incentive planning.
- **Auto Industry**: Predicts market trends for EV manufacturer

##  Why This Project Matters

 Supports **sustainable development goals**  
 Combines **data science with real-world impact**  
 Great example of **time series forecasting**  
Excellent addition to a **data science portfolio**

---

 ## Contact

**Created by:** Aman Kumar  
**Email:** aman1782003@gmail.com
**GitHub:** https://github.com/Aman-kumar-178.



