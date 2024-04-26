# Proximity to Landmarks as a Predictor of Prices in the Airbnb Market
## ADA24 Final Project -- Group 1
Stuart Fong, Robbie Hendler, Kunyan Li, Huy Nguyen, Peter Danilin

<img src="https://i.imgur.com/BjYsFxN.png" alt="Airbnb review wordcloud" width="500"/>

### Abstract
> The tourism industry has witnessed a shift towards more personalized travel experiences, prompting the need for innovative service models that cater to individual preferences. This study focuses on the fast growing peer-to-peer accommodation sector, exemplified by Airbnb, which has reshaped lodging options for travelers by offering more economical alternatives to traditional hotels. Particularly, this project explores the influence of spatial factors, such as proximity to landmarks, on Airbnb listing prices across three major cities: Toronto, Sydney, and Barcelona. Through log-linear and non-linear regression models, incorporating novel predictors like distances to nearest and most popular landmarks, we confirm these spatial features’ substantial impact on pricing. The models demonstrate robust predictive power in price predictions. Our findings not only enhance the understanding of factors affecting Airbnb prices but also serve as valuable insights for investors and users in the platform’s community, guiding investment decisions and enabling more informed rental choices.

In this work, we focus on the Airbnb listing prices inside of three major cities: Toronto, Sydney, and Barcelona. 
1. We show how Airbnbs are clustered based on their location using Global Moran’s I and Anselin Local Moran’s I statistics.
2. We analyze the contribution of spatial features to the overall price of an Airbnb listing while controlling the other features using log-linear regression models.
3. We propose non-linear regression models to more accurately predict the prices of Airbnb listings.

### Files
* `Airbnb_predictor.ipynb`: Pre-processing, EDA, and non-linear regression models
* `Spatial_Hypothesis_Testing.ipynb`: Hypothesis testing and visualizations for clustering of Airbnb listings
* `LASSO_Ridge.ipynb`: LASSO and ridge regression models
* `Linear_Regression_Hypothesis_Testing.ipynb`: Hypothesis testing and residual analysis for linear regression models
* `airbnb_attractions.csv`: Base pre-processed dataset
* `airbnb_attractions2.csv`: Pre-processed dataset with additional features
* `attractions-merged.csv`: Tourist attractions for Toronto, Sydney, and Barcelona
