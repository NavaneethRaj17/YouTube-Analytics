# YouTube-Analytics
YouTube is an amazing data source.There are so many problems we can solve by collecting data from YouTube. In this article, I’ll take you through the task of YouTube data collection and analysis using Python.

# Collect data about the trending videos on YouTube to analyze and find what makes a video trend on YouTube.
So, let’s start with data collection first. To collect data from YouTube, you need to set up an API. Here are the steps you can follow:
1. Go to Google Cloud Console.
2. Click on the project drop-down at the top, then “New Project”.
3. Enter a project name and click “Create”.
4. In the Google Cloud Console, navigate to “APIs & Services” > “Library”.
5. Search for “YouTube Data API v3” and click on it.
6. Click “Enable”.
7. Go to “APIs & Services” > “Credentials”.
8. Click “+ CREATE CREDENTIALS” and select “API key”.
9. Copy the generated API key.
Now, let’s get started with YouTube data collection using Python. I’ll collect data about the top 200 trending videos on YouTube.

Install all the necessary python libraries as mentioned in the requirements.txt file

# Inferences from Analytics
![Screenshot 2025-03-17 173307](https://github.com/user-attachments/assets/1394349d-e989-42cd-8c3d-3940b5900e36)
The histograms show that the distributions of view counts, like counts, and comment counts are right-skewed, with most videos having lower counts and a few videos having very high counts.

![Screenshot 2025-03-17 173449](https://github.com/user-attachments/assets/12f9a078-def0-4c0c-9156-d207cbeca0a0)
The heatmap confirms strong positive correlations between views, likes, and comments.

![Screenshot 2025-03-17 173554](https://github.com/user-attachments/assets/a087d0ce-0ce3-4e8d-8cdc-2b589a355451)
The bar chart shows that the Gaming, Entertainment, Sports, and Music categories have the highest number of trending videos.

![Screenshot 2025-03-17 173723](https://github.com/user-attachments/assets/0ca0f222-9d39-484b-8377-6fff49fc53f9)
Music and People & Blogs categories have the highest average view counts, likes, and comments. Film & Animation also shows high engagement, especially in view counts and like counts.

![Screenshot 2025-03-17 173840](https://github.com/user-attachments/assets/e888cdee-fc9f-4ce6-8dce-d6ed44d8615f)

![Screenshot 2025-03-17 173927](https://github.com/user-attachments/assets/4dc7821e-69fe-4552-bb48-f7eb63aaf1a9)

The scatter plot shows a slight negative correlation between video length and view count, indicating shorter videos tend to have higher view counts. Videos in the 0-5 minute range have the highest average view counts, likes, and comments. Engagement decreases as video length increases.


![Screenshot 2025-03-17 174056](https://github.com/user-attachments/assets/d5e4673d-5674-42b3-8a66-ccbff7dc0f12)
The scatter plot shows a very weak relationship between the number of tags and view count, suggesting that the number of tags has minimal impact on a video’s view count

![Screenshot 2025-03-17 174151](https://github.com/user-attachments/assets/1c6546df-f0af-481f-a35b-d035e0e48d54)
The distribution shows that most videos are published between 14:00 and 20:00 hours (2 PM – 8 PM), indicating this may be an optimal time for uploading videos. There is a very weak negative relationship between publish hour and view count, suggesting that the hour of publication has minimal impact on engagement metrics.

# Conclusion
1. Encourage viewers to like and comment on videos to boost engagement metrics.
2. Aim to create shorter videos (under 5 minutes) for higher engagement, especially for categories like Music and Entertainment.
3. Schedule video uploads around peak times (2 PM – 8 PM) to maximize initial views and engagement.




