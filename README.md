# Lux-Data-Science-Capstone-Project

Project description:
In week 4, we performed time series modelling on the Craigslist vehicles dataset, which is available on Kaggle at https://www.kaggle.com/datasets/mbaabuharun/craigslist-vehicles. This project builds on that work. You will need to download the dataset, copy the data using SQL to a local PostgreSQL database, move the data from your local database to Snowflake, perform data transformation with DBT (data build tool), and use your preferred data visualization tool to create a report and dashboard.



These are the steps that I followed to tackle the project described above:
#### Step 1: Download the Dataset
##### Description:
I began by obtaining the necessary dataset for the project, which is crucial for subsequent analysis and predictions.
##### Procedure:
Identified the source of the dataset, which was [https://www.kaggle.com/datasets/mbaabuharun/craigslist-vehicles].
Downloaded the dataset in CSV form, ensuring compatibility with the project requirements.


#### Step 2: Copy Data Using SQL to a Local PostgreSQL Database
##### Description:
To manage and analyze the data locally, I set up a PostgreSQL database and copied the downloaded dataset into it using SQL scripts.
##### Procedure:
Installed PostgreSQL on my local machine and the pgAdmin interface.
Created a new PostgreSQL database named LuxTech.
Developed SQL scripts to copy the dataset into relevant tables within the PostgreSQL database.


#### Step 3: Move Data from Local Database to Snowflake
##### Description:
For scalability and flexibility, I transferred the data from the local PostgreSQL database to Snowflake, a cloud-based data warehouse. I used Supabase as the local Postgresql was having some issues.
##### Procedure:
Created a Snowflake account.
Configured the connection between the local PostgreSQL database and Snowflake.
Utilized Snowflake's tools to transfer the data seamlessly.


#### Step 4: Perform Data Transformation with DBT
Description:
Leveraging DBT, I performed essential data transformations, modeling, and structuring within Snowflake to prepare the data for analysis.

##### Procedure:
Installed DBT on my system, ensuring compatibility with Snowflake. (tried dbtLabs)
Developed DBT models to transform raw data into a structured format suitable for analysis.
Executed DBT commands to apply transformations and build the structured dataset.


#### Step 5: Use Preferred Data Visualization Tool to Create a Report
##### Description:
To derive meaningful insights, I utilized PowerBI to create comprehensive reports based on the transformed data.
##### Procedure:
Selected PowerBI as my preferred data visualization tool.
Tried to connect PowerBI to the Snowflake database but later on resolved to use the local data I had earlier.
Designed and generated reports and visualizations to convey insights effectively.


#### Step 6: Build a Dashboard
##### Description:
Compiling the individual reports into an interactive dashboard allowed for a more holistic exploration of the data.
##### Procedure:
Used the features of PowerBI to build an interactive dashboard.
Arranged the reports in a logical and user-friendly layout.
Implemented interactivity features, enhancing the user experience with dynamic insights.
By documenting these steps in this manner, you provide a comprehensive guide for team members or stakeholders, ensuring transparency and replicability of the process in future iterations or for other projects.
