# cde_linear_regression

### Project Proposal Template

#### Analysis of Los Angeles Housing Market (MVP)

Urban housing markets were heavily destabilized in the aftermath of the Covid-19 pandemic. For investors, this presents an opportunity to capitalize in a new market environment. Redfin wants to understand the LA housing market so that it invest in properties. Our objective is to explore whether the sale price of a home can be modeled against other housing/geographic features. We will seek to produce a regression model that can best interpret a relationship for sale price and a model that can best predict home sale price in Los Angeles. 

Can we predict housing prices using housing features and surrounding socio-economic and geographic data? 

#### Data Description:

Home data was scraped from [Zillow](zillow.com) and geographic socio-economic data was scraped from [City-Data.com](city-data.com) by zip code. 

Each row represents a ‘Recently Sold’ property in the Los Angeles area. Of 600+ home sales scraped, 288 were used in our final analysis. We excluded manufactured homes, lots, multi-family residences.

Our analysis leverages BeautifulSoup and Selenium for web scraping, Numpy and Pandas for data processing, Scikitlearn and Statsmodels for machine learning, Matplotlib and Seaborn for data visualization, and Folium, Geopandas and Geopy for geospatial visualization.

#### Tools:

Our analysis leverages BeautifulSoup and Selenium for web scraping, Numpy and Pandas for data processing, Scikitlearn and Statsmodels for machine learning, Matplotlib and Seaborn for data visualization, and Folium, Geopandas and Geopy for geospatial visualization.

#### MVP Goal:

Our initial goal will be to produce a base linear regression model using a train-test-validate split and only features from the home. Then, we will analyze the diagnostic plots to evaluate our models and inform feature selection, feature engineering, and model selection.

