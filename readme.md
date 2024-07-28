# Fairfax County Real Estate Analysis

This repo contains notebooks to gather data and train models to predict home sales price for homes in Fairfax County, VA.

To gather a dataset I downloaded publicly available real estate related data from https://www.fairfaxcounty.gov/maps/open-geospatial-data. I also wanted to include data that adds information about the location of the homes sold, so I used the wmata api to get locations for metrorail stations to calculate distances from sold homes to metro stations.

- The query_wmata_api notebook shows how metro station location data was queried, organized, and saved to a small csv file
- The prepare_sales_price_data notebook shows how the various datasets downloaded from Fairfax County's data portal, as well as the wmata data, were used to create a dataset to train machine learning models with
- The sales_price_regression notebook uses the prepared dataset to experiment with training a few different models to try and predict the sales price of a single family home in Fairfax County in 2023.


