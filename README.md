# Youtube Trending Videos Analysis

## Data Source

YouTube has used a combination of factors including measuring users interactions(number of views, shares, comments and likes) to determine its top-treinding vides. This is a daily record of the top trending YouTube videos in 2017-2018.
This project is based on a Kaggle dataset: [Trending Youtube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new). For research interest, only U.S. region dataset was used for this project, including 6,351 rows and 17 columns after cleaning.

## Objectives

Questions that helped drive this project:
- Are likes & dislikes distributed differently across category?
- What are the correlations between views, comments and likes, if any?
- What are the TOP videos by number of comments?
- Is there any pattern for publishing date and time of a day for the trending videos?
- What insihts can we draw from the trending viedos' titles?

## Data Processing
- Replace NaN values
- Convert data types
- Seperate and uniform columns
- Map Category Name to Category ID
- Drop duplicated videos that trended for multiple times

## Data Visulization

### Inspect Numeric Variables

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/insp_num_var.png)

We note from the table above that the average number of views of a trending video is 1,962,117. The median value for the number of views is 518,107, which means that half the trending videos have views that are less than that number, and the other half have views larger than that number
The average number of likes of a trending video is 55,575, while the average number of dislikes is 3,067. The
Average comment count is 6,451 while the median is 1,266.

#### Views Distribution

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/views_dist.png)

The majority of trending videos have views concentrated near 1 million, 50% of which have less than 0.5 million views when zooming in.

#### Comments Distribution

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/com_dist.png)

Similarly, most comments count concentrate in range 0-10k. 12% of them have more extrame counts that are above 10 thousand. 51% with less than 1.3 thousand comments, and majority have less than 400.

#### Likes & Dislike Distribution

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/like_dislike_dist.png)

From the hisogram we can see that Entertainment, Music and Sport rank the top 3 category with number of likes and dislikes. Across categories, the proportion of likes and dislikes are roughly 50:50. 

#### Top 20 Trending Videos by number of comments

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/top20.png)

We see 7 out of the top 20 trending vides by # of comments are Korean pop related.

#### Top 10 Channels/Categories by number of videos

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/top10_channels.png)

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/top10_categories.png)

### Publishing day and publishing hour
![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/date_time.png)

During weekend less videos are uploaded compared to weekdays. And 4pm is the most popular time of a day to publish videos. Majority of videos are published from 1pm to 23pm.

### Title analysis
![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/title.png)

44% of titles contain at least one fully-capitallized word.
And the title length is normally distributed with most trending videos having title lengths between 30-60 characters approximately.

![alt text](https://github.com/lisu1222/Youtube-Trending-Videos-Analysis/blob/master/title_word_cloud.png)

We notice also that words "Video", "Trailer", "Official", and "New" are very common in trending video titles.


