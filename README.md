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
We note from the table above that

The average number of views of a trending video is 1,962,117. The median value for the number of views is 518,107, which means that half the trending videos have views that are less than that number, and the other half have views larger than that number
The average number of likes of a trending video is 55,575, while the average number of dislikes is 3,067. The
Average comment count is 6,451 while the median is 1,266.

#### Views Distribution



