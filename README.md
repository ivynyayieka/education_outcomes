For this project, I analysed factors associated with education outcomes in Kenya. 

# How I analysed illiteracy rates

I analysed illiteracy rates using government-provided data on portion of populations by county which has ever attended a school or learning institution

# How I analysed dropout rates

Using government-provided data, I took numbers for portion of the population that left a school or learning instution before completion normalised by portion of the population that has left the instutions before completion PLUS portion of population that lest school after completion. 

# How I analysed both illiteracy rates and dropout rates

For this, I blended two layers representing each factor through multiplication on QGIS

# How I analysed how each factor relates to education outcomes

For this, I ran linear regressions one by one to see which factors had low p-values, that is, which factors were associated with each outcome in a statistically significant way.

## New skills:

#### QGIS
I have successfully avoided QGIS to this point, but was finally convinced to welcome it into my life (given the ups and downs we have had together, though, it remains under strict supervision). 
Shoutout to Kelly Waldron for all her forever kind guidance on mapmaking and QGIS

#### Bivariate map-making
Specifically, I have felt that previous projects I have worked on required bivariate maps and I wanted to attempt the same. 
I got the inspiration for an introduction guide above the maps from my project mentor, Daniel Wolfe, who shared [this article by FiveThirtyEight](https://projects.fivethirtyeight.com/abortion-driving-distance/)

#### Statistical analysis
I tried to use new statistical methods, with Dhrumil and Aishi's guidance. eg linear regressions, multivariable regressions etc

#### Tabula
A cult I am henceforth willing to join

# Tech:
#Python, #R, #Tabula, #QGIS, #ggplot, #Flourish

# Sources
*Number of people with no education by county: 
[Distribution of Population Age 3 Years and Above by School Attendance Status, Area of Residence, Sex, County and Sub-County:](https://s3-eu-west-1.amazonaws.com/s3.sourceafrica.net/documents/119795/VOLUME-IV-KPHC-2019.pdf)<br/>
*[County Government Revenues, 2020/21-2021/22](https://www.knbs.or.ke/wp-content/uploads/2022/05/2022-Economic-Survey1.pdf)<br/>

Number of schools per square area:<br/>
*[Source for number of schools: Primary Schools, Total Enrolments & Average School Size, 2019](https://africacheck.org/sites/default/files/Kenya-Basic-Education-Statistical-Booklet-2019.pdf)<br/>
*[Source for area of county: Distribution of Population, Land Area and Population Density by County](https://www.knbs.or.ke/2019-kenya-population-and-housing-census-results/) <br/>

[These are likely correlated with wealth but the data exists:](https://africacheck.org/sites/default/files/Kenya-Basic-Education-Statistical-Booklet-2019.pdf):<br/>
*Pupil -Teacher Ratio in public pre-primary, primary and secondary schools, 2019<br/>
*Public Lower Primary Textbooks Distribution by Grade and County, 2019<br/>
*Public Primary Schools with Electricity by County, 2019<br/>
*Number of Public Primary Schools Installed with Digital Devices<br/>
*Number of Complete Set of Digital Devices Installed in Primary Schools<br/>
*[Achievement in Numeracy and Literacy in NASMLA by County](https://africacheck.org/sites/default/files/Kenya-Basic-Education-Statistical-Booklet-2019.pdf)<br/>
*[Left school or learning institution before completion](https://s3-eu-west-1.amazonaws.com/s3.sourceafrica.net/documents/119795/VOLUME-IV-KPHC-2019.pdf)<br/>





