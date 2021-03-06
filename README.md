# Identifying COVID-19 Lead Effects in Texas
Dhruv Arora (dharora@uw.edu)  
University of Washington  
12/05/2020  

![Lead effect](https://github.com/Arora-Dhruv/Identifying-COVID-19-Lead-Effects-in-Texas/blob/main/Visualizations/Leadeffect_1.PNG)

## Abstract
The COVID-19 pandemic has caused unprecedented public health and economic crises. Texas has surpassed California in recording the highest number of positive coronavirus cases in the U.S as of Nov'20. As part of this analysis, we apply statistical techniques to understand the lead effect of COVID-19 cases in Texas on hospitalization as well as lead effect of hospitalization on ICU patients. The outcome of the analysis can potentially enable Texas department of state and health services to take proactive data driven decisions to regulate and plan for health care resources such as availability of hospital beds and ICU beds in the future. The idea of identifying lead effect is analogous to websites like Redfin where current traffic on Redfin website can lead to more home sales X months later.  

We examine the relationship between three time-series metric - active COVID cases in Texas, active hospitalization count and active ICU patients. We found that increase in active hospitalization count leads to an increase in ICU patients up to 17 days later in Texas. We could not find evidence to establish relationship between active COVID cases and hospitalization count.  

This analysis complements other studies on the subject by using a primarily human-centered approach.

## Directory Structure
```bash
├── Visualizations (all visualizations plotted for this analysis)
├── data (backup dataset downloaded from Texas COVID tracking API)
├── Presentation Deck (content prepared for presentation)
├── 'Analysis.ipynb'
├── README.md
├── LICENSE

```

## Research questions for this study are:
<font color='#C24914'>**1. Research Question:** Is there a statistically significant relationship between COVID positive cases in Texas and rise in hospitalization X days later?</font> 

<font color='#C24914'>**2. Research Question:**  Is there a statistically significant relationship between Hospitalization in Texas and rise in ICU patients X days later?</font>


## Data source
The data is available on [Covidtracking.com](https://covidtracking.com/) which is a volunteer organization launched from The Atlantic and dedicated to collecting and publishing the data required to understand the COVID-19 outbreak in the United States. The site collects the data from all 50 states and their data is being used by national and local news organizations across the US.  
#### Link to the Dataset: [Here](https://covidtracking.com/data/api)
#### Link to the Data Defintions: [Here](https://covidtracking.com/about-data/data-definitions)
#### Terms and Conditions for the Data: [Here](https://covidtracking.com/terms-and-conditions). 

## Conclusion
<font color='#C24914'>**1. Research Question:** Is there a statistically significant relationship between COVID positive cases in Texas and rise in hospitalization X days later?</font>  
**Null hypothesis:** Increase in positive cases in Texas do not lead to increase in hospitalization X days later.  
**Alternate hypothesis:** Increase in positive cases in Texas lead to increase in hospitalization X days later.  
<font color='#C24914'>**Outcome of hypothesis test:**</font> We did not find evidence to reject the null hypothesis.  
   
   
<font color='#C24914'>**2. Research Question:**  Is there a statistically significant relationship between Hospitalization in Texas and rise in ICU patients X days later?</font>    
**Null hypothesis:** Increase in positive cases in Texas do not lead to increase in hospitalization X days later.   
**Alternate hypothesis:** Increase in hospitalization in Texas lead to increase in Active ICU Count X days later.  
<font color='#C24914'>**Outcome of hypothesis test:**</font> We did find evidence to reject the null hypothesis and found that increase in hospitalization lead to increase in ICU patients up to 17 days later.  

## Final Visualizations
![P-value plot from Granger Casuality Test to identify lead effect of active COVID cases on hospitalization:](https://github.com/Arora-Dhruv/Identifying-COVID-19-Lead-Effects-in-Texas/blob/main/Visualizations/Granger%20Casuality%20Test-%20Active%20Cases%20on%20hospitalization.png)

![P-value plot from Granger Casuality Test to identify lead effect of hospitalization on ICU Patients:](https://github.com/Arora-Dhruv/Identifying-COVID-19-Lead-Effects-in-Texas/blob/main/Visualizations/Granger%20Casuality%20Test-%20Active%20Hospitalization%20on%20ICU.png)


## Main Requirements
* [Python](https://www.python.org/)- version 3.6
* Before installing we recommend setting up a clean [virtual enironment](https://docs.python.org/3.6/tutorial/venv.html).
  
## License
* This project is available under the [MIT License](https://covidtracking.com/terms-and-conditions/).
* [COVIDTracking](https://covidtracking.com/terms-and-conditions/) Terms of use.

## Course Wiki
This analysis was conducted in the context of Data-512A [Human Centered Data-Science at the University of Washington](https://www.washington.edu/datasciencemasters/course-descriptions/).
