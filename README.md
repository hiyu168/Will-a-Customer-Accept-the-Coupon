# Will a Customer Accept the Coupon?

## Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor in whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

## Overview

The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

## Data

This data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then asks the person whether they will accept the coupon if they are the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons: less expensive restaurants (under $20), coffee houses, carry out & take away, bars, and more expensive restaurants ($20 - $50).

## Deliverables

The final product should be a brief report highlighting the differences between customers who did and did not accept the coupons. To explore the data, you will utilize your knowledge of plotting, statistical summaries, and visualization using Python. The findings will be published in a public-facing GitHub repository as your first portfolio piece.

## Data Description

Keep in mind that these values mentioned below are average values.

### User Attributes

- **Gender**: male, female
- **Age**: below 21, 21 to 25, 26 to 30, etc.
- **Marital Status**: single, married partner, unmarried partner, or widowed
- **Number of Children**: 0, 1, or more than 1
- **Education**: high school, bachelor's degree, associate's degree, or graduate degree
- **Occupation**: architecture & engineering, business & financial, etc.
- **Annual Income**: less than $12,500, $12,500 - $24,999, $25,000 - $37,499, etc.
- **Number of times they go to a bar**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
- **Number of times they buy takeaway food**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
- **Number of times they go to a coffee house**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
- **Number of times they eat at a restaurant with an average expense less than $20 per person**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8
- **Number of times they go to a bar**: 0, less than 1, 1 to 3, 4 to 8, or greater than 8

## Conclusion

The analysis and visualization of probability distributions highlight a distinct difference between drivers who accept coupons and those who do not. Factors such as job type, age range, and yearly income, when combined, seem to significantly influence coupon acceptance rates. Our observations show that individuals from specific professional backgrounds and financial standings are more likely to accept coupons. Notably, acceptance rates vary across different age groups, emphasizing that age plays a critical role in drivers' decisions to accept coupons.

Based on these insights, data-driven marketing strategies can be developed. For instance, younger customers aged 21 to 26, as well as those with very low incomes (below $12,500) or very high incomes (above $100,000 annually), show higher receptivity to coupon offers. Although it is uncertain whether this is due to effective marketing or inherent characteristics of the variables, it suggests the necessity of creating and implementing market strategies to target these two groups for maximizing profits.

The coupons 'Restaurant(<20)' and 'Carry out & Take away' have a higher probability of being accepted, while 'Bar' coupons are among those least likely to be accepted. Drivers with a 'friend(s)' passenger type are the most likely to accept the coupon, while those with 'Kid(s)' passengers are the least likely.

In summary, understanding these probability distributions that drive the trends is essential for developing predictive models for future coupon distribution strategies. This approach will enable more strategic marketing investments and yield better results.
