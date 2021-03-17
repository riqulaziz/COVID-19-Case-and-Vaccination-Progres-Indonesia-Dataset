# COVID-19 Case and Vaccination Progress Indonesia Dataset

## Context

Since the first time the Covid 19 case in Indonesia attacked, which was announced for the first time on March 2, 2020, it has affected many fields such as the economy to education. many companies or businesses are bankrupt and education is not running properly which is very likely to cause a decline in the academic ability of the nation's young generation. In 2021, Indonesia has started efforts to solve this pandemic through one way, namely vaccines. Several vaccines are used, one of which is Sinovac and will then follow the Nusantara Vaccine.

The reason I created this dataset is not only because I am still pursuing my first professional career (im fresher guys :) )which is still unclear and also provides data which can then be processed as insight to convince the public that this pandemic will end soon?? .


## Content

This data was scraped from several source ( I'll write it down in the Acknowledgments section) on March, 15 2021 by Thoriqul Aziz:)

Some data represented all province in Indonesia

The records of each location (province/city/regency) have different date first case or first vaccinated. but the announcement of first case is March, 2 2020 and first vaccination in January, 13 2021

Indonesia Coronavirus daily data Columns Description:
- **Date:** Means the Date of Observation
- **Province:** Means Location/ Province which the data was observed
- **Daily_Case:** Means Daily new number of confirmed case in observed province
- **Daily_Death:** Means Daily new number of confirmed death in observed province
- **Daily_Recovered:** Means Daily new number of confirmed recover in observed province
- **Active_Case:** Means Daily new number of active case such as isolated or threated in hospital (still didnt recover nor die)
- **Cumulative_Case:** Means total for each day number number of confirmed case of the row's date, for the row's province
- **Cumulative_Recovered:** Means total for each day number number of confirmed Recover of the row's date, for the row's province
- **Cumulative_Death:** Means total for each day  number of confirmed death of the row's date, for the row's province
- **Cumulative_Active_Case:** Means total for each day number of active case of the row's date, for the row's province

Vaccination Data columns Description:
- **City_or_Regency:** Location which data was observed (regency or city)
- **Vaccinated:** Total person who get Vaccinated ( first vaccination)
- **Fully_Vaccinated:** Total person who get Full Vaccinated (second vaccination)
- **Total:** Total vaccin each day each location
- **Date:** Date of observation
- **URL:** Source of Data

## Acknowledgements

All data present in this dataset is get or scraped from:
1. [covid19.go.id](https://covid19.go.id/peta-sebaran)
2. [Diskominfo JATIM Twitter Account](https://twitter.com/KominfoJatim)


## Inspiration

From this data, you can makes some visualization from trend in several province in indonesia.
you can also combine this dataset with  other dataset like GDP Each Province or news in some point time like Lebaran, christmas day, or last PILKADA.(regional head elections) in order to get insight and effect of these events on the progression of Covid-19 

## Source
images cover : [Unsplash](https://unsplash.com/photos/_ts3NfjvaXo?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
