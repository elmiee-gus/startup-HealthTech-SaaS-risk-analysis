# startup-HealthTech-SaaS-risk-analysis
# Business Problem 
1. How to maintain customer retention for health tech that only provides DNA Screening Test results (as one time transaction)
2. How does the vertical intergration from one time transaction to long term ecosystem affect customer retention and company revenue.
3. Users aren't transitioning from "results viewed" to "taking action." This project identifies "High-Risk" users to drive adoption of Telehealth/ Doctor on demand and Caregiving services.

# Key Metrics
- Customer Genetic Risk Score
- User Login frequency
- Attach rate - users that booked any services

# Dashboard Preview
[![Risk vs Engagement] (Healthtech and SaaS.pdf)]
*Correlation between genetic risk score and website usage*

# Key Business insights
- 50% User with genetic risk score >50 engaged with followup service - telehealth/caregiving
- *Churn Risk identified* : 10% of users with genetic score >50 have not booked a follow-up consultation.
- Integrated Caregiving services shown 63.67% of total revenue despite only being 15% of total bookings.
- Action Status represent user's genetic risk score to service adoption (it clarify those who actually booked a Doctor or Caregiver after the DNA test result)
- Overall service attach rate to service adoption is 65%, the attach rate for "Telehealth" is 35% higher than "Caregiving" which is 15% despite higher revenue.


# Tools Used
- Excel (Data Cleaning, IF-Logic, Countifs )
- Power BI (Data Visualization)


# Data Source
Synthetic dataset simulating genetic risk score and service adoption


# Business Recommendation
- Trigger an automated "Grab Doctor" discount for any user with a Risk Score >75
- Create an automated "Priority Alert" system. When a DNA result exceeds a risk threshold of 75, the system should automatically: Offer a "First Consultation" discount code valid for 48 hours to create urgency. 
- Bundle one "Free Doctor Discovery Call" with every DNA kit to increase the attach rate for "Telehealth" service.
- Transition from a one-time purchase model to a "Family Care" subscription.
  
