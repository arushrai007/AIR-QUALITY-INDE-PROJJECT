Air pollution has emerged as one of the most pressing global concerns, impacting public 
health, environmental sustainability, and economic development. In urban centers, particularly 
in rapidly growing cities like Lucknow, the problem has been intensifying due to increasing 
industrial activity, vehicular emissions, construction dust, and other anthropogenic sources. 
The Air Quality Index (AQI) serves as a comprehensive measure that encapsulates the severity 
of air pollution in a specific location by combining data from various pollutants into a single 
number. Monitoring, analyzing, and forecasting AQI is critical for policymakers, 
environmental researchers, and the general public to take informed actions that mitigate 
pollution and protect health. 
This project focuses on analyzing air quality in the city of Lucknow using a rich dataset 
containing several years' worth of environmental data. The dataset includes readings of key 
pollutants such as PM2.5, PM10, NO, NO₂, NOx, NH₃, CO, SO₂, O₃, Benzene, Toluene, and 
others, along with corresponding AQI values. By leveraging tools from Python's data science 
ecosystem—including pandas, seaborn, matplotlib, NumPy, and scikit-learn—we perform 
exploratory data analysis (EDA), statistical testing, visualization, and machine learning 
modeling. 
Lucknow, the capital of Uttar Pradesh, is one of the cities identified by the Central Pollution 
Control Board (CPCB) under the National Clean Air Programme (NCAP) as suffering from 
non-attainment of air quality standards. Due to growing urban sprawl, vehicular traffic, and 
combustion-based energy use, the city often registers AQI levels that fall into 'Poor' or worse 
categories, posing threats of respiratory illnesses, cardiovascular conditions, and reduced life 
expectancy. Hence, analyzing the dynamics of pollutants and their influence on AQI over time 
is not just an academic exercise—it’s a step toward enabling real-world impact. 
The project begins with a thorough examination of the dataset to understand its structure, 
trends, and anomalies. Using descriptive statistics, we explore the distribution of individual 
pollutants, identifying central tendencies, spread, and outliers. Next, we delve into visual 
analysis, employing line graphs, pie charts, histograms, and heatmaps to gain intuitive insights 
into temporal patterns, pollutant correlations, and AQI category distributions. 
One of the core parts of the project is the correlation heatmap, which reveals how pollutants 
like PM2.5 and NO₂ are strongly associated with the AQI value. These insights can help 
prioritize which pollutants to control for maximum impact. Moreover, advanced statistical 
tests—such as the Shapiro-Wilk test for normality, independent t-tests to compare AQI 
categories, and chi-squared tests for dependency analysis—help validate the patterns observed 
visually. 
Following the EDA, the project transitions into the construction of a predictive model. We use 
Linear Regression to predict AQI based on pollutant concentrations. The model is trained and 
tested on scaled and cleaned data using an 80-20 train-test split. Model evaluation metrics like 
R² (coefficient of determination) and Mean Squared Error (MSE) provide a quantitative 
measure of the model’s accuracy and performance. The scatter plot of actual vs. predicted AQI 
further visualizes the model's predictive power. 
In terms of data preprocessing, missing values are handled through appropriate imputation, and 
outlier detection is performed using Z-score analysis. This ensures the integrity of the model 
and the reliability of insights. StandardScaler is used for feature normalization, a crucial step 
for algorithms sensitive to the scale of data. 
The implications of this analysis are far-reaching. For instance, knowing that PM2.5 is the 
most correlated pollutant with AQI allows local authorities to implement stricter controls on 
activities that release fine particulate matter. Seasonal trends in AQI can inform public health 
advisories and policy regulations during specific months. Moreover, the predictive model 
could be integrated into real-time air monitoring dashboards to forecast AQI based on current 
pollutant readings, thus enabling timely public warnings. 
Additionally, this project aligns with broader trends in environmental data science. Modern 
machine learning models are increasingly being used to simulate future air quality under 
different policy and urban planning scenarios. Tools like Generative AI are also contributing 
by generating synthetic environmental data when historical records are insufficient. Such 
advancements indicate a growing convergence of AI with environmental science, opening up 
new avenues for interdisciplinary research and sustainable development. 
This project showcases not only the application of statistical and machine learning techniques 
to a real-world problem but also emphasizes the importance of data in driving environmental 
awareness and action. From data cleaning and visualization to predictive modeling and 
hypothesis testing, each stage of the project contributes to a holistic understanding of air 
quality trends in Lucknow. 
Ultimately, this work aims to serve as a blueprint for similar studies in other cities facing 
pollution challenges. As data becomes more readily available and computational tools become 
more powerful, such projects can play a key role in the fight against air pollution. By 
equipping governments, researchers, and citizens with actionable insights, data science 
becomes a powerful ally in the quest for cleaner, healthier air. 
