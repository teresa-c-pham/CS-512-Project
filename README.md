# Sentiment Analysis in Recommendation Systems
## CS-512-Project
### Contributors: Teresa Pham, Tri Quan Do, Pranav Bhardwaj

## Problem
The goal of this project is to learn how sentiment analysis is used in texts to generate predictions on user preference.

## Datasets
This project features the following datasets: <br>
* **Customer Complaint** [Kaggle](https://www.kaggle.com/datasets/meetnagadia/consumer-complaint-finance?resource=download) (Pranav) - 18 columns, 2,396,033 rows. After processing out missing values, there are 164,063 entries, however the data is still imbalanced, such that there are more negative examples than positive. The target attribute to predict is "Consumer disputed?"
* **IMDB Movie Review** [Kaggle](https://www.kaggle.com/datasets/meetnagadia/consumer-complaint-finance?resource=download) (Teresa) - 2 columns, 50,000 rows. The data is balanced with 25,000 positive reviews and 25,000 negative. The target attribute to predict is "sentiment".
* **Customer Sharing Thinking on Movieset** [Dataset](https://nlp.stanford.edu/sentiment/code.html) (Tri) - 10,605 raw thinking entries in the original_rt_snippets.txt file. This data is normalized to be a text file and indicated by index with majority non-null values.
