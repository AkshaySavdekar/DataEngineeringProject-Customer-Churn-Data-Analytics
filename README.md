
# Customer Churn Data Analytics Project

Created End to End DataPipeline from S3 Bucket.Created & Run the Glue Crawler to generate Glue Catalog. We can run sql query over glue catalog directly using Athena.We can create a DataWarehouse by connecting the Redshift Cluster with Glue Catalog.Airflow is used to schedule the Dag. The Visualization can be done using PowerBI.

## Architecture
![image](https://github.com/AkshaySavdekar/DataEngineeringProject-Customer-Churn-Data-Analytics/assets/119107773/941118d3-cc8c-4a70-8e92-02ebd028f0fb)

## Tech Stack

Technology: Python, SQL, AWS S3, AWS Glue, AWS Redshift,AWS Athena, PowerBI, Airflow

**Server:** AWS EC2 Instance

## Project Component

#### Programming Language - 
🐍 Python: Python served as the cornerstone, enabling seamless interaction with S3 Bucket and handling data effectively.

#### ☁️ Amazon Web Services (AWS): 
We harnessed the power of AWS Glue, AWS Athena, AWS Redshift.Extracting data from S3 and transforming using Glue and loading to Redshift.Amazon S3 played a crucial role in storing raw data.

#### 🌨️ AWS Redshift for Data Storage: 
For the loading part, I employed Redshift, an ideal platform for data warehousing and analytics.

#### 🌨️ AWS GLUE for Transformations:
AWS Glue is a serverless data integration service that makes it easier to discover, prepare, move, and integrate data from multiple sources for analytics 

#### 📊 PowerBI for Visualization:
 Can utilise PowerBI to craft stunning data visualizations and interactive dashboards, simplifying data-driven decision-making.

#### ☁️ Airflow
 Airflow is used for managing ETL workflows , monitoring data and computing workflows in Python. AWS EC2 Instance is used to Setup Airflow in this Project.
## Airflow

Install Airflow on EC2 Instance by using below Commands

```bash
sudo apt update
sudo apt install python3-pip
sudo apt install python3.10-venv
python3 -m venv endtoendyoutube_venv
source endtoendyoutube_venv/bin/activate
pip install --upgrade awscli
sudo pip install apache-airflow
airflow standalone
pip install apache-airflow-providers-amazon
```
    
