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
