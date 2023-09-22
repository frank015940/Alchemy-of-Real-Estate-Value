# Alchemy-of-Real-Estate-Value

# Overview
1. Business Understanding
2. Data Understanding
3. Modelling
4. Conclusion
5. Recommendation

## Business Understanding
This project aims to improve Zillow's property valuation models, delivering precise and timely home price estimates. By enhancing the accuracy of housing predictions, Zillow provides valuable insights to homebuyers, sellers, and investors. This, in turn, empowers users to make informed real estate decisions, ultimately bolstering Zillow's position as a trusted real estate platform.

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

## Modelling
The modeling procedure entails preprocessing the data, splitting it into training and testing sets, and applying time series models, such as ARIMA, to forecast real estate prices for each zip code. Model performance is assessed using metrics like RMSE, and the top 5 investment-worthy zip codes are identified based on forecasts and specific investment criteria.

## Conclusion
* Top Zip Codes: We've identified the top 5 zip codes for investment, based on our rigorous analysis.
* Reliable Models: Our time series models, validated by RMSE, are reliable for price predictions.
* Historical Insights: We've uncovered valuable historical trends to guide investment decisions.
* Zip Code 48822
    * Invest: $184,700
    * 2-Year ROI: 7.20%
* Zip Code 49309:
    * Invest: $49,200
    * 2-Year ROI: 5.24%
* Zip Code 29645:
    * Invest: $116,500
    * 2-Year ROI: 1.44%
* Zip Code 48835:
    * Invest: $138,600
    * 2-Year ROI: 0.01%
* Zip Code 49265:
    * Invest: $159,600
    * 2-Year ROI: -0.48%

## Recommendation
* Zip codes 48822, 49309, 29645, and 48835 emerge as prime investment opportunities, boasting promising ROIs and expected property value appreciation over the next two years. We recommend that Fahari seriously consider these options for their investment portfolio. These choices strike a harmonious balance between appealing property prices and lucrative returns on investment, aligning perfectly with Boma Yangu's risk tolerance.
* Regarding zip code 49265, we advise Fahari to exercise prudence, as it hints at the potential for a negative return on investment.

## Next step
* Focus on Top 5: Invest significantly in the top 5 zip codes with consistent growth.
* Diversify Thoughtfully: Diversify investments to manage risk while staying aligned with growth areas.
* Regular Monitoring: Continuously monitor the market to adapt strategies to evolving conditions.
* Enrich Data: Enhance predictions by incorporating additional data sources.
* Mitigate Risk: Implement risk mitigation strategies and contingency plans for market fluctuations.

## Non-Technical Presentation
To access the canvas slides click on the link [Presentation](https://www.canva.com/design/DAFuUuMXaP4/2NGDxOnn-SgmyIjRGLYKvA/edit?utm_content=DAFuUuMXaP4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
