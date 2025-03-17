# BI-EV-Adoption

A structured process for designing and implementing a Business Intelligence (BI) tool, application or interface to ensure it fully performs its role in supporting problem-solving or decision-making is outlined in the step-by-step guide described below:

1.	Excel Geography feature can help the user to view different types of data around countries, such as population, area, GDP, and many others. In the Data Types group, click the Geography button. Excel will attempt to convert the selected cells into the Geography data type.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/591979fa-13fe-4c8c-9ca4-23f0df886946" />


2.	An icon will appear in cells that represent the Geography data type, and clicking on it will display a list of country-related data fields. Select one to add, for example: "Carbon dioxide emissions". Excel will create a new column and fill it with the selected data for each country in the list.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/a4ddcdb8-c2ee-4626-8acd-fc6fc02e299b" />


3.	Every relevant data field that is accessible has been filled in, and duplicate entries have been deleted to guarantee that each entry is unique. Incomplete numbers were replaced with the median value or eliminated, and data types were verified and converted to the relevant data types as needed. New columns have been created for the analysis including CO2 Emissions per Capita, CO2 Emissions by EPC and CO2 Emissions by FEC. Rows and columns that are irrelevant or required for analysis have been filtered out.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/9b53e7fa-af99-4b36-8830-a2c2fefed5e6" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/f177c258-749d-4415-90e1-54aef0ec3f06" />


4.	All relevant data can be imported in Power BI through the option "Get Data". Excel Workbook, Power BI semantic models, SQL server, Text/CSV, and other data sources can be imported.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/730faece-a215-4aff-b6e1-38ae89a75b73" />


5.	Load or transform the data in Navigator. The Navigator previews the data to ensure that it includes the relevant range of data, and if any changes are required, transform the data before loading it.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/bb2a94ee-644d-46c5-a597-c33060790637" />


6.	One of the most used data cleaning steps is to change data types. In this case, the CO2 Emissions are in decimal format. Click the title of the column that contains the CO2 Emissions, and under the Transform tab, look for Data Type and select Whole Number. Click Replace current to change the column type.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/ef329eb9-8067-40fe-b54e-a442a95426d5" />


7.	This Power BI dashboard provides a comprehensive perspective of General Motors Electric Vehicle adoption, including CO2 emissions, charging points availability, EV charging point projections, and electric car sales by different entities. Below is a detailed explanation:

Initial Dashboard

<img width="750" alt="image" src="https://github.com/user-attachments/assets/69cff6f5-78af-4635-978f-9c993020add9" />



General Motors EV Adoption requirements included global CO2 Emissions of approximately 27M, CO2 Emissions by FEC (Fuel and Energy Consumption) of 11K, and CO2 Emissions by EPC (Energy Power Consumption) of 361K. 

The left section shows a pie chart illustrating the distribution of CO2 emissions by country. The leading countries with high CO2 emissions are China, USA, India, Japan, Germany and more. China, United States, and India have the largest shares.  The bar chart shows EV sales by each country, and the main countries are China, United States, Germany, United Kingdom, France, Norway, etc. China has the highest sales, followed by the United States and other countries. 

In the right section is a bar chart illustrating the availability of charging points in various countries. The key countries are China, USA, Korea, Netherlands, France, Germany, Japan. China leads in the availability of charging points, followed by the USA. The second bar chart shows the future availability of EV charging points, and top countries are China, USA, India. The number of charging points in China is expected to increase significantly. 

In the bottom part, the bar chart shows the labor force participation rate, unemployment rate, and tax revenue percentage for different countries. The most suitable countries for EV adoption should have high level of labor force participation, low level of unemployment rate and low level of tax revenue. Based on this single metrics representation, the following countries have high potential for EV adoption: Qatar, United Arab Emirates, Kuwait, Oman, Switzerland and China. 

The dashboard provides detailed information on the EVs market, with a focus on CO2 emissions, electric car sales, and EVs infrastructure including charging points. China is the current market leader and is expected to lead in EV adoption and infrastructure development. Additional context in these regions will include labor force participation, unemployment rates, and tax revenue data.


8.	Dashboard Testing

<img width="600" alt="Screenshot 2025-03-17 at 19 57 04" src="https://github.com/user-attachments/assets/991af62b-e9fb-4f37-a14c-d2a1ec5107c9" />


<h3> <b> Maintenance </b> </h3>

The Power BI APIs allow services with endpoints for handling user resources, management, regulation, and embedding. Power BI sets restrictions on the maximum number of API calls that each user can make in a given time frame in order to maintain balanced utilisation and avoid overuse of resources by a single user (Microsoft, 2023). 

Data Cloud provides a self-managed solution for the processing of data, analytics, and storage. When compared to conventional management of data solutions, it delivers quicker, user-friendly, and less restrictive solutions (Snowflake, 2024). 

Effective methods for managing dynamic data and improving performance are provided by Power BI's periodic refresh and real-time data features for conceptual models. A gradual data refresh significantly improves the effectiveness of data handling by minimising the amount of data necessary to be updated and enabling the use of real-time data by automating the setup and handling of components (Microsoft, 2024). 

With Power BI's updates in real time features, General Motors Ltd. can effortlessly adjust dashboards and display data to get insights that are up to date. Data sources from International Energy Agency (IEA) and the World Bank provide extended data on carbon dioxide emissions, consumption of electricity, and indicators of economic growth that are particularly valuable for analysis on the adoption of electric vehicles. With the help of API connectors, these datasets can also be seamlessly included into Power BI, supporting dynamic and data-driven choices (Microsoft, 2023).

