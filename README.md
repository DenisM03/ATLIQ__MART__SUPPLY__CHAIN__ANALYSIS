#  Insights From Supply Chain In FMCG Domain

__Dashboard link__:

# Problem  Statement 
Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and OnTime in full (OTIF) %’ of the customer orders daily basis against the target service level set for each customer.
   

#  Task
Peter Pandey is the data analyst in the supply chain team who joined AtliQ Mart recently. He has been briefed about the the task in the stakeholder business review meeting. Now imagine yourself as Peter Pandey and play the role of the new data analyst who is excited to build this dashboard and perform the following task:

1.Create the metrics according to the metrics list.   
2.Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in comic form.  
3.Create relevant insights not provided in the metric list/stakeholder meeting.  

# Data Source   
The data was provided by Codebasics as part of Codebasicsresumechallenge.These files consists of required details about customers,products and order details.    
    1. dim_customers   
    2. dim_date  
    3. dim_products   
    4. dim_targets_orders   
    5. fact_order_lines  
    6. fact_orders_aggregate


## Data Model 
![Screenshot 2024-06-06 223908](https://github.com/DenisM03/SUPPLY__CHAIN__PERFORMANCE__DASHBOARD-/assets/163861750/6317d1ab-0d0d-4854-80c8-83f8e7680c96)

## Analytical Dashboard   
![Screenshot 2024-06-08 185441](https://github.com/DenisM03/ATLIQ__MART__SUPPLY__CHAIN__ANALYSIS/assets/163861750/6c737d93-0a86-44f6-abe6-0b8ae1480f94)


## Tools Used   
Excel,PowerBi 

## Business  Terminologies
   
1.LIFR%   -  Line Fill Rate   
2.VOFR%   -  Volume Fill Rate  
3.OT%     -  On Time Delivery %   
4.IF%     -  In Full Delivery %     
5.OTIF%   -  On Time In Full %

## Content   
1.Process
2.KPI's   
3.Insights

## 1.Process    
The data files are transformed into power Bi desktop using power query.A data model was built by connecting the necessary fields
for analysis.Using DAX and measures  metric values were calaculated. Based on requirements measures are built that support the analysis.Tables and charts were created for visualization.A dashboard was created, that showcases the performance and analytics of the data.   

## 2. Key Metrics  

1.Total Order Lines    
2.Total Orders        
3.LIFR%   
4.VOFR%   
5.OT%       
6.IF%         
7.OTIF%     
8.On Time Target    
9.In Full Target    
10.On Time In Full Target

## 3.Insights    
