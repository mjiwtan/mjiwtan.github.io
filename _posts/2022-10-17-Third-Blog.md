Hello Everyone,

Today I will be talking about why and how we use Exploratory Data Analysis(EDA) on the data for analysis and visualization.

**What is your overall goal when doing an EDA?**

EDA's major goal is to encourage data analysis before making any assumptions. It can assist in finding glaring errors, better understanding data patterns, spotting outliers or unusual occurrences, and discovering intriguing relationships between the variables. Every data scientist should have exploratory data analysis (EDA) in their toolbox since the outcomes are helpful for addressing crucial business concerns.

**Strategy to use for EDA?**

While performing EDA we need to follow a 5 point strategy so that we dont have bottleneck in analysis.

1. Checking for Missing Data: 

Missing values can hurt the data. We need to figure out we are going to handle the data. For example if there is no seasonality we can directly do linear interpolation to fill out the missing values.

2. Provide Basic Descriptions of Your Sample and Features:

Not all the variables can be visualized in the same way. Features can be continuous, discrete and categorical. We need different statistical and visualization tool for each type of feature and thats why its important that we know in detail about such variables. 

3. Identify The Distributon of Your Data:

Its important to know how the data behaves across different sample and time 

4. Identify Significant Correlations:

Variables have relationship among themselves. It is crucial to know how their relationship would impact the data and which features should we take into consideration while analyzing the data as multi collinearity is an important aspect in data science.

5. Spotting Outliers:

Performing statistical modelling becomes difficult when outliers are present in data. We need to make sure that we spot outliers and find ways to deal with them.

**Important methods in EDA**

Univariate Non-Graphical: With only one variable in the data, this is the most basic type of EDA. Data experts do not have to deal with relationships because there is just one variable.

Univariate Graphical: Techniques without graphics do not provide a complete picture of the facts. Therefore, data professionals use graphical techniques including box plots, and histograms

Multivariate Non Graphical: Multiple variables make up multivariate data. Non-graphic multivariate EDA methods use statistics or cross-tabulation to depict correlations between two or more data variables.

Multivariate Graphical:   This EDA method employs graphics to demonstrate connections between two or more datasets. Bar charts, bar plots, heat maps, and scatter plots are some of the often used multivariate graphics.

**Things we should look for?**

EDA primary purpose is analysis. We need to make some interpretation of the data. For that we look how large the data set is and how a change in feature would impact the our result. Also, we need to look whether there is a relationship among variables.
EDA also helps to find patterns and seasonlity in data which comes in handy in understanding the data.



