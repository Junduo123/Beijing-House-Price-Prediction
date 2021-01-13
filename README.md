# Beijing-House-Price-Prediction

Nov 2019 – Dec 2019

## Project description
The purpose of this project is to analysis key features for Beijing house sold price and date on market (DOM). The data is from the China's largest second-hand housing website, it contains more than 35 features and 310 thousands records. The prediction is base on regression model of historical transaction data through 2008 to 2018 in Beijing.
- `Team name`: Team Hortons
- `Team members`: [Junduo Dong](https://www.linkedin.com/in/junduo-dong/), [Jack Shi](https://www.linkedin.com/in/yue-shi-a921301a2/)

## Analytics Roadmap
- Exploratory analysis with distribution and correlation between features to check skewness and correlation coefficient between features, in order to define outliers and collinearity.
- Data cleaning and transformation on different types of features, such as house, community, location and market features. The market features contain average price nearby, followers and DOM, avoiding dummy trap for multi-collinearity.
- Interpretation of t-test on house price with DOM and trade time to suggest market heat through times.
- Use MLR, backward elimination, decision tree regression, random forest regression and neural network regression to predict total price, with MSE as cost function and R square as accuracy. Final model we choose is random forest regression with 91 percent accuracy and 19 depth learning curve.
- Using external resources and domain to explain the unpredictable feature DOM, across political reasons (Chinese National Regulation) and economy growth through 10 years begin at 2008.
