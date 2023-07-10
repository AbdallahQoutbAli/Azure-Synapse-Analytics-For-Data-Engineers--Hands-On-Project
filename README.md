Azure Synapse Analytics For Data Engineers -Hands-On Project

# 1- Data Overview 

The dataset that we are going to use for our project is the trip data from New York City Taxi Services.
There are three different taxi-haliing services in New York.
The first one is yellow taxis, which are only allowed to pick up passengers from the inner city.
The next one is green taxis. They, on the other hand, are allowed to only pick up passengers from the outer boroughs, but they can drop them off anywhere in the city.
Then we have the farm vehicles which operate throughout the city.
There is a further classification of the For Hire Vehicles called High Volume For-Hire Vehicles.
![image](https://github.com/AbdallahQoutbAli/Azure-Synapse-Analytics-For-Data-Engineers--Hands-On-Project/assets/47276503/8293544d-c6a4-46f6-b77b-4137b59d8693)



# 2- NYC Taxi Data Flies Overview 
There are a lot of flies as shown below : 

1- Taxi Zone (CSV) <br>
2- Calendar (CSV)  <br>
3- Trip Type (TSV)  <br>
4- Rate Code (JSON)  <br> 
5- Payment Type (JSON)  <br>
6- Vendor (CSV Quoted )  <br>
7- Trip Data (Parquet,CSV,Delta)  <br>

![image](https://github.com/AbdallahQoutbAli/Azure-Synapse-Analytics-For-Data-Engineers--Hands-On-Project/assets/47276503/540bd0bf-bc64-4e1a-af1f-8e67cf1fa1bb)

# 3- Project Requirements
### 1- Data Discovery 
<ol>
<li> Data exploration capabliity on the raw data </li>
<li> Schema applied to the raw data </li>
<li> Discovery using T-SQL </li>
<li> Discovery using pay-per-query model </li>
  
</ol>

### 2- Data Ingestion

<ol>
<li> Ingested data to be stored as Parquet </li>
<li> Ingested data to be stored as tables/ views </li>
<li> Abliity to query the ingested data using SQL</li>
<li> Ingestion using pay-per-query model</li>
  
</ol>

### 3- Data Transformation


<ol>
<li> Join the key information required for reporting to create a new table. </li>
<li> Join the key information required for Analysis to create a new table.</li>
<li> Abliity to query the ingested data using SQL</li>
<li> Must be able to analyze the transformed data via T-SQL </li>
<li> Transformed data must be stored in columnar format (i.e., Parquet) </li>

</ol>

### 4- Reporting Requirements

<ol>
<li> Taxi Demand </li>
<li> Join the key information required for Analysis to create a new table.</li>
<li> Credit Card Campaign</li>
<li> Must be able to analyze the transformed data via T-SQL </li>
<li> Operational Reporting</li>

</ol>


# 4- Solution Architecture
![image](https://github.com/AbdallahQoutbAli/Azure-Synapse-Analytics-For-Data-Engineers--Hands-On-Project/assets/47276503/52a2d5ed-fb72-4ad1-92c4-a0ef020c717e)




