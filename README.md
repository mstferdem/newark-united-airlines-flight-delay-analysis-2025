# United Airlines Departure Delay Analysis (EWR - 2025)
## Project Overview

This project analyzes United Airlines flight departure performance from Newark Liberty International Airport (EWR) in 2025. The goal is to identify patterns in delays and understand how factors such as destination, time of day, and flight duration influence departure delays.

### Objectives
- Identify destinations with the highest average departure delays
- Analyze whether flight duration impacts departure delays
- Examine delay patterns across different times of day
- Explore major causes of delays in the dataset
- Visualize key operational trends using Python
### Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
### Dataset Source

Bureau of Transportation Statistics (BTS)
On-Time Performance Data
https://transtats.bts.gov/ONTIME/Departures.aspx

### Data Processing Steps
- Loaded and cleaned flight delay dataset
- Converted time values into usable formats
- Created features such as:
  * Time periods (Morning, Afternoon, Evening, Night)
  * Delay indicator (is_delayed)
- Grouped data by destination, time period, and aircraft tail number
### Key Findings
#### Cancellations
- Overall cancellation rate was very low at 1.34%, indicating most disruptions were delays rather than cancellations.
#### Time of Day Analysis
- Evening had the highest number of delayed flights (7,283)
- Followed by Afternoon (6,935)
- Morning (5,788) and Night (4,191) had fewer delays
- Delays tend to increase later in the day due to congestion
#### Destination Performance
- Significant variation in delay performance across destinations
- Louisville International Airport (SDF) showed the highest average delay and acted as a major outlier
- Most other destinations showed moderate and consistent delay levels
#### Flight Duration Analysis
- Correlation between flight duration and departure delay: -0.002
- Indicates no meaningful relationship between flight length and delays
  #### Delay Causes
- Major contributors:
* Late Aircraft delays
* National Airspace System (NAS) delays
* Carrier-related delays
- Weather and security delays were minimal compared to operational causes
### Visualizations Included
- Bar charts of average delay by destination
- Scatter plot of flight duration vs delay
- Time-of-day delay comparison charts
- Delay distribution summaries
  ### Conclusion

The analysis shows that departure delays at Newark Liberty International Airport are primarily driven by operational and system-level factors rather than flight distance or duration. Congestion, scheduling pressure, and late aircraft arrivals are the main contributors to delays, especially during evening hours when airport activity is highest.

### Author
Mustafa Erdem
