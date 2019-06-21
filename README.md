# Loseit Weight Loss Challenge Analysis

[![Word Cloud](figures/online_wordcloud_100_words.svg)](figures/online_wordcloud_100_words.svg)
*Word cloud showing the 100 most common words people use when describe their motivation for losing weight not related to the number on a scale.

## Findings

To see the in-depth analysis check out my [blog post](https://www.coreydeon.com/blog/motivating-weight-loss/).

## How to Use the Code

To run the code that fetches and downloads the challenge trackers from r/loseit and Google Sheets, you will need to have access tokens for both Reddit and Google. Instructions for how to set up and access Reddit through PRAW can be found [here](https://github.com/reddit-archive/reddit/wiki/OAuth2). Note that you will need to be signed into a reddit account to follow the instructions and create an app. After registering your new app, you will need to have your access tokens available for python to read. An example of that this may look like is included in the `notebooks` folder, but remember that you should ***never commit access credentials*** to a GitHub repository, even if it is private. To get access to Google Sheets, you can follow the instructions [here](https://gspread.readthedocs.io/en/latest/oauth2.html) on how to register an app with Google. Again I have included an example of what the credential file might look like in the `notebooks` folder, but again remember this is just an example and you should never commit secrets to a GitHub repository. If you don't want to go through the hassle of setting up access to Google and Reddit, I've included both the raw challenge tracking and final cleaned data frames used for the analysis in the form of CSV files located in the data folder.
