# ElasticSearch-Twitter-Stream-in-Python

### Installation

1. Download [ElasticSearch](https://www.elastic.co/downloads/elasticsearch/). Extract it to your desired location.

2. Open Terminal and cd to the directory of elastitcsearch folder and `cd bin/elasticsearch`. Now open a browser type this address `http://localhost:9200/` to verify if elasticsearch is running

### Usage

1. Open new terminal window and run `python load.py trump`(where trump is the hashtag used to filter stream). Once the stream starts you can stop it anytime by pressing ctrl+c

2. Now run `python fetch.py trump` to print all the tweets retrieved from the elasticsearch index. (trump is the hashtag used to retrieve tweets for that id)
