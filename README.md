# Analysis of Amazon product reviews with NLP techniques

### Preview
- [Python HTML](http://htmlpreview.github.io/?https://raw.githubusercontent.com/gl2668/amazon_product_reviews/master/NLP_Final_Project.html)
- [Python Notebook](https://github.com/gl2668/amazon_product_reviews/blob/master/final_project.ipynb)
- [Presentation Slides](https://github.com/gl2668/amazon_product_reviews/blob/master/NLP_Final_Project.pdf)

### Scope
- Text Pre-Processing
- Applying Sentiment Analysis to product reviews (using AFINN lexicon)
- Comparing distribution of product reviews to product ratings
  - Plain-Text VS Numerical Ratings
- Using Logistic Regression to classify products
  - Recommended VS Not-Recommended
- Using LDA for Topic-Modelling (Not Effective)

### Data
- Data from [Jianmo No](https://nijianmo.github.io/amazon/index.html)
- Only looking at Amazon-Fashion, i.e. Amazon branded fashion products
- 883,636 rows and 6 columns

### Results
- Scores from Sentiment Analysis are less-inflated than numerical 5-star ratings
- But not always accurate (due to sentiment analysis algorithms)
- Logistic Regression Classifier had 88% mean CV accuracy score (pretty decent)
- LDA topics too broad and similar (10 components not the best)
