# _Inventory Prediciton_

## Synopsis

This project explores the well-known problem of time series. We tested out different models from SARIMA models to LSTM neural networks for inventory prediction.

The code includes some exploration analysis, trend analysis, and finally some models in Jupyter notebooks. These models were then rewritten into Python scripts.

The purpose of the web app is to provide some insights on the data, give recommendations by introducing product names, and getting recommended products based on the ones commonly bought together.

Finally, it also provides predictions for items in the inventory, giving you a glimpse of what the rate of consumption will be in the following weeks.

## Libraries used

- Flask
- statsmodels
- seaborn

## Motivation

Our primary motivation was to work on real datasets solving real problems for companies. Being able to provide forecasts on inventory could lead to better stock management since both overstocking and understocking mean losing money. Recommendations are also a big feature because they provide both customers and salespeople with a better experience during a sale.

## File Structure

- **notebooks/** includes the Jupyter notebooks that we used for exploration and testing

## Future Work

There is still a lot of room for improvement. For example, making more transformations to the data. During the data exploration, we found that the transformation that had the best results was the log function, but there are many ways to stationarize and it could be worthwhile to explore more. The recommendation engine can be expanded into a product-to-product recommendation using NLP over the product features and descriptions to find similar products. This is useful when you run out of stock or if a company wants to find a similar product but from another brand.
