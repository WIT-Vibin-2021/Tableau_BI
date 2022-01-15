
![Tableau](https://a11ybadges.com/badge?logo=tableau)
![Microsoft Excel](https://a11ybadges.com/badge?logo=microsoftexcel)
# Covid-19 Vaccination Dashboard
The main objective is to prepare a Vaccination dashboard based on the data available in the source GitHub (covid-19-data) using the Tableau prep builder and Tableau desktop.



## Authors

- [@VibinVarghese](https://github.com/WIT-Vibin-2021)





## Support

For support, email 20096057@mail.wit.ie or join our Slack channel.

# Hi, I'm Vibin Varghese ! 👋
## 🚀 About Me
I'm a SAP B1, .net developer and a PG student in WIT Ireland. Who have worked in IT Industry for couple of years. Technical tools used these years are basic .net, MS SQL and reporting tools like Crystal report and Excel reporting.


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/WIT-Vibin-2021)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/vibinlipage)

## Covid-19 Vaccination Dataset
In the middle of Covid-19 pandemic, by the beginning of the year 2021 all the countries started giving vaccination to the people from the age above 80. And this process continues in the current date, since vaccination is the only source to reduce the death rate. 
Many originations started collecting the raw vaccination data and make it available for the public to use. For this vaccination dash board, I have used the data set from “Our World in Data” GitHub Account  , specifically the vaccination data. World population data also used in the dashboard; the original source data used by ‘Our World in Data’ team  . Three data set are mainly used in the dashboard-Location, Manufacture Wise Vaccination and Vaccination also the World Population.
Few key points of the data set
- Total Vaccinations: Total number of doses administered. For vaccines that require multiple doses, each individual dose is counted, i.e. For first dose, metric added 1 and again adds 1 for second dose; Total will be 2.
- Total Vaccinations per hundred:  Total vaccinations per 100 people in the total population of the country.
- People Vaccinated: Total number of people who received at least one vaccine dose. Even the person receives two doses, metric will be set as one for that person.
- People vaccinated per hundred: People vaccinated per 100 people in the total population of the country.
- People Fully Vaccinated: Total number of people who received all doses prescribed by the vaccination protocol. If a person receives the first dose of a 2-dose vaccine, this metric stays the same. If they receive the second dose, the metric goes up by 1.
- People Fully Vaccinated Per Hundred: People fully Vaccinated per 100 people in the total population of the country.
Note that, data set day wise data is a running total values, which means it’s an incremental value. 

## Data Preparation
As mentioned in the dataset details, data is been captured from the ‘Our World in Data’ GitHub account, where they regularly update the data. The data set used is till mid of November 2021. For preparing the dashboard, I have used 
1.	Vaccination Data
2.	Location Data
3.	Age-group Wise Vaccination
4.	Manufacturer Wise Vaccination
5.	World population
Most of the data is correct for the country Ireland. And in tableau prep builder, I have modified few of the fields, remove not utilized field and done necessary grouping and joins based on the date.

##	Dashboard
The dash board have four charts
1.	Vaccination Administered per hundred people - Age group: This chart will show the fully vaccinated people and the total people vaccinated on different four age group. The value will be less than or equal to 100, since it’s a per hundred rates.
2.	Vaccination Administered per hundred people – Month/Quarterly: This chart will show the fully vaccinated people and the total people vaccinated by month wise, filter option is given to get data quarterly also. User can select multiple quarter while filtering the data.
3.	Ireland vs Other European Countries (Total Vaccination %) – Chart is to show the percentage pf people vaccinated in these countries. Ireland is highlighted, since it’s an Ireland dashboard. Two set of filtration given in this chart, Range filter 0% to 100% and Country filter for checking and comparing multiple European country by users choice.
4.	Vaccination Type Administered – This chart to show percentage of total vaccine administrated by different manufacture vaccine type in Ireland.

    <img alt="HackerRank" src="https://github.com/WIT-Vibin-2021/Tableau_BI/blob/main/Covid-19%20DashBoard/Dashboard%20Preview.jpg">


