# Customer Satisfaction Measurement with Sentiment Analysis
## Overview 
This projects goal was to develop a system for measuring customer satisfaction through sentiment analysis on customer feedback.This system analyzes customer reviews, comments, or any text-based feedback, categorizing them into positive, negative, or neutral sentiment categories.  By understanding customer sentiment, businesses can identify areas for improvement, track sentiment trends, and make data-driven decisions to enhance overall customer satisfaction.

![Your paragraph text](https://github.com/saimaansi13/Customer-Satisfaction-Measurement-with-Sentiment-Analysis/assets/125540201/b54c1d4e-e928-4b84-aedb-6f720dedb1bf)

## Process

### Data Collection
This stage orchestrates the gathering of customer feedback data from various channels, including online reviews, social media platforms, customer surveys, and support tickets. It employs methods such as web scraping, API integration, or manual data entry, tailored to specific data sources and accessibility.
### Data Preprocessing
Collected data undergoes refinement and transformation to ready it for sentiment analysis. Tasks encompass removing irrelevant information, handling missing data, standardizing text (lowercasing, removing punctuation), and tokenization to split text into manageable units.
### Sentiment Analysis
This phase involves dissecting sentiment expressed in customer feedback. It includes the following sub-processes:
#### a. Text Classification
Using machine learning or rule-based algorithms, this process categorizes sentiment of text units (sentences, phrases, documents) as positive, negative, or neutral, often involving feature extraction and training sentiment classifiers on labeled data.
#### b. Lexicon-Based Analysis
Utilizing pre-built sentiment lexicons, this method assigns sentiment scores to customer feedback based on the presence and intensity of sentiment-bearing terms in the text.
#### c. Aspect-Based Analysis
This process identifies sentiments towards specific aspects or features of a product or service, extracting aspects from feedback and determining sentiment polarity for each aspect individually.
### Insights Generation
This process was to extract actionable insights from sentiment analysis results. Tasks include aggregating sentiment scores, visualizing sentiment trends, identifying key drivers of customer satisfaction/dissatisfaction, and generating reports or dashboards for stakeholders.
### Performance Evaluation
To assess the sentiment analysis module's accuracy and effectiveness, this phase compares sentiment analysis results with human-labeled data or ground truth, calculating metrics such as accuracy, precision, recall, and F1 score.
![1](https://github.com/saimaansi13/Customer-Satisfaction-Measurement-with-Sentiment-Analysis/assets/125540201/17aaf664-dfc5-4836-8ee6-a0b707ff9297)

![4](https://github.com/saimaansi13/Customer-Satisfaction-Measurement-with-Sentiment-Analysis/assets/125540201/8eab0f2c-34b1-4495-82c7-1ef75b64c175)

## Software Requirements
- **Operating System**  :  Windows 
- **Programming/Scripting Languages**  :  Python, JavaScript, HTML, CSS
- **Libraries** : Pandas ,Numpy, Nltk, sklearn
- **Frameworks**  : Django
- **Database** **management** **system** :  Sqlite3
- **Integrated** **Development** **Environment** :  Visual Studio
## References 
- Ibrahim Rouby, Performance evaluation of an adopted sentiment analysis model for Arabic comments from the facebook ,2018, pp. 992-1045, 2018.
- J. Singh, G. Singh, and R. Singh, A review of sentiment analysis techniques for opinionated web text, CSI Trans. ICT, 2016.
- Hu, Fei, Li Li, Zi-Li Zhang, Jing-Yuan Wang, and XiaoFei Xu, “Emphasizing essential words for sentiment classification based on recurrent neural networks”, Journal of Computer Science and Technology, vol. 32, no. 4, pp. 785-795, 2017. 
