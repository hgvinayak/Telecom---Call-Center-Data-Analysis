# Telecom: Call-Center-Data-Analysis
This Repository will focus on Telecom - call center data and related important KPI parameters associated with it.

✔ Data Set: Call center data set of Telecom domain

🔵	Tool Used : Postures SQL (Pgadmin)

🌱	Objective: to analyse the call center dataset and provide the insights on the different KPI parameters to the Telecom manger to explain the whole story.

To achieve the required result we need to focus on important KPI Parameters as mentioned below,
1.	Total calls received ( abonded and answered)
2.	Average customer satisfaction rating
3.	Total unresolved calls and by Topic.
4.	Average speed of answer in seconds
5.	Category wise complaints received.
6.	Calls by time – Hourly wise count and cumulative count.
7.	Agent’s Performance Quadrant – Average handle time (talk duration) VS calls answered.


# Steps: 
1.	Connecting the Python to PSSQL.
2.	Reading the Excel File from Python using Pandas
3.	Inserting that data into PSSQL Database.
4.	Handling the null values and ensure the data integrity.
5.	Data analysis in SQL to get the required KPI parameters and providing the recommendations to Telecom manager.

# 💐 Key Takeaways and Recommendations from the analysis:

 1. Total 5000 calls has bee received out of which 946 calls has been abonded.
 2. The average customer satisfaction rating is only 2.76.
 3. Total 1354 calls has not resolved so far and on an average 250 calls are unresolved for each Topic wise.
 4. The average speed of answer for each agent is above 50 seconds.
 5. The calls are at peak between 11am to 5pm and at 6pm suddenly dropped.
 6. The highest calls answered by Agent "Jim" and the lowest calls answered by "Stewert'.

# Recommendations:
1. Need to focus on not answered calls as it will affect the customer satisfaction.
2. To work on the unresolved calls and find out why these calls are still unreslolved.
3. To find out the drastic reduction in calls suddenly by 6 pm -- is it genuine or any issue is happended from call ceter side.
4. Need to provide the training to all the agents on all the Topics to effectively resolve the issue.

