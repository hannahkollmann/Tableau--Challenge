# Tableau-Challenge

## Instructions
Congratulations on your new job! As the new lead analyst for the New York Citi Bike program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers. Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.


## Data Source
Monthly CSV files (January 2024 - March 2024) were collected from [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage. Then, a Juypter notebook was used to merge the files into one CSV file. Due how large the data is, the results were not uploaded to Github. 

## Visualizations 
https://public.tableau.com/app/profile/hannah.kollmann/viz/Tableau_Challenge_Kollmann/Story 


## Analysis


### 1. User Analysis
A total of 171,855 users registered using the app from January 2024 to March 2024. Memebers used the Citibikes the most when compared to casual riders. Electric bikes were a more popular than the classic bike amongst both members and casual riders. The most popular days to ride during this three-month span were Thursdays and Fridays. The peak ride times were during the morning and evening comute hours (between 7-8 am and 5-6 pm). 
<img width="648" alt="Screenshot 2024-07-15 at 8 06 08 PM" src="https://github.com/user-attachments/assets/02ef6fa8-34b6-4fc5-a9df-0418df1eb815">

### 2. Station Analysis
Top ten stations for both ending and starting a journey are Grove St PATH and Hoboken Terminal - River St. & Hudson Pl. As stated earlier, the most popular ride times appear to be on Thursdays and Fridays. 
<img width="662" alt="Screenshot 2024-07-15 at 8 12 31 PM" src="https://github.com/user-attachments/assets/56774c28-d9d2-45b8-8ae6-1a95c3872e18">

### 3. Map Analysis
Most bike rides were made for short distances as noted by the clusters of data. 
<img width="636" alt="Screenshot 2024-07-15 at 8 14 01 PM" src="https://github.com/user-attachments/assets/a4fa0640-81c2-4883-b0fe-bdc09749f29f">

### 4. Limitations 
There is not enough data in this analysis about rider statistics (e.g., duration of trip) or rider demographics. This data only explores three months worth of data. Results and trends may vary if a longer time period was studied. 


### 5. Recommendation & Next Steps
My recommendations is to increase the number of electric bikes in the busy stations (specially Grove St. Path and Hoboken Terminal - River St. & Hudson Pl.) as they are more popular than the classic bikes. I also recommend to find ways to convert more casual riders into members to better predict ride patterns. Additionally, rebalance the electric bikes in the busy areas ensuring that there is more availability during peak hours (7-8 a and 5-6 pm).


Next steps include to create a docking system aimed at rebalancing electric bikes. Further analysis could be used to predict how the bikes move across the city better to assist wit the availability. 



