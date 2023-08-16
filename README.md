# Franklin Tan

## My Links
* [LinkedIn](https://www.linkedin.com/in/franklinjtan/)
* [Github](https://github.com/franklinjtan)
* [Book Reads](https://docs.google.com/spreadsheets/d/e/2PACX-1vRV0-0uWWpNxamZL3CbJzEVE6gsGag2Ik7O8Gn5PzjvLQXLtnl_dGavcmdh_MqkBgkChYxQzVF6ksvc/pubhtml)
* [Cornell University MSBA Data Science Club](https://cornell-msba-ds.github.io/website/)

# [Project 1: Kickstarter Analytics Capstone Project](https://github.com/franklinjtan/Kickstarter-Analytics)
![KS Business Problem](/images/ks_current_challenges.png)
* **Business Recommendations Summary:**
  * Kickstarter New Campaign Moratorium (during low activity months) to focus on improving the quality of current projects, and create a sense of excitement.
  * Green Day! Similar to Black Friday, but to support entrepreneurs and bring ambitious, innovative, and imaginative ideas to life
  * Provide marketing services to Kickstarter Creators to help them optimize the launch of their campaigns. Overambitious funding targets can lead to project failure, disappointment among backers, and potential damage to Kickstarter's reputation. By helping creators set appropriate funding goals, Kickstarter can increase the chances of project success and backer satisfaction.
  * Attract Organic Backers: One way to achieve this is by enhancing the platform's visibility and outreach to potential backers, showcasing successful projects, and engaging with the creative community. Building a strong initial backing for projects will help create a sense of momentum and social proof, which can attract additional support.
  * Incentivize Larger Pledges: Kickstarter should continue pursuing strategies that reward and incentivize backers who contribute higher amounts. Offering exclusive perks, early access, or special recognition like badges to backers making significant contributions can motivate backers to pledge more, leading to increased revenue for both Kickstarter and project creators.
* Classification Methodology
![KS method](/images/method.png)

**Key Findings**
![ROC_curve](/images/finding_1.png)
![bar-chart](/images/finding_2.png)
![log_curve](/images/finding_3.png)

![KS Business Problem](/images/ks_hypotheses_and_approaches.png)
* [See Implemented Machine Learning Models and Statistical Methods (Logistic Regression, Decision Trees, LightGBM + ANOVA, and Tukey's Honest Significance Test)](https://github.com/franklinjtan/Kickstarter-Analytics/tree/main/modeling)
* [See Descriptive Statistics and Exploratory Data Analysis Presentation](https://github.com/franklinjtan/Kickstarter-Analytics/blob/main/files/Descriptive%20Statistics%20and%20Results%20from%20Data%20Exploration.pdf)
* [See Hypotheses Testing and Implementation Plan](https://github.com/franklinjtan/Kickstarter-Analytics/blob/main/files/Revised%20Results%2C%20Insights%20Summary%2C%20and%20Implementation%20Plan.pdf)

# [Project 2: Spendalyzer - A Bank Statement Analytics Application](https://github.com/franklinjtan/Spendalyzer-Bank-Statement-Analytics)
* 2nd Place Winner at the Cornell SC Johnson Data Science Showcase on May 22, 2023
* Our motivation to address this problem stemmed from our research on the growing credit card debt in the United States and the lack of predictive and prescriptive analytics in budgeting and personal finance apps. While you may receive information on your spending and where it occurs, you typically don't receive real-time feedback on which categories to cut back on, personalized strategies to adopt, or an understanding of your strengths and weaknesses.<br>
* Our solution incorporates the OKR and KPI measurement framework to track spending data and establish a realistic budget. We utilize ML models like Naive Bayes to classify transactions as necessities or not, advanced forecasting methods to predict categories of overspending and prescribe strategies to take, gamification to encourage healthy spending habits, and a Chrome Extension that analyzes your recent purchase history and engages System 2 (deliberate thinking) to prevent impulse purchases.<br>
* Used pandas, numpy, dash, nltk, panel, and plotly libraries for data wrangling, data visualizations, web application framework, ML algorithms, and dashboard deployment.
![Dashboard](/images/dashboard.jpeg)
![Spendalyzer](/images/Spendalyzer.png)
![Recommendations](/images/SMA-and-ES-Forecasting.png)

# [Project 3: Supplemental Nutrition Assistance Program: Consumer Behavior Analysis with Python](https://github.com/franklinjtan/Food-Stamps-Consumer-Behavior-Analysis/tree/main)
I conducted a comprehensive consumer behavior analysis for the Supplemental Nutrition Assistance Program (SNAP) using Python. SNAP is a food assistance program in the US for low-income households. The analysis aimed to understand the psychological mechanisms driving SNAP households' tendencies to purchase unhealthy, hedonic food items. The research identified key insights and made recommendations to the USDA Director to reduce unhealthy food consumption among SNAP participants.<br>

**Key Insights:**
  1. _Attention to Hedonic Food Items_: SNAP households exhibit higher cravings for both hedonic and utilitarian food items compared to non-SNAP households. Their circumstances may lead to reliance on heuristics (system 1 thinking) rather than analytical thinking (system 2), influencing their food choices.
  2. _Emotional Responses_: SNAP households experience stronger cravings for both hedonic and utilitarian food items due to their stressful situation, prioritizing immediate gratification.
  3. _Coherence in Hedonic Purchases_: Despite being aware of potential health risks, SNAP households justify hedonic food choices to maintain coherence and emotional well-being.
  4. _Statistically Significant Findings_:
     * SNAP households buy more hedonic products but fewer utilitarian products compared to non-SNAP households
     * Income and education are not statistically significant predictors of SNAP households' consumption patterns.
     * SNAP households do not consider hedonic food to be better value for money compared to utilitarian food.
     * SNAP households perceive both hedonic and utilitarian products as less unhealthy than non-SNAP households.
     * SNAP households report higher craving levels for both hedonic and utilitarian products compared to non-SNAP households.
     * The relationship between craving and unhealthiness perception is stronger among SNAP households.
      
# [Project 4: Customer Lifetime Value Prediction](https://github.com/franklinjtan/Customer-Lifetime-Value-Prediction/tree/main)
* Performed RFM analysis, created customer segments, and predicted CLV for a 6-month period, enabling businesses to make informed decisions about customer acquisition, retention, and management strategies.<br>
* Recency scores were assigned to each customer based on their last purchase date.
* Recency clusters were ordered and assigned based on the recency scores.<br>
* Frequency clusters were determined by calculating the number of orders for each customer.<br>
* Revenue clusters were created by calculating the revenue generated by each customer.<br>
* Overall scores were calculated by summing the recency, frequency, and revenue cluster numbers.<br>
* Customers were segmented into low-value, mid-value, and high-value segments based on their overall scores.<br>
* Customer Lifetime Value (CLV) for a 6-month period was calculated by summing the revenue for each customer.<br>
![Dashboard](/images/ltv_plot.png)

# [Project 5: Exploratory Data Analysis: Netflix Movie Data](https://github.com/franklinjtan/Exploratory-Data-Analysis-Netflix-Movie-Data)
* Created a set of analyses and data visualizations that explores whether Netflix movies are getting longer or shorter<br>
* Used matplotlib, pandas, seaborn to generate line charts, bar charts, histograms, box plots, scatterplots, and groupedby dataframes
![Scatterplot-Netflix](/images/scatterplot-netflix.png)
![Linechart-Netflix](/images/lineplot-netflix.png)

# [Project 6: Portfolio Diversification: Correlation Risk Management with Python](https://github.com/franklinjtan/Portfolio-Diversification-Correlation-Risk-Management-with-Python)
* Understanding the importance of diversification and a portfolio of uncorrelated returns, I plotted the 5-year returns of several equities, ETFs, and commodities against SPY. 
* I also used linear regression to calculate the beta and correlation, and generated a correlation matrix and a heatmap.<br>
![Correlation Matrix](/images/correlation_matrix.png)
![Heatmap of Portfolio](/images/heatmap.png)

# [Project 7: Subway Yelp Reviews Analysis](https://github.com/franklinjtan/Subway-Yelp-Reviews-Analysis)
* Created a set of analyses and data visualizations that support or disprove the following statements made by Subway Restaurant leadership:
  * Head of Customer Service: “Our ratings are gradually improving, and we will soon reach 4.5/5.”
  * Head of Store Operations: “Sandwiches are a tricky business. All sandwich chains suffer from poor customer ratings.”
  * Head of Social Media: “The goal of 4.5/5 is unreasonable for national chains like us. Only small, local, and boutique restaurants can achieve such high ratings.”
  * Chief Data Scientist: “It is well known that customers make the effort to give a rating only when they are either extremely angry or absolutely delighted with the service. So online ratings are not reliable.”
* Used matplotlib, seaborn, scipy, and pandas to generate line charts, bar charts, scatterplots, groupedby dataframes, and linear regression<br>
![Avg Ratings by State through the Years](/images/subway_fig_10.png)
![Total Ratings Received by stars value and years 2018-2021](/images/subway_fig_11.png)

# [Project 8: Monte Carlo Simulation - Optimal Production Level](https://github.com/franklinjtan/-Monte-Carlo-Simulation---Optimal-Production-Level-)
* Created a program simulation written in Python that will generate a production level recommendation given a set of parameters
* Used NumPy to generate a random sample of demand instances from a normal (Gaussian) distribution.
* Used matplotlib to generate a scatterplot visualization with a color scale depicting optimal ranges of production
![](/images/fig2.png)
![](/images/fig3.png)

# [Project 9: Visualizing and Forecasting Monthly Retail Trade Data](https://github.com/franklinjtan/Visualizing-and-Forecasting-Monthly-Retail-Trade-Data)
* Cleaned and prepared monthly retail trade data from the Census Burea to create a time-series of various industries from 1992 to 2022
* Used Python Pandas for data cleaning and Tableau to create visualizations
* [Tableau Dashboard](https://public.tableau.com/app/profile/franklin.tan/viz/StartupsFueleCommerceGrowth/Dashboard5)

# [Project 10: Fashion Store Crawler](https://github.com/franklinjtan/fashion-store-crawler)
* Created an application that crawls the a fashion store website and extracts product information to helps users track and reduce their environmental impact.
* Scraped over 1000 product descriptions from the clothing store, The Reformation using python and selenium
* Stored the data in a hosted database (AWS RDS).
* Optimized solution by targeting unique identifier-keys like ASIN in cases where website structure changes or product becomes out-of-stock.

# Certificates:
* [Data Manipulation with Pandas](https://github.com/franklinjtan/Frank_Portfolio/blob/main/certificates/Data%20Manipulation%20with%20Pandas%20Certificate.pdf)

* [Intro to Portfolio Analysis in Python](https://github.com/franklinjtan/Frank_Portfolio/blob/main/certificates/Introduction%20to%20Portfolio%20Analysis%20in%20Python%20Certificate.pdf)

* [Time Series Analysis in Python](https://github.com/franklinjtan/Frank_Portfolio/blob/main/certificates/Time%20Series%20Analysis%20in%20Python%20Certificate.pdf)

* [Intermediate Python](https://github.com/franklinjtan/Frank_Portfolio/blob/main/certificates/Intermediate%20Python%20Certificate.pdf)

* [Analyzing Data in Spreadsheets](https://github.com/franklinjtan/Frank_Portfolio/blob/main/certificates/Analyzing%20Data%20in%20Spreadsheets%20Certificate.pdf)

* [Financial Analytics in Spreadsheets](https://github.com/franklinjtan/Frank_Portfolio/blob/main/certificates/Financial%20Analytics%20in%20Spreadsheets%20Certificate.pdf)

* [Intro to Python](https://github.com/franklinjtan/Frank_Portfolio/blob/main/certificates/Introduction%20to%20Python%20Certificate.pdf)
