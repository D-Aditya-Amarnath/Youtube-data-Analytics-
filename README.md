# Youtube-data-Analytics
This project is done using a dataset in Kaggle
* Creating a tableau dashboard to tell a story how each video performed through interactive visualizations
* Kaggle Dataset url: https://www.kaggle.com/datasets/thedevastator/youtube-analytics-how-to-keep-your-viewers-engag

## About Dataset

This YouTube Analytics dataset contains a wealth of information that can be used to study how to engage viewers and keep them coming back for more. With columns like thumbnail link,, country codes, views, and user subscriptions added, this dataset provides valuable insights into how YouTube videos perform and what factors influence viewer engagement. Additionally, the average view percentage and watch time columns can be used to gauge the overall success of a video in terms of engagement


### File: AggregatedMetricsByCountryAndSubscriberStatus.csv

Column name	Description
Thumbnail link	:- A link to the thumbnail image of the video. (String)
Country Code	:- The country code of the viewer. (String)
Is Subscribed	:- Whether or not the viewer is subscribed to the channel. (Boolean)
Views	:- The number of views the video has. (Integer)
User Subscriptions Added	:- The number of subscriptions the video has gained. (Integer)
User Subscriptions Removed	:- The number of subscriptions the video has lost. (Integer)
Average View Percentage	:- The average percentage of the video that viewers watch. (Float)
Average Watch Time	:- The average amount of time viewers spend watching the video. (Float)

### File: AggregatedMetricsBy_Video.csv

Column name	Description
Views	:- The number of views the video has. (Integer)
Shares	:- The number of times the video was shared. (Integer)
Likes	:- The number of likes the video has. (Integer)
RPM (USD)	:- The revenue per thousand views the video has. (Float)
CPM (USD)	:- The cost per thousand views the video has. (Float)
Watch time (hours)	:- The total number of hours the video has been watched. (Float)

### File: AllCommentsFinal.csv

Column name	Description
Comments	:- The number of comments on the video. (Integer)
Reply_Count	:- The number of replies to the video. (Integer)
Like_Count	:- The number of likes on the video. (Integer)
Date	:- The date the video was published. (Date)

### File: VideoPerformanceOver_Time.csv

Column name	Description
Date	:- The date the video was published. (Date)
Thumbnail link	:- A link to the thumbnail image of the video. (String)
Views	:- The number of views the video has. (Integer)
User Subscriptions Added	:- The number of subscriptions the video has gained. (Integer)
User Subscriptions Removed	:- The number of subscriptions the video has lost. (Integer)
Average View Percentage	:- The average percentage of the video that viewers watch. (Float)
Average Watch Time	:- The average amount of time viewers spend watching the video. (Float)
