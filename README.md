# azure-dashboard
Perfect.
Below is **plain text only**, professional, clean, and written like **hand-typed by a real data analyst**.
You can **copy-paste directly into GitHub README.md**.

---

Azure Data Analyst Project – Movie Analytics

Overview
This project demonstrates an end to end data analytics solution built using Microsoft Azure services and Power BI. The goal of the project is to analyze movie ratings data stored as CSV files in the cloud and generate meaningful business insights using SQL and data visualization.

The project uses Azure Data Lake Storage Gen2 for data storage, Azure Synapse Analytics Serverless SQL for querying data directly from files without provisioning servers, and Power BI for building an interactive dashboard.

This project was designed with a beginner friendly and low cost approach while following real world cloud data analytics practices.

---

Business Objective
The objective of this project is to analyze movie data to understand user behavior and movie performance. The analysis focuses on identifying highly rated movies, popular genres, user engagement, and rating trends.

The final outcome is an interactive Power BI dashboard that allows users to explore movie ratings and insights dynamically.

---

Technologies Used
Microsoft Azure
Azure Data Lake Storage Gen2
Azure Synapse Analytics Serverless SQL
SQL
Power BI Desktop

---

Dataset
The project uses MovieLens CSV datasets, which include the following files:

Movies data containing movie titles and genres
Ratings data containing user ratings for movies
Tags data containing user generated tags
Links data containing external movie identifiers

All files are stored in Azure Data Lake Storage Gen2.

---

Architecture
CSV files are uploaded to Azure Data Lake Storage Gen2.
Azure Synapse Analytics Serverless SQL queries the files directly using OPENROWSET.
SQL views are created to represent each dataset.
Analytical SQL queries are written by joining multiple views.
Power BI connects to Synapse Serverless SQL and imports the data.
An interactive dashboard is built in Power BI for visualization.

---

Data Modeling
Each CSV file is exposed as a SQL view using Azure Synapse Serverless SQL.
The views are logically connected using the movieId column.

Views created in Synapse:
vw_movies
vw_ratings
vw_tags
vw_links

These views are used for analysis and visualization in Power BI.

---

Key Analysis Performed
Average movie ratings
Number of users who rated each movie
Genre based rating analysis
Most popular movies based on number of ratings
User engagement analysis using tags

---

Power BI Dashboard
The Power BI dashboard includes:

KPI cards showing average rating, total movies, and total users
Bar charts showing average rating by genre
Bar charts showing top rated and most rated movies
A detailed table with movie title, average rating, user count, and IMDb ID
Interactive filters for genres and rating range

The dashboard provides an easy way to explore and understand movie performance and user preferences.

---

Cost Optimization
This project uses Azure Synapse Serverless SQL, which operates on a pay per query model. No dedicated SQL pool or Spark pool was used, ensuring minimal cost. Storage usage is minimal due to small CSV file sizes.

---

Skills Demonstrated
Cloud data storage using Azure Data Lake Gen2
Querying data directly from files using Serverless SQL
Writing analytical SQL queries with joins and aggregations
Building data models for reporting
Creating professional Power BI dashboards
End to end data analytics workflow in Azure

---

Conclusion
This project demonstrates a complete Azure based data analytics solution from raw data ingestion to final visualization. It highlights practical skills required for a data analyst role, including cloud data handling, SQL based analysis, and dashboard creation using Power BI.

---

If you want, next I can help you with:
Resume project description
LinkedIn project post
Architecture diagram explanation
Power BI dashboard review

Just tell me what you want next.
