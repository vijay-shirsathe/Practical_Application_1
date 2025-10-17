# Practical_Application_1

## Project Title: Will the Customer Accept the Coupon?

** Overview: **
The goal of this project is to analyze the survey data to determine whether a driver accepts the coupon once it is delivered to them. Data is sourced from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he/she will accept the coupon if he/she is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - $50).

** Report: **
Below is a brief report that highlights driver/customer characterisitics that influence acceptance of two coupon categories: (1) bar coupons and (2) carryout and takeaway coupons.

** Link to the Jupyter notebook: ** [Practical_App_1](Practical_App_1.ipynb)

** Key findings and conclusion for bar coupons: **
* On an average, 41% of bar coupons get accepted
* Drivers that visit bars more frequently (>= 4 times per month) are almost twice as likely to accept bar coupons (approx 77% acceptance) than those who visit less often or dont visit at all (approx 37%)
* Drivers over age of 25 that visit bars at least once a month are two times likely to accept bar coupons (approx 70%) Vs rest of the drivers
* Within the drivers that visit bars at least once a month, bar coupon acceptance rate stays at approx. 70% regardless of the age
* Within the drivers that visit bars at least once a month, bar coupon acceptance rate stays at approx. 70% when they don't have kid passengers
* Drivers that frequently ( >=4 times a month) visit cheap restaurants and have lower income (<$50K) are more likely (1.5 times) to accept bar coupons than average population.
* Bar coupons are highly effective for drivers who visit bar 4 or more times a month and also quite effective for lower income (<$50K) drivers that frequently eat at cheap restaurants, although not as much as for the frequent bar visitors.

** Key Findings and Conclusion for carry out & takeaway coupons: **

* Carry out & takeaway coupons are more popular (overall acceptance rate of 73.55%) than bar coupons
* 1 day carryout coupons are more effective  (78% acceptance) than the ones with 2 hour expiry, although 2 hr expiry coupons do get accepted at 66%
* Bad weather does lower the coupon acceptance rate down to 61% and good weather boosts it (76%)
* 2 PM is the best time and 7 AM is the worst time for coupon acceptance
* Coupon acceptance rate doesn't seem to significantly vary with the factors such as whether the driver is (a) going in the opposite direction, (b) a high income earner, (c) carrying kids in the car, and (d) eating frequenty (4 or more times a month) in expensive restaurants.

