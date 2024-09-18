Project Title: Network Performance Analysis

Description:
This project aims to analyze and visualize network performance data to identify potential bottlenecks and areas for improvement. The data includes signal strength, SNR, call duration, environment, and more, with the goal of providing insights into network health and user experience.

1. Dataset
The dataset contains the following columns:

Timestamp: Date and time of the call
Signal Strength (dBm): Received signal strength in dBm
SNR (Signal-to-Noise Ratio): Quality of the signal
Call Duration (s): Duration of the call in seconds
Environment: Type of environment (e.g., home, urban)
Attenuation: Signal attenuation
Distance to Tower (km): Distance between the user and the nearest tower
Tower ID: Unique ID for each tower
User ID: Unique identifier for each user
Call Type: Type of call (e.g., voice, data)
Incoming/Outgoing: Indicates whether the call was incoming or outgoing

2. Key Steps
Data Cleaning: Checked for missing values and handled data appropriately.
New Columns Created:
Signal Strength Classification: Classified signal strength as weak or medium based on predefined ranges.
Call Drop Analysis: Classified calls as normal or dropped.
Part of the Day: Segmented data into morning, afternoon, evening, and night.
User Experience: Categorized users as having a good, medium, or bad experience based on signal strength.

4. Dashboard Visuals
   
Key Metrics:

Average Signal Strength: -85.00 dBm
Average SNR: 19.83
Total Call Duration: 413,143.44 seconds
Count of Users: 462

Visualizations:

Average Signal Strength by Tower: Visualizing the average signal strength for each tower.
Average Signal Strength by Environment: Comparison of signal strength across different environments (home, open, suburban, urban).
Signal Strength Classification: A bar chart showing the count of users with medium and weak signal strength.
Signal Strength vs. Timestamp: Line graph showing how signal strength fluctuates over time.
Signal Strength vs. SNR: Scatter plot showing the relationship between signal strength and SNR.
Distance to Tower vs. Signal Strength: Scatter plot showing the impact of distance on signal strength.
Average Distance and User Count by Tower: Bar chart showing the distance and user count for each tower.
SNR by Tower and Environment: SNR variation across towers and environments.
User Experience: Pie chart of users segmented by experience (good, medium, bad).
Average SNR and Signal Strength by Time of Day: Analyzing performance at different times (morning, afternoon, evening, night).

4. Key Insights
Signal Strength by Tower: Tower 4 had the lowest average signal strength at -90.03 dBm, indicating potential network issues.
Environment Impact: Users in urban areas experienced the weakest signal strength, while home environments had better performance.
User Experience: A significant portion of users (226) reported poor signal strength.
Distance Impact: As expected, signal strength deteriorates as the distance to the tower increases, reinforcing the need for more towers in weak signal areas.
Time-of-Day Variation: The best signal strength was observed during the evening, while the worst was during the morning.

6. Conclusion
The analysis reveals critical insights into network performance, with key areas for improvement including tower placement and signal strength optimization in urban areas. More towers or signal-boosting infrastructure may be needed to improve user experience and minimize call drops.


