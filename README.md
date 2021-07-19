# Unit 10—A Yen for the Future

![Yen Photo](Images/unit-10-readme-photo.png)

## Background

The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies. 

In this assignment, you will test the many time series tools that you have learned in order to predict future movements in the value of the Canadian dollar versus the Japanese yen.

You will gain proficiency in the following tasks:

1. Time series forecasting
2. Linear regression modelling

- - -

### Files

[Time-Series Starter Notebook](Starter_Code/time_series_analysis.ipynb)

[Linear Regression Starter Notebook](Starter_Code/regression_analysis.ipynb)

[CAD/JPY Data CSV File](Starter_Code/cad_jpy.csv)

- - -

### Instructions

#### Time-Series Forecasting

In this notebook, you will load historical CAD-JPY exchange rate data and apply time series analysis and modelling to determine if there is any predictable behaviour.

Follow the steps outlined in the time series starter notebook to complete the following:

1. Plotting the Settle price to check for long or short-term patterns.
   
    * Do you see any patterns, long-term and/or short?

2. Decomposition using a Hodrick-Prescott filter (decompose the settle price into trend and noise).
    
     *  Do you see any patterns, long-term and/or short?

3. Forecasting returns using an ARMA model.
    
    * Based on the p-value, is the model a good fit?

4. Forecasting the exchange rate price using an ARIMA model.
    
    * What does the model forecast will happen to the Japanese Yen in the near term?

5. Forecasting volatility with GARCH.
   
    * What does the model forecast will happen to volatility in the near term?

Use the results of the completed time series analysis and modelling to answer the following questions:

1. Based on your time series analysis, would you buy the yen now?
2. Is the risk of the yen expected to increase or decrease?
3. Based on the model evaluation, would you feel confident in using these models for trading?

#### Linear Regression Forecasting

In this notebook, you will build a Scikit-Learn linear regression model to predict CAD/JPY returns with *lagged* CAD/JPY futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

Follow the steps outlined in the regression_analysis starter notebook to complete the following:

1. Data preparation (creating returns and lagged returns, and splitting the data into training and testing data)
2. Fitting a linear regression model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

Use the results of the linear regression analysis and modelling to answer the following question:

* Does this model perform better or worse on out-of-sample data compared to in-sample data?

- - -

### Hints and Considerations

* Out-of-sample data is data that the model hasn't seen before (testing data).
* In-sample data is data that the model was trained on (training data).

- - -

### Submission

* Use the starter Jupyter Notebooks for the time series and regression analyses and host the notebooks on GitHub.

* Include a markdown that summarizes your models and findings and include this report in your GitHub repo.

* Submit the link to your GitHub project to Bootcampspot.

---

### Submission

* Create Jupyter Notebooks for the analysis and host the notebooks on GitHub.

* Include a Markdown that summarizes your models and findings and include this report in your GitHub repo.

* Submit the link to your GitHub project to Bootcampspot.

- - -

### Requirements

#### Time Series Forecasting  (20 points)

##### To receive all points, your code must:

* Utilize the Hodrick-Prescott Filter to decompose the settle price into trend and noise. (5 points)
* Use the ARMA Model to forecast returns. (5 points)
* Use the ARIMA Model to forecast returns. (5 points)
* Use the GARCH Model to forecast returns. (5 points)
#### Time Series Analysis  (15 points)

##### To receive all points, your code must:

* Analyze the yen to decide whether to make a purchase. (5 points)
* Analyze the risk of the yen. (5 points)
* Analyze the confidence of models as a basis for trading. (5 points)

#### Linear Regression Forecasting  (30 points)

##### To receive all points, your code must:

* Prepare the data, create returns and lagged returns, then split the data into training and testing sets. (5 points)
* fit a linear Regression model to the data. (5 points)
* Make predictions using the testing data. (6 points)
* Evaluate the out-of-sample performance. (7 points)
* Evaluate the In-sample performance. (7 points)

#### Linear Regression Analysis  (5 points)

##### To receive all points, your code must:

* Analyze the model performance for out-of-sample and in-sample data and write a conclusion. (5 points)

#### Coding Conventions and Formatting (10 points)

##### To receive all points, your code must:

* Place imports at the beginning of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
* Name functions and variables with lowercase characters and with words separated by underscores. (2 points)
* Follow Don't Repeat Yourself (DRY) principles by creating maintainable and reusable code. (3 points)
* Use concise logic and creative engineering where possible. (2 points)

#### Deployment and Submission (10 points)

##### To receive all points, you must:

* Submit a link to a GitHub repository that’s cloned to your local machine and contains your files. (5 points)
* Include appropriate commit messages in your files. (5 points)

#### Code Comments (10 points)

##### To receive all points, your code must:

* Be well commented with concise, relevant notes that other developers can understand. (10 points)


---

© 2021 Trilogy Education Services
