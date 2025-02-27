# Flight Booking Dataset Analysis

## Introduction

The objective of this study is to analyze the flight booking dataset obtained from the "Ease My Trip" website and to conduct various statistical hypothesis tests to derive meaningful insights from it. The study employs the 'Linear Regression' statistical algorithm to train the dataset and predict a continuous target variable, which is the ticket price. 

'EaseMyTrip' is an internet platform for booking flight tickets, and this platform is used by potential passengers to buy tickets. A detailed study of this dataset will help in the discovery of valuable insights, which can be of significant benefit to passengers and the industry.

## Data Collection and Methodology

Data was collected using the **Octoparse scraping tool** from the **Ease My Trip** website. The dataset consists of two parts:
- One for economy class tickets.
- One for business class tickets.

A total of **300,261 distinct flight booking options** were extracted over a period of **50 days** from **February 11th to March 31st, 2022**. The source of the data is secondary, collected directly from the **Ease My Trip** website.

**Dataset Source:** This dataset is available on [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction). Please check the dataset's original page for any licensing and usage terms.

## Dataset

The dataset contains information about flight booking options from **Ease My Trip** for travel between India's top 6 metro cities. There are **300,261 data points** and **11 features** in the cleaned dataset.

### Features

Below is an explanation of the various features included in the dataset:

1. **Airline**: The name of the airline company. This is a **categorical** feature with 6 unique airlines.
2. **Flight**: The flight code. This is a **categorical** feature.
3. **Source City**: The city from which the flight takes off. This is a **categorical** feature with 6 unique cities.
4. **Departure Time**: A **categorical** feature created by grouping time periods into bins. It has 6 unique time labels representing different departure times.
5. **Stops**: A **categorical** feature with 3 distinct values that stores the number of stops between the source and destination cities.
6. **Arrival Time**: A **categorical** feature created by grouping time intervals into bins, with 6 distinct time labels representing different arrival times.
7. **Destination City**: The city where the flight will land. This is a **categorical** feature with 6 unique cities.
8. **Class**: A **categorical** feature indicating the seat class. It has two distinct values: **Business** and **Economy**.
9. **Duration**: A **continuous** feature representing the total travel time between cities, measured in hours.
10. **Days Left**: A **derived feature** calculated by subtracting the booking date from the trip date. It gives the number of days remaining before the flight departs.
11. **Price**: The **target variable** containing the ticket price.

## Methodology

The data will be analyzed using various statistical hypothesis tests. Additionally, a **Linear Regression** model will be implemented to predict the target variable, **Price**, based on the other features in the dataset.

## Conclusion

The insights gathered from this analysis will be valuable to passengers and the airline industry, providing a better understanding of the factors that influence flight prices and helping passengers make informed decisions while booking their flights.

