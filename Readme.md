# Namma Yatri-Analytics-Dashboard

Interactive Dashboard Link -> https://public.tableau.com/app/profile/ayan.basak8085/viz/NammaYatriDashboard/RidesSummary

>Namma Yatri is an open network mobility application built with the idea to provide multi-modal service to the commuters without the involvement of any middlemen. This application is built on the common network standards defined by ONDC built on the Beckn protocol (open source). The common network standards allows for interoperability for any buyer app compliant with the network standards to offer rides.
>
>Website Link -> https://www.nammayatri.in/open?cc=
>
>They have shown an open data analyzing completed trips, earnings, drivers, conversion rate etc. on basis of location and duration on their website.


## Problem Statement

> I wanted to study and experiment how the company collects real time data of their customers, drivers, completed trips etc. through their app and display them as an interactive dashboard on their website for the common public to see.

Some of their application features which I noticed were:

>- Data of clicks for each customer searching trips on their app.
>- Data of location searches by the customers.
>- Data of clicks for each customer who evaluated their search results.
>- Data of clicks for each customer to whom fare prices of their ride were shown.
>- Data of clicks for each customer who opted for the ride after seeing the fare price.
>- Data of clicks for each customer who were alloted a ride.
>- Data of the distance for the ride.
>- Data of clicks for each customer who successfully completed the ride.


## My Work

- I analysed the data they have shown on their website as well as their app and created a small dataset for a single day. The dataset can be found in the follwoing SQL report:
  >SQL Report Link -> https://github.com/Ayan-OP/Namma-Yatri/blob/main/SQL%20Files/Data_Entry.sql
- I created the database on MySQL and defined a schema structure to explain how the company might receive and collect data for each customer and driver through their app.

![Database_Schema](https://github.com/Ayan-OP/Namma-Yatri/blob/main/Imp%20images/Database_schema.png)

- I analysed the data collected and extracted various KPIs and trends in the data. The analysis can be found in the following SQL report:
  >SQL Report Link -> https://github.com/Ayan-OP/Namma-Yatri/blob/main/SQL%20Files/Data_Exploration.sql
- Finally I created an interactive and dynamic Tableau Dashboard based on the data I analyzed and tried to replicate similar to what they have shown on their website.


## Overall Analytics Report

![Analyst_Report](https://github.com/Ayan-OP/Namma-Yatri/blob/main/Imp%20images/%231.png)


## Trip Details Report

![Employee_Details](https://github.com/Ayan-OP/Namma-Yatri/blob/main/Imp%20images/%232.png)


## Data Model

![Data_Model](https://github.com/Ayan-OP/Namma-Yatri/blob/main/Imp%20images/%233.png)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

