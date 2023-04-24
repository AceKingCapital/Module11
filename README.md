# Module11: Forecasting net Profit

### Analysing Mercado Libre's financial & user data in clever ways to help the company grow more than 200 million users.

## HvPlot to visualize the data for May 2020:
![HVPlot 1](https://user-images.githubusercontent.com/118318397/234135978-a4c7cd64-0820-43ab-82e9-6c3c6a340140.JPG)

Question: Did the Google search traffic increase during the month that MercadoLibre released its financial results?

Answer: Yes, the Google search traffic increased from an overall monthly median value of 51 to 54 in May 2020 - the month that MercadoLibre released its financial results.

## Average traffic by the day of week:
![AverageTraffic](https://user-images.githubusercontent.com/118318397/234136225-236b9915-aab5-44ee-8c84-19daa4a34a6f.JPG)

## HvPlot to visualize the hour of the day and day of week search traffic as a heatmap:
![Heatmap](https://user-images.githubusercontent.com/118318397/234136263-f1664bae-d56e-4b1a-98b4-79f43882ef7e.JPG)

Question: Does any day-of-week effect that you observe concentrate in just a few hours of that day?

Answer: Based on the heatmap, it appears that search traffic is highest during 11pm to midnight on weekends and from 11pm to 1am on all weekdays except Friday.

Average traffic by the week of the year:
![avgtraffic](https://user-images.githubusercontent.com/118318397/234136421-a62f5695-8112-481d-9c1d-ab67d07ff085.JPG)

Question: Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?

Answer: The traffic tends to increase during the winter holiday period. However, it initially dips in weeks 40 and 41 before increasing.

## HvPlot to visualize the closing price of the df_mercado_stock DataFrame:
![closingprices](https://user-images.githubusercontent.com/118318397/234136552-41c947ab-e714-4fca-a61e-cf63b2128227.JPG)

## HvPlot to visualize the close and search trends data for first half of 2020:
![VariableClose](https://user-images.githubusercontent.com/118318397/234136965-fe2dee90-157e-4a67-9809-f963fb92afb5.JPG)
![Variable SearchTrends](https://user-images.githubusercontent.com/118318397/234136992-2490aab0-af5d-4caa-ba28-d021969590be.JPG)


Question: Do both time series indicate a common trend that’s consistent with this narrative?

Answer: Subsequent to COVID-19 being declared a pandemic by WHO in March 2020, the stock price and search declined dramatically. Both, the stock price and search, gradually picked up around April 2020 and then consistently went up.

## HvPlot to visualize the stock volatility:
![StockVolitality](https://user-images.githubusercontent.com/118318397/234137095-d20bbf3f-e1b5-4267-a7a4-3073182ac376.JPG)

Question: Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?

Answer: There does not appear to be a predictable relationship between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns.
![ForecastingStockprices](https://user-images.githubusercontent.com/118318397/234137638-0c93a78d-8f52-48fa-b201-b6f65b613b8e.JPG)

**use hvPlot to visualize the yhat, yhat_lower, and yhat_upper columns over the last 2000 hours
![yhatHVPlot](https://user-images.githubusercontent.com/118318397/234137276-7e5f7a8a-f4d9-4816-9caa-50a1ff2d43bb.JPG)

## hvPlot to visualize the daily sales figure:
![dailysalesfigures](https://user-images.githubusercontent.com/118318397/234137376-4fef4254-5f78-4f5a-8806-9477decf3ac8.JPG)
