# AI-ML-Assignment-5.1 - Coupon Acceptance Analysis  

## Data Cleaning  
- **"car"** feature removed due to **99% missing values** and minimal predictive impact.  
- Features **'Bar', 'CoffeeHouse', 'CarryAway', 'RestaurantLessThan20', and 'Restaurant20To50'** had **<1% missing values**, replaced with their **most frequent values**.

## Key Observations  
- **Frequent bar-goers** (3+ times/month) have a significantly higher **coupon acceptance rate (77%)** than less frequent visitors (37%).  
- **Drivers over 25** maintain the **same 77% acceptance rate** as younger drivers when they visit bars often.  
- **Passengers (excluding kids) and non-farming jobs** correlate with **higher acceptance rates (77%)**.  
- Expanding demographics to **young bar-goers, non-widowed people, and price-conscious diners** lowered acceptance to **53%**, suggesting varying influences on coupon behavior.  

## Hypothesis  
- **Social & frequent bar-goers** are the **most likely** to accept coupons.  
- **Young age & price consciousness** influence acceptance but are **less significant**.  
- **Bars should directly target habitual customers** for better promotional success.

## Restaurant Coupon Insights  
- The **overall coupon acceptance rate is 70.78%**, indicating broad appeal for **discounted restaurants**.  
- **Frequent visitors (3+ times/month) accept restaurant coupons at a higher rate (73%)** than infrequent diners (69.3%).  
- **Age does not significantly impact coupon acceptance** (71.5% for over 25 vs. 70.5% for under 25).  
- **Drivers without kid passengers and those in non-farming professions accept coupons more frequently (72.6%)** compared to others (69.8%).  
- **Passengers, occupations, and restaurant visit frequency** play a role in acceptance, while **age and income have minor effects**.  

## Conclusion  
- **Frequent diners** are **more likely** to accept restaurant coupons.  
- **Passenger type & occupation** influence coupon acceptance significantly.  
- **Age and income play smaller roles in decision-making**.

## Source Code
- **Data:** 
- **Jupyter Notebook:** 
