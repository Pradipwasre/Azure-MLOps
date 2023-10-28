# Business Objective:

Deep Learning has become a fundamental part of the new generation of Time Series
Forecasting models, obtaining excellent results While in classical Machine Learning
models - such as autoregressive models (AR) or exponential smoothing - feature
engineering is performed manually and often some parameters are optimized also
considering the domain knowledge, Deep Learning models learn features and
dynamics only and directly from the data. Thanks to this, they speed up the process
of data preparation and are able to learn more complex data patterns in a more
complete way.

Till now, in this sequence of time-series projects, we have covered the machine
learning topics such as Autoregression modelling, Moving Average Smoothing
techniques, ARIMA model, Multiple linear regression, Gaussian process, and ARCHGARCH models.

In this project, we will demonstrate how deep learning in time series can be used.
There are four major models which will be built,

    > Multi-Layer Perceptron (MLP)
    > Convolutional Neural Network (CNN)
    > Long Short-Term Memory (LSTM)
    > Hybrid CNN – LSTM
    
## Data Description:
--------------------------------------------------------------------------------
    
The dataset is “Call-centres” data. This data is at month level wherein the calls are
segregated at domain level as the call centre operates for various domains. There are
also external regressors like no of channels and no of phone lines which essentially
indicate the traffic prediction of the inhouse analyst and the resources available.
The total number of rows are 132 and number of columns are 8:

    • Month, healthcare, telecom, banking, technology, insurance, no of phonelines
    and no of channels.

* Aim

We aim to build four deep learning models such as MLP, CNN, LSTM, and a hybrid
CNN-LSTM model on the given time series dataset.

Tech stack

* Language - Python
* Libraries - pandas, numpy, matplotlib, TensorFlow

 Approach
    1. Import the required libraries and read the dataset

    2. Perform descriptive analysis

    3. Data pre-processing
        * Setting date as Index
        * Setting frequency as month
    
    4. Exploratory Data Analysis (EDA) -
        * Data Visualization
    
    5. Set the training format
        * Reshape the input data
    
    6. Perform train-test split
    
    7. MLP model
        * Define learning rate, number of epochs, and optimizer.
        * Build a sequential model with dense layers
        * Fit and train the model
        * Make predictions on the test data
        * Plot the results
    
    8. CNN model
        * Reshape the data in three dimensions
        * Define learning rate, number of epochs, and optimizer.
        * Build a sequential model with convolution, max-pooling layers
        * Fit and train the model
        * Make predictions on the test data
        * Plot the results
    
    9. LSTM model
        v Define learning rate, number of epochs, and optimizer.
        * Build a sequential model with LSTM layer and dense layers
        * Fit and train the model
        * Make predictions on the test data
        * Plot the results
    
    10. CNN-LSTM model
        * Reshape the data in four dimensions
        * Define learning rate, number of epochs, and optimizer.
        * Build a sequential model
        * Fit the model
        * Make predictions on the test data
        * Plot the results

--------------------------------
# Time Series Introduction

    - We're going to discover how it deffers from other types of data you've previously encountered and why
    - Time Series is a sequence of information which attaches a time period to each value
    - The value can be pretty much anything measurable
    - It depends on time in some way, like prices, humidty or number of people
    - As long as the values we record are unambiguous, any medium could be measured with Time series.
    - There aren't any limitations regarding the total time span of our Time Series.
    - It could be a minute, a day, a month or even a century
    - All we need is a stating and an ending point. 

## Time Series Basics

    - Chronological Data
    - Cannot be shuffled
    - Each row indicate specific time record
    - Train - Test split happens chronologically
    - Data is analyzed univariately and multivariately (for given use case)
    - Nature of the data represents if it can be predicted or not


## Data Examining and Preporocessing

    - Reading data using pandas - describe, head
    - Check for null values
    - Line plot for each feature
    - Convert date from string to date time feature
    - Setting the desired frequency
    - Handling missing values
    - QQ plots
