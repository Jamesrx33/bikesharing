# Citibike Analysis

### A Tableau analytics report designed to show Bike Rental statistics from prior Citibike data.

---
## **<p align="center">Overview</p>**
##### **<p align="center">How to optimize performance in the proposed Des Moines location</p>**
---

This report will show how to best implement a new branch of Citibike in the city of Des Moines. Using metrics provided from the New York Citibike branch, we were able to determine when and how bikes should be made available in our new branch in order to maximize expected volume. Below, in our Results section, is the list of our findings followed by a Summary statement and additional suggestions for further anaylsis.

---
## **<p align="center">Results</p>**
---
##### **<p align="center">August Peak Hours</p>**
---

<p align="center">
   <img width="1000" height="500" src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/August%20Peak%20Hours.png?raw=true">
</p>

  * Bikes are used primarily between the hours of 6am-10pm with peaks at 8am and 5pm.

---
##### **<p align="center">User Types</p>**
---

<p align="center">
   <img src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/User%20Types.png?raw=true">
</p>

  * Most of our customers are Subscribers.

---
##### **<p align="center">Overall Trip Duration per Ride</p>**
---

<p align="center">
   <img src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/Ride%20Durations.png?raw=true">
</p>

  * Nearly all of our rides last less than an hour.

---
##### **<p align="center">Trip Duration per Ride by Gender</p>**
---

<p align="center">
   <img src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/Ride%20Durations%20by%20Gender.png?raw=true">
</p>

  * Women, on average, ride slightly longer than men.

---
##### **<p align="center">Bike Usage by Weekday</p>**
---

<p align="center">
   <img src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/Bike%20Usage%20by%20Weekday.png?raw=true">
</p>

  * Weekdays are most busy at the beginning and ends of the day. Weekends are most busy in the middle of the day.

---
##### **<p align="center">Bike Usage by Weekday - Gender Comparison</p>**
---

<p align="left">
   <img width="400" height="500" src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/Female%20Hours%20of%20Operation.png?raw=true">
   <img width="400" height="500" src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/Male%20Hours%20of%20Operation.png?raw=true">
</p>

  * Female and Male customers have nearly identical Bike rental trends throughout the week.

---
##### **<p align="center">Customer Type Usage Comparison</p>**
---

<p align="center">
   <img src="https://github.com/Jamesrx33/bikesharing/blob/main/Resources/Customer%20vs%20Subscriber%20Weekday%20Heatmap.png?raw=true">
</p>

  * Customers tend to rent bikes on the weekends more than on weekdays. Subscribers rent more often during the week than during the weekend.


---
## Summary
#### What this means for the Des Moines location
---
When the Des Moines location is opened we would suggest making incentive plans for subscription users, as this is the preferred method of payment. More bikes should be in circulation on weekdays to accommodate higher volumes and maintenance should be performed from 11pm-3am daily. As less women than men are using the service in New York, some efforts should be made to cater to the female populous of Des Moines (Smaller, more colorful bikes and or advertising).


  * **Suggested Additional Analysis:**
    1. An Age-Based analysis should be done with "Birthdate" as a column and "Count of Bikes" as the rows
       * This will show the age of our users so we can cater to their generation
    2. A UserType vs Gender analysist should be done with "UserType" and "Gender" as rows and "Count of Bikes" as the size of marker
       * This will show the number of male/female/unknown by subscribers vs customers


---

## Reference Documentation - [Source Code Repository](https://github.com/Jamesrx33/bikesharing), [Download .zip file](https://github.com/Jamesrx33/bikesharing/archive/refs/heads/main.zip)
