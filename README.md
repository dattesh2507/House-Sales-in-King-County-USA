# House-Sales-in-King-County-USA

 House Sales Prediction in King County USA
 
[ House Sales Prediction in King County USA](https://github.com/dattesh2507/House-Sales-in-King-County-USA/blob/main/Data%20Analytics%20for%20House%20Pricing%20Data%20Set.ipynb)


This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

The following questions were explored in this analysis:

## Data Wrangling 

1. Drop the columns "id" and "Unnamed: 0" from axis 1 using the method
drop() , then use the method describe() to obtain a statistical summary of
the data.
2. replace the missing values of the column 'bedrooms' with the mean
of the column 'bedrooms' and 'bathrooms' with the
mean of the column 'bathrooms'using the method replace() .

## Exploratory Data Analysis
3. Use the method value_counts to count the number of houses with unique
floor values, use the method .to_frame() to convert it to a dataframe.
4. Use the function boxplot in the seaborn library to determine whether houses
with a waterfront view or without a waterfront view have more price outliers.
5. Use the function regplot in the seaborn library to determine if the feature
sqft_above is negatively or positively correlated with price.
6. use the Pandas method corr() to find the feature other than price
that is most correlated with price.

## Model Development
7. Fit a linear regression model using the longitude feature 'long' and
caculate the R^2.
8. Fit a linear regression model to predict the 'price' using the feature
'sqft_living' then calculate the R^2.
9. Fit a linear regression model to predict the 'price' using the list of features. Then calculate the R^2. 
10. Create a list of tuples, the first element in the tuple contains the name of the estimator:
      'scale'
      'polynomial'
      'model'
      The second element in the tuple contains the model constructor
      StandardScaler()
      PolynomialFeatures(include_bias=False)
      LinearRegression()
11. Use the list to create a pipeline object to predict the 'price', fit the object using
the features in the list features , and calculate the R^2.
12. split the data into training and testing sets (test_size=0.1)
13. Create and fit a Ridge regression object using the training data, set the
regularization parameter to 0.1, and calculate the R^2 using the test data.
14. Perform a second order polynomial transform on both the training data and
testing data. Create and fit a Ridge regression object using the training data, set
the regularisation parameter to 0.1, and calculate the R^2 utilising the test data
provided. 


# Conclusion

- In this analysis, I meticulously handled data preprocessing, including missing value treatment and outlier removal. Feature engineering was enhanced by encoding categorical variables and normalizing numerical features. I explored multiple models and ensured thorough hyperparameter tuning and validation to avoid overfitting.

## 🔑 Key Skills Learned 
- Using Pandas, Numpy and Scipy libraries for data manipulation
- Using Scikit-Learn to build smart models and make predictions
- Building machine learning regression models
- Building data pipelines

 ## 🛠️ Tools
The following tools were used to complete this certification: <br> <br>
  <img src="https://user-images.githubusercontent.com/84391594/152705364-f16bb223-41aa-4510-8113-51171dfe9953.png" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705271-083f8784-b3c9-4065-9733-ea3fa8ad5a7a.png" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705273-adffe1bf-b509-44d0-b3ac-671cce5071df.svg" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705324-68f777a0-3875-4b65-ae96-646643284541.png" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705298-bb170d32-3dd0-4ad4-8221-8b7b029116b4.png" height="75">
</p>
(Python, Jupyter, GitHub, IBM Watson Studio, IBM Cloud Pak)


## 📖 Libraries
The following Python libraries were used throughout the certification: <br> 
<p align="left">
  <img  src="https://user-images.githubusercontent.com/84391594/152706127-ce41990f-2588-472a-b5df-6b403a5947e6.png" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706130-5577011e-ecb3-47aa-af73-f6bd1bda05bc.png" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706132-5939da7e-7d1e-43b8-9c46-2d3fe5198dda.png" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706135-85cdd35e-922a-414a-a198-c670fbf8fb25.svg" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706148-36f27f03-1967-45d1-82d8-f6c149c6f21c.svg" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706211-7966848a-a2e1-4c4a-bc08-594a4ca6ff07.png" height="35">
 <img  src="https://user-images.githubusercontent.com/84391594/152706214-d018bc5e-1477-4de2-94d7-5c0886e0477d.png" height="35">
 <img  src="https://user-images.githubusercontent.com/84391594/152706217-c0cfd9d8-22ad-4c3b-9ac7-70a6cf2799f7.png" height="35"> <br>
</p>
