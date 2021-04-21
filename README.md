## Project 1
### Home Credit Default Risk

This project aims to tackle [this](https://www.kaggle.com/c/da-pt-02/overview) Kaggle competition.

The competition uses AUC Score as the evaluation metric. You can read more about it [here](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc#:~:text=AUC%20represents%20the%20probability%20that,has%20an%20AUC%20of%201.0.)

The given model fetched an AUC Score of 0.78065

## Project 2
### Who said it? Hillary or Trump?

![Hillary vs Trump](https://github.com/ShubhiKhanna/Who-said-it-Trump-or-Clinton-/blob/main/trumpclinton.jpg)

Twitter played an increasingly prominent role in the 2016 US Presidential Election. Debates had raged and candidates had risen and fallen based on tweets. 

[This](https://www.kaggle.com/benhamner/clinton-trump-tweets/home) dataset provides ~6000 recent tweets from Hillary Clinton and Donald Trump, the two major-party presidential nominees.

Our goal is to develop a model which determines the author of a given tweet.

To do so, we're using the Multinomial Naive Bayes Classifier. You can read more about it [here](https://www.mygreatlearning.com/blog/multinomial-naive-bayes-explained/).

Classification Report:

|              | Precision | Recall | f1-score | Support |
|--------------|-----------|--------|----------|---------|
| Hillary      | 0.92      | 0.93   | 0.92     | 521     |
| Trump        | 0.94      | 0.93   | 0.94     | 624     |
| accuracy     |           |        | 0.93     | 1145    |
| Macro Avg    | 0.93      | 0.93   | 0.93     | 1145    |
| Weighted Avg | 0.93      | 0.93   | 0.93     | 1145    |


## Project 3
### Fake-News

“Fake news is false or misleading information presented as news. It often has the aim of damaging the reputation of a person or entity, or making money through advertising revenue.” 

Nowadays, people can easily access various news around the world at his/her home using social media. According to Pew Research Center, two thirds of Americans read news online through social media platforms instead of traditional news organizations.  This trend shows that news can be published by not only journalists(formal) but also anybody(informal).  Then, what could be the fake news and how can we detect them? 

The project was divided into 2 parts:

# Formal News

We used the dataset called  [“Liar, Liar Pants on Fire: A New Benchmark Dataset for Fake News Detection”](https://arxiv.org/abs/1705.00648) by William Yang Wang. The dataset is divided into three sets; train, test, and validation. The dataset includes around 12.8K short statements labeled for truthfulness.

[Binary Classification](https://github.com/ShubhiKhanna/Fake-News/blob/main/Fake_News_Detection%20(Binary).ipynb)
[6 Way Classification](https://github.com/ShubhiKhanna/Fake-News/blob/main/Fake_News_Detector%20(6%20classifications).ipynb)

# Informal News

The data was extracted from [Reddit](https://www.reddit.com/) using the [PushShift API](https://pushshift.io/api-parameters/).

[Access the Jupyter Notebook](https://github.com/ShubhiKhanna/Fake-News/blob/main/FakeNews_NLP_Onion.ipynb)
