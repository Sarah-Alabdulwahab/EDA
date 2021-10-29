# MTA Turnstile Exploratory Data Analysis

### 1.	Introduction

The Metropolitan Transportation Authority (MTA) is North America's largest transportation network, covering a 5,000-square-mile travel area surrounding New York City through Long Island, southeastern New York State, and Connecticut [1]. The goal of this project is to explore the Metropolitan Transportation Authority (MTA) turnstiles data to determine the busiest stations in order to reduce the traffic by adding more turnstiles in those stations. I worked on four months of data provided by the MTA, which had features such as the station, date, cumulative number of entries and exits, etc.

### 2.	Data Description

The MTA Turnstile dataset will be obtained from the MTA website that stores weekly data that contains the following fields:

•	C/A: Control Area (A002).

•	UNIT: Remote Unit for a station (R051).

•	SCP: Subunit Channel Position represents a specific address for a device (02-00-00).

•	STATION: Represents the station name the device is located at.

•	LINENAME: Represents all train lines that can be boarded at this station.

•	DIVISION: Represents the Line originally the station belonged to BMT, IRT, or IND.

•	DATE: Represents the date (MM-DD-YY).

•	TIME: Represents the time (hh:mm:ss) for a scheduled audit event.

•	DESC: Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours).

•	ENTRIES: The cumulative entry register value for a device.

•	EXITS: The cumulative exit register value for a device.

<br>
Additionally, I want to create new fields, as follows:

•	DAILY_ENTRIES: Represents the total of entries per station per day.

•	DAILY_EXITS: Represents the total of exits per station per day.

•	DAILY_TOTAL: Represents the total entries and exits per day.

### 3.	Tools

To meet the requirement of the project, the Python libraries I will be using are SQLAlchemy, Pandas, Numpy, Matplotlib, and Seaborn. 
 
### 4.	Reference

[1] 	"The MTA," Metropolitan Transportation Authority, [Online]. Available: https://new.mta.info/about-us. [Accessed 20 September 2021].



*********************************************
The first project - T5 Data Science Bootcamp

Tuesday, September 21, 2021
