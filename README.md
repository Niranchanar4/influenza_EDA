# influenza_EDA
This repository contains the data cleaning, analysis and visualizations of the influenza dataset obtained from WHO
Overview of the project and the goals
The project deals with performing exploratory data analysis on the Influenza dataset obtained from WHO.This information can help in understanding the trends in the disease to better track and handle the influenza spread. Influenza dataset provides the count of the cases tested positive for influenza across regions and countries. The virus type for the recorded cases have also been specified. Additionally, the accompanying FLUID dataset also provides information about influenza-like-illness cases,their seriousness and fatalities.

Goals related to the analysis plans:-
The analysis is focussed on areas with highest values of reported count of influenza and Influenza-like illness region-wise and country-wise in the recent years.

Perform EDA by removing missing and inconsistent values,removing duplicate rows,unwanted rows and columns.I may group together suitable columns,change data type /column name to make it more appropriate and perform other required pre-processing.
Understand the worldwide trend of total influenza cases.I would liked to determine the region wise(WHO has 6 regions) distribution of influenza cases and also find out countries with the highest count of influenza cases in the recent years.

Understand the recent yearly and seasonal trends in the selected countries.

Understand the more contagious virus-type and virus trends in influenza and influenza-like illness across the countries.
Explore the trends in influenza in the past two decades and identify changes.

Perform analysis based on total influenza like illness (ILI) cases reported,cases of Acute Respiratory Illness (ARI)and Seriously Acute Respiratory Illness ( SARI) and percentage deaths. I would like to understand the trends and also see if any relationship between age-groups and fatalities is visible in these areas.
I believe, this analysis could possibly also help in developing a time-series forecast model as a future scope.
Why I chose this project?
I am very interested in the application of data science and artificial intelligence to transform healthcare.Covid-19 caused a massive upheavel in the society and affected numerous people.There are other respiratory illnesses that affect significant proportion of population around the world.Influenza is a common illness that cause mild to severe symptoms and could also be deadly. I feel better understanding and tracking incidence of the illness can help in better managing them.
I chose this data because it is very comprehensive,covers data pertaining to incidence of influenza across counties on a weekly and yearly basis, provides classification according to influenza type A or B or mention of other category of respiratory illness when tested for influenza. Data in the other data file can also help in estimating the seriousness of the incident lung infections .I believe this can facilitate in depth anaylsis to yield several informative insights.It can help to better understand the disease spread,identify trends,determine the contagious type of virus and fatality of respiratory illness across the age groups etc.
This type information can help public health organizations track the disease,understand trends in virus and impact and take effective action to control the spread. It can help in administering vaccines,develop more effective flu shots, forecast future spread and take preventive measures.It can also help healthcare providers in better decision-making.
Hypothesis and hunches about the data
It would be interesting to investigate the following questions about the data:

Has influenza spread increased over the recent years and are marked changes observed over the decade?
Are there particular WHO regions that are strongly affected by influenza and contibute a greater proportion of worlwide cases? -Are there particular countries that are strongly affected by influenza and contibute a greater proportion of overall cases in the continent/WHO region?
Has there been a change in the countries most affected by influenza in the recent years?
Is a particular country responsible for sudden high cases in a particular year?
Has a new virus subtype emerged in years with sudden high cases causing sharp increase in cases?
Is a particular virus type more contagious?
Is there a relationship between the influenza cases and weeks? Is there a seasonality in the influenza trends?
Are respiratory diseases more serious and deadly in certain countries(more fatalities)
Is there a relationship between age and respiratory illness fatalities
These questions can provide some information to track,better understand possible causes, manage and treat influenza across the world

Influenza
2. Data Explained
Data sources
The datasets for the project have been chosen 
from WHO(World Health Organization). The World Health Organization is a specialized agency of the United Nations responsible for international public health. The Global Influenza Programme of WHO provides a global platform for influenza surveillance information reporting, analysis and presentation. The dataset is shared through FluNet and FluID by the Global Influenza Surveillance and Response System (GISRS) and national epidemiological institutions. The count for influenza for various virus types and other ILI types is recorded respectively country wise and on a weekly basis The FluNet and FluID csv data files have been used in this project.The link is:

https://www.who.int/teams/global-influenza-programme/surveillance-and-monitoring/influenza-surveillance-outputs
