+++
draft = false
image = "img/news/news_head.png"
showonlyimage = false
title = "Go News App Demo"
weight = 2
+++

A News Aggregator web service written in Go. Build and deployed using only Go's standard library.

<!--more-->

- [View Source Code](https://github.com/andybyers21/go_news_app_demo)
- [View Site](https://go-news-app-demo.herokuapp.com/)

Some more stuff qabout the app: something about RESTFUL API"s

- Use Go tamplating
- Create search routing
- Create and make requests to the News API server
- Render and format the results
- Deploy to the web (using Heroku)

![news 1](/img/news/news_1.png)

Using [NewsAPI.org](https://newsapi.org/)'s JSON API integration to colect data,
fetch news articles matching a user search query
and present the results on the page. News API is a simple HTTP REST
API for searching and retrieving live articles from all over the web.

Input a search term and News API will scan thousands of news websites and
organsie the information of the latest articles.

![news 2](/img/news/news_2.png)

You can search for articles with any combination of the following criteria:

- **Keyword or phrase.** Eg: find all articles containing the word 'Microsoft'.
- **Date published.** Eg: find all articles published yesterday.
- **Source name.** Eg: find all articles by 'TechCrunch'.
- **Source domain name.** Eg: find all articles published on thenextweb.com.
- **Language.** Eg: find all articles written in English.

When building the app locally you will requires a `.env` file to be created in
the root with the following [info](info.md):

```txt
PORT=

NEWS_API_KEY=
```

![news 3](/img/news/news_3.png)

Technology Stack:

- HTML
- CSS
- Javascript
- Golang
