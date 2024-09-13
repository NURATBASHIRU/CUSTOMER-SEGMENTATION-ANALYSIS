## CUSTOMER-SEGMENTATION-ANALYSIS

### Behavioral, Demographic, Transactional and Geographical Segmentation
#### Introduction
##### Customer Segmentation is an act of classifying customers into different categories based on shared characteristics. This act makes it easier for businesses to modify its product and/ or services in order to improve customer satisfaction and retention, ensure customer inclusion and optimize business relevance in the long –run. This project unveils the different categories of customers for an online retail store and I have successfully created different segments for the purpose of this analysis. 

##### Three datasets were consolidated solely for the purpose of this analysis and this analysis is tailored to the RFM methodology (although, there were limitations to this method which I intend to explain in the coming paragraphs). 


### Data Overview
#### Data Sources
##### The data source for the datasets used are as follows; 
##### 1.	[Kaggle](https://www.kaggle.com/code/karnikakapoor/customer-segmentation-clustering/input)
##### 2.	[Kaggle](https://www.kaggle.com/datasets/kaushiksuresh147/customer-segmentation)
##### 3.	[Google Drive](https://docs.google.com/spreadsheets/d/1R-NjFCpGDAgtUKRaf-ZVXXbf-JdQb-JK/edit?gid=111825067#gid=111825067)


#### Data Preparation Process
##### The datasets went through thorough cleaning process individually before and after they were integrated and I used this process to identify the metrics needed for my analysis while getting rid of the irrelevant / excessive metrics in the dataset. The dataset started out as 53 columns and 9,800 rows and later cut down to 28 columns and 2,240 rows as a result of cleaning, formatting and aggregation.


#### Data Cleaning steps Taken
##### After identifying the required metrics, the datasets went through the following processes to ensure that the best quality is derived for further analysis.
##### 1.	Trim() Function; I used trim function to get rid of unnecessary spaces to ensure consistent information
##### 2.	Proper() Function; I used the proper function to format texts into sentence cases to ensure consistency of information – because I noticed some texts were not in proper cases and that made the data messy.
##### 3.	Removed Duplicates – I made sure I removed duplicate rows before consolidating the datasets
##### 4.	Removed Blanks
##### 5.	Format each row
##### 6.	I created two columns for “Age” and “Customer_Relationship” using the “Birthyear” and “Dt_Customer” Columns. The “Birthyear” column represents the customers birth year while the “Dt_Customer” represents the date the customer joined the company.
##### 7.	Spell check
##### 8.	Removed irrelevant rows and columns – due to merging data from different sources, that left me with a lot of rows and columns that were not helpful to the analysis. 


#### Segmentation Approach
##### The result of this analysis is visually represented in two interactive dashboards that contains 10 charts and 6 KPIs. These charts and KPIs are projections of four customer segmentation approaches; The Geographical, Behavioral, Transactional and Demographic approach.
##### The KPIs are a clear indication of the analysis objective. The KPIs have been selected in a way that keeps the spotlight on the essence of the analysis.
##### The charts in the dashboard includes;
##### 1.	Top 10 Customer Locations
##### 2.	Customer Age Distributions
##### 3.	Distribution of Customer Type
##### 4.	Gender Distribution
##### 5.	Segmentation by Profession
##### 6.	Segmentation By Income Range


#### Analysis Results
#### A.	Geographical, Behavioral and Demographic Analysis
##### 1.	It’s evident that we have customers scattered across different regions of the United States with California, New York and Texas being the most populated cities.
##### 2.	The analysis Indicates that majority of our customers are in their middle age which means our products and services should be tailored to fit these age group – suggesting products for their kids, fitness equipment, health monitoring devices or retirement saving services could while they shop for other items could be a great marketing strategy.
##### 3.	A really large extent of the customer type goes to the “Home office” customers which mean they are most likely professionals and they probably prefer goods that would improve workflow or convenience. These types of customers may need an improved delivery service.
##### 4.	The gender distribution is almost equal which makes it easier to include people of different sexuality in the business operation
##### 5.	Also, the analysis indicates that a large extent of the customers are “Artists” by profession and a notable number of them are “HealthCare” professionals. Makes it really easy to involve them in social activities.
##### 6.	Customers earn less than a hundred thousand dollars yearly and that gives us a little perspective on how much they are likely to spend on purchases.

#### B.	Transactional Analysis
##### 1.	The “Consumer” customer type have a huge impact on the overall sales and profit percentage of this retail company and it has been that way over the years
##### 2.	The corporate customer type had a huge increment in sale in the recent year but in contrast, profit percentage dropped.


#### Skills Applied
##### 1.	Data Research
##### 2.  Data cleaning
##### 3.	Data Integration
##### 4.	Data Aggregation
##### 5.	Data Visualization
##### 6.	Data Interpretation
