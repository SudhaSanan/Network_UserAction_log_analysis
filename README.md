# Network_UserAction_log_analysis
##Overview
This project involves the analysis of network and user action logs for an IT group within a multinational company. The primary objective is to gain insights into user behavior, device usage, and application usage patterns.

##Data Description
The dataset includes various event types and captures the following information:

Device MAC
Date and time
Data centre
Variable data in a description field
Most users in this dataset work on one file at a time, saving and closing it before starting a new file or opening another.
##Event Types
Workstation (cabled to the network) startup and shutdown
Wi-Fi connected devices that connect or disconnect
User logins and logouts
User file saves/closes and file new/opens
User use of MS Office, a browser, and other apps
User work breaks and lunch breaks
##Analysis Tasks
###E4: List Devices and Usernames
Identify the devices involved in the dataset.
Determine if they are workstations or Wi-Fi connections.
List the usernames involved in the dataset.
###E5: Profile Users' Computer Use
Analyze each user's application usage, including browser and other app startups/shutdowns.
Provide the average, count, minimum, and maximum times (in minutes) for these events for each user and device over the 5 days of data.
###E6: Value of Calculating Mod([Log Time])
Explain the necessity of calculating the mod([log time]) or ([log time] - int([log time])) for profiling application usage.
Discuss the implications of averaging the date and time of events without this calculation.
###E7: Profile MS Office Use (Duration)
Profile the length of MS Office use in hours for each device.
Provide count, average, minimum, and maximum usage times.
Develop a data model that uses two log record types and "Previous" calculations to support this analysis.
###E8: Lunch and Learn Video Content
Propose a brief profile of a significant historical event related to Data Analysis.
Pose a question about the ethics and/or social impact of the event.
Provide an answer to start the discussion.
##Methodology
Data Cleaning: Preprocess the data to handle missing values, incorrect entries, and any inconsistencies.
Descriptive Statistics: Calculate basic statistics (count, mean, min, max) for each user and device.
Time Calculations: Use the modulo operation on log times to accurately profile user activities.
Data Modeling: Develop models to analyze MS Office usage and other application patterns.
Visualization: Create visualizations to represent user behavior and device usage effectively.

##Conclusion
This analysis provides valuable insights into user behavior and device usage within the organization. By understanding these patterns, the IT group can make informed decisions to improve network efficiency and user productivity.


##Contributions
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.
