# A-B-Testing-Analysis
## Objective: Experimenting a New Food & Drink Landing Page Banner
An A/B test is an experimentation technique used by businesses to compare two versions of a webpage, advertisement, or product feature to determine which one performs better. By randomly assigning customers or users to either the A or B version, the business can determine which version is more effective at achieving a particular goal.
The setup of the A/B test is as follows:
### A/B Testing Steps:
The experiment is only being run on the mobile website.
  1. A user visits the GloBox main page and is randomly assigned to either the control or test group. This is the join date for the user.
  2. The page loads the banner if the user is assigned to the test group, and does not load the banner if the user is assigned to the control group.
  3. The user subsequently may or may not purchase products from the website. It could be on the same day they join the experiment or days later. If they do make one or more purchases, this is considered a “conversion”.
### The Dataset
GloBox stores its data in a relational database, which you can access here:

(postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Globox)
![Alt Text](https://github.com/Fitasdj/A-B-Testing-Analysis/blob/main/DataSet.png)

### Summary
A/B testing was carried out for a landing page banner displaying food and product categories. In the trial, users were placed into two groups: A and B, which acted as the control and treatment, respectively. Tracking the proper data for each group, such as conversion rates and spending amounts, to evaluate how effective the banner is during a specific time period


![Alt Text](https://github.com/Fitasdj/A-B-Testing-Analysis/blob/main/Interface.png)

### Experimet Context 
   We intended to do A/B testing and make business decisions based on the results in order to determine if the food and beverages banner would be featured on the app. Assigning users equally to control and treatment groups and tracking their purchasing activities with the option to convert after seeing the banner.The conversion rate, defined as the percentage of users who made a purchase during the experiment, and the amount spent per user were deemed critical metrics and recorded for each individual between January 25th and February 6th, with a total number of users reaching 49k divided 50/50 to each group.

# Result & Analysis    

## Hypothesis Testing Results 
   The sample user analysis revealed an 18% increase in conversions and a 0.6% increase in total amount spent, indicating that the banner did not influence as many users to convert as anticipated.
Based on our sample size and the results of the hypothesis testing performed on the data we gathered, we found that the conversion rate for Group A was 3.92% and for Group B it was 4.63% with an 18% lift. Statistically, this result is very significant, with a p-value of 0.0001. We find no evidence to support the premise that the control and treatment groups had similar user conversion rates (reject the null hypothesis).
We did not notice a significant difference between group A (3.37$) and group B (3.39$) in terms of average expenditures. The significance level of the p value for the test of the hypothesis was 0.94%. Concluding that no significant difference in average spending between the control and treatment groups, hence the null hypothesis is not rejected.

![Alt Text](https://github.com/Fitasdj/A-B-Testing-Analysis/blob/main/User%20Conversion%20Rate%20%26%20Amount%20Spent.png)

## CONFIDENCE INTERVAL FOR DIFFERENCE IN CONVERSION RATE
The difference between the control and treatment groups, calculated at 0.71%, lies within the 95% confidence interval for conversion rates of between 0.35% and 1.07%.


![Alt Text](https://github.com/Fitasdj/A-B-Testing-Analysis/blob/main/CR1.png)

## CONFIDENCE INTERVAL FOR DIFFERENCE IN AMOUNT SPENT
The determined 0.02$ difference between the control and treatment groups is within the 95% confidence interval for average amount spent of -0.44$ to 0.47$.
