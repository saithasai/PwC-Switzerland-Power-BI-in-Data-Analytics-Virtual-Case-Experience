# PwC-Switzerland-Power-BI-in-Data-Analytics-Virtual-Case-Experience-

I recently completed the PwC Switzerland job simulation program on Forage. This program was based on 4 tasks.

## Task 1
It started with a question “Tell us, what do you hope to learn during this experience with us?”   

## Task 2 : Call Centre Trends 
Create a dashboard in Power BI on Call Centre Trends for Claire, the Call Centre Manager at PhoneNow.  

### *Call Centre Trends---Situation*
Telecom fights hard for the customers. The Call Centre Manager at PhoneNow can't see what the trends are. Create a clear Power BI dashboard to understand today's trends.

### *Call Centre Trends---Task*
Create a dashboard in Power BI for Claire that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset.     
The KPIs to be included are:  Overall customer satisfaction, Overall calls answered/abandoned, Calls by time, Average speed of answer, Agent’s performance quadrant -> average handle time (talk duration) vs calls answered to showcase customer and agent behaviour.  

### *Call Centre Trends---Action*
Performed data cleaning in Power Query Editor and made ready to make the visualization.    
Used DAX measures for creating KPIs and visualize. 
Used slicers for Agent name, call topic and Date of call, pie charts on calls answered and calls resolved, line chart to show avg speed of answer by each Agent, bar chart to depict calls arrived by each month, guage chart for showing average customer satisfaction.

### *Dashboard*
<img width="758" alt="Image" src="https://github.com/user-attachments/assets/2c939eeb-d655-427b-84c1-4c44261036ea" />

### *Call Centre Trends--Insights*   
Overall customer satisfaction  = 3.40   
Overall calls answered/abandoned = 4054 were answered and 946 unanswered calls.     
Calls by time as calls by month - Calls on February were answered most   
Average speed of answer = 67.52  
Agent’s performance quadrant -> average handle time (talk duration) vs calls answered  

## Task 3: Customer Retention
Create a Power BI dashboard for the Call Centre Manager on customer retention.

### *Customer Retention---Situation*
The Retention Manager from the telecom is impressed with the dashboard and requests a new one focused on customer retention(to reduce churn rate). They aim to proactively identify at-risk customers before contract termination, as current analysis in Excel has been ineffective. They seek a clear, visual dashboard that provides actionable insights for management.

### *Customer Retention---Task*
Create a dashboard for the Call Centre Manager using the defined KPIs related to customer retention, reflecting customer demographics and insights, and providing recommendations based on the data.

### *Customer Retention---Action*
Performed data analysis in Power Query Editor and made ready to make the visualization.   
Added conditional column for Tenure as tenure % for making smooth analysis  
Used DAX measures for creating KPIs and visualize.  
Created two dashboards -- Churn dashboard and Customer Risk Analysis  

Churn dashboard------  
Churn dashboard contains Customer Demographics, Customer Account Information, and Service Customers Signed Up for.    
KPIs Defined = No. of customers at risk, count of administrative and technical tickets , yearly and monthly charges   
Services each customer has signed up for: phone, internet, online security, online backup, device protection, tech support, and streaming TV and movies   
Customer account information: Customers with different contract types, payment method, paperless billing, monthly charges, total charges   
Demographic info about customers — gender, age range, and if they have partners and dependents.       
Used Donuts, stacked bar charts for the visualization.  

Customer Risk Analysis------  
KPIs Defined = No. of customers, churn rate, churn count, count of administrative and technical tickets , yearly charges, totall revenue at risk   
Visualizations for Churn by internet service, no. of customers by internet service, Monthly charges by internet service, Churn by Contract, Churn by Tenure, Churn by Payment method  
Used Pie chart, line with stacked bar charts for the visualization.  
Used slicers for churn, contract type, months subscribed and Internet service

### *Customer Retention---Dashboard*
<img width="758" alt="Image" src="https://github.com/user-attachments/assets/c93e8e5b-0cbe-4acc-9c8b-16c1b057d948" />

<img width="758" alt="Image" src="https://github.com/user-attachments/assets/f153fb1f-75f2-48f7-a017-da90024338a9" />

### *Customer Retention---Insights*  
The churn rate of 26.5%  means overall retention rate is a commendable 73.5%. Exploring the reasons behind this churn can uncover valuable insights for proactive strategies.  
Total revenue loss of $2.86M due to customer churn.  
A considerable number of customers have opted for month-to-month contracts with us.   

### *Customer Retention---Recommendations*  
Based on the analysis, the longer the Tenure, the lower the Churn rate. Therefore, it is better to focus on keeping their customers on a long-term contract.  
Around 6% of Churned Customers and 27% of Customers of the company do not have internet. This is a one of the reasons of churning. So,make to ensure that all customers are satisfied.  
Factors like online security, online backup, device protection, tech support, and streaming TV and movies are not satisfied by the customers. They are comparatively low. Company needs to check regarding this.  
PaperlessBilling is not satisfied by the customers who have not internet service.    

## Task 4: Diversity & Inclusion 
Create visualizations to represent HR data, particularly focusing on gender-related KPIs and identify and discuss potential root causes for the slow progress in achieving gender balance at the executive management level.

### *Diversity & Inclusion---Situation*
Human Resources at our telecom client is highly into diversity and inclusion. They’ve been working hard to improve gender balance at the executive management level, but they’re not seeing any progress. They’re reaching out to us for help.

### *Diversity & Inclusion---Task*
Create a Power BI dashboard and define relevant KPIs in hiring, promotion, performance and turnover and identify root causes for the slow progress.  

### *Diversity & Inclusion---Action*  
Performed data analysis in Power Query Editor and made ready to make the visualization.   
Used DAX measures for creating KPIs and visualize.  
KPIs Defined = No.of men, No.of women, No.of leavers, % employees promoted (FY21), % of women promoted, % of hires men, % of hires women, % turnover , Average performance rating: men, Average Performance rating: women   
Used stacked bar chart, line and clustered bar chart, line chart, donuts for the visualization.
Applied filters for department, job level, age group, region group.   

### *Dashboard*
<img width="758" alt="Image" src="https://github.com/user-attachments/assets/0b4f5d14-a58b-4d43-b426-84f981495e23" />

<img width="758" alt="Image" src="https://github.com/user-attachments/assets/2b13ee26-5a75-44bc-922c-ba80f1c1f903" />    

### *Diversity & Inclusion---Insights*  
The workforce comprises 59% men (295) and 41% women (205).    

----Gender Distribution  
There is a significant gender imbalance in the overall workforce
Women are underrepresented particularly in senior positions (Directors and Executive levels)
The imbalance becomes more pronounced at higher job levels  
Lower promotion rates for women compared to men

------Performance Ratings  
The data suggests similar performance ratings between men and women
However, this equal performance is not translating to equal promotion opportunities  

### *Diversity & Inclusion---Root Causes for Slow Progress:*  
a) Pipeline Issues:

Limited pool of women in middle management positions
Fewer women in roles that typically lead to executive positions

b) Structural Barriers:

Potential unconscious bias in promotion decisions
Lack of sponsorship and mentorship programs
Limited representation of women in decision-making roles

c) Retention Challenges:

Higher turnover rates among women in middle management
Career progression bottlenecks

### *Diversity & Inclusion---Recommendations*  

a) Short-term Actions:

Implement structured mentorship programs
Review promotion criteria for potential bias
Set clear diversity targets for hiring and promotions

b) Long-term Initiatives:

Develop leadership pipeline programs specifically for women  
Create sponsorship programs pairing senior leaders with high-potential women  
Implement unconscious bias training for all managers
