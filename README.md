# Identifying COVID-19 Lead Effects in Texas
Dhruv Arora (dharora@uw.edu)  
University of Washington  
12/05/2020

## Abstract

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
<font color='#C24914'>1. Research Question: Is there a statistically significant relationship between COVID positive cases in Texas and rise in hospitalization X days later?</font> 

<font color='#C24914'>2. Research Question:  Is there a statistically significant relationship between Hospitalization in Texas and rise in ICU patients X days later?</font>


## Data source


## Conclusion
<font color='#C24914'>1. Research Question: Is there a statistically significant relationship between COVID positive cases in Texas and rise in hospitalization X days later?</font>  
Null hypothesis: Increase in positive cases in Texas do not lead to increase in hospitalization X days later.  
Alternate hypothesis: Increase in positive cases in Texas lead to increase in hospitalization X days later.  
<font color='#C24914'>Outcome of hypothesis test:</font> We did not find evidence to reject the null hypothesis.  
   
   
<font color='#C24914'>2. Research Question:  Is there a statistically significant relationship between Hospitalization in Texas and rise in ICU patients X days later?</font>    
Null hypothesis: Increase in positive cases in Texas do not lead to increase in hospitalization X days later.   
Alternate hypothesis: Increase in hospitalization in Texas lead to increase in Active ICU Count X days later.  
<font color='#C24914'>Outcome of hypothesis test:</font> We did find evidence to reject the null hypothesis and found that increase in hospitalization lead to increase in ICU patients up to 17 days later.  

## Final Visualizations


## Main Requirements
* [Python](https://www.python.org/)- version 3.6
* Before installing we recommend setting up a clean [virtual enironment](https://docs.python.org/3.6/tutorial/venv.html).
  
## License
* This project is available under the [MIT License](https://covidtracking.com/terms-and-conditions/).
* [COVIDTracking](https://covidtracking.com/terms-and-conditions/) Terms of use.

## Course Wiki
This analysis was conducted in the context of Data-512A [Human Centered Data-Science at the University of Washington](https://www.washington.edu/datasciencemasters/course-descriptions/).
