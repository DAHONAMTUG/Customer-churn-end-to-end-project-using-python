# End-to-End-Data-analytics-project-using-python-and-power-BI-

![Example image](https://github.com/DAHONAMTUG/End-to-End-Data-analytics-project-using-python-and-power-BI-/blob/main/maxresdefault%20(1).jpg)

The objective of this project to identify the factors that may lead to customer churn, for that i will use python and power BI. and also build a churn prediction model using machine learning.

Bank customer churn is a major challenge for financial institutions. It's a measure of customer loyalty and can happen for reasons like dissatisfaction, high prices, or better alternatives, and it may indicate problems with a company's products, services, or customer experience, leading to a loss of market share, increased acquisition costs, and reduced revenue. 

in the project i will answer:

 1) What are the key drivers of churn in the bank?  Are there particular groups or customer segments that are more  likely to churn?
 
2) How does the length of the customer relationship impact churn?  Are long-term customers less likely to churn than newer customers?
 
3) Is there a relationship between the number of products or services a customer use and their likelihood of churning?

4) How does the customer's interaction with the bank, such asfrequency of calls, impact churn?
 
 in the data science project i will pick try to predict customer churn using machine learning.
 
 all this will be display in Power BI dash board.
 
the main insights from the data analysis are : 

1)	Gender: by looking at churn by gender we can see that females were churning at higher rate than males, and the chi-squared test result suggests that there is a statistically significant relationship between gender and attrition. 
The odds ratio of 1.23 indicates that the odds of churning for females are 1.23 times higher compared to males, or in other words, females are 23% more likely to churn compared to males.

2)	Marital status: based on the chi- 2 tests we can conclude that there is no significant association between marital status, and attrition rate for both genders.

3)	Education: based on the test   there is a statistically significant association between education level and attrition for female customers. Looking at the odds of attrition for female customers, we can see that  the odds of attrition are highest for customers with a Doctorate
education level (0.33) and lowest for customers with an Uneducated  education level (0.19).for male customers that we cannot reject the null hypothesis that there is no association    between education level however the odds of attrition are highest for customers with a Post-Graduate education level.

4)	Income:  Based on the results of the analysis, we can make the following observations: The odds of attrition are highest for customers with an income of over $120K, followed by customers with an income of less than $40K. The Chi-square statistic of 12.83 and the p value of 0.025 indicate that there is a significant association between income category and attrition. Overall, these results suggest that income 
category is a relevant factor for predicting attrition, and should be 
taken into account when developing strategies to retain customers.

5)	Age: Older customers are less likely to churn compared to younger one. There could be many reasons for this relationship. For example,
younger customers may be more likely to switch companies for better dealsor job opportunities, while older customers may be more loyal or have 
fewer options available to them. Additionally, different age groups may  have different preferences or needs when it comes to banking services

6)	Tenure and attrition: The chi-squared test statistic value is 0.61 and the corresponding p-value is 08948. This test result suggests that there is no significant association between the distribution of attrition and tenure, as the p-value is much greater than the commonly used significance level of 0.05. In summary, the test results indicate that there is no significant relationship between attrition and tenure in the given data set.


7)	Gender and tenure: The results of the chi-squared test between gender and tenure suggest that there is no significant relationship between these two variables.

8)	no. of products held: By observing the total no. of products held by the customer there an idication that a rise in th no. of products, the less likelihood there is to churn, this correlation can be observed in various scenarios. And could indicatethe customer loyalty and love for the service the company offers.

9)	Total revolving balance: The results suggests that customers with higher revolving balances are
less likely to churn. we can assume that when a customer's revolving  balance is low, it could indicate that they are not using their credit 
frequently or are paying off their balances regularly. In this case, the credit card company or bank may not be earning as much interest or fees
from that customer, which could make them less profitable. Therefore, thecredit card company or bank may be less motivated to retain that customerand the likelihood of churn could increase.

10)	Customer status based Total count change Q1-4, Total amount change Q1-4, and Total utilization ratio: 
The results indicate that there are statistically significant negative relationships between the Attrition_Flag and Total_Ct_Chng_Q4_Q1, Total_Amt_Chng_Q4_Q1, and Avg_Utilization_Ratio. As the Total_Ct_Chng_Q4_Q1 and Avg_Utilization_Ratio increase, the likelihood of customer churning decreases, while for Total_Amt_Chng_Q4_Q1, the relationship is weaker. The p-values for all three variables are very small, indicating that these relationships are unlikely to have occurred by chance.

11)	Customer status by Total_Trans_Ct, Total_Trans_amt: Overall, the results suggest that both Total_Trans_Amt and Total_Trans_Ct are negatively associated with Attrition_Flag, which means thatcustomers who churn tend to have lower values for these variables. The strength of the association is stronger for Total_Trans_Ct than for Total_Trans_Amt.

12)	Attrition based on number of calles made in the past 12 months:
The results of the Chi squared test indicate that there is a significant association between thedistribution of attrition and the contacts count in the last 12 month.
Looking at the table, it seems that customers who had fewer contacts in the last 12 months (0-3) were more likely to leave the company, while customers who had more
 contacts (4-6) were more likely to be stay. Customers who are more inactive are more likely to be attrited customer To avoid churn, the company should consider taking the following actions:
 

13)	Is customer inactivity a significant predictor of customer attrition:
We can conclude that there is a significant association between attrition status and number of calls made. Looking at the table, we can see that customers who had fewer contacts in the last 12 months (0-3) were more likely to leave the company, while customers who had more contacts (4-6) were more likely to stay. This suggests that the number of calls made is a significant predictor of customer attrition, with customers who have had fewer calls being more likely to leave. . Therefore, customer inactivity should be considered an important factor to monitor and address in order to reduce customer attrition.

 

