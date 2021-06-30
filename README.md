# cde_linear_regression

### Project Proposal Template

#### Question/need:

- Today, a college degree is more important than ever before. The education earnings premium has grown tremendously over the past few decades, and college degree attainment remains the surest path to a choice-filled life. Despite all we know about the benefits of a college deegree, California policymakers and educators have little information about the college destinations of high school graduates. This report seeks to fill some of this gap by providing statistics on where California high school students attend college. We also provide an interpretable model to shed light on factors affecting college enrollment. 
- This report is part of a collaboration between the California Department of Education and the University of California, Los Angeles exploring college and career readiness. 

#### Data Description:

- We examine publicly availbale records housed on [DataQuest](https://dq.cde.ca.gov/dataquest/), the California Department of Education's web-based data reporting systeem for public information about California students, tachers, and schools. Each unit of analysis will be one high school in California, and we seek to predict the college-going rate for each given a number of feature characteristics. We will use web scraping to obtain relevant data.

#### Tools:

- We are using Beautiful Soup and Selenium to retrieve data from the Dataquest website, pandas for data analysis and manipiulation, matplotlib and seaborn for visualizations, geopandas for geospatial analysis, and scikitlearn for linear regression modeling.

#### MVP Goal:

- To begin, we produce a basic baseline linear regression model with one feeature to describe College-Going Rate as a function of Free and Reduced Price Lunch Enrollment, which serves as a proxy for socio-economic status. 

<details class="details-reset details-overlay details-overlay-dark" id="jumpto-line-details-dialog" style="box-sizing: border-box; display: block;"><summary data-hotkey="l" aria-label="Jump to line" role="button" style="box-sizing: border-box; display: list-item; cursor: pointer; list-style: none;"></summary></details>

