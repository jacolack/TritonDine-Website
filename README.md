# About Triton Dine
This is an app I made in my free time after a few of my suitemates in Snoopy 703D came up with the idea behind it.

## Special Thanks To:

 * Juan Castaneda - UI Design
 * Grace Meister - App Logo
 * Ming Liu - The other three app logos... try to find them :)
 

## How the calculation works:

let `totalDays` be the number of days total in the current school year.
let `yourBalance` be the total number of dining dollars you have left (fetched via the login).
define a 'valid' day as one that a student can use their dining dollars roughly defined [here](https://hdh.ucsd.edu/housing/docs/Housing-Calendar-2019-20.pdf).
let `daysLeft` be the number of 'valid' school days left until the last day of Spring Quarter.

1. `ucsdGivesYou` = `totalDays`/your meal plan
2. "You've saved:" = `yourBalance` - `ucsdGivesYou` * `daysLeft` (if negative, that means overspent)
3. `weRecommend` = `yourBalance`/`daysLeft`
4. `youveUsed` = running total of all transactions today.
5. "You have:' = `weRecommend` - `youveUsed` (if negative, that means overspent)

# Questions? Problems? Feedback?
Email me at [tritondine@jacksheridan.com](mailto:tritondine@jacksheridan.com).

## Thanks for downloading! 
##### - Jack Sheridan
