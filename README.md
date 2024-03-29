# Natural Language Sentiment Analysis and model on Walmart Customer Review data

The Walmart Customer Reviews Dataset offers a wealth of insights into consumer sentiment and product feedback related to one of the world's largest retail giants. This dataset contains a vast collection of customer reviews, star ratings, and other relevant information that has been gathered through web scraping and data compilation. The key features include: Customer Reviews: Detailed textual reviews provide firsthand accounts of shopping experiences and product satisfaction. Star Ratings: Each review is accompanied by a star rating, allowing for sentiment analysis and product rating assessment. Review Dates: The dataset includes review submission dates, facilitating temporal analysis and trend detection. Product Identification: For some reviews, product identification details such as SKU numbers or product categories are provided. Sentiment analysis on the data found the key features that will promote or impair customers’ experience. These information will not only help Walmart but also other retailers to improve their services. After that, I build model to predict customer rating based on review language by transfer learning and fine tuning on of pre-trained RoBERTa model (cardiffnlp/twitter-roberta-base-sentiment-latest) from hugging face. 

In walmart_data_exploration.ipynb, walmart reveiw data are cleaned to remove unrelated columns and records containing NA. After that, the basic describution and correlation of intereting features are checked.

In walmart-review-sentiment-analysis.ipynb, review data are processed to transforming to lower case, removing punctuations, number, stop words and rare words, lemmatization, etc. After that the words count distribution and tf_idf encoded logistic regression analysis are implemented.

In walmart-review-twitter-roberta-classification.ipynb, I built RoBERTa model to classify postive rating and negative rating using reviews as input. Pretrained RoBERTa model are futher tunned with walmart review and rating data. After that an independent walmart data is used to furhter validate the model.

capstone_two_report_walmart_review_NLP_WenhuiWang.pdf is the full report file describing Data collection, data wrangling, data exploration, sentiment analysis, RoBERTa modeling, final takeaway and future plan.

capstone_two_presentation_walmart_review_NLP_WenhuiWang.pdf is the presentation power point for the capstone two project.
