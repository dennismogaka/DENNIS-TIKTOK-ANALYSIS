# DENNIS-TIKTOK-ANALYSIS
This project analyzes Dennis' TikTok Account to investigate the low growth rate and come up with recommendations from the insights and findings for the strategies to grow the account.

##**INTRODUCTION**
This project analyzes Dennis’ Tiktok Account performance from 2022-2025. By exploring key metrics 
such as Total Likes, Total Comments, Total Following, Total Followers, Total Posts, Engagement and 
Engagement Rate, the analysis aims to provide valuable insights into account performance.
Leveraging Excel’s analytical and powerful visualization capabilities, the project will uncover actionable 
data driven strategies to improve and enhance decision making on how to improve and grow the 
account.
##**STATEMENT OF PROBLEM**
Dennis’ Tiktok Account faces a challenge of low growth rate. Dennis seeks to identify the factors for the 
low growth rate and those for account success, uncover patterns and relationship between these 
variables. This will enable timely and targeted growth of the account.
##**PROJECT OVERVIEW**
Since launching my Tiktok content journey in 2022, the account has not had any considerable growth. I
 have decided to track the engagement metrics to understand how the audience interacts with my 
account. Key performance indicators such as total likes, total comments, total followers, total following, 
engagement and engagement rate were closely monitored to guide in strategic decisions for growth.

 ##**AIM OF THE PROJECT**
•	Provide an overview of year over year account performance focusing on posts, likes, followers, 

following and comments.

•	Analyze growth trend identifying years with low growth and those with higher growth.

•	Visualize account metrics and trend using Excel to present actionable insights.


•	Use insights to make recommendations on improvement and growth of the account.

##**SKILLS DEMONSTRATED**
•	Extracting data from Tiktok account.

•	Data import to Excel


•	Data cleaning and preparation

•	Creating pivot tables


•	Designing an interactive Dashboard

•	Creating visualization from the data


##**DATA SOURCE AND EXTRACTION PROCESS**

The data used in this analysis was extracted from TikTok and saved as a CSV file.

##**DATA PROCESSING**
•	Conditional formatting was used to highlight rows that were not necessary for the analysis after

 which the rows were deleted. 

•	TEXT TO COLUMN function was used to convert date-time text to column. Time column was 

then deleted because it was not useful in analysis.

•	After deleting time column, another column was created to tally dates. Each date was assigned 

1.

•	The dates that appeared more than once were consolidated to one.

•	After consolidation, columns for Followers, Following, Comments, Likes and Posts were created.


•	INDEX-MATCH was used to match data from raw data to consolidated dates and a table was 

created. 

**=INDEX($B$2:$B$198,MATCH(M2,$A$2:$A$198,0)**

•	IFERROR was used to fill rows with missing data with 0.

**=IFERROR(INDEX($B$2:$B$198,MATCH(M2,$A$2:$A$198,0)),"0")**

•	After all the data had been matched into one, a table was created.

 
•	Pivot tables were inserted and data analysis began.

   

##**DATA ANALYSIS**
The analysis reveal several key insights related to posts, comments, likes, followers and following 
performance.

Key Performance Indicators (KPIs)

Total Likes, Total posts, Total Following, Total comments and Total Followers were used as KPIs.

•	**Total Posts (73):** Shows consistent content creation and effort from November 2024 to 

April 2025 laid the foundation for the account growth.

 
•	**Total Likes (1383):** Likes account for a significant portion of engagement, signaling positive 

reception from viewers.

 
•	**Total Followers (1178):** The number of followers rose considerably between November 

2024 and April 2025 due to consistent posting of content that resonates with the audience.

 

•	**Total Following (1060)** 

 

•	**Total Comments (56)**

 
•	**Engagement Rate (4.2%):** The engagement rate is WITHIN Tiktok’s typical 3-6% suggesting 

that the content posted resonated well with the audience.
**DEFINITION RECAP**

**ENGAGEMENT= LIKES + COMMENTS + SHARES**

**ENGAGEMENT RATE = ENGAGEMENT/VIEWS**

**TOTAL VIEWS = 35,000**

##**DATA VISUALIZATION**
##**DASHBOARD REVIEW**
The dashboard provides a comprehensive analysis of account performance from 2022-2025. It 
Incorporates interactive parameters that allow filtering and viewing performance data for a specific 
year, enabling focused analysis and comparison of growth trend across different years.

##**INSIGHTS & FINDINGS**
•	No content was posted between 2022 and 2023 making the account dormant leading to low 

growth of the account.

•	Engagement in terms of likes and comments was zero (0).


•	There was high growth rate between November 2024 and March 2025 due to consistent 

content posting that resonated with the audience.

•	Followers increased from 273 in 2024 to 835 in 2025 which was a 67% growth.

•	Comments grew by 80% from 11 in 2024 to 45 in 2025.


•	Likes also grew by 81.8% between November 2024 and March 2025.

•	Content type Drives engagement

	Educational and career-focused posts led to the high growth between 2024 and 2025.

	Personal story-telling content also resonate well with my audience.


##**LIMITATIONS**
•	The analysis focuses on likes, comments, followers, following and posts. It does not include 

views, watch through rate, saves, paly-time or audience demographics which are key for deeper 

understanding.

•	The analysis did not fully separate the effects of captions, hashtags or sound usage which are 

known to impact discoverability and engagement.

##**ANSWERS TO BUSINESS PROBLEMS**
Using the analysis from the dataset:
1.	**Discover patterns that lead to higher likes and comments**
**Observed Patterns: By Posts**
	The higher the number of posts that resonates with the audience, the higher the engagement. 

In 2024, there were 11 comments and 212 likes and as the number of posts increased to 73 in 

2025, number of comments increased by 76% and likes by 81.8%.

2.	**Determine effective strategies to increase audience engagement.**

	Double down on educational content: posts that offer tips, career guidance and skills advice get 

higher interactions –create more of these.

	Incorporate personal stories; sharing your journey creates relatability and encourages 

engagement.

##**RECOMMENDATIONS**
Here are recommendations to help improve and grow Dennis’ TikTok account in the coming years based 
on the insights drawn from the dataset:
•	Continue to create content around career advice, data skills, remote work as these clearly drive 

engagement.

•	Explore data beyond engagement which are audience retention, most effective sound trends 

performance of posts by format. E.g., storytelling vs. tutorials

•	Implement a snapshot report at the start of each month to track changes and prevent real-time 

data shifts from skewing insights.







 









