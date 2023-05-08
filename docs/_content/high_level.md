# An overview

This section provides an overview of the observations of the data set to provide context for further analysis.

## Set statistics

The data set entails `366` shootings over the time period of April 20th 1999 until February 2nd 2023. With a period of `8689` days, there was a shooting occurring on school grounds every `23.74` days.

There have been `603` casualties, of which `192` were deaths. On average, around two were injured and one person was killed during every two school shootings. The highest amount of deaths occurred during the Sandy Hook shooting (December 14th, 2012) with `26` deaths.

## States affected

 An initial step to understanding the geospatial distribution of the phenomenon is to look at the states with the most occurrences of shootings. Additionally, it is important to observe the amount of total deaths as a result of these shootings, available as an separate layer on the map below. States of interest have been marked with a bolded outline (these are California, Texas, Florida, Colorado, North Carolina and Connecticut).

<div style="width: 100%;">
    <iframe 
        class="ioda"
        width="100%" height="516x" 
        src="assets/htmls/choropleth.html"
        style="overflow: hidden;"
        >
    </iframe>
</div>

Initially, it appears that the core of the issue lies in California with the highest number of occurrences over the two decades at `40`. With `38` individuals harmed by the shootings there certainly is a problem in this state, yet a relatively small death toll of `7` brings California to smaller side of the spectrum for state deaths.

The states with the highest death counts are Connecticut and Texas, homes of Sandy Hook Elementary and Robb Elementary. Florida (Stoneman Douglas) and Colorado (Columbine) are second to follow. All of these states have a death toll of at least `15` and up to `32`. States such as California and North Carolina may have a large amount of shootings, yet a small amount of deaths and (in the case of North Carolina) injuries.

The takeaway is that most shootings are not lethal and more commonly result in injuries, while mass shootings claim lives in extremely high numbers. There are some states which are defined by the mass shootings which occur in their schools, bringing them to the forefront of the school shooting problem. 

## Shootings on the rise

A concerning observation made by the authors of the data set, corroborated as well by similar data set maintainers, is that the trend of school shootings is increasing annually.

<img class="ioda" src="assets/imgs/total_shootings.png"/>

Within the year 2018, the number of school shootings has increased twofold compared to the previous rolling average, a trend which is followed in the next years. It is unclear whether this is due to an increase in recording of events - where previous "minor" events such as accidental discharges were never reported beyond a closed internal news environment, or if there is a societal and psychological reason for the drastic rise in school shootings.

It is important to note that the year 2023 does not bode well. Just one month of data (January 1st - February 2nd) already brings the 2023 shootings count to `7`, exactly as many as the entire year of 2015.

### The covid lockdown effect

The year 2020, infamous for the start of the pandemic and the introduction of remote schooling has observed a proportional decrease in shootings, yet the count of shootings is equal to that of the average shootings in the 2010s, a time of only in-person schooling. While the adoption of remote schooling was very successful at keeping children safe not only from the virus, but even more so from gun violence, the number of recorded shootings has not dropped to any level below previous trends.

Upon closer inspection, during the remote schooling period ([March 2020 -  February 2021](https://www.edweek.org/leadership/forever-changed-a-timeline-of-how-covid-upended-schools/2022/04#2020-21-school-year)) there were "only" four shootings, all of which were deemed accidental with just one injured casualty. March 2021 saw the reopening of many schools and with it five shootings occurred in March alone, three of which were deemed as targeted.
