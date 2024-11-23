# Project_1













David: Does a certain language of a song impact the song’s success and popularity?

Analysis: With the help of Xpert Learning Assistant and ChatGPT. I was able to come up and write a code that allows me to use an API that pulls a link from Genius using the title of a song from the dataset. The dataset I obtained was from Kaggle called the most streamed spotify songs. It contains songs that had the most streams on Spotify as of 2023. Then those links are placed in the dataset and it leads to the Genius page of the song where the lyrics are contained. Then using Beautiful Soup, a library in python, I was able to scrape the lyrics from the Genius lyrics webpage, and place them in the dataset as well. After that, I use another python library called langdetect to read the lyrics and give me the language of those lyrics. Now that I have the language of each song, I am then able to conduct some visualization of data based on the song's language. I first sorted the dataset by descending streams, which means that the most streamed songs will be at the top of the dataset. I took the top 100 songs in the dataset and created a new dataset that contains the top 100 songs of that dataset. Using those top 100 songs, I created a pie chart to visualize how many songs are in what language. I found that out of those top 100 songs, 89 songs were in English, 1 song in Korean, 1 song in Indonesian, and 9 in Spanish. Next, I made another visualization which was a bar chart that compared the top streaming songs out of those 4 languages. From that bar graph, I was able to see that the most streamed English song had nearly a 1 billion streams while the top Korean/Indonesian/Spanish each haven't hit 100 million streams. Based on these data visualizations, I can determine that English songs are more popular than other songs in other languages. To prove that this statement is true, I used python to conduct statistical analysis and have it calculate the p-value using a code that samples only 100 songs out of the 943 total songs. So everytime I run that code, a different p-value will be calculated. And every p-value it calculated was small that 0.05. This allows me to reject the null hypothesis and accept the null. For this question, the null hypothesis will be that the language of a song does certainly play a role in impacting a song's success and popularity.






