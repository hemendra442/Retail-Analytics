# Azure Retail Data Analytics Framework

**Project Objective**

<span style="font-size:larger;">
Our goal was to create a scalable, end-to-end Retail analytics framework capable of processing large volumes of data from diverse sources, including sales, customer, and inventory levels. By leveraging Azure's powerful cloud computing capabilities, we aimed to provide data-driven insights to optimize operations, personalize customer engagement, and boost sales.
</span>

# **Project Architecture**
End to End Project Framework using Azure Platform.
<img width="927" alt="Arch" src="https://github.com/hemendra442/Retail-Analytics/assets/31797686/d665c058-a45e-46c7-92d1-18c2e6977b83">


## **Tools & Technologies**
<span style="font-size:larger;"> List of all the components which are part of this project.</span>

<span style="font-size:20px;">

Data sources          : web services

Ingestion tool        : Azure Data Factory

Storage solutions     : Azure Data Lake Storage 

Data processing       : Azure Databricks 

Data consumption tool : Power BI 

Programming Languages : Pyspark
</span>


**Data**:-

Retail Sales source dataset from Kaggle.

https://www.kaggle.com/datasets/tforsyth/4-year-historical-sales-data?select=master_product.csv


# **Data Ingestion Pipeline with Azure Data Factory**
Using AZure Data Factory (ADF) pipeline, We aim to establish a robust data ingestion pipeline for a retail company looking to centralize its data from multiple sources, including sales, in-store transactions, inventory systems. The ultimate goal is to create a unified data repository that supports advanced analytics, reporting, and data-driven decision-making.
<img width="1221" alt="ADF_Ingestion" src="https://github.com/hemendra442/Retail-Analytics/assets/31797686/2d1a240b-7e29-40bd-91be-e17636164810">

### **Data Ingestion Output** :-
<img width="1057" alt="ADLS_Ingestion" src="https://github.com/hemendra442/Retail-Analytics/assets/31797686/4d709341-05b1-4db1-a153-a73f9d4d7cdf">

# **Data Transaformation**
Using Databricks, We aim to process, clean, and transform data into a format that's ready for analytics, machine learning, or further data processing tasks.
Using Pyspark programming on Databricks performed various transformations on central repository source data.

ADLS Processed Data:-
<img width="915" alt="ADLS " src="https://github.com/hemendra442/Retail-Analytics/assets/31797686/57292883-935e-451d-958f-b42f82f8044c">

# **Data Visualization**

Using  Power BI's advanced analytics capabilities, Designed interactive dashboard that provide  insights to business, thereby supporting strategic decision-making and operational efficiencies.

<img width="1440" alt="Screenshot 2024-02-23 at 12 39 02 AM" src="https://github.com/hemendra442/Retail-Analytics/assets/31797686/244d5a29-0297-4652-bfa4-50ba2066dfa4">

