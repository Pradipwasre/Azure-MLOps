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
    