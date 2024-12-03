#   BANK CHURN DATA ANALYSIS



 ## OVERVIEW

 
 ### Problem Statement
  
   A bank aims to leverage its customer data to enhance decision-making processes by gaining insights into customer demographics, 
   
   financial behaviors, and engagement trends. By understanding the characteristics and needs of different customer segments,
   
   the bank seeks to identify opportunities for improving customer retention, optimizing service offerings, and increasing customer satisfaction.
   
   Objective
  
- Demographic Analysis

- Customer Engagement Patterns

- Financial Performance

- Exited Customers Analysis


    Approach

     To achieve this, we are going to approach the analysis using the following steps
     
    -  Properly Master The Business And Data
    
    -  Clean And Explore Data For Analysis
    
    -  Using Visualisations To Answer Questions Enabling Us Achieve Our Objective
    
    -  Draw A Conclusion
    
    -  Prepare A Summary


    ## DATA

    The Bank churn folder contains two datasets for Customer and Account Information.

  The Customer dataset carries information about the customer details, and the Account dataset carries information about the customer's financial perfomance.


    CustomerId    -     A unique identifier for each customer                                                           
  
    Surname       -     The customer's last name                                                                        
  
    CreditScore    -    A numerical value representing the customer's credit score                                      
  
    Geography      -    The country where the customer resides (France, Spain, or Germany)                              
  
    Gender       -      The customer's gender (Male or Female)                                                          
  
    Age          -      The customer's age                                                                              
  
    Tenure      -       The number of years the customer has been with the bank                                         
  
    Balance       -     The customer's account balance                                                                  
  
    Number Of Products - The number of bank products the customer uses (e.g., savings account, credit card)              
  
    Has Credit Card  -  Whether the customer has a credit card (1 = yes, 0 = no)                                        
  
    IsActiveMember   -  Whether the customer is an active member (1 = yes, 0 = no)                                    
  
    EstimatedSalary  -  The estimated salary of the customer                                                            
  
    Exited           - Whether the customer has churned (1 = yes, 0 = no)                                  
  
  
     # Insights
  


    Demographic Segmentation:

    -  Customer Distribution: France constitutes 50% of the bank’s customer base, with a significant majority being male.

    
              ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Customer%20Distribution%20By%20Geography.png)

    
    -  Age Distribution: The predominant age cohort of customers ranges from 21 to 50 years.


              ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Age_group_of_customer.png)


    Credit Score Utilization:

    - Geographical Comparison: Customers in France exhibit higher credit score utilization compared to counterparts in other regions.


               ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Location%20CreditScore.png)


    - Age Correlation: There is a positive correlation between younger age groups and higher credit scores.
    
    - Activity Status: Active customers are more likely to utilize the bank’s credit scoring services.
    
    Customer Tenure and Engagement:

    - Product Adoption: Customers with longer tenure hold a greater number of bank products.


               ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Average_Number_of_Products.png)

    
    - Credit Card Usage: A negative trend is observed in credit card usage among longer-tenured customers.


                ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Creditcard%20against%20Tenure.png)

    
    - Account Balance Retention: Longer-tenured customers tend to maintain lower account balances.
    
    Account Balance Analysis:

    - High-Balance Accounts: A minimal number of customers maintain balances exceeding €200,000, with only one customer surpassing €250,000.


                 ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Customer%20Distribution%20by%20Balance.png)


    Gender and Age Insights:
    
    - Female customers under 20 hold the lowest account balances.
    
    - Male customers consistently have higher balances across all age groups compared to female customers.


                  ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Average_Balance_by_Gender_and_Age_Group.png)

    

    Estimated Salary Trends:

    - Gender and Age Dynamics:
    
       -  Males under 20 have the lowest estimated salaries.
       
       -  Males under 25 have the highest estimated salaries.

    -  Age-Related Declines:
    
       -  Estimated salaries decrease for both genders starting at age 50.
       
       -  Account balances begin to decline at age 60.
   
       -  Peak Balances: A peak in account balances is observed among males aged 61-65.
    
       -  Salary Growth: Female customers demonstrate a steeper increase in estimated salaries compared to males.


                         ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Average_Estimated_Salary_by_Gender_and_Age_Group.png)


                     

    Churn Analysis:

    - Tenure vs. Churn Rate: Customers with moderate tenure exhibit higher churn rates.


                  ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Churn%20Rate%20By%20Tenure%20Category.png)
                  


    Age Group Retention:

    - Customers under 20 have the lowest churn rates, indicating higher retention among younger demographics.
    
    - Customers above 51 exhibit significantly higher churn rates, suggesting potential gaps in product offerings for older customers.


                  ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Churn%20Rate%20By%20Age%20Group.png)



    Customer Activity Levels:

    - Gender Activity Comparison: Male customers are more active than female customers across all metrics.


    Regional Activity Insights:
    
    - France has a higher proportion of active customers, predominantly male.
    
    - Spain has the lowest number of exited customers, indicating better retention in this region.


                   ![image alt](Charts/https://github.com/RosemaryDeal/Data-Analysis-Final-Project/blob/6867202042177dbb5118d564336277848592d8ae/Charts/Customer%20Status%20by%20Geography%20and%20Gender.png)


  
    # Recommendations:
    
   
    - Targeted Product Development: Develop and tailor banking products to better serve older customers (above 51) to reduce churn rates.
   
    - Gender-Specific Strategies: Implement strategies to engage female customers more effectively, considering their lower account balances and different salary trends.
  
    - Enhance Credit Services: Continue to support and potentially expand credit score utilization services, particularly among active and younger customer segments.
  
    -  Retention Programs: Focus retention efforts on customers with moderate tenure to mitigate high churn rates in this group.


