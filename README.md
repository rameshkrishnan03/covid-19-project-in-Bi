# Covid-19 Project using PowerBI

### Dashboard Link : https://app.powerbi.com/groups/me/reports/05f1b130-4686-4fac-8cc5-f45df1a21912/ReportSection72f72c268564ca31c3a8?experience=power-bi

## Problem Statement

The Global COVID-19 Tracking Project utilizing Power BI for data analysis aims to integrate diverse datasets related to COVID-19, including infection rates, mortality rates, testing data, and vaccination progress, to develop visually appealing dashboards for comprehensive tracking and analysis. Through real-time updates and interactive features, users can dynamically explore trends, disparities, and correlations between countries, regions, and time periods, facilitating informed decision-making and policy development. Predictive modeling will enable forecasting of COVID-19 trends, while ensuring user accessibility and adhering to strict data privacy and security protocols. The project seeks to contribute to global efforts in combating the pandemic by providing accessible, informative visualizations and leveraging data-driven insights to monitor, analyze, and respond to the ongoing COVID-19 crisis effectively.

 
 


### Steps followed 

- Step 1 : Load data into Power BI Desktop, 3 Datasets in csv file.
1.covid-19 2. Daywise 3.worldometer_data

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

- Step 4 : It was observed that in none of the columns errors & empty values were present  in  3 datasets.

- Step 5 : For calculating Total Activecases and Total Deaths and Total Recovered in covid-19 Dataset and required calculation is done move to next stage.

- Step 6 : In the report view, under the view tab, theme was selected.

- Step 7 : Since the data contains various Death rates, thus in order to represent ratings, a new visual was added using the Stacked Bar Chart in the visualizations pane in report view.And put the filter in it Top 10  countries in visual using TopN filter give the values in Total deaths. 

- Step 9 : Since the data contains various Active cases, thus in order to represent ratings, a new visual was added using the Stacked Column Chart in the visualizations pane in report view.And put the filter in it Top 10  countries in visual using TopN filter give the values in Total Activecases. 
           
- Step 10 : A Stacked column chart was also added to the report design area representing the number of Total recovered cases. While creating this visual, filter the Top 10 countries in recovered cases. 


  - Step 11 : In the report view, using the map visualization showing the countries with deaths for each country in page 2.
  A card visual was used to represent the Total countries were affected by covid-19.


- Step 12 : In the report view, using the line chart to compare the Active cases and Death  in Month wise in page 3. 


 - Step 18 : The report was then published to Power BI Service.
 
 
![bi serivce](https://github.com/rameshkrishnan03/covid-19-project-in-Bi/assets/70803627/8f23c088-5e4d-487e-a8b0-192a74efea60)


# Snapshot of Dashboard (Power BI Service)

![page1](https://github.com/rameshkrishnan03/covid-19-project-in-Bi/assets/70803627/a98e3de3-6fa6-4ef7-bbe8-af1b98b0fb26)

![page2](https://github.com/rameshkrishnan03/covid-19-project-in-Bi/assets/70803627/cf336c7c-4f6e-430d-bf9e-35598f611a98)

![page3](https://github.com/rameshkrishnan03/covid-19-project-in-Bi/assets/70803627/168690f8-04f4-4ac8-8d71-597786b9fee7)

# Insights

The Three pages report was created on Power BI Desktop & it was then published to Power BI Service.

