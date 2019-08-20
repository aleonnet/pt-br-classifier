# pt-br-classifier

## Description
Classifying Portuguese texts according to their variety (European or Brazilian Portuguese) 
The repository documents the entire process of building a ML model and deploying it:
- Scraping data from TED lectures with Scrapy (BRCrawler.py, PTCrawler.py)
- Basic data processing, setting up a classifier using scikit-learn (ptclassifier.ipynb)
- Exporting the model with joblib (ptclassifier.ipynb)
- Setting an API with Flask (flask_app.py)

## Contributions
Are highly encouraged. Some paths to explore:
- Scrape other kinds of texts (movie subtitles, media articles, blog posts, forum discussions) and check the model's performance
- Make a basic frontend app that consumes the API 
- Return weights for separate words and show their "brazilness" or "portugueseness" in the frontend (eXplainable AI)
- Use an LSTM network instead of NaiveBayes

## License
MIT
