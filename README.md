# How accurately can my Youtube watch history be used to characterize me?

This project aims to analyze what my youtube watch history looks like. This probably shouldn't be public information but what the heck, people like to learn about others and their habits.

In this I look at a few things:
1. What was the first video I watched (in my case Youtube doesn't have the data for youtube video so it shows the video URL)
2. How old is my watch history (for some reason google only has history from 7/2017 onwards)
3. How many videos I watch (on average) per day
4. My most watched videos (and their views, no wonder all top 20 are songs)
5. Wordcloud of what the title of these videos are (It's pretty evident I love Chelsea FC)
6. How many Unique channels i have watched and which are the ones I watch the most

## TO-DO
Incorporate my likes history and comapre wordclouds and do other analysis on the same.

# Instructions to run
1. Make sure you have Jupyter installed so you can open this notebook locally
2. Run `pip install -r requirements.txt`
3. Download your data from Google via [Google Takeout](https://takeout.google.com/). Make sure you request youtube data as JSON and NOT html.
4. Place "watch-history.json" in directory of notebook and run the cells.
