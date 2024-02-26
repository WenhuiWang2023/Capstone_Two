# Natural Language Sentiment Analysis and model on Walmart Customer Review data

The Walmart Customer Reviews Dataset offers a wealth of insights into consumer sentiment and product feedback related to one of the world's largest retail giants. This dataset contains a vast collection of customer reviews, star ratings, and other relevant information that has been gathered through web scraping and data compilation. The key features include: Customer Reviews: Detailed textual reviews provide firsthand accounts of shopping experiences and product satisfaction. Star Ratings: Each review is accompanied by a star rating, allowing for sentiment analysis and product rating assessment. Review Dates: The dataset includes review submission dates, facilitating temporal analysis and trend detection. Product Identification: For some reviews, product identification details such as SKU numbers or product categories are provided. Sentiment analysis on the data found the key features that will promote or impair customers’ experience. These information will not only help Walmart but also other retailers to improve their services. After that, I build model to predict customer rating based on review language by transfer learning and fine tuning on of pre-trained RoBERTa model (cardiffnlp/twitter-roberta-base-sentiment-latest) from hugging face. 

In walmart_data_exploration.ipynb, walmart reveiw data are cleaned to remove unrelated columns and records containing NA. After that, the basic describution and correlation of intereting features are checked.
In
