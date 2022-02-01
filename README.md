#Naive stock prediction in Dash

This project purpose is to learn Dash and its components by making a simple dashboard with naive future stock price prediction. The data is automatically scraped from the URL site www.stooq.pl and the basic informations are scraped from the Google Finance site. There is possiblity to choose between the companies from WIG20 Warsaw Stock Exchange. The prediction of the future price is made by naive average model from the last 3 days prices. Furthermore there is implemented an additional RandomForest algorithm for making prediction if the price of stock will go up in the next day or no.

To create the models, no in-depth EDA or advanced feature engineering were used - the goal is to implement the model under Dash dashboard, not to create great predictive models.

These results are not credible and do not constitute any proposition or financial advice for any investment and should not be taken into account in making any such investment. This dashboard is designed for learning and entertainment purposes, not as an investment tool.