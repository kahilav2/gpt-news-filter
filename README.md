# Simple GPT-powered news filter

Ever wished you could decide what kind of web content you're exposed to? With the recent rapid development of AI technologies, it has become possible. This application lets you pick news feeds and filter them using your personalized filtering rules. 

## What's needed?

You'll need an API key for OpenAI's API. You need to insert it into the code or set an environment key in your terminal with `export OPENAI_API_KEY=yourkeyhere`.

## How to run?

### Clone project
`git clone `

### Install dependencies
`pip install -r requirements.txt`

### Run
`python simple_gpt_news_filter.py`

## How to get the filtering right?
It's hard to say how to get the best results with filtering. An example, which is close to what I'm using is written in the code as an example. You need to experiment with it.

## How to add the news sites that I read?
The code lets you to add new feeds to the script rather easily. You will need to write your own News Fetcher. If you don't know how, try asking ChatGPT. 