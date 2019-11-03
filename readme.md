<h1> Driving Licenses, Traffic Accidents and Casualties Analysis </h1>

<h3> Overview </h3>
In this project I provided an analytical study for two sets of data,  traffic accidents for 2016 and 2017,  and  driving licenses issued from  1993 till 2017  in Saudi Arabia, using basic statistics, Python programming, visualizations, EDA. I have tracked data sets and gave recommendations that may help reduce traffic accidents and its negative side effects. 


<h3> Datasets </h3>

- [Traffic Accidents and Casualties by Region](/data/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008.csv)
- [Driving Licenses Issued By Administrative Area](/data/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008.csv)

You can see the source for the accident data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/), and the source for the license data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/). 

A quick overview on two datasets'  features / variables / columns, alongside data types and descriptions

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|integr|df_1Traffic_Accidents & df_2Driving_Licenses|It is a year when driver's liceses were issued and Accidents were happened|
|region|string|df_1Traffic_Accidents & df_2Driving_Licenses|It is a region where driving licenses were issued and Accidents were happened|
|driving_licenses|intger|df_2Driving_Licenses|Number of driving licenses issued per region per year|
|indicator|string| df_1Traffic_Accidents | Describe incidents |
|value|integr| df_1Traffic_Accidents | Number of injuries, deaths and accidents |
|  geo_point_2d  | string | df_1Traffic_Accidents & df_2Driving_Licenses |Region location coordinates |
|x| float | df_1Traffic_Accidents & df_2Driving_Licenses | x coordinates for region |
|y| float | df_1Traffic_Accidents & df_2Driving_Licenses | y coordinates for region |



<h3>Conclusion</h3>
I have prepared a report to whom it may concern, useing the  provided data and outside research to make recommendations to help in reducing traffic accidents in three regions whose obtained the highest rate of driving licenses and traffic accidents which are Riyadh, Makkah and Eastern.
I found  a strong correlation between rate  of licenses issued, accident traffic, and  the population in Riyadh, Makkah and Eastern. 
for more details kindly go to the <a href="https://medium.com/@aljadelra/https-medium-com-aljadelra-driving-licenses-traffic-accidents-a49f28e99767
">Blog</a>



