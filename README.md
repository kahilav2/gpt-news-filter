# GPT-powered news filter

Ever wished you could decide what kind of web content you're exposed to? With the recent rapid development of AI technologies, it has become possible. This application lets you pick news feeds and filter them using your personalized filtering rules. With the power of AI, you can filter news like "no clickbaity, sensationalist, anxiety-inducing news, or news about Donald Trump", which has been difficult thus far.

## What's needed?

You'll need an API key for OpenAI's API, [get it here](https://platform.openai.com/overview). You need to insert it into the code or set an environment key in your terminal with `export OPENAI_API_KEY=yourkeyhere` command.

## How to run?

### Clone project
```
git clone git@github.com:kahilav2/gpt-news-filter.git
cd gtp-news-filter
```

### Install dependencies
`pip install -r requirements.txt`

### Modify the filter
Edit simple_gpt_news_filter.py and change the contents of *preprompt* to your liking. 

### Set api key
Modify *api_key* inside simple_gpt_news_filter.py or set environment variable by e.g. running
`export OPENAPI_API_KEY=yourkeyhere`

### Run
`python simple_gpt_news_filter.py`

### Enjoy your news
The web page showing your filtered news should automatically open up, but in case it doesn't, mofidy simple_gtp_news_filter.py or simply open your_ai_powered_news_feed.html generated in the project folder.

## How to get the filtering right?
It's hard to say how to get the best results with filtering. An example, which is close to what I'm using is written in the code as an example. You need to experiment with it.

## How to add the news sites that I read?
The code lets you to add new feeds to the script rather easily. You will need to write your own News Fetcher. If you don't know how, try asking ChatGPT. 
