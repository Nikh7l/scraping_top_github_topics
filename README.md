# scraping_top_github_topics

<h2>Introduction</h2>

1. This Python script scrapes GitHub topics, retrieves information about the top repositories for each topic, and saves the data to CSV files.
2. Tools used Python , requests, BeautifulSoup, Pandas

<h2>Project Outline</h2>
1. We're going to scrape https://github.com/topics
2. We'll get a list of the top topics. For each topic, we'll get the top 20 reopsitories in the topic from the topic page
3. For each repository we'll get the repo name, username , number of stars and the repo url
4. For each topic we'll create a csv file in the following format:
Repo_name , username , stars , repo_url
