# Alchemy-of-Real-Estate-Value

## Introduction
Zillow is a company that provides an online platform for various aspects of the real estate industry, such as buying, selling, renting, or financing properties. Zillow’s main goal is to help people make smart decisions in the real estate market.

## Business Understanding
For GNB Bank, understanding and predicting customer churn is critical for several reasons. First and foremost, customer churn impacts the bank's revenue and profitability. Acquiring new customers is more expensive than retaining existing ones, so preventing churn can lead to significant cost savings. Moreover, customer retention contributes to a positive reputation and strengthens the bank's position in the highly competitive financial industry. By leveraging machine learning techniques to predict customer churn, GNB Bank can proactively address the needs of at-risk customers, personalize their banking experience, and develop targeted marketing campaigns to foster long-term customer loyalty.

## Data Understanding
The dataset, zillow_data.csv, is ideal for this project, offering historical real estate price data for multiple zip codes. Its substantial size and granularity provide rich information. Descriptive statistics give an overview of key features, and feature selection is justified based on relevance and significance. While the dataset holds great potential, it's essential to address potential missing values, outliers, and the assumption of trend continuity. Overall, it forms a valuable foundation for data-driven insights and recommendations in this project.
The dataset consists of a total of 14,723 rows and encompasses 272 different variables:

* RegionID: A unique identifier ranging from 58196 to 753844.
* RegionName: A unique Zip Code, varying between 1001 and 99901.
* City: The city in which the respective zip code is situated.
* State: The state where the zip code is located.
* Metro: The metropolitan area encompassing the zip code.
* CountyName: The county within which the zip code falls.
* SizeRank: A numerical ranking reflecting the size of the zip code, ranked from 1 to 14723.
* 1996-04 through 2018-04: These columns represent the median housing sales values for each month, from April 1996 through April 2018, amounting to 265 data points of monthly data for each zip code.

## Modeling
The modeling procedure entails preprocessing the data, splitting it into training and testing sets, and applying time series models, such as ARIMA, to forecast real estate prices for each zip code. Model performance is assessed using metrics like RMSE, and the top 5 investment-worthy zip codes are identified based on forecasts and specific investment criteria.

## Conclusion
* Top Zip Codes: We've identified the top 5 zip codes for investment, based on our rigorous analysis.
* Reliable Models: Our time series models, validated by RMSE, are reliable for price predictions.
* Historical Insights: We've uncovered valuable historical trends to guide investment decisions.

## Recommendation
* Focus on Top 5: Invest significantly in the top 5 zip codes with consistent growth.
* Diversify Thoughtfully: Diversify investments to manage risk while staying aligned with growth areas.
* Regular Monitoring: Continuously monitor the market to adapt strategies to evolving conditions.
* Enrich Data: Enhance predictions by incorporating additional data sources.
* Mitigate Risk: Implement risk mitigation strategies and contingency plans for market fluctuations.

## Non Technical Presentation
To access the canvas slides click on the link [Presentation](https://www.canva.com/design/DAFuUuMXaP4/2NGDxOnn-SgmyIjRGLYKvA/edit?utm_content=DAFuUuMXaP4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
