![pulsar_star_wp](https://gssc.esa.int/navipedia/images/a/a9/Example.jpg)


# Predicting Market Movements Using NLP Techniques

### Project Overview
Objective: The main goal of this project is to use machine learning techniques to predict market movements based on sentiment analysis of text data. This involves analyzing news headlines to gauge market sentiment and predict subsequent market behavior.

Context: Financial markets are heavily influenced by news events and public sentiment as captured in news headlines. The challenge lies in accurately interpreting these short and often ambiguous text snippets to predict market trends. Common obstacles include the variability in headline tone, context, and the challenge of aligning textual sentiment with market data.

Significance: Achieving accurate predictions based on news headline sentiment is crucial for investors, analysts, and policymakers. It can lead to better investment decisions, improved risk management, and a deeper understanding of market dynamics. Reliable predictions based on headline sentiment can provide a significant edge in financial markets.

Goal: The ultimate aim of the project is to identify patterns in news headline sentiment that correlate with market movements, improve the accuracy of market predictions, and prioritize specific headlines for more detailed investigation.
## Team Members

- Younes: [GitHub](https://github.com/ZahYou)
- Anjelo: [GitHub](https://github.com/anji94)

## Jupyter Notebooks

This project consists of several Jupyter Notebooks that serve different purposes:

1. **eda.ipynb**: 

This notebook focuses on Exploratory Data Analysis (EDA) and preprocessing of news headline data. It includes data cleaning, tokenization, removal of stop words, and sentiment scoring using models like VADER and TextBlob.

2. **sentiment.ipynb**: 

This notebook covers feature engineering, including the aggregation of sentiment scores over time intervals, and the synchronization of sentiment data with market data. It also explores various visualization techniques to understand the data better.


3. **model.ipynb**: 

This notebook is dedicated to model training and evaluation. It includes training different machine learning models (e.g., linear regression, LSTM, Random Forest) on the prepared dataset, hyperparameter tuning, and evaluation using metrics like RMSE, MAE, and R².



## Installation and Setup

To set up the project locally, follow these steps:

1. Clone the repository:
```
git clone https://github.com/daistmarco/PredictingPulsarStar.git
```
2. Navigate to the project directory:
```
cd your-repository
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
4. Download the modified dataset and place it in the project directory. The original dataset can be acquired from the link [xxx](link here).

5. Additional setup steps:

Ensure you have the necessary API keys if fetching real-time data.
Modify the configuration files as needed to point to the correct data sources and directories.


**Note:** If any of the above files are missing, the corresponding functionality may not work as expected.

Once the setup is complete, you can use the provided functions, such as `ann_prediction(csv_file)`, to make predictions on new data using the pre-trained models.


## Dataset

The dataset consists of news headlines collected from various financial news websites. Market data is sourced from Yahoo Finance. All data is publicly available, and links are provided in the respective notebooks.


## Attribute Information

The dataset contains the following attributes:

1. **Headline:** The actual news headline.
2. **Timestamp:** The time when the headline was published.
3. **Sentiment Score:** The sentiment score calculated from the headline.
4. **Market Data:** Market indicators such as stock prices, trading volumes, etc.


The dataset contains a total of xxx examples, with xxx positive examples and xxx negative examples.


## EDA/Cleaning

The EDA involves understanding the distribution of sentiment scores, visualizing the relationship between sentiment and market movements, and identifying any data quality issues. Cleaning steps include removing duplicates, handling missing values, and standardizing text formats.



## Model Choices

What models did you test against each other and why? How did you optimize them? 

## Results

What metric did you use and why? How did you final model perform? 

## Prediction Function

What happens when a prediction is made using the final function? What scripts are run? 

## Final Remarks

This project demonstrates the potential of using NLP techniques for predicting market movements based on news headlines. The approach can be further refined by incorporating more data sources, improving sentiment analysis models, and enhancing the integration with real-time data feeds. The findings underscore the value of sentiment analysis in financial market prediction and open avenues for further research and development.
