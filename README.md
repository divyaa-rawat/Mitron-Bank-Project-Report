# Mitron Bank Credit Card Launch Project Report

### Explore the Dashboard : https://app.powerbi.com/view?r=eyJrIjoiYjc3MmE5NDEtODg5Yi00YjkzLWI1NDctYzI1MDUzZjRjZjI5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Overview

Mitron Bank, a financial institution headquartered in Hyderabad, is gearing up to introduce a new line of credit cards. This dynamic dashboard, crafted for strategic decision-making, delves into customer needs and market trends. The goal is to broaden Mitron Bank's product offerings and enhance its presence in the financial market.

## Project Focus :


The project is divided into three main parts 

1. DEMOGRAPHIC VIEW

         Uncover intricate details about Mitron Bank's diverse customer base:

         - City of residence
         - Occupation
         - Gender, and more

         This exploration aims to provide a holistic understanding, 
         guiding strategic decisions for the credit card launch.

2. SPENDING INSIGHTS

         Dive deep into customer spending habits:

         - Top spending categories
         - Preferred payment methods
         - Monthly spending patterns

         Gain insights to inform strategic decisions for the 
         upcoming credit card launch.
3. INSIGHTS & RECOMMENDATIONS 

         Distill and present key insights from the project:

         - Practical recommendations for Mitron Bank
         
         This section is designed to guide the bank in making 
         well-informed decisions for a successful credit card launch.

## Key Measures 
 
- Female = CALCULATE(COUNT(dim_customers[customer_id]),dim_customers[gender] = "Female")

- Female % = DIVIDE([Female],[Total Customers],0)

- Income = CALCULATE([Sum of avg income],ALLSELECTED())

- Male = CALCULATE(COUNT(dim_customers[customer_id]),dim_customers[gender] = "Male")

- Male % = DIVIDE([Male],[Total Customers],0)

- Married = CALCULATE(COUNT(dim_customers[customer_id]),dim_customers[marital status] = "Married")

- Married % = DIVIDE([Married],[Total Customers],0)

- Single = CALCULATE(COUNT(dim_customers[customer_id]),dim_customers[marital status] = "Single")

- Single % = DIVIDE([Single],[Total Customers],0)

- Sum of avg income = SUM(dim_customers[avg_income])

- Total Customers = COUNT(dim_customers[customer_id])

- Total Sending = SUM(fact_spends[spend])

- Utilization % = DIVIDE([TSpend],[Sum of avg income],0)

   

## Dashboard in a Snapshot

### Home 

![or](https://github.com/divyaa-rawat/HR-Analytics/assets/147628244/0ba18b86-4b0c-4b7c-830c-7f712bf4b150)


### Demographic View
![Screenshot 2024-01-09 154259](https://github.com/divyaa-rawat/HR-Analytics/assets/147628244/fd26d544-4924-41bb-9633-abb8b5b303bc)



### Spending Insights
![Spend](https://github.com/divyaa-rawat/HR-Analytics/assets/147628244/444e8750-fe5d-4c83-a72e-423ef9412695)


### Insights & Recommendations
![Insights](https://github.com/divyaa-rawat/HR-Analytics/assets/147628244/8fb393ac-0927-4497-9b03-377672b79def)
 
# Insights

Following inferences can be drawn from the dashboard;

### [1] Demographics:
     
     Mumbai stands out with the highest Mitron users (26.95%), followed by Chennai and Bengaluru.

     A significant majority of customers are male (65%) and married (78%).

     Salaried IT employees are the largest occupational group (32.35%), followed by other salaried employees (22.33%).

     The age group of 25-34 (37.45%) and 35-45 (31.83%) dominates the customer base.
    
### [2] Spending Patterns:
     
     Credit cards are mainly used for bill payments and groceries.

     September reflects the highest spending, likely due to the festive season.

     Mumbai (32%), Delhi NCR (21%), and Bengaluru (19%) lead in spending behavior.

     Males and married individuals tend to have higher spending patterns.

### [3] Utilization Percentage:

     Mumbai and Delhi NCR exhibit the highest Utilization Percentage.

     Higher utilization is observed among males and single individuals.

     Salaried IT employees, freelancers, and other salaried employees show significant utilization.

     The age group of 35-45 displays the highest utilization percentage, followed by 25-34.


# Recommendations
 
### [1] Geographic Targeting:

     Establish local partnerships in Mumbai for co-branded promotions. 
     Engage with local events and influencers to strengthen brand presence.
  
### [2] Demographic Focus:
      
     Introduce a "Family Milestone" program, offering special rewards for joint account holders 
     and additional benefits for families, aligning with the majority of married customers. 
     This feature promotes financial collaboration within families.

### [3] Occupational Incentives:

     Collaborate with renowned IT training platforms for exclusive discounts on certifications. 
     Launch a Tech Enthusiast Program, providing additional perks for IT employees.

### [4] Age-Specific Rewards:
    
     Introduce a dynamic rewards system that evolves with age. For example, adventure sports discounts 
     for the younger demographic and premium travel benefits for the 35-45 age group.


### [5] Festive Season Promotions:

     Organize a Mitron Festival, offering limited-edition festive-themed rewards, 
     discounts, and exclusive events throughout September to boost engagement.

These insights and recommendations are tailored to support Mitron Bank in the successful launch of their credit card, ensuring a strategic and impactful market entry.










