# Robo Texts

Looking at complaints for robotexts. 

Final story [here](https://www.newsy.com/stories/robotext-complaints-at-fcc-reveal-tactics-of-spammers/).

Air clip [here](https://www.youtube.com/watch?v=fpWKfT3Czq4)

*Created by Amy Fan (<amy.a.fan@gmail.com>)*


## Project goal

Counting and categorizing complaints about texts to the FCC. 


## Staff involved

Story reported by Patrick Terpstra, analyses checked by Rachel Gold.

## Data sources

### /source

* ** CGB_-\_Consumer_Complaints_Data.csv ** 
    * Consumer complaints from the FCC, downloaded July 28, 2022. 
    * Ticket 5632270 is the most recent complaint
    * [Source] (https://opendata.fcc.gov/Consumer/CGB-Consumer-Complaints-Data/3xyp-aqkj/data)

* ** npa_report.csv ** 
    * data on area codes, downloaded August 23, 2022
    * [Source] (https://www.nationalnanpa.com/reports/reports_npa.html) 
 
### /processed

* ** robotext_counts_07292022.csv ** 
    * Number of complaints for each number + the number of zip codes those complaints come from
* ** robotext_types_07292022.csv **
    * categories for robotext complaints
