# Project_Module_5
ML-Project-5-PCMLAI
[Jupyter Link](http://localhost:8888/lab/tree/Downloads/assignment5_1_starter/prompt.ipynb](http://localhost:8888/lab/tree/Downloads/assignment5_1_starter/prompt.ipynb)
# Coupon Acceptance Rate Analysis

This project investigates coupon acceptance rates among various demographic groups and how different factors such as weather, destination, and marital status influence the likelihood of using coupons.

## Data Cleaning
- The `Car` column had a significant number of `NaN` values (see Fig.1), which were replaced with `1` to represent individuals with cars. 
- Columns with few `NaN` values were removed to maintain data integrity.
Figure1: 
![image](https://github.com/user-attachments/assets/114bc04c-5f42-4329-9006-71559af9d0cb)

4-What proportion of the total observations chose to accept the coupon?
percentage of coupon acceptance % 57
Figure 2

![image](https://github.com/user-attachments/assets/13319633-61c6-464a-8c24-edf79912b111)


5.	Use a bar plot to visualize the coupon column.
Figure 3

![image](https://github.com/user-attachments/assets/a00f384e-e86b-49e2-bfbe-b70a08228264)


6.	Use a histogram to visualize the temperature column.

   Figure 4

  ![image](https://github.com/user-attachments/assets/2473b763-94b0-4407-9cd9-616f25555aaf)

  The correlation between the columns are also investigated to gain insight (see Fig.5)

  Figure 5

  ![image](https://github.com/user-attachments/assets/355659a4-ad69-42af-9aee-8a3b8b7ab9f1)

  In addition, A for loop was generated to create a series of plots to study the influence of columns on coupons acceptance (see the Jupyter link above)

## Investigating the Bar Coupons
  
2.	What proportion of bar coupons were accepted?
Accepted bar coupons:: 41.19%
3.	Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.
Acceptance rate for those who go to bars 3 or fewer times a month: 56.26%
Acceptance rate for those who go to bars more than three times a month: 62.13%
Figure 6
![image](https://github.com/user-attachments/assets/0bcf7752-97f3-4fb9-9553-a1a911cb1667)

4.	Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others.  Is there a difference?
Acceptance rate for Group 1 (more than once a month and are over the age of 25): 62.30%
Acceptance rate for Group 2 (all others): 55.41%
Yes, there is a difference. 
5-Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forest.
Acceptance rate for Group 1 (goes to bars more than once a month, passengers not kids, non-farming occupations): 62.50%
Acceptance rate for Group 2 (all others): 54.61%


6.	Compare the acceptance rates between those drivers who:
•	go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
•	go to bars more than once a month and are under the age of 30 OR
•	go to cheap restaurants more than 4 times a month and income is less than 50K.
•	Acceptance rate for Group 1 (goes to bars more than once a month, passengers not kids, not widowed): 62.50%
•	Acceptance rate for Group 2 (goes to bars more than once a month and under 30): 62.92%
•	Acceptance rate for Group 3 (goes to cheap restaurants more than 4 times a month, income less than 50K): 60.25%


Summary of above results
1. People who go to bars regularly are more likely to use coupons since it fits their lifestyle.
2. Older drivers (over 25) who visit bars frequently seem more interested in bar coupons.
3. Drivers without kids or dependents tend to accept coupons more, possibly because they have more flexibility to go out.
4. Lower-income drivers who eat at cheaper restaurants are more likely to appreciate savings from bar coupons.
5. In general, social habits and fewer family responsibilities seem to increase the chance of using bar coupons.

## Investigating the Bar Coupons
The independent investigation focused on comparing the acceptance rate of passengers who visited coffeehouses 3 or fewer times a month to those who visited more than 3 times. The investigation sought to understand how social habits, age, income levels, and family responsibilities influenced coupon acceptance behavior.
•	Social Habits: Passengers who frequently visited social places like coffeehouses were more likely to accept coupons. This trend parallels findings in the bar coupon analysis, where social habits increased the likelihood of coupon usage.
•	Income and Flexibility: Similar to the behavior observed with bar coupons, passengers without dependents or family obligations appeared to accept coupons more readily, likely because they have more flexibility to indulge in social activities, such as going to coffeehouses.
•	Age and Income Levels: Older passengers, particularly those over 25, who frequented coffeehouses were more likely to accept coupons. Lower-income passengers who typically ate at lower-cost venues were also more inclined to use the coupons to maximize savings.
Figure 7 
![image](https://github.com/user-attachments/assets/9e61bbff-0823-431f-b69e-f4e8e538b8d5)

The acceptance rate of any coupon among individuals who visit coffeehouses 4-8 times a month varies depending on the weather:

Sunny Days: Highest acceptance rate at 67.51%.
Rainy Days: Moderate acceptance rate at 50.00%.
Snowy Days: Lowest acceptance rate at 48.36%.
This indicates that coupon acceptance is most favorable on sunny days, while it decreases slightly in rainy or snowy weather (see fig.8).

Figure 8
![image](https://github.com/user-attachments/assets/578e7e8d-6cb1-41a7-96aa-3b37c0cb5f5c)

Fig.9 shows the Acceptance Rate of Coupons by Destination with the following results:

Home: The acceptance rate is around 50%.
No Urgent Place: The highest acceptance rate, exceeding 60%.
Work: The acceptance rate is slightly below 50%.
This suggests that passengers traveling to non-urgent destinations are more likely to accept coupons, while those heading to work or home have a lower, but still significant, acceptance rate.
Figure 9
![image](https://github.com/user-attachments/assets/e0dd2e90-0ceb-4790-b761-5d192f658ece)

Fig.10 shows the Coupon Acceptance Rate by Destination with respect to total participants with the following results:

Home: The acceptance rate is around 12%.
No Urgent Place: The highest acceptance rate, reaching over 30%.
Work: The acceptance rate is slightly below 15%.
This indicates that participants heading to non-urgent places are much more likely to accept coupons compared to those going home or to work. This suggests that people with more flexible or leisurely destinations may be more inclined to use coupons.

Figure 10
![image](https://github.com/user-attachments/assets/78fc4008-d15a-4c00-b883-8e079514001f)

Fig.11 indicates the following:
Home: The coupon acceptance rate is around 12%.
No Urgent Place: The highest acceptance rate at about 30%, indicating that people with no urgent destinations are the most likely to accept coupons.
Work: The acceptance rate is just under 15%, suggesting that those headed to work are less likely to use coupons compared to individuals with flexible or non-urgent plans.
This figure reinforces the trend that coupon acceptance is highest among those with more leisure or non-urgent destinations.

Figure 11
![image](https://github.com/user-attachments/assets/da93f94f-806f-434f-81ad-ea81e9cc4828)

Figure 12 represents the Coupon Acceptance Rate by Marital Status with respect to total participants. Here are the observations:

Married Partner and Single individuals show the highest acceptance rates, both above 20%.
Unmarried Partner has a moderate acceptance rate, close to 15%.
Divorced and Widowed participants exhibit the lowest acceptance rates, each below 5%.
This suggests that single and married participants are more likely to accept coupons compared to those who are divorced or widowed.
Figure 12
![image](https://github.com/user-attachments/assets/e0691d8b-6a87-48f1-ae72-1202baccea4f)


Fig 13 shows the Coupon Acceptance Rate by Gender with respect to total participants.
Observations:
Female and Male participants have nearly identical coupon acceptance rates, both close to 30%.
There is no significant difference in coupon acceptance between genders.
Figure 13
![image](https://github.com/user-attachments/assets/06102465-a840-44bf-8e08-478954ba9c6b)

## Conclusion
Will this strategy work? Yes, the strategy is likely to work. Results shows high coupon acceptance among people who frequently visit coffeehouses or bars. For example, passengers visiting coffeehouses 4-8 times a month had a 67.51% acceptance rate on sunny days. Similarly, regular bar-goers accepted coupons at a rate of 62.13%.

Will drivers use coupons right away, later, or never?

Right away: Likely if drivers are heading to non-urgent destinations (30% acceptance rate).
Later: Possible if drivers are busy or on their way to work (15% acceptance rate).
Never: Some may not use coupons if offers don't match their needs, but overall coupon acceptance is high at 57%.
In summary, targeting frequent social destination visitors with coupons should increase customer traffic effectively.











   
