# Extracting Sentiment from stock news

Welcome to the Financial News Sentiment Analysis repository! This project leverages web scraping, natural language processing, and data visualization to analyze the sentiment of financial news headlines and provide insights into market sentiments for specific stocks.

## Project Overview

In the age of the internet, financial news travels at the speed of light. This project aims to extract valuable insights from financial news articles using cutting-edge techniques. By applying sentiment analysis to news headlines from FINVIZ.com, we gain a deeper understanding of the market's emotional response to stocks like Facebook (FB) and Tesla (TSLA).

## Features

- **Web Scraping and HTML Parsing:** The project includes scripts to scrape financial news headlines from HTML files using the BeautifulSoup library. This step allows us to transform raw data into structured information.

- **Sentiment Analysis:** Leveraging the NLTK library's VADER sentiment analysis tool, we analyze the emotional tone of news headlines. Compound sentiment scores are used to predict whether the market's sentiment towards stocks is positive, negative, or neutral.

- **Data Manipulation and Visualization:** The Pandas library is employed to manipulate and organize data, while Matplotlib is used to create insightful visualizations. The resulting graphs provide a visual representation of sentiment trends over time.

## Project Structure

- `datasets/`: Folder containing raw HTML files for Tesla (TSLA) and Facebook (FB) stocks obtained from FINVIZ.com.

- `financial_news_sentiment_analysis.ipynb`: Jupyter Notebook where the project unfolds. This notebook guides you through the process of web scraping, sentiment analysis, data manipulation, and visualization.


## Contribution

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements. Let's collaborate to enhance the project further!
