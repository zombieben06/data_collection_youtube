# Dataset Description: YouTube Data Collection

## Overview
This dataset contains information collected from YouTube videos using the YouTube Data API v3.  
The data was gathered for research and analysis purposes, focusing on video metadata, engagement metrics, and publishing trends.

## Data Source
- Platform: YouTube
- Collection Method: YouTube Data API v3
- Tools: Python, requests, pandas
- Type of Data: Public video metadata (title, views, likes, publish date, etc.)
- Target Keywords: Example — “nồi cơm điện”, “smartwatch”, or any keyword defined in the script.

## Data Fields
- `video_id`: Unique identifier for the video.
- `title`: Title of the video.
- `channel_title`: Name of the channel publishing the video.
- `published_at`: Date and time of publication.
- `view_count`: Number of views.
- `like_count`: Number of likes.
- `comment_count`: Number of comments.
- `description`: Short description of the video content.
- `tags`: List of tags assigned to the video.
- `category_id`: Category code defined by YouTube.

## Purpose
The dataset is intended for:
- Sentiment analysis of video titles/descriptions.
- Trend analysis of keyword popularity.
- Engagement metric prediction (views, likes).
- Comparative analysis of different product types.

## Ethical Note
All data collected are public information accessible via YouTube Data API, used strictly for educational and research purposes.
