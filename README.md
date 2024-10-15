

#  TELCO CHURNING

### PROJECT STRUCTURE


<img width="1256" alt="Screenshot 2024-10-15 at 14 52 04" src="https://github.com/user-attachments/assets/e6177d6c-f48f-4f4a-9217-2875dc29ac63">

•Interactive PowerBI Dashboard: Available for download [here].

•Jupyter Notebook: Python code and libraries [[here]](https://github.com/ManuelMebrat/TELCO_CHURNING/blob/e332f57bb493e15494778e493ec88b48f1cfa4e4/Churn_Files/Telco_EDA.ipynb).

•SQL Queries: For QA testing of the dashboard [[here]](https://github.com/ManuelMebrat/TELCO_CHURNING/blob/f8651f0e24319716efd08e31b1e4deb6349dab68/Churn_Files/SQL_QA_Churn.pages).

•CSV Dataset: Download [[here]](https://github.com/ManuelMebrat/TELCO_CHURNING/blob/5dcf90172e48c1c4f5202ba78a73255ef38373a3/Churn_Files/Cchurn.csv).


# Conclusions & recommendations: 

1. **Enhancing Customer Loyalty**

**What is driving customers to stay?**

A. The presence of relationships or dependents significantly lowers churn rates, dropping from 33% to 19% and 31% to just 15%, respectively. Customer acquisition campaigns should target these groups, as they are more likely to maintain long-term loyalty.

B. Increased Perceived Value: Offering additional services enhances the overall value, making it difficult for customers to find equivalent packages elsewhere. This strategy could save nearly $250,000 monthly by retaining customers through added services.

2. **Key factors contributing to customer churn**

**What are we doing wrong?**

A. Device Quality and Offers: Customers are more inclined to switch to competitors when they perceive better devices quality, competitive pricing, and improved data or speed offerings. Notably, 46% of churn cases involve customers moving to competitors due to superior device options and offers.

B. Payment Methods and Service Quality Issues: Specific categories, such as Paperless Billing and the Electronic Check payment method, exhibit high churn rates (33.57% and 45.29%, respectively). Additionally, poor quality in Fiber Optic service is associated with a significant churn rate of 41.89%. Addressing these factors could substantially reduce churn within these segments.


### PROJECT BACKGROUND 
The telecom industry uniquely relies on both customer experience and emotional factors to drive retention. This project leverages the Telco Customer Churn Dataset from IBM Congos to delve into consumer psychology and its impact on customer retention. 

By analyzing this data, we aim to identify the variables that enhance customer loyalty and reduce the likelihood of churn. Specifically, the project will explore two key areas: **Enhancing Customer Loyalty & Key factors contributing to customer churn.**


# Why is this happenning?

Companies today often focus on customer acquisition, but what’s really happening is a lack of loyalty and high early churn. New customers frequently leave soon after joining, pointing to deeper issues beyond initial attraction. Without strong retention strategies, businesses risk losing customers as quickly as they gain them, missing opportunities for long-term growth and loyalty.


![image](https://github.com/user-attachments/assets/89264236-b8cb-4f1b-91cf-46473b33c1cc)

Out of 1,869 customers who churned, an alarming 55.49% left within the first 12 months. This underscores the critical importance of early customer experience, prompting two key questions:

1. What is driving customers to stay?

2. What is causing them to leave?

# 1. What is driving customers to stay?

### • A Loyal customer

![image](https://github.com/user-attachments/assets/e4c03504-6dc8-44ff-99c4-b53655bd5602)

• Our highest customer density is within the first 12 months, with 2,186 customers out of 7,043. After this period, we observe more stable retention. We define a loyal customer as one who remains beyond this initial 12-month period. Let’s explore customer behavior over time in more detail.

## Relationships

![image](https://github.com/user-attachments/assets/36b4c31f-c1f0-47a2-af7a-d2b9a57c34f8)

• Customers with dependents or partners tend to perceive a potential loss of stability and security as more significant. According to [Prospect theory,](https://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Behavioral_Decision_Theory/Kahneman_Tversky_1979_Prospect_theory.pdf) the fear of losing benefits or support from their current services may outweigh the perceived gains of switching providers. Having a partner can reduce the churn rate from 33% to 19%,and a dependant from 31% to just 15%. 

In conclusion, customers with family responsibilities show a higher propensity to stay with their current provider, as they value the stability and security it offers. 

However we can't directly control this variable, so what can we control to make they stay?

## Extra ~~services~~ Value

In a telco company, extra services refer to additional features or options offered to customers beyond basic services like internet, phonelines and multiple lines. For this company  the extra services are Only security, Online backup, Device protection, and Tech support. 

![image](https://github.com/user-attachments/assets/146d161c-3285-4bd5-98ab-807b624afa5b)

Understaing the cost of oportunity of diference churn rate between having or not this extra services, will give us an image of how much or company is losing by not engagig our customer with this services: 

![image](https://github.com/user-attachments/assets/42b3b9c4-4e2a-49f7-8491-2464fef6bc0d)

Extra services play a crucial role in reducing churn rates for telco companies. By bundling these additional features, the perceived value of the service increases, and customers are more hesitant to switch providers. Contributing to customer retention:

• Increased Perceived Value: Extra services enhance the overall package, making it harder for customers to find equivalent value elsewhere.

• Loss Aversion: Customers fear losing added protections (security, backup), making them less likely to switch providers.

• Customer Inertia: A comprehensive service package creates a barrier to leaving, as switching feels more complex and risky.

# **So how to increase Loyalty?**

**Personalized Support:** 

Implementing tailored support for customers with family. By understanding their need for stability and security, personalized offers or family bundles could resonate strongly with these segments.

**Loyalty Programs:** 

Creating a rewards or loyalty program that builds value over time would encourage longer-term relationships. For instance, customers could earn points for maintaining their service or using extra services, redeemable for discounts or upgrades.

**Flexible Bundles:** 

Creating flexible service bundles that offer customers more control over choosing extra services like security or backup could increase perceived value and reduce churn. Customers are less likely to leave if they feel the package is designed specifically for them.

**Promotional Trials:** 

Offering free trials of services like device protection or tech support can showcase the benefits and create habits of use, making customers more reluctant to give them up.


# 2. What are we doing wrong?

## • Straight reasons
![image](https://github.com/user-attachments/assets/6bb23a3c-8d30-4b6f-8f3f-ce8b66681910)

Competitor (841): A significant portion of customers are switching to competitors, suggesting they may perceive better value or service elsewhere. This highlights a need for competitive analysis and differentiation strategies.

Churn Reasons Due to Competitors:

• Competitor had better devices:  313 customers.

• Competitor made a better offer: 311 customers.

• Competitor offered more data:   117 customers.

• Competitor offered higher download speeds 100. 

Customers are more likely to switch when they perceive better value in terms of device quality, competitive pricing, and enhanced data and speed offerings. This underlines the importance for telecom providers to continually assess and potentially upgrade their device offerings and data plans to remain competitive and retain customers. So what are we doing wrong?


## • Payment process


![PEque;a](https://github.com/user-attachments/assets/849136e4-0033-496f-883c-c49aa70f1540)

![file](https://github.com/user-attachments/assets/97a92709-ddeb-4a61-9a8a-484d005c4cb6)


The data suggests that the Electronic Check payment method is associated with a notably high churn rate of 45.29%, compared to much lower rates for other methods like Credit Card (15.24%) and Bank Transfer (16.71%). 

• This discrepancy indicates a potential problem with the Electronic Check option that could be driving customers away.

Additionally, customers using Paperless Billing also show a higher churn rate of 33.57% compared to those using paper billing (16.34%). 

• This difference raises questions about whether the Electronic Check users might have concerns related to billing preferences or whether there is a broader issue with digital payment experiences.

The data indicates that customers using the Electronic Check payment method, particularly those enrolled in Paperless Billing, exhibit higher churn rates compared to other payment options. This suggests that while these options are popular, they may not provide the level of convenience or reliability that customers expect. Improving the ease and security of our payment infrastructure could enhance customer satisfaction and reduce churn.

## • Internet Service

![file2](https://github.com/user-attachments/assets/274a993a-e1b9-44d6-a7c8-e030d630959a)


The data reveals that Fiber Optic service users experience a high churn rate of 41.89%, which is significantly higher compared to DSL users (18.96%) and those without internet service (7.40%). This trend suggests potential issues specifically associated with Fiber Optic services that might be causing dissatisfaction among customers.



# What can we do?

**Handle Service Expectations:** Fiber Optic is often marketed as a high-speed and premium internet service. Customers may therefore expect top-notch performance and reliability. If we fall short in meeting these expectations, customers are more likely to look elsewhere.

**Competitive Pricing:** Fiber Optic plans are typically priced higher than DSL, but customers may not feel the extra cost is justified by the quality of service. To retain these customers, it may be necessary to ensure that our pricing is perceived as fair or provide additional value that justifies the cost.

**Adapt to Tech-Savvy Customers:** Fiber Optic users and those who prefer user-friendly payment methods are likely to be more tech-savvy. This demographic may be more sensitive to competing offers that highlight features like speed, data limits, or overall performance. They may also be more inclined to switch to a provider that delivers the best available service. Improving our service offerings and enhancing our payment infrastructure could therefore be key to retaining these customers.

