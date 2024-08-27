# Literary Web Scraping and Advanced Analytics

## Project Overview

This project involves web scraping multiple literary works from Project Gutenberg, followed by advanced text data analysis, including word frequency analysis, sentiment analysis, and topic modeling. The analysis aims to uncover the dominant themes, sentiment, and common words across the texts.

### Features:
1. **Web Scraping Multiple Books**: We scrape *Moby Dick*, *Pride and Prejudice*, and *A Tale of Two Cities*.
2. **Word Frequency Analysis**: Determine the most common words in each text after removing stopwords.
3. **Sentiment Analysis**: Use TextBlob to analyze the sentiment polarity of each book.
4. **Topic Modeling**: Identify key themes within each text using Latent Dirichlet Allocation (LDA).
5. **Advanced Visualizations**: Generate Word Clouds and sentiment bar charts to visualize the data.

## Steps:
1. **Web Scraping**: Scraping HTML content from multiple Project Gutenberg sources using BeautifulSoup.
2. **Data Cleaning**: Tokenizing and cleaning the text data.
3. **Word Frequency Analysis**: Counting word occurrences.
4. **Sentiment Analysis**: Analyzing sentiment polarity.
5. **Topic Modeling**: Performing topic modeling to identify dominant themes.
6. **Visualizations**: Displaying Word Clouds and sentiment distributions.

## Results
The project provides detailed insights into the frequency of words, sentiment, and key topics within each book.

## Libraries Used
- `requests`: To fetch HTML content.
- `beautifulsoup4`: For HTML parsing.
- `nltk`: For tokenization and stopword removal.
- `collections`: For counting word frequencies.
- `textblob`: For sentiment analysis.
- `gensim`: For topic modeling.
- `matplotlib`, `wordcloud`: For visualization.

## How to Run
1. Clone this repository.
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the `Literary_Analysis.ipynb` notebook and run all cells to perform the analysis.
