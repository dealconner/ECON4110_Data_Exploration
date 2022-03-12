### ECON4110_Data_Exploration
Conner Deal

## Data

This project utilizes a total of fifteen datasets with information from the college scorecard released in September of 2015 and Google search trends. The purpose of this analysis is to explore the causal effect of the college scorecard on search trends for high-earning colleges (the distinction between high-earning and low-earning colleges will be clarified below). Our central research question asks: Among colleges that predominantly grant bachelor's degrees, did the release of the Scorecard shift student interest to high-earnings colleges relative to low-earnings ones.

The data used and manipulated for our research consists of many files included in this Github repository. The following is each file listed with an explanation of its purpose:
trends_up_to_...csv: This file contains the Google trends index for an indicated keyword in a given month or week. The keyword reflects the corresponding university in the United States. 
Most+Recent+Cohorts+(Scorecard+Elements).csv: This file contains the data from the College Scorecard, hosting information about US colleges and the students that graduate from them. The variables in this dataset primarily function as our regression variables and controls, and many were filtered out for redundancy or irrlevance.
CollegeScorecardDataDictionary-09-008-2015.csv: This file contains descriptions for the variables in the Scorecard dataset.
Id_name_link.csv: This file contains identification tags that correspond to colleges identified in the Scorecard dataset. These tags ('UNITID' and 'OPEID') connect our Scorecard and Google Trends datasets.

## Data Manipulation


