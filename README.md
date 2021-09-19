# News_Article_Scrapping
Scraping articles from investing.com and performing sentimental analysis for algorithmic trading

The notebook contains a function which enables to scrape the news articles and do sentiment analysis from investing.com. We can use the output "polarity" of each article along with the time stamp of the article to guide our trading decisions. Change the link in the notebook for any commodity or stock.

# Description of the DataFrame
# time: Time of release of the article
# title: Title of the article
# link: link of the respective article
# full_artile: The entire article
# polarity: it the sentiment analysis, it has 4 classes and their values range from 0 to 1
    # neg: the negitivity rating 
    # neu: neutrailty rating
    # pos: positivity rating
    # compound: the combined rating to the article
