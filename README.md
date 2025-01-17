# Electoral Malpractice, Cyber-security, and Political Consequences in Russia and Beyond Project

## Data on cross-regional Electoral Malpractice in Russia

*Release: 1 version*

*Date: 15 November 2021*

[![DOI](https://zenodo.org/badge/427669912.svg)](https://zenodo.org/badge/latestdoi/427669912) 

*[Electoral Malpractice, Cyber-security, and Political Consequences in Russia and Beyond Project](url) is funded by the University of Helsinki and is based in Aleksanteri Institute, Helsinki, Finland*

### Project team:
1. Margarita Zavadskaya, Project Leader, Postdoctoral Researcher
2. Elena Gorbacheva, Project Planner, Doctoral Student
3. Valeria Caras, Research assistant

#### About the dataset

The data covers socioeconomic characterisics of Russian regions, as well as variables on TV and Internet coverage in the each subject of the Russian Federation. The dataset contributes with the new variables on electoral coverage during both Presidentional and State Duma electoral campaigns which capture the amount of messages on elections in Russian regional media sources and amount of messages on electoral fraud. Data covers the 2007, 2011, 2016, 2021 State Duma elections and 2008, 2012, 2018 Presidential elections. 

| Variable Name | Variable Label and Variable Description | Scale and timeframe of coverage | Source|
| --- | --- |--- |--- |
| fad_id | ID of the federal administrative district |Numeric |
| cec_id | ID of region | Numeric | [Central Electoral Commission](url) |
| id | Number of Federal district and ID of the region | Numeric | [Central Electoral Commission](url) |
| r_name | Name of a region in English | Text | [Wikipedia/Road signs romanization of Russian](url) |
| r_translit | Name of a region in Russian | Text | [Wikipedia](url) | 
| iso_id  | ISO country code 3166-2 Russia | Text | [Wikipedia](url) |
| is_nat_republ | The status of the national republic: 1 – National republic, 0 – Other types (Kray, oblast’, avtonomnaya oblast’, avtonomny okrug | dichotomous | [Wikipedia](url) |
| perc_urban | Share of the urban population in total population | Interval (share), 2007 - 2018 | [Federal State Stastics Service](url) |
| share_non_work_pop | Age composition of the population over working age | Interval, 2010 - 2019 | [Federal State Stastics Service](url) |
| grp_capita | Gross regional product per capita (rubles) | Interval, 2007 - 2018 | [Federal State Stastics Service](url) |
| gini | The Gini coefficient is calculated as the ratio of the incomes of the richest and the poorest segments of the population | Interval, from low to high (0-1), 2010 - 2017 | [Federal State Stastics Service](url) |
| lab_educ_p | Percent of people working in the education sector | Interval, 2013 - 2019 | [Federal State Stastics Service](url) |
| ratio_msal_educ_gen | The ratio of mean salary in education to mean salary in general | Interval (share), 2013 - 2019 | [Federal State Stastics Service](url) |
| share_sbenefits | Share of income from social benefits | Interval (share), 2010 - 2019 | [Federal State Stastics Service](url) |
| investments_cap_fbudg_p | Percent of capital investments by federal budget | Intervel (percent), 2010 - 2019 | [Federal State Stastics Service](url) |
| govern_app | Is the head of the region appointed or elected: 1 – is appointed; 0 - elected | dichotomous, 2011 - 2021 |  [Wikipendia/Elections of the heads of the regions in the Russian Federation](url) |
| turnout_gd | Regional turnout for the State Duma elections calculated as: (valid+invalid votes)/people having the right to vote | Interval, years: 2007, 2011, 2016, 2021 | [Central Electoral Commission](url) |
| turnout_presd| Regional turnout for the presidential elections calculated as: (valid+invalid votes)/people having the right to vote | Interval, years: 2008, 2012, 2018 | [Central Electoral Commission](url) |
| deyr_crude | Number of falsifications filed during the day of elections | Numeric, years: 2012 Presidential Elections, 2016 State Duma Elections, 2018 Presidential Elections, 2021 State Duma Elections | [Violation map (Karta narusheniy)](url)|
| tv_cov_pervy | TV and radio coverage ratio: First Channel (Pervy kanal) | Interval (share), 2008 - 2017 | [Federal State Stastics Service](url) |
| tv_cov_rossiya | TV and radio coverage ratio: Rossiya Channel | Interval (share), 2008 - 2017 | [Federal State Stastics Service](url) |
| tele_cov_mobile | Coverage by mobile/wireless networks. The number of connected subscriber devices of mobile radiotelephone communication per 1000 population | Interval (share), 2010 - 2019 | [Federal State Stastics Service](url) |
| tele_cov_internet | Coverage by Internet.  Number of active subscribers of fixed broadband Internet access | Interval (share), 2011 - 2019 | [Federal State Stastics Service](url) |
| npapers_1000pep | Publication of newspapers per 1000 people | Numeric, 2007 - 2019 | [Federal State Stastics Service](url) |
| mess_fals_presid_year | Coverage of electoral fraud by regional mass media. The results for query “(выборы and (президент Россия)) and (фальсификация or фальсифицировать or вбросы or махинация)”. Search was filtered for the dates of the electoral campaign and regional media | Numeric, years: 2008, 2012, 2018 | [Integrum World Wide. Electoronic Portal of Russia and the CIS](url) |
| elect_mess_pres_year | Coverage of elections by regional media. The result for query “(выборы and (президент Россия))”. The search was filtered for the dates of the electoral campaign and regional media| Numeric, years: 2008, 2012, 2018 | [Integrum World Wide. Electoronic Portal of Russia and the CIS](url) |
| per_violmess_all_pres_year | Percent of mentions of falsifications in media from the total number of messages covering the electoral campaign | Interval (share, years: 2008, 2012, 2018 | [Integrum World Wide. Electoronic Portal of Russia and the CIS ](url)|
| crude_fals_parl_year | Coverage of electoral fraud by regional mass media. The results for query “(выборы and (государственная and дума)) and (фальсификация or фальсифицировать or вбросы or махинация)”. The search was filtered for the dates of the electoral campaign and regional media. | Numeric, years: 2007, 2011, 2016, 2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elect_mess_parl_year | Coverage of elections by regional media. The results for query “(выборы and (государственная and дума))”. The search was filtered for the dates of the electoral campaign and regional media | Numeric, years: 2007, 2011, 2016, 2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| per_violmess_all_parl_year | Percent of mentions of falsifications in media from the total number of messages covering the electoral campaign |  Interval (share), years: 2007, 2011, 2016, 2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |






 




 








