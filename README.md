# Lede Project 1: Zombie Songs

This repository include the data and notebooks used for the first project I've worked on as a part of the Lede program for Data Journalism from Columbia Graduate School of Journalism.

# The project
## Zombie Songs
The suspicious is confirmed: zombies are real. An analysis using data from the social network TikTok reveals the resurrection of forgotten songs. Among the top 100 trending songs on the platform, more than half of the list is over 2 years old. However, if you listen to an item from that list, you will likely not recognize your favorite song immediately. This is due to a new phenomenon driven by the way TikTok users consume content. Now, zombie songs make a comeback more quickly...
[Read this story.](https://juditecypreste.com/portfolio-lede/project_1/project_1.html)

# The files:
1. [Getting the data](https://github.com/juditecypreste/zombie_songs/blob/main/scrapper_tiktok.ipynb)

I can't retrieve the information about trending songs on TikTok from the official API. I need to research this information on the platform's website. The information is indeed available there, but the only way to access it is by using a browser automation tool. That's why I used Selenium for this task.

2. [The data](https://github.com/juditecypreste/zombie_songs/blob/main/trending_songs.csv)

This is the result of my scraper.

4. [Analyzing the data](https://github.com/juditecypreste/zombie_songs/blob/main/tiktok_analysis.ipynb)

In this notebook, I cleaned and analyzed the data using the pandas library.

5. [The csv for graphics](https://github.com/juditecypreste/zombie_songs/blob/main/trending_songs_analysis.csv)

This is the result of my analysis.

# New tools and skills

I really struggle with performing web scraping, so it has been quite challenging to do it multiple times. During the process, the most complicated part was figuring out what I needed to manipulate on the website correctly. Additionally, I encountered issues trying to get my tool to work using Google Chrome, which forced me to use another browser, something very unexpected.

# I could not

I would have liked to be able to create a chart with the number of streams for these old songs on Spotify. However, the platform's API is quite confusing and returns strange values. Additionally, I haven't yet figured out if it's possible to obtain such an extensive temporal analysis.

Furthermore, I wanted my charts to be animated. I chose to create them using Illustrator to experiment, but I don't think they turned out as well as I had hoped.
