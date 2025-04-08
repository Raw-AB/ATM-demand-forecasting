Data source: https://www.kaggle.com/datasets/nittha/atm-data-m2

Key Insights :
1- This data set is highly seasonal, it consistent patterns that repeat at regular intervals like higher withdrawals during certain months or certain weekdays.
2- dates are duplicates due to different withdrawals at the same day.
3- Saturday has the highest withdrawals, it could be due to people withdraw cash on Saturdays to prepare for the weekend. Many businesses and banks are closed on Sundays, reducing ATM visits.
4- High withdrawal months are December (12), October (10) and July (7). December is Holiday season (Christmas, New Year). October season of Diwali (major Indian festival). July Could be linked to seasonal spending, travel, or school fees.
5- there was an Exponential Growth and Sudden Decline. it could be due to: 2014 peak: Economic growth, increased ATM usage. 2015 slight drop: Possible early signs of digital payments increasing. 2016 dramatic drop: Demonetization in India (November 2016). The Indian government banned ₹500 and ₹1000 notes, causing a huge cash shortage and forcing people to shift to digital payments. ref: https://www.strategy-business.com/article/What-Happened-after-India-Eliminated-Cash
6- Withdrawals are higher on holidays.

Business Value:
we could develop a pipeline to forecast future withdrawals and allocate resources accordingly.
also, planning for periods of high withdrawal demand.

Conclusion:
This dataset is highly complex and seasonal. Classical models (ARIMA, SARIMA, SARIMAX) struggled to capture complex patterns.  Facebook Prophet has strong performance in modeling trend and seasonality while LSTM achieved the lowest RMSE.

What's next?
A potential hybrid approach combining Prophet's long-term forecasting and LSTM’s short-term precision could further enhance performance.
