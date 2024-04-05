# Influenza_EDA
This repository contains the data cleaning, analysis and visualizations of the influenza dataset obtained from WHO
## Overview of the project and the goals
The project deals with performing exploratory data analysis on the Influenza dataset obtained from WHO.This information can help in understanding the trends in the disease to better track and handle the influenza spread. Influenza dataset provides the count of the cases tested positive for influenza across regions and countries. The virus type for the recorded cases have also been specified. Additionally, the accompanying FLUID dataset also provides information about influenza-like-illness cases,their seriousness and fatalities.

### Goals related to the analysis plans:-
* The analysis is focussed on areas with highest values of reported count of influenza and Influenza-like illness region-wise and country-wise in the recent years.

* Perform EDA by removing missing and inconsistent values,removing duplicate rows,unwanted rows and columns.I may group together suitable columns,change data type /column name to make it more appropriate and perform other required pre-processing.
Understand the worldwide trend of total influenza cases.I would liked to determine the region wise(WHO has 6 regions) distribution of influenza cases and also find out countries with the highest count of influenza cases in the recent years.

* Understand the recent yearly and seasonal trends in the selected countries.

* Understand the more contagious virus-type and virus trends in influenza and influenza-like illness across the countries.
Explore the trends in influenza in the past two decades and identify changes.

* Perform analysis based on total influenza like illness (ILI) cases reported,cases of Acute Respiratory Illness (ARI)and Seriously Acute Respiratory Illness ( SARI) and percentage deaths. I would like to understand the trends and also see if any relationship between age-groups and fatalities is visible in these areas.
* I believe, this analysis could possibly also help in developing a time-series forecast model as a future scope.
  
### Why I chose this project?
I am passionate about applying data science and AI to healthcare transformation, especially after witnessing the societal impact of COVID-19. Understanding and tracking respiratory illnesses like influenza is crucial for effective management. The comprehensive data on influenza cases, including types and severity, can provide valuable insights for public health organizations to track disease spread, identify trends, and take preventive measures. This information can aid in vaccine administration, forecast future spread, and support healthcare decision-makin
### Hypothesis and hunches about the data
It would be interesting to investigate the following questions about the data:

*Has influenza spread increased over the recent years and are marked changes observed over the decade?
* Are there particular WHO regions that are strongly affected by influenza and contibute a greater proportion of worlwide cases? -Are there particular countries that are strongly affected by influenza and
contibute a greater proportion of overall cases in the continent/WHO region?
* Has there been a change in the countries most affected by influenza in the recent years?
* Is a particular country responsible for sudden high cases in a particular year?
* Has a new virus subtype emerged in years with sudden high cases causing sharp increase in cases?
* Is a particular virus type more contagious?
* Is there a relationship between the influenza cases and weeks? Is there a seasonality in the influenza trends?
* Are respiratory diseases more serious and deadly in certain countries(more fatalities)
* Is there a relationship between age and respiratory illness fatalities
* These questions can provide some information to track,better understand possible causes, manage and treat influenza across the world

### Data sources
The datasets for the project have been chosen 
from WHO(World Health Organization). The World Health Organization is a specialized agency of the United Nations responsible for international public health. The Global Influenza Programme of WHO provides a global platform for influenza surveillance information reporting, analysis and presentation. The dataset is shared through FluNet and FluID by the Global Influenza Surveillance and Response System (GISRS) and national epidemiological institutions. The count for influenza for various virus types and other ILI types is recorded respectively country wise and on a weekly basis The FluNet and FluID csv data files have been used in this project.The link is:

https://www.who.int/teams/global-influenza-programme/surveillance-and-monitoring/influenza-surveillance-outputs
