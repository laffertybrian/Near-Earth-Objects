# Asteroid Classification
## Machine Learning Model Protecting Earth 

**Author**: Brian Lafferty

### Classification challenge:

Tranforming descriptive near earth object data into a predictive model used to protect Earth from annihilation.


### Data
Over 4500 near earth object (NEO) oberavtions from the National Aeronautics and Space Administration. Data included information about the product (weight, fat content, category, etc.) and sales establishment infomation (size, type, etc.).


## Methods
- Data cleaned and prepared using imputing and category standardization strategies
- Visualization of data to explore and find underlying trends
- Analyzed data using multiple machine learning models to optimize results

## Model
The machine learning model selected for this project was a regression tree. This model preformed best with the data when compared with a linear regression model. After tuning hyperparameters of the regreesion tree, it produced a R^2 value of 0.5947 on the test data.

## Results

![sample image](fig1.png)

> Identified categories with opportunity for growth and product segmentation.

#### Histogram of the Prediction Difference
![sample image](fig2.png)

> Visualizing the prediction differences in this way allows for clear understanding of the models performance.

#### Regression Tree Metrics

-   The MSE is 738.31. This shows that the models average error is $738.31 per item prediction. The average value of Item_Outlet_Sales is $2181.29, so the error represents approximately 33% of the total sales.
-   The model can predict the Item_Outlet_Sales target within $100 dollars 14.36% of the time.
-   The model had 555 predictions that were over $1000 off of the actual value. That represents approximately 26% of the predictions.
-   49% of the values had predictions over $500 from the actual value.

## Recommendations:
- I do not recommend using the Decision Tree Model for predicting the Item_Outlet_Sales
- Breakfast category should be expanded to increase market share
- Location of stores matter. Future stores should be in Outlet_Location_Type of Tier 2 or above



## Limitations & Next Steps
The regression tree model did not perform to the level I had envisioned. As I continue to learn more about Machine Learning, I will conintue to improve this analysis and strive to improve upon the results.


### For further information


For any additional questions, please contact me on [LinkedIn](https://www.linkedin.com/in/brian-lafferty). 
