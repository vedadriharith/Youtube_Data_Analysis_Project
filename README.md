# YouTube Data Collection and Analysis with Python

## Project Description
If you are learning Data Science, YouTube is an amazing data source for you. There are so many problems we can solve by collecting data from YouTube. This project focuses on collecting data about the trending videos on YouTube to analyze and find what makes a video trend.

## YouTube Data Collection and Analysis

### Data Collection
To collect data from YouTube, you need to set up an API. Follow these steps to get your API key:

1. Go to Google Cloud Console.
2. Click on the project drop-down at the top, then “New Project”.
3. Enter a project name and click “Create”.
4. In the Google Cloud Console, navigate to “APIs & Services” > “Library”.
5. Search for “YouTube Data API v3” and click on it.
6. Click “Enable”.
7. Go to “APIs & Services” > “Credentials”.
8. Click “+ CREATE CREDENTIALS” and select “API key”.
9. Copy the generated API key.

### Data Collection with Python
We use the YouTube Data API to fetch details of the top 200 trending videos in the US. The collected data includes details such as title, description, published date, channel information, tags, duration, definition, captions, and various engagement metrics like views, likes, and comments. The data is then saved to a CSV file named `trending_videos.csv` for analysis.

### Data Analysis
The analysis includes:

1. **Data Cleaning**: Handling missing values and converting data types.
2. **Descriptive Statistics**: Summarizing engagement metrics.
3. **Visualization**: Plotting histograms, scatter plots, and bar charts to understand the distribution and relationships within the data.
4. **Category Analysis**: Identifying trends based on video categories.
5. **Duration Analysis**: Exploring how video length affects engagement.
6. **Tag Analysis**: Examining the impact of the number of tags on view counts.
7. **Publish Hour Analysis**: Analyzing the effect of the time a video is published on its views.

### Key Findings
1. **Engagement Metrics**: Encouraging viewers to like and comment on videos significantly boosts engagement.
2. **Video Length**: Longer videos (under 5 minutes) tend to have higher engagement, especially in categories like Film & Animation and Gaming.
3. **Publish Time**: Most videos are published between 11 AM – 4 PM, suggesting this may be an optimal time for uploading videos.
