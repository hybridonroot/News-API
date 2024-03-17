# Webz.io Free News API Lite Documentation

Welcome to the [Webz.io Free News API Lite documentation](https://webz.io/products/news-api#lite). This API is designed to empower students, developers, and researchers by providing easy access to high-quality, relevant news data for non-commercial projects. With this API, you can tap into Webz.io's extensive repository of global news content, spanning up to 30 days of historical data, and leverage advanced search capabilities to refine and target your queries effectively. Harness the power of timely news data to uncover trends, analyze sentiment, and build innovative applications and dashboards.


## 3 Steps Quick Start Guide

Follow these three simple steps to start using the News API Lite:

### 1. Obtain an API Key

- To get started, visit the [News API page](https://webz.io/products/news-api#lite). and provide your email address to receive your unique API key.

<img src="https://webz.io/wp-content/uploads/2024/03/First-box.png" width="70%" height="80%">

  

### 2. Make an API Request
Use the API key provided to make your first call to the API. Make sure you also specify a search term in the request. For example, the following API request will return news articles related to the search term “Bitcoin.” The default time frame is 3 days, but you can set this to up to 30 days.

- `https://api.webz.io/newsApiLite?token=[token]&q=Bitcoin`.

Here is a screenshot showing a part of the API call results in a web browser:

<img src="https://webz.io/wp-content/uploads/2024/03/step-2-API-call.png" width="70%" height="80%">


## 3. Explore Webz.io news data
Experiment with different API call configurations, refining your searches with advanced features like [filters and Boolean queries](https://docs.webz.io/reference/news-blogs-discussions-api-overview). For example, you could search for news articles about U.S. President Joe Biden or his presidential challenger Donald Trump, refining the search to return articles with negative sentiment:

`https://api.webz.io/newsApiLite?token=[token]&ts=0&q=title%3A(Trump%20OR%20Biden)%20sentiment%3Anegative`

This query includes negative news posts about President Biden or Donald Trump in the past 30 days. Here is a screenshot of the call results in a web browser:

<img src="https://webz.io/wp-content/uploads/2024/03/step-3-corrected.png" width="70%" height="80%">



## Limitations

 - Monthly Call Limit: The API allows up to 1,000 calls per month.
 - Results per Call: Each API call returns a maximum of 10 articles.

Start exploring the News API Lite today and unlock valuable insights from the world of news data! For more details, refer to the official documentation.
