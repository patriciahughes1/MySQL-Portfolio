# Patty's_MySQL_Portfolio
✈️ **Flying High: Analyzing Key Drivers of Passenger Satisfaction in Airline Customer Service** 

In this case study I plan to demonstrate my skills, including data exploration, statistical analysis, predictive modeling, and data visualization, to uncover actionalbe insightsthat can enhance the customer experience. This case study wil explore and identify the main factors influencing airline passenger satisfaction. 

By using MySQL for data querying and manipulation, I will conducting and end-to-end analysis. I will go through exploring satisfaction drivers and demographic trends to building a predictive model to classify customer satisfaction. 

## Problem Statement
The airline industry is heavily reliant on delivering excellent customer service to maintain customer loyalty and satisfaction, particularly given its highly competitive landscape. Customer satisfaction influences customer retention, brand reputation, and overall business profitability. This case study seeks to address the question: What are the main factors contributing to passenger satisfaction or dissatisfaction?

### Objective:
1. **Identify Key Satisfaction Drivers:** Determine which aspects of the customer experience (e.g., seat comfort, inflight Wi-Fi, food and drink quality) are most strongly associated with high levels of passenger satisfaction.
2. **Understand Satisfaction Patterns Across Demographics and Customer Types:** Examine how satisfaction varies across demographic groups (such as age and gender) and by customer type (loyal vs. disloyal) to gain insights into the preferences of different passenger segments.
3. **Explore the Impact of Operational Factors:** Assess the effect of flight distance, delays, and class of travel (Business, Economy, Eco Plus) on satisfaction levels to see if operational variables directly influence customer perceptions.
4. **Predictive Modeling for Satisfaction:** Build a predictive model capable of classifying a passenger’s satisfaction level based on the collected survey responses and operational data. This will demonstrate the potential to predict and respond to passenger needs proactively.

### Key Questions:
* **What customer experience factors have the strongest correlation with overall passenger satisfaction?** Identifying these key factors can help focus improvement efforts on the most influential aspects of the passenger experience.
* **How does passenger satisfaction vary by customer type and demographic?** By segmenting satisfaction levels by variables like customer type, age, and travel purpose, the analysis can reveal valuable insights about targeted service improvements.
* **To what extent do operational delays and flight class impact satisfaction?** Understanding the role of delays and class type will highlight potential areas where operational changes could positively affect customer satisfaction.
* **Can passenger satisfaction be predicted based on survey responses and other data?** A predictive model can serve as a valuable tool for anticipating customer sentiment and preparing service teams to meet or exceed passenger expectations.

### Expected Outcomes:
Through detailed data exploration, statistical analysis, and predictive modeling, this case study aims to provide actionable insights that could guide improvements in airline service offerings, marketing strategies, and operational processes. Additionally, this analysis will demonstrate my proficiency with MySQL for data manipulation and querying, as well as my skills in data exploration, analytical interpretation, and visualizations.

## Data Exploration
Here we will dive deep into understanding the dataset and preparing for the analysis. 

### Initial Data Assessment
* Preview the data by using queries to examin the first few rows and check the schema of the dataset, reviewing the data types for each column.
* Summary statistics to understand the distribution of each variable.
* Explore categorical features and numberical ones to see how they relate to statisfaction.
* Check for null or missing values in each column

### Data Cleaning
* **Handle missing values:** Using MySQL functions to fill in or ignore ulls where appropriate.
* **Outlier Detection:** detect and review outliers in criticial columns.
* **Adjust Data Types:** Ensure numerical columns are correctly typed.

### Exploratory Data Analysis (EDA)
* **Column Summaries:** Generate summary statistics (mean, median, mode, min, max) for numerical columns, and count unique values for categorical columns.
* **Numerical Variables:** Use MySQL group by and count functions to examine distributions for key numerical fields such as Age, Flight Distance, and Delay Times.
* **Satisfaction Correlations:** Compare Satisfaction with other columns using conditional aggregation to see which factors vary most by satisfaction level.
* **Delay Impact:** Analyze the relationship between delays (Departure Delay in Minutes, Arrival Delay in Minutes) and satisfaction.
* **Customer Type and Satisfaction:** Explore satisfaction levels across Customer Type (loyal vs disloyal) and Class (Business, Eco, Eco Plus) to understand whcih customers groups are more satisfied.
* **Age Groups:** Create age group brackets (Young adults, middle-aged, and seniors) to analyze satisfaction by age group.
* **Delay Groups:** Convert delay times into categories (No Delay, Short Delay, Long Delay) for easier analysis of delay impacts on satisfaction.


_This exploration phase not only sets up the dataset for deeper analysis but also allows me to establish a thorough understanding of its structure and nuances. It will help me uncover actionable insights and demonstrate my ability to perform a complete and thoughtful analysis._

## Data Analysis
This section will analyze the factors that contribute to passenger satisfaction using statistical techniques. The analysis will include a mix of summary statistics, correlations, segment analysis, and delayed impact analysis to uncover key insights.

* **Descriptive Analysis:** I will generate summary statistics for some numerical features focusing on Satisfaction, Flight Distance, Age, and Delay times. Visualize the data distribution for each feature using histograms for continuous variables (e.g., Age, Flight Distance) and bar charts for categorical variables (e.g., Class, Customer Type). Assess missing values and outliers, deciding whether to impute, exclude, or handle them based on their impact on the dataset.
* **Correlation Analysis:** Calculate correlation coefficients between Satisfaction and numerical variables like Departure/Arrival Delay, Flight Distance, and various satisfaction metrics (e.g., Seat Comfort, Inflight Entertainment). Explore interactions among satisfaction metrics (e.g., whether higher Seat Comfort correlates with higher Inflight Service satisfaction) to determine interdependencies.
* **Segment Analysis:** Group passengers by categorical features (e.g., Customer Type, Class, Type of Travel) and calculate average satisfaction scores within each group. Use visualization tools like box plots to show satisfaction distribution across Age and Class or scatter plots to analyze patterns across Flight Distance and Satisfaction by travel purpose. Examine segment differences, such as how satisfaction trends for loyal vs. disloyal customers or how business vs. personal travel influences key satisfaction factors.
* **Delay Impact Analysis:** Investigate the relationship between Departure and Arrival Delays and Satisfaction using linear regression or correlation coefficients.
Group delay times into categories (e.g., 0-15 mins, 15-30 mins, etc.) and assess satisfaction scores for each group to observe threshold points where satisfaction significantly drops.
Visualize the delay data against satisfaction, possibly using a line graph or scatter plot, to emphasize how increasing delays impact passenger experience.

## Predictive Modeling
*  Preprocess the data, encoding categorical variables and standardizing features as needed.
*  Train a predictive model (e.g., logistic regression, decision tree, or random forest) to classify passengers as “Satisfied,” “Neutral,” or “Dissatisfied.”
*  Fine-tune the model, optimizing parameters to improve classification accuracy.
*  Evaluate model performance using metrics like accuracy, precision, recall, and F1 score, and generate a confusion matrix to analyze misclassifications.

## Insights and Recommendations
1. Passenger Satisfaction Drivers
   * Insight:
   * Recommendation:
   
2. Segmented Satisfaction Insights
   * Insight:
   * Recommendation:
3. Impact of Delays on Satisfaction
   * Insight:
   * Recommendation:
4. Online and Offline Booking Satisfaction
   * Insight:
   * Recommendation:
5. Predictive Modeling for Customer Retention
   * Insight:
   * Recommendation:

## Conclusion 
