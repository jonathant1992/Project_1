# Project_1













David: Does a certain language of a song impact the song’s success and popularity?

Analysis: With the help of Xpert Learning Assistant and ChatGPT. I was able to come up and write a code that allows me to use an API that pulls a link from Genius using the title of a song from the dataset. The dataset I obtained was from Kaggle called the most streamed spotify songs. It contains songs that had the most streams on Spotify as of 2023. Then those links are placed in the dataset and it leads to the Genius page of the song where the lyrics are contained. Then using Beautiful Soup, a library in python, I was able to scrape the lyrics from the Genius lyrics webpage, and place them in the dataset as well. After that, I use another python library called langdetect to read the lyrics and give me the language of those lyrics. Now that I have the language of each song, I am then able to conduct some visualization of data based on the song's language. I first sorted the dataset by descending streams, which means that the most streamed songs will be at the top of the dataset. I took the top 100 songs in the dataset and created a new dataset that contains the top 100 songs of that dataset. Using those top 100 songs, I created a pie chart to visualize how many songs are in what language. I found that out of those top 100 songs, 89 songs were in English, 1 song in Korean, 1 song in Indonesian, and 9 in Spanish. Next, I made another visualization which was a bar chart that compared the top streaming songs out of those 4 languages. From that bar graph, I was able to see that the most streamed English song had nearly a 1 billion streams while the top Korean/Indonesian/Spanish each haven't hit 100 million streams. Based on these data visualizations, I can determine that English songs are more popular than other songs in other languages. To prove that this statement is true, I used python to conduct statistical analysis and have it calculate the p-value using a code that samples only 100 songs out of the 943 total songs. So everytime I run that code, a different p-value will be calculated. And every p-value it calculated was small that 0.05. This allows me to reject the null hypothesis and accept the null. For this question, the null hypothesis will be that the language of a song does certainly play a role in impacting a song's success and popularity.






Ray Lawrence: For my analysis, we were concerned about whether or not artist popularity would contribute to the popularity of a song on the social media platform TikTok based on 2022 data. I took 2 datasets, Top Spotify songs of 2022 and Top TikTok songs of 2022 and merged them into one, paying attention to track popularity, artist popularity, and danceability. I was concerned with danceability because some of Tiktok’s trending audio is used for dance challenges and trends and I wanted to see if a more danceable song by a popular artist did better on Tiktok than a less danceable one from the same artist. Testing scatterplot data from both artist popularity vs song popularity and danceability vs song popularity, we found that both scatterplot graphs showed little to no correlation between either metric (danceability/artist popularity) and song popularity. We decided to test this further and look at the top 5 artists based on popularity from the dataset and compare where their songs finished within the top 20 songs on Tiktok for 2022. We found that 2 of the top 5 artists were in the top 5 of songs, 3 of the top 5 were in the top 20, with 2 artists finishing outside of the top 20 Tiktok songs. These findings further reinforced the data and analysis that we conducted and collected from the scatterplot data which is that artist popularity has no effect on song popularity on TikTok, and that there are more factors that contribute to a song's success, specifically on TikTok
Dataset used: https://www.kaggle.com/datasets/sveta151/spotify-top-chart-songs-2022






Tavneet Kaur: Country Analysis on Spotify Streaming Data

Project Overview:

This project analyzes global Spotify streaming data to explore the top songs, artists, and countries contributing to streaming trends. The dataset used includes song names, artist names, total streams, and country details. Various insights and visualizations are generated to highlight the most streamed songs and artists, top contributing countries, and patterns in streaming data.

Goals of the Project:

Top 10 Songs by Streams: Identify the most streamed songs globally.
Top 10 Artists by Streams: Highlight the artists with the highest number of streams.
Top 10 Countries by Streams: Analyze which countries contribute the most to Spotify streams.
Song-Specific Analysis: Visualize country-specific streams for individual songs.
Relationship between Streams and Tracks: Explore the relationship between the total number of streams and unique tracks per country.

Key Analyses and Visualizations:

Top Songs: STAY (with Justin Bieber) leads with 6.3M streams.
Top Artists: Lil Nas X tops with 11.4M streams, followed by Doja Cat and Drake.
Top Countries: The United States dominates with 70M streams, followed by Brazil and Mexico.
Song-Specific Analysis: Shape of You streams are highest in India, followed by Japan and Australia.
Streams vs. Tracks: Higher unique tracks correlate with higher total streams.

Conclusion:

Through this project, we identified key trends in Spotify streaming data:

The United States dominates global streams.
Artists like Lil Nas X and Doja Cat are among the most popular.
Specific songs like Shape of You have country-specific popularity (e.g., high streams in India and Japan).



