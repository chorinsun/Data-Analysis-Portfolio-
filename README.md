# Data-Analysis-Portfolio

Following are my projects in SQL, R, Python, Tableau & Excel

## Contact:

email: chorinsun0@gmail.com

LinkedIn: https://www.linkedin.com/in/chorin-sun-576518204/

## Portfolio Projects

In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Coupon Distribution User List Optimization 


**Code:** [`Purchasing Intention Score Calculator`](xyz)

**Objective:** Optimize coupon distribution by identifying users with high purchase intent who are still evaluating their purchase, and deliver targeted coupons to encourage conversion.

**Challenge/Problem:** Through results from quantitative surveys, users reported two main reasons for not purchasing:
  1. Product price is too high
  2. Forgot to purchase before project had ended

Previously, coupons were sent to users who have low or no purchasing intent, resulting in minimal impact and inefficient distribution. The targeting approach lacks sufficient selectiveness, causing coupon usage rates to be unpredictable. As a result, it becomes difficult to accurately estimate the appropriate number of recipients, causing the coupon budget to be either underutilized or exceeded.


**Solution:** Develop an algorithm that scores users from 0 to 10 on their purchasing intent, based on their on-site behavior and past purchasing history. Coupons are then delivered to users who have not yet purchased and have a score above 6, motivating them to convert and helping extend their lifetime value (LTV).


**Results:** After A/B testing across each scoring group, users who received a coupon generated 93% more GMV than those who did not, achieving a 132% campaign ROI (after costs) during the coupon validity period. ROI increased consistently with higher scoring groups, validating the algorithm’s ability to accurately identify users with strong purchase intent.


The positive impact extended beyond the coupon window: even 90 days after the campaign, users who received the coupon continued to purchase 97% more than those who did not.
