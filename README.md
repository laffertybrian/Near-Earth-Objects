# Asteroid Classification
## Machine Learning Model Protecting Earth 

**Author**: Brian Lafferty

### Classification challenge:

Tranforming descriptive Near Earth Object (NEO) data into a predictive model used to protect Earth from annihilation.

This project took a different turn after finding a key relationship between two features. It turned out that an untuned decision tree could protect Earth with only two features! After finding this link, I attempted to protect Earth without these key features and began training models on the reduced dataset.

### Data
Over 4500 near earth object (NEO) oberavtions from the National Aeronautics and Space Administration. Data included information about the objects size, orbit, speed and totaled 40 different features.


## Methods
- Addressing class imbalance with undersampling and oversampling strategies
- Normalizing skewed data
- Visualization of data to explore and find underlying trends
- Used Principal Component Analysis (PCA) to improve model performance
- Analyzed data using multiple machine learning models
- Tuned hyperparameters of top two models for improved performance

## Model
The machine learning model preformed the best for this project was XGBoost. This model preformed best with the data when compared with a linear regression, k neareset neighbors, and random forest models. After tuning hyperparameters of the XGBoost model, it produced an accuracy score of 0.9453 on the test data.

## Results

![sample image](fig1.png)

> Identified key features that proved to be the secret to predicting hazardous objects.

#### Histogram of the Prediction Difference
![sample image](fig2.png)

> Visualizing the key features in this way allows for a clear understanding of the relationship the model was able to find.

#### XGBoost Model Metrics

-   The XGBoost model had an accuracy score of .94539 on the dataset without the key features.
-   The model had 40 false negatives! The worst possible option.
-   The model had 24 false positives. Which avoids Earths destruction, but does cause world wide panic.
-   With hyperparameter tuning the model improved its accuracy score by .02987

## Recommendations:
- When protecting Earth there is no choice besides the Decision Tree Model. It was able to predict all hazardous NEOs.




## Limitations & Next Steps
This dataset did not pan out how I had envisioned. The project does highlight the importance of data analysis and understanding the features in each dataset. As I continue to add to my machine learning knowledge I will continue to review this dataset and see if there are additional strategies I can explore.


### For further information


For any additional questions, please contact me on [LinkedIn](https://www.linkedin.com/in/brian-lafferty). 
