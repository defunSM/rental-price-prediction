# rental-pricing-explore

Credit to the [Data Science Working Group](http://datascience.codeforsanfrancisco.org) for this template.

## Project Intro/Objective
The purpose of this project is to determine appropriate pricing for rental properties recently acquired by a real estate company in Taipei City. This is in order to maximize the rental income while still ethically charging accurate prices to potential tenants. This will also help with tenant satisfaction and retention if they are paying a reasonable and fair price while avoiding any legal issues that may arise from overcharging. In essense this project will help with financial success, legal compliance and tenant satisfaction for the newly aquired rental properties in Teipei City.

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* Pandas, jupyter, Seaborn


## Project Description

This project creates a linear regression model to identify fair pricing for each rental property in Teipei city. The project utilizes cleaned historical data to be able to make a model that can provide accurate and ethical prices for rental properties. 

Four key features that were looked at to help identify the price of rental properties are distance from MRT station, house age, unit price area, and number of convinence stores near by. Using these features the linear regression model can provide a price with a MSE of 94.

One of the challenges of this data set was cleaning the dataset by removing outliers and missing data. Through the bivariate analysis two features that affect the price of rental prices the most are the distance from MRT station and the number of convinence stores. Specifically the shorter the distance from the MRT station the higher the pricing and the more convinence stores there are the higher the pricing for rental properties.

