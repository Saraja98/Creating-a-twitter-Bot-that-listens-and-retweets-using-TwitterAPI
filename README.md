# hastags_TwitterAPI
A Bot is simply an application you create for doing a specific job on a social platform (Twitter, Facebook, Slack…) let’s say you have a hashtag for your campaign and you need to listen for everything happens on this hashtag.
In this code, we are going to create a very basic twitter bot that will listen for a specific hashtag and grab the latest tweet on that hashtag and retweet it on the user’s account.
Bots use specific platforms API for fetching and submitting data, therefore we need to use Twitter’s API for searching for hashtag tweets and retweet them.
First, create a Twitter App that will allow you access the Twitter’s API through an access token keys that will be generated once you create the application so make sure to copy those keys (Consumer Key/Secret and Access Token Key/Secret) in order to use them later for bot API authentication.
Also, make sure to take a look on the Twitter’s API Reference for more information on the endpoints and the needed parameters for accessing a specific piece of information and for more information to expand your basic bot.
We will use VSCode as the editor and Nodejs for a javascript engine since bots run on the server so that makes it a bit easier for you to use.
