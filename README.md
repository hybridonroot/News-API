# Webz.io Free News API Lite Documentation

Welcome to the [Webz.io Free News API Lite documentation](https://webz.io/products/news-api#lite). This API is designed to empower students, developers, and researchers by providing easy access to high-quality, relevant news data for non-commercial projects. With this API, you can tap into Webz.io's extensive repository of global news content, spanning up to 30 days of historical data, and leverage advanced search capabilities to refine and target your queries effectively. Harness the power of timely news data to uncover trends, analyze sentiment, and build innovative applications and dashboards.


## 3 Steps Quick Start Guide

Follow these three simple steps to start using the News API Lite:

### 1. Obtain an API Key

- To get started, visit the [News API page](https://webz.io/products/news-api#lite). and provide your email address to receive your unique API key.

<img src="https://webz.io/wp-content/uploads/2024/03/First-box.png" width="70%" height="80%">

  

### 2. Make Your First API Request
Once you have your API key, you can make your first API call. Include your API key in the request URL along with a search term. For instance, to retrieve news articles related to "Bitcoin" within the default 3-day timeframe, use the following endpoint:

- `https://api.webz.io/newsApiLite?token=[token]&q=Bitcoin`.

Explore the returned data to see relevant news articles.

<img src="https://webz.io/wp-content/uploads/2024/03/step-2-API-call.png" width="70%" height="80%">


## 3. 3. Dive Deeper & Explore Webz.io news data

Experiment with different API call configurations, refining your searches with advanced features like [filters and Boolean queries](https://docs.webz.io/reference/news-blogs-discussions-api-overview). For example, you could search for news articles about U.S. President Joe Biden or his presidential challenger Donald Trump, refining the search to return articles with negative sentiment:

Experiment with various API configurations to refine your searches further. Utilize advanced features such as [filters and Boolean queries](https://docs.webz.io/reference/news-blogs-discussions-api-overview) to tailor your results. 
For example, you can search for news articles about U.S. President Joe Biden or his challenger Donald Trump with a negative sentiment as follows:

`https://api.webz.io/newsApiLite?token=[token]&ts=0&q=title%3A(Trump%20OR%20Biden)%20sentiment%3Anegative`

This query retrieves news posts with negative sentiment related to either President Biden or Donald Trump within the past 30 days :

<img src="https://webz.io/wp-content/uploads/2024/03/step-3-corrected.png" width="70%" height="80%">

## Limitations

 - Monthly Call Limit: The API allows up to 1,000 calls per month.
 - Results per Call: Each API call returns a maximum of 10 articles.

Start exploring the News API Lite today and unlock valuable insights from the world of news data! For more details, refer to the official documentation.
