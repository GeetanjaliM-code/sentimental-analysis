# sentimental-analysis
# Twitter Sentiment Analysis using VADER

This project performs sentiment analysis on a dataset of tweets using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. It uses a dataset originally released for sentiment classification tasks and generates visual insights using Matplotlib, Seaborn, and WordCloud.

## 📦 Features

- Preprocesses raw tweet text (removes mentions, hashtags, URLs, etc.)
- Applies VADER sentiment analysis (Positive, Neutral, Negative)
- Visualizes:
  - Predicted sentiment distribution
  - Word clouds for each sentiment

## 🧰 Requirements

Install the required Python packages (you can use `pip install -r requirements.txt` if you add one):

```bash
pip install pandas numpy matplotlib seaborn vaderSentiment wordcloud
## Dataset

This project utilizes the [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140) dataset from Kaggle, which contains 1.6 million tweets labeled for sentiment analysis.

> Note: Accessing the dataset requires a Kaggle account.


---

📚 Citation Formats

If you're preparing a report, academic paper, or any formal documentation, it's important to cite the dataset appropriately. Here are standard citation formats:

APA Style:

Go, A., Bhayani, R., & Huang, L. (2009). Sentiment140 Dataset with 1.6 Million Tweets [Data set]. Kaggle. https://www.kaggle.com/datasets/kazanova/sentiment140

IEEE Style:

A. Go, R. Bhayani, and L. Huang, "Sentiment140 Dataset with 1.6 Million Tweets," Kaggle, 2009. [Online]. Available: https://www.kaggle.com/datasets/kazanova/sentiment140

BibTeX:

@misc{go2009sentiment140,
  author       = {Go, Alec and Bhayani, Richa and Huang, Lei},
  title        = {Sentiment140 Dataset with 1.6 Million Tweets},
  year         = {2009},
  publisher    = {Kaggle},
  url          = {https://www.kaggle.com/datasets/kazanova/sentiment140}
}


---
