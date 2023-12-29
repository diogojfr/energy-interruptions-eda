# U.S. electric disturbance events analysis

This repository contains an exploratory analysis of data on electrical disturbance events in the United States from 2019 to 2022.

The dataset analyzed in this repository is provided by the United States Department of Energy (DOE). The DOE provides this annual data in the form of spreadsheets that are available in their annual summaries and also in the 'dataset' folder of their repository.

The data includes information such as month, type of event that caused the electrical disturbance, and number of consumers affected.

### What is a electric disturbance event?
In a general way, an electrical disturbance event can be described as a term to categorize problems associated with power interruptions, ranging from a loss of electrical service for a short period of time to major blackouts.

Various factors can cause power interruptions, including severe weather, human/vegetation interference near power lines, system operations, and even cyber attacks.

### Objectives
- Collect annual summaries from DOE and clean/prepare dataset for analysis;
- Investigate whether or not the number of electrical disturbance events is increasing;
- Examine how the number of events changes during different seasons, months, and times of day;
- Investigate what types of events have increased or decreased over time;
- Create other questions to answer using the data.

### Tools used
For this analysis, it was used: 
- Pandas for data manipulation;
- Seaborn, Matplotlib, and Plotly for data visualization.


### Exploratory data analysis findings

# 
- Texas and California are the states that registered more electric disturbance events, with 211 and 195 events, respectively.
  
 ![newplot2](https://github.com/diogojfr/energy-interruptions-eda/assets/96347565/e4429dc0-436b-4c82-bc12-5b4bf4605dbe)

# 

- Severe weather is the most commom event type.
  
  ![output1](https://github.com/diogojfr/energy-interruptions-eda/assets/96347565/8511c023-fa72-46d7-a7a9-5fa2501e6665)

# 

- In the last four years, summer season had more disturbance events in three years.
  
  ![newplot1](https://github.com/diogojfr/energy-interruptions-eda/assets/96347565/bfd43c92-ceca-4fb2-8c32-ad9273ab202e)

# 

- Periods of the day such as 11-12 p.m. and 18-19 p.m. registered more electric disturbances events.

![output2](https://github.com/diogojfr/energy-interruptions-eda/assets/96347565/91481a85-70aa-4e81-af14-f87257f297ed)

# 

- The number of electric disturbances caused by cyber-attacks and suspicious activities is on the rise.
  
![output3](https://github.com/diogojfr/energy-interruptions-eda/assets/96347565/5aec4570-cd64-419c-99d1-a6e2896e75f5)
