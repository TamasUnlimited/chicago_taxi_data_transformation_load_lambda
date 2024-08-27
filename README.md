# Chicago Taxi trips transformation load

This project uses the Chicago Taxi Trip dataset and weather API. Every part of this project is a sample code which shows how to do the following:

* Get daily dataset from chicago taxi trips
* Get daily dataset from  weather API https://open-meteo.com/
* Data Loading and Cleaning: Load the CSV data into a Pandas Data Frame, handle missing values, data types and modifying columns.
* Transforming, loading and automatizing data in AWS systems
* Creating visualizations from transformed data

# Technologies

* Used Python 3.12
* AWS: 
    
    - Lambda - For automating the ETL process 
    - S3 - For storing and accessing data 
    - Glue - Data transformation
    - Crawler - Discovers and catalogs data from sources to make it queryable
    - Athena - Analyze data in S3 using standard SQL
    - Boto3 - AWS SDK for Python, for interacting with AWS services
 
# Data visualizations with matplotlib and seaborn

