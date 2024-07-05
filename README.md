# Ecommerce-Project
Using Big Query platform to solves problems such as Data mining and Data exploration, joining data from separate spreadsheets on Ecommerce data.
## 1: Introduction
### 1.1: Google Bigquery
In the realm of modern data analytics, leveraging robust platforms like Google BigQuery has become indispensable for organizations aiming to extract actionable insights from vast datasets. BigQuery, a fully managed data warehouse solution on the cloud, offers unparalleled scalability and speed, making it ideal for complex data mining and exploration tasks.
### 1.2: Dataset
dataset includes 1 public table ga_sessions_20170801 on Bigquery
Fields that need attention
|fullVisitorId	| STRING |The unique visitor ID.|
|date| STRING |The date of the session in YYYYMMDD format.|
|totals|RECORD| This section contains aggregate values across the session.|
|totals.bounces|	INTEGER|	Total bounces (for convenience). For a bounced session, the value is 1, otherwise it is null. |
|totals.hits|	INTEGER	|Total number of hits within the session.|
|totals.pageviews|	INTEGER|	Total number of pageviews within the session.|
|totals.visits|	INTEGER|	The number of sessions (for convenience). This value is 1 for sessions with interaction events. The value is null if there are no interaction events in the session.|
|totals.transactions|	INTEGER|	Total number of ecommerce transactions within the session.|
|trafficSource.source |STRING	|The source of the traffic source. Could be the name of the search engine, the referring hostname, or a value of the utm_source URL parameter.|
|hits|RECORD|	This row and nested fields are populated for any and all types of hits.|
|hits.eCommerceAction|	RECORD	|This section contains all of the ecommerce hits that occurred during the session. This is a repeated field and has an entry for each hit that was collected.|
