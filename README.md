# Covid19-Project
This is basically a project that was assigned by my teacher, Rafia Shaikh of Artificial Intelligence. I took a latest dataset of 13th of December 2020 covid19 cases with their corresponding countries and provinces. So we had to clean, analyze and visualize the data according to the tasks I was given by my teacher. I am writing down the whole sequence of my project with questions.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

From Wikipedia,
Coronavirus disease 2019 (COVID-19) is an infectious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The disease was first identified in 2019 in Wuhan, China, and has since spread globally, resulting in the 2019–20 coronavirus pandemic. Common symptoms include fever, cough and shortness of breath. Muscle pain, sputum production and sore throat are less common. The rate of deaths per number of diagnosed cases is on average 3.4%, ranging from 0.2% in those less than 20 to approximately 15% in those over 80 years old.
Data Source (Date wise) : 2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE
Data Source: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports
File naming convention
MM-DD-YYYY.csv in UTC.
Field description
Province/State: China - province name; US/Canada/Australia/ - city name, state/province name; Others - name of the event (e.g., "Diamond Princess" cruise ship); other countries - blank.
Country/Region: country/region name conforming to WHO (will be updated).
Last Update: MM/DD/YYYY HH:mm (24 hour format, in UTC).
Confirmed: the number of confirmed cases. For Hubei Province: from Feb 13 (GMT +8), we report both clinically diagnosed and lab-confirmed cases. For lab-confirmed cases only (Before Feb 17), please refer to who_covid_19_situation_reports. For Italy, diagnosis standard might be changed since Feb 27 to "slow the growth of new case numbers." (Source)
Deaths: the number of deaths.
Recovered: the number of recovered cases.
Update frequency
Files after Feb 1 (UTC): once a day around 23:59 (UTC).
Files on and before Feb 1 (UTC): the last updated files before 23:59 (UTC).
Using above dataset we have created some exercises on COVID-19 (Spread of the novel coronavirus, Analysis, Visualization, Prediction & Comparisons
1. Write a Python program to display the first 5 rows from COVID-19 dataset. Also print the dataset information and check the missing values.
2. Write a Python program to get the latest number of confirmed, deaths, recovered and active cases of Novel Coronavirus (COVID-19) Country wise.
3. Write a Python program to get the latest number of confirmed deaths and recovered people of Novel Coronavirus (COVID-19) cases Country/Region - Province/State wise.
4. Write a Python program to get the Chinese province wise cases of confirmed, deaths and recovered cases of Novel Coronavirus (COVID-19). 
5. Write a Python program to get the latest country wise deaths cases of Novel Coronavirus (COVID-19). 
6. Write a Python program to list countries with no cases of Novel Coronavirus (COVID-19) recovered. 
7. Write a Python program to list countries with all cases of Novel Coronavirus (COVID-19) died.
8. Write a Python program to list countries with all cases of Novel Coronavirus (COVID-19) recovered. 
9. Write a Python program to get the top 10 countries data (Last Update, Country/Region, Confirmed, Deaths, Recovered) of Novel Coronavirus (COVID-19). 
10. Write a Python program to create a plot (lines) of total deaths, confirmed, recovered and active cases Country wise where deaths greater than 150.
11. Write a Python program to visualize the state/province wise death cases of Novel Coronavirus (COVID-19) in USA.
12. Write a Python program to visualize the state/province wise Active cases of Novel Coronavirus (COVID-19) in USA
13. Write a Python program to visualize the state/province wise combined number of confirmed, deaths, recovered, active Novel Coronavirus (COVID-19) cases in Pakistan.
14. Write a Python program to visualize Worldwide Confirmed Novel Coronavirus (COVID-19) cases over time.
