# Reddit Scraper using PRAW

This Python script uses the PRAW (Python Reddit API Wrapper) library to scrape the top 5 posts from the Python subreddit. The results include the post title and its score.

## Requirements

- Python 3.x
- PRAW library

To install the required libraries, run the following command:

```bash
pip install praw
reddit = praw.Reddit(
    client_id='<your_client_id>',
    client_secret='<your_client_secret>',
    user_agent='<your_user_agent>',
    redirect_uri='https://localhost:3000/'
)
Titre : Lad wrote a Python script to download Alexa voice recordings, Score: 12343
Titre : This post has a score: 9235
Titre : I redesign the Python logo to make it more modern, Score: 7859
Titre : Automate the boring stuff with Python - tinder, Score: 6721
Titre : I'm excited to share my first published book. Introduction to Python Programming for Business, Score: 6523
WARNING: praw: It appears that you are using PRAW in an asynchronous environment. It is strongly recommended to use Async PRAW.

You can update the placeholders with your actual credentials and adjust the details if necessary. Let me know if you'd like to add or modify any section!
