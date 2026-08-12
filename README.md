# Apartment Rental Market Analysis & Price Prediction

## Project Overview
In this project, our team acted as data analysts developing backend insights for a consumer-facing real estate platform. The goal is to help users explore local apartments, compare amenities (bathrooms, bedrooms, fees), and understand regional rent ranges. By analyzing property similarities and market drivers, this analysis aims to match users with the best choices for their specific requirements and budgets.

## The Data
The dataset is sourced from the UC Irvine (UCI) Machine Learning Repository. It contains detailed property features, rental prices, and location data. Prior to analysis, the data underwent rigorous cleaning, including the handling and dropping of missing values as needed to ensure robust modeling.

## Methodology & Core Research Questions
Our analytical approach was divided into four main technical phases to understand how specific variables impact one another:

*   **Exploratory Data Analysis (Pandas & Data Viz):** What factors highly influence apartment rental prices across different cities and categories?
*   **Regression Modeling:** How accurately can we predict the specific price of an apartment based on the number of rooms, fee, state, and currency provided?
*   **Classification:** Based on its square footage, can we predict whether an apartment falls into a high or low price tier?
*   **Ad-Hoc Analysis:** Do higher rental cost apartments (greater than $1500 a month) tend to have photos listed on the website?

## Team Contributions
*   This project was a fully collaborative effort. The data cleaning, exploratory data analysis, regression modeling, and final documentation were jointly engineered and co-authored by:
*  Kate Aldrich
*  Stella Hung
*  Malayka Mudassar
*  Sarah Toniuk

## Future Iterations & Improvements
* **Advanced Modeling:** To improve the current 40.6% predictive accuracy, future iterations should explore non-linear regression models to better handle extreme pricing outliers.
* **Threshold Adjustment:** Re-evaluating and adjusting the dollar-amount threshold that classifies an apartment as "expensive" could yield more accurate classification results regarding marketing features like photos.
